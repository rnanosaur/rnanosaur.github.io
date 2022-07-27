---
title: "Run nanosaur with gz-omni connector"
excerpt: "Run nanosaur use the Isaac SIM connector, to bridge Ignition Gazebo on Isaac SIM"
permalink: /tutorial/isaacsim-connector
classes: wide
header:
  teaser: /assets/docs/simulation/gz-omni-hybrid_diagram.png
---

If you want to work with the gz-omni connector you need to install some extra steps on your desktop 

# Install

**before** to follow this tutorial, install [nanosaur simulators](/install/simulation)!

## Install Ignition Gazebo - Edifice

GZ-omni works with only with **Ignition Gazebo - Edifice**. You need to install on your desktop this Ignition Gazebo version following the lines below

{% capture code %}sudo apt update
sudo apt install python3-pip wget lsb-release gnupg curl
sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -
sudo apt-get update
sudo apt-get install python3-vcstool python3-colcon-common-extensions
sudo apt-get install git libfreeimage-dev

sudo apt-get install ignition-edifice{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

## Compile gz-omni

We need to compile some Ignition packages from source with a specific flag due the `omni-client` library.

To compile this libraries you should run:

{% capture code %}mkdir -p ~/ign-omni/src
cd ~/ign-omni/src
git clone https://github.com/ignitionrobotics/ign-omni-meta
vcs import . < ign-omni-meta/repos.yaml
cd protobuf
git -C . apply ../ign-omni-meta/protobuf-cmake.patch
cd ~/ign-omni
colcon build --merge-install --event-handlers console_direct+ --packages-select protobuf
cp src/ign-omni-meta/colcon.meta .
colcon build --merge-install --event-handlers console_direct+ --packages-up-to ignition-omniverse1{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

You can ignore the following message:

```
WARNING:colcon.colcon_cmake.task.cmake.build:Could not run installation step for package 'ignition-omniverse1' because it has no 'install' target
```

# Run gz-omni Connector

Run Ignition Gazebo

{% capture code %}source nanosaur
ros2 launch nanosaur_ignition ignition.launch.py{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

Start realtime converter

{% capture code %}export IGN_GAZEBO_RESOURCE_PATH="/opt/ros/foxy/share:~/nanosaur_core/install/share"
source ~/ign-omni/install/setup.bash
cd ~/ign-omni/src/ign-omni
reset && bash run_ignition_omni.sh -p omniverse://localhost/Users/nanosaur/nanosaur.usd -w lab -v --pose ignition{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}
---
title: "Install nanosaur desktop simulation"
permalink: /install/simulation
classes: wide
---

Do you want to try nanosaur on a simulator? You can start directly from this tutorial.

 **Before** to follow this tutorial, install [nanosaur desktop software](/install/desktop)!

# Install simulation packages

{% capture code %}nanosaur install simulation{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

This script enable and install all simulation packages to drive such a real nanosaur robot, but on Gazebo.

The script install in your desktop:
 * Simulation packages [**nanosaur simulation**](https://github.com/rnanosaur/nanosaur_simulations.git)
 * Docker compose to run Isaac ROS perception docker

## Install NVIDIA Isaac SIM

Do you want to jump on NVIDIA Isaac SIM? **nanosaur** is made for it!

There are two steps to do to have your robot on NVIDIA Isaac SIM:
1. [Requirements](https://docs.omniverse.nvidia.com/app_isaacsim/app_isaacsim/requirements.html)
2. [Installation](https://docs.omniverse.nvidia.com/app_isaacsim/app_isaacsim/install_basic.html)

When is done, you can use Isaac SIM with your robot

{% include figure image_path="/assets/docs/simulation/NVIDIA-IsaacSIM.png" alt="NVIDIA Isaac SIM" caption="NVIDIA Isaac SIM" %}

# Run simulation

There are three simulations available for nanosaur:
1. Gazebo
2. Ignition Gazebo
3. NVIDIA Isaac SIM

For each simulation there are different ways to switch on nanosaur

nanosaur on Gazebo is pretty simple, you need only to write:

{% capture code %}source nanosaur
ros2 launch nanosaur_gazebo gazebo.launch.py{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

the command is pretty similar on Ignition Gazebo

{% capture code %}source nanosaur
ros2 launch nanosaur_ignition ignition.launch.py{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

working on NVIDIA Isaac SIM, run the script below

{% capture code %}cd nanosaur_core/src/nanosaur_simulations
bash nanosaur_isaac_sim/scripts/launcher.sh{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}
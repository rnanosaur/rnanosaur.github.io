---
title: "nanosaur install"
excerpt: "Install the nanosaur basic software"
permalink: /install/nanosaur/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
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

### Setup NVIDIA Omniverse nucleus

When nucleus is first installed, it will prompt you to create a user.
**Remember** your username this is necessary for the [gz-omni connector](/tutorial/isaacsim-connector).

{% include figure image_path="/assets/docs/simulation/nucleus_install_01.png" alt="Create new nucleus user" caption="Create new nucleus user" %}

Otherwise you can follow the image below to make your **nanosaur** user:

{% include figure image_path="/assets/docs/simulation/nucleus_install_02.png" alt="Setting up nucleus user" caption="Setting up nucleus user" %}

* User: **nanosaur**
* Password: *Chose your best password*
* email: your email

# Run simulation

There are three simulations available for nanosaur:
1. Gazebo
2. Ignition Gazebo
3. NVIDIA Isaac SIM

For each simulation there are different ways to switch on nanosaur

nanosaur on Gazebo is pretty simple, you need only to set up the script or follow the [tutorials](/tutorial):

{% capture code %}nanosaur simulation set{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

{% include figure image_path="/assets/docs/simulation/set_simulator.png" alt="Set nanosaur simulator" caption="Set nanosaur simulator" %}

After that you can run the simulator only with:

{% capture code %}nanosaur simulation run{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

Otherwise watch the tutorials:
1. [Gazebo/Ignition Gazebo](/tutorial/gazebo-simulation)
2. [NVIDIA Isaac SIM](/tutorial/isaacsim-simulation)
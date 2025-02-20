---
title: "Nanosaur on Gazebo"
excerpt: "How to work with nanosaur on Gazebo"
permalink: /simulation/gazebo/
classes: wide
header:
  teaser: /assets/images/collections/simulation/gazebo/nanosaur-gazebo-robot.png
---

How to simulate nanosaur on [Gazebo Sim](https://gazebosim.org/) and what is this simulator?

# What is Gazebo?

> Gazebo is an open-source robotics simulator that provides realistic physics, sensor simulation, and 3D environments for testing and developing robotic applications. It integrates with ROS, supports multiple physics engines, and allows for modular robot modeling. Gazebo is widely used in research and industry for prototyping and validating robotic systems before real-world deployment.

{% include figure image_path="/assets/images/collections/simulation/gazebo/gazebosim.png" alt="Gazebo sim" caption="Gazebo sim" %}

Learn more: [Gazebo Sim](https://gazebosim.org/).

# Start Gazebo

Gazebo can be run from a docker container or you can run native from your computer. The only command you need to start the simulator is:

{% capture code %}nanosaur simulation start{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

Remember to setup your computer with [`nanosaur simulation set`](/simulation/configuration#set-simulator).

**:memo: Note** If you set [`nanosaur simulation headless`](/simulation/configuration#headless-mode) to **yes** will be not activated any GUI.
{: .notice}

**:warning: WARNING** When you run Gazebo from a docker container, the GPU will be not used, the simulation may be slower than running from host.
{: .notice--warning}

{% include figure image_path="/assets/images/collections/simulation/gazebo/nanosaur-gazebo-gui.png" alt="Gazebo GUI" caption="Gazebo GUI" %}

Now you can open a *new terminal* and switch on the robot with:

{% capture code %}nanosaur robot start{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

**:warning: WARNING** Every time you change the nanosaur configuration, you need to reboot the simulation.
{: .notice--warning}

{% include figure image_path="/assets/images/collections/simulation/gazebo/nanosaur-gazebo-robot.png" alt="Gazebo GUI with nanosaur" caption="Gazebo GUI with nanosaur" %}

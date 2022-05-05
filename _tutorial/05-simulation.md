---
title: "Run nanosaur on Gazebo"
excerpt: "Run nanosaur in simulation using Gazebo"
permalink: /tutorial/gazebo-simulation
classes: wide
header:
  teaser: /assets/tutorial/simulation/gazebo-nanosaur.png
---

Do you want to try nanosaur on a simulator? You can start directly from this tutorial.

 **before** to follow this tutorial, install [nanosaur software](/tutorial/install-desktop)!

# Install simulation enviroment

If your desktop is installed, now you can run the command below.

{% capture code %}nanosaur install simulation{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

This script enable and install all simulation packages to drive such a real nanosaur robot, but on Gazebo.

# Run script

To run nanosaur on gazebo you need first for all load all sources

{% capture code %}source nanosaur{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

When the shell is done, run the simulator using this launch file:

{% capture code %}ros2 launch nanosaur_gazebo gazebo.launch.py{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

The final output on gazebo, will be like:

{% include figure image_path="/assets/tutorial/simulation/gazebo-nanosaur.png" alt="nanosaur on gazebo" caption="nanosaur on gazebo" %}
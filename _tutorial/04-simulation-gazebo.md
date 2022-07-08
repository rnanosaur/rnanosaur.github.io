---
title: "Run nanosaur on Gazebo"
excerpt: "Run nanosaur in simulation using Gazebo"
permalink: /tutorial/gazebo-simulation
classes: wide
header:
  teaser: /assets/tutorial/simulation/gazebo-nanosaur.png
---

Do you want to try nanosaur on a simulator? You can start directly from this tutorial.

 **before** to follow this tutorial, install [nanosaur simulators](/install/simulation)!

# Run script

To run nanosaur on gazebo you need first for all load all sources

{% capture code %}source nanosaur{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

When the shell is done, run the simulator using this launch file:

{% capture code %}ros2 launch nanosaur_gazebo gazebo.launch.py{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

The final output on gazebo, will be like:

{% include figure image_path="/assets/tutorial/simulation/gazebo-nanosaur.png" alt="nanosaur on gazebo" caption="nanosaur on gazebo" %}

# Run perception

If you want to enable the nanosaur perception run this command in a new shell

{% capture code %}nanosaur perception{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}
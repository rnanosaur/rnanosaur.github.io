---
title: "Run nanosaur on Gazebo"
excerpt: "Run nanosaur in simulation using Gazebo or Ignition Gazebo"
permalink: /tutorial/gazebo-simulation
classes: wide
header:
  teaser: /assets/docs/simulation/sim_02_ignition.png
---

Do you want to try nanosaur on a simulator? You can start directly from this tutorial.

 **before** to follow this tutorial, install [nanosaur simulators](/install/simulation)!

# Run script

To run nanosaur on gazebo you need first for all load all sources

{% capture code %}source nanosaur{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

When the shell is done, run the simulator using this launch file:

You have two simulators really simple to run: **Gazebo** or **Ignition Gazebo**

## Gazebo

{% capture code %}ros2 launch nanosaur_gazebo gazebo.launch.py{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

The final output on gazebo, will be like:

{% include figure image_path="/assets/docs/simulation/sim_01_gazebo.png" alt="nanosaur on Gazebo" caption="nanosaur on Gazebo" %}

## Ignition Gazebo

{% capture code %}ros2 launch nanosaur_igniton ignition.launch.py{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

The final output on gazebo, will be like:

{% include figure image_path="/assets/docs/simulation/sim_02_ignition.png" alt="nanosaur on Ignition Gazebo" caption="nanosaur on Ignition Gazebo" %}

# Run perception

If you want to enable the nanosaur perception run this command in a new shell

{% capture code %}nanosaur perception{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}
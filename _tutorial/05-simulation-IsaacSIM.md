---
title: "Run nanosaur on Isaac SIM"
excerpt: "Run nanosaur in simulation using Isaac SIM"
permalink: /tutorial/isaacsim-simulation
classes: wide
header:
  teaser: /assets/docs/simulation/sim_03_IsaacSIM.png
---

Do you want to try nanosaur on a simulator? You can start directly from this tutorial.

 **before** to follow this tutorial, install [nanosaur simulators](/install/simulation)!

# Run script

To run nanosaur on gazebo you need first for all load all sources

{% capture code %}source nanosaur{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

When the shell is done, run the simulator using this launch file:

You have two simulators really simple to run: **Gazebo** or **Ignition Gazebo**
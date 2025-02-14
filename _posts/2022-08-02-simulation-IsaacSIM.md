---
title: "Run nanosaur on Isaac SIM"
excerpt: "Run nanosaur in simulation using Isaac SIM"
permalink: /tutorial/isaacsim-simulation
classes: wide
header:
  teaser: /assets/images/collections/simulation/sim_03_IsaacSIM.png
categories:
  - Course
tags:
  - NVIDIA
---

Do you want to try nanosaur on a simulator? You can start directly from this tutorial.

 **before** to follow this tutorial, install [nanosaur simulators](/install/simulation)!

You can run your simulator directly 

{% capture code %}nanosaur simulation set{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

{% include figure image_path="/assets/images/collections/simulation/set_simulator.png" alt="Set nanosaur simulator" caption="Set nanosaur simulator" %}

Otherwise follow below how this script works!

# Run script

To run nanosaur on gazebo you need first for all load all sources

{% capture code %}cd nanosaur_core/src/nanosaur_simulations
bash nanosaur_isaac_sim/scripts/launcher.sh{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

In a second terminal

{% capture code %}source nanosaur
ros2 launch nanosaur_isaac_sim isaac_sim.launch.py{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

## Run perception

In your last terminal you need the perception module active

{% capture code %}nanosaur perception{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}
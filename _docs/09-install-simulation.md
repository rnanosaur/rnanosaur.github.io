---
title: "Install simulation"
permalink: /install/simulation
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

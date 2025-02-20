---
title: "Simulation nanosaur"
excerpt: "In this guide we start to work with nanosaur in simulation"
layout: collection
permalink: /simulation/
collection: simulation
entries_layout: grid
hidden: true
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/collections/simulation/IsaacSIM.png
  teaser: /assets/images/collections/simulation/IsaacSIM.png
  actions:
    - label: ":sparkling_heart: Sponsor"
      url: "https://github.com/sponsors/rbonghi"
    - label: ":star: Star"
      url: "https://github.com/rnanosaur/nanosaur"
install:
  - image_path: /assets/images/collections/install/cli/nanosaur-cli.png
    alt: "install nanosaur software"
    title: "💾 Install"
    excerpt: "In this section you will install all required nanosaur software. Starting from the nanosaur Command Line Interface (CLI) and after all software."
    url: /install/
    btn_label: "📃 learn more"
    btn_class: "btn--success"
tutorial:
  - image_path: /assets/images/collections/tutorial/nanosaur-rviz.png
    alt: "Tutorial nanosaur robot"
    title: "🕹️ Tutorial"
    excerpt: "If you don't know how to start and setup the nanosaur robot or how to drive follow this tutorial."
    url: /tutorial/
    btn_label: "📃 learn more"
    btn_class: "btn--success"
---

Before to move ahead working with nanosaur in simulation, if you did not do yet, follow the installation page. To enable your desktop to work with nanosaur.

{% include feature_row id="install" type="left" %}

If you follow the installation guide, we can start to configure your desktop to work with the simulator selected. At this time nanosaur can be simulated on:

* [NVIDIA Isaac Sim](/simulation/isaac-sim/)
* [Gazebo](/simulation/gazebo/)

You can use the simulation working with the simulators directly installed on your desktop, otherwise you can run everything in a docker container.

{% include feature_row id="tutorial" type="right" %}

With only two terminal and two commands you can switch on your simulation with nanosaur:

* First terminal:

{% capture code %}nanosaur simulation start{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

* Second terminal:

{% capture code %}nanosaur robot start{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

But how to configure your computer and how the simulators are working are explained in the next pages we setup the simulators from the `nanosaur-cli` and how to use them.

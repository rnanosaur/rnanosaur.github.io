---
title: "Tutorials"
excerpt: "In this section we learn how to control, setup and visualize nanosaur. The basic skills to work with nanosaur."
layout: collection
permalink: /tutorial/
hidden: true
classes: wide
author_profile: false
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/collections/tutorial/nanosaur-robot.png
  teaser: /assets/images/collections/tutorial/nanosaur-robot.png
  actions:
    - label: ":sparkling_heart: Sponsor"
      url: "https://github.com/sponsors/rbonghi"
    - label: ":star: Star"
      url: "https://github.com/rnanosaur/nanosaur"
    - label: "🤖 Discord"
      url: "https://discord.gg/NSrC52P5mw"
simulation:
  - image_path: /assets/images/collections/simulation/IsaacSIM.png
    alt: "simulation nanosaur"
    title: "👨‍💻 Simulation"
    excerpt: "In this guide you learn how to set up a simulation on your desktop and run it. If you are working in simulation follow this guide before to start the tutorial."
    url: /simulation/
    btn_label: "📃 learn more"
    btn_class: "btn--success"
---

In this tutorial we start to use nanosaur, controlling by keyboard or joystick and visualize the output on screen.

With this basic tutorial you will be always able to control nanosaur in simulation or real, changing the configuration and test new feature.

This tutorial will teach you how to use the robot and how to use the command:

{% capture code %}nanosaur robot{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

{% include figure image_path="assets/images/collections/tutorial/nanosaur-robot.png" alt="nanosaur robot" caption="nanosaur robot command" %}

{% include feature_row id="simulation" type="left" %}

Follow the guide below to learn how to use the robot.

**:memo: Note** These commands are always available for every installation you choose.
{: .notice}

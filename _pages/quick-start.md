---
title: "Quick-Start Guide"
excerpt: "Follow your path to work with nanosaur. Building the real robot or quickly work in simulation!"
layout: collection
permalink: /quick-start/
author_profile: false
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/collections/make/assembly/body-head-04-magnets.jpg
  teaser: /assets/images/collections/make/assembly/body-head-04-magnets.jpg
  actions:
    - label: ":sparkling_heart: Sponsor"
      url: "https://github.com/sponsors/rbonghi"
    - label: ":star: Star"
      url: "https://github.com/rnanosaur/nanosaur"
    - label: "🤖 Discord"
      url: "https://discord.gg/NSrC52P5mw"
sidebar:
  - nav: "about"
make-simulation:
  - image_path: /assets/images/nanosaur_build.jpg
    alt: "nanosaur"
    title: "🔧 Make"
    excerpt: "Follow this guide to build nanosaur, step by step, from the Bill of material, 3D printing, assembly and hardware setup."
    url: "/make/"
    btn_label: "📃 learn more"
    btn_class: "btn--primary"
  - image_path: /assets/images/collections/simulation/gazebo/nanosaur-gazebo-robot.png
    alt: "nanosaur quick-start"
    title: "👨‍💻 Simulation"
    excerpt: "In this guide we start to work with nanosaur in simulation, learning how to configure your computer and how to run nanosaur in simulation. You need to install first the nanosaur software."
    url: "/simulation/"
    btn_label: "📃 learn more"
    btn_class: "btn--primary"
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
courses:
  - image_path: /assets/images/collections/courses/courses-02.webp
    alt: "nanosaur courses"
    title: "📚 Courses"
    excerpt: "Let's learn how is it work nanosaur and how to build a ROS 2 package and work with Isaac ROS."
    url: /courses/
    btn_label: "📃 learn more"
    btn_class: "btn--success"
---

{% include 3steps.md %}

# 1. Make or Simulate it

Chose how to work with nanosaur, build in it or working in simulation.

{% include feature_row id="make-simulation" type="left" %}

# 2. Install

In this section the fundamentals to install all nanosaur software.

{% include feature_row id="install" type="left" %}

# 3. Tutorial

learn how to move nanosaur and all basics control to setup the robot.

{% include feature_row id="tutorial" type="left" %}

# 4. Courses

When your robot is ready, it's time to learn how to work with ROS and Isaac ROS. This course is for designed for you.

{% include feature_row id="courses" type="left" %}

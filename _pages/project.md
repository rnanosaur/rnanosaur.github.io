---
title: "Project"
excerpt: "Project timeline. Next step and current stage"
permalink: /project/
author_profile: false
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/nanosaur_arch.jpg
  teaser: /assets/images/nanosaur_arch.jpg
  actions:
    - label: ":sparkling_heart: Sponsor"
      url: "https://github.com/sponsors/rbonghi"
    - label: "📐 Architecture"
      url: /architecture/
    - label: "🚦 Status"
      url: /status/
sidebar:
  - nav: "about"
---

nanosaur is not a simple robot, but is designed like a real industrial robot, with a year develop roadmap, a develop workflow and a technical tagging release version.

# Roadmap

For rhe nanosaur roadmap 2022, will be defined and make stable all code for Isaac ROS, make a new nanosaur-shield to be able to use an NVIDIA Jetson Xavier NX and finally enable all simulator Gazebo and Isaac SIM

{% include figure image_path="/assets/docs/project/roadmap2022.drawio.png" alt="nanosaur project timeline" %}

For more technical detail and which featuer or issues are fixing, take look the nanosaur project 

[nanosaur project](https://github.com/orgs/rnanosaur/projects/6)

# Workflow

This project follow an extended version of [gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) where:

{% include figure image_path="/assets/docs/project/workflow.drawio.png" alt="nanosaur package architecture" %}

 * **main** branch record only stable release from the stable ros foxy branch
 * **ROS2** branches record progress for specific ROS2 repository (usually these branches are unstable)

# Tagging

nanosaur follow a code release tagging 

...

**:construction: This part will be updated soon.**<br/>For any issue join on [Discord](https://discord.gg/NSrC52P5mw)
{: .notice--warning}
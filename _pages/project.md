---
title: "Project"
excerpt: "Project timeline. Next step and current stage"
permalink: /project/
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/intro.jpg
  teaser: /assets/images/intro.jpg
  actions:
    - label: ":sparkling_heart: Sponsor"
      url: "https://github.com/sponsors/rbonghi"
    - label: "🦕 About"
      url: /about/
    - label: "📐 Architecture"
      url: /architecture/
    - label: "🚦 Status"
      url: /status/
sidebar:
  - nav: "about"
---

**:construction: This page is under construction.**<br/>For any issue join on [Discord](https://discord.gg/NSrC52P5mw)
{: .notice--warning}

# Roadmap

{% include figure image_path="/assets/docs/project/timeline.drawio.png" alt="nanosaur project timeline" %}

[nanosaur project](https://github.com/orgs/rnanosaur/projects/6)

# Workflow

This project follow an extended version of [gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) where:
 * **main** branch record only stable release from the stable ros foxy branch
 * **ROS"** branch record progress for specific ROS2 repository (usually these branch are unstable)

{% include figure image_path="/assets/docs/project/workflow.drawio.png" alt="nanosaur package architecture" %}
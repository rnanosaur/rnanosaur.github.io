---
title: "nanosaur script"
excerpt: "How it is works and how you can use the nanosaur script on your robot or on your desktop"
# permalink: /tutorial/nanosaur-script
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  teaser: /old/images/nanosaur-script/nanosaur_sheel.png
  overlay_image: /old/images/nanosaur-script/nanosaur_sheel.png
---

**:construction: This part will be updated soon.**<br/>For any issue join on [Discord](https://discord.gg/NSrC52P5mw)
{: .notice--warning}

The nanosaur script is an all-in-one script to manage nanosaur, updating the software, developing or running in simulation.

Use this script will be your first reference to use nanosaur avoiding weird commands or know the status of your robot.

# Overview

You already used this script when you installed all [nanosaur software](/install). In this scprit is already included a way to detect in which NVIDIA Jetson or desktop is running the script and install all dependencies or packages.

Also with this script you can remotely connect from your Ubuntu desktop machine and use the ROS2 tools to know what is going on your nanosaur.

**:bulb: Hint** You can use the bash completition to quickly work with nanosaur!
{: .notice--info}

The nanosaur script have to different set of commands if you are running on your robot or on your desktop, below we go in detail of all options available

# Manage the robot

```
nanosaur is your manager to control, update your robot or your desktop to work with nanosaur.

Commands:
  nanosaur help                     This help
  nanosaur info                     Status
  nanosaur cover                    Set cover type
  nanosaur config                   Open/create robot.yml in /opt/nanosaur/param (use nano)
  nanosaur dds                      Set DDS communication RMW_IMPLEMENTATION
  nanosaur domain                   Set ROS_DOMAIN_ID
  nanosaur install                  Install nanosaur environment.
  nanosaur update                   Update docker and scripts
  nanosaur distro                   Set nanosaur distribution
  nanosaur network [host/bridge]    Select network configuration
  nanosaur wakeup/down              start/stop nanosaur systems (eq. nanosaur up -d)
  nanosaur [start/restart/stop/up/logs/top/rm/exec]  Control nanosaur docker
  nanosaur run [CNT:core][CMD:bash] Run a new nanosaur container for development
  nanosaur clean                    clean all dangling images

nanosaur manager v2.0.3 | Configuration folder is in /opt/nanosaur
```

# Manage from desktop

```
nanosaur is your manager to control, update your robot or your desktop to work with nanosaur.

Commands:
  nanosaur help                     This help
  nanosaur info                     Status
  nanosaur cover                    Set cover type
  nanosaur config                   Open/create robot.yml in /opt/nanosaur/param (use nano)
  nanosaur dds                      Set DDS communication RMW_IMPLEMENTATION
  nanosaur domain                   Set ROS_DOMAIN_ID
  nanosaur install                  Install nanosaur environment.
  nanosaur update                   Update docker and scripts
  nanosaur build                    Build developer boards
  nanosaur branch                   Set branch nanosaur projects
  nanosaur perception               Run docker with Isaac ROS perception
  nanosaur teleop                   Run the nanosaur keyboard controller
Simulation info:
  nanosaur simulation               Start the nanosaur simulator
  nanosaur ignition                 Set simulation Ignition version. Default: $IGNITION_VERSION

nanosaur manager v2.0.3 | Configuration folder is in /opt/nanosaur
```

## Simulation

TODO
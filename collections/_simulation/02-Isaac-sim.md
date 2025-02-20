---
title: "Nanosaur on NVIDIA Isaac Sim"
excerpt: "How to work with nanosaur on Isaac Sim"
permalink: /simulation/isaac-sim/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
header:
  teaser: /assets/images/collections/simulation/isaac-sim/isaac-sim-host.png
---

How is it work [Isaac Sim](https://developer.nvidia.com/isaac/sim) with nanosaur?

In this guide we are going more in detail about this Simulator.

# What is Isaac Sim?

> NVIDIA Isaac Sim™ is a reference application built on NVIDIA Omniverse that enables developers to develop, simulate, and test AI-driven robots in physically-based virtual environments.

{% include figure image_path="/assets/images/collections/simulation/isaac-sim/hero_shot.png" alt="Isaac Sim" caption="Isaac Sim" %}

Learn more: [NVIDIA Isaac Sim](https://developer.nvidia.com/isaac/sim).

# Requirements

Check the requirements for your computer to run Isaac Sim at the [requirement page](https://docs.isaacsim.omniverse.nvidia.com/4.5.0/installation/requirements.html).

# Start NVIDIA Isaac Sim

Isaac Sim can be run from a docker container or you can run native from your computer. The only command you need to start the simulator is:

{% capture code %}nanosaur simulation start{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

Remember to setup your computer with [`nanosaur simulation set`](/simulation/configuration#set-simulator).

**:warning: WARNING** If is your first time you start Isaac Sim will require a while before the simulator start.
{: .notice--warning}

**:memo: Note** If you set [`nanosaur simulation headless`](/simulation/configuration#headless-mode) to **yes** will be not activated any GUI.
{: .notice}

## GUI from docker container

After the simulation start you will see a new folder in `nanosaur/isaac-sim-cache` where all Isaac Sim cached will be stored. This folder will save you time for all next Isaac Sim restart!

```sh
user-home/
└── nanosaur/
    └── ...
    └── isaac-sim-cache
    └── nanosaur.yaml
```

If you work with Isaac Sim from docker, you need the external Streaming tool to visualize the simulator.

Jump to the [download page](https://docs.isaacsim.omniverse.nvidia.com/latest/installation/download.html#latest-release) and download the Streaming Client for your operative system.

**:memo: Note** By downloading or using the NVIDIA Isaac Sim WebRTC Streaming Client, you agree to the [NVIDIA Isaac Sim WebRTC Streaming Client License](https://docs.isaacsim.omniverse.nvidia.com/4.5.0/common/license-isaac-sim-webrtc-streaming-client.html) Agreement.
{: .notice}

{% include figure image_path="/assets/images/collections/simulation/isaac-sim/isaac-sim-download-client.png" alt="Isaac Sim Streaming client download" caption="Isaac Sim Streaming client download" %}

Follow the installation steps:

1. Extract the zip file
2. In Terminal, run `chmod +x *.AppImage` to allow the app to be executable.
3. Double-click the AppImage file to run Isaac Sim WebRTC Streaming Client.

**:memo: Note** *libfuse2* is required to run on Ubuntu 22.04 or later. See Install [FUSE 2](https://docs.appimage.org/user-guide/troubleshooting/fuse.html#setting-up-fuse-2-x-alongside-of-fuse-3-x-on-recent-ubuntu-22-04-debian-and-their-derivatives).
{: .notice}

At the end you will the Isaac Sim Streaming client coming up.

Just press **Connect** , you don't need to change the default configuration.

{% include figure image_path="/assets/images/collections/simulation/isaac-sim/isaac-sim-docker-wrtc-client.png" alt="Isaac Sim client" caption="Isaac Sim client" %}

After a while you will see the the User Interface coming up with a world.

{% include figure image_path="/assets/images/collections/simulation/isaac-sim/isaac-sim-docker-wrtc.png" alt="Nanosaur on Streaming client" caption="Nanosaur on Streaming client" %}

Now you can open a *new terminal* and switch on the robot with:

{% capture code %}nanosaur robot start{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

## GUI from host

If you selected the run from your host and Isaac Sim is properly [installed](https://docs.isaacsim.omniverse.nvidia.com/latest/installation/download.html#latest-release) you will see the User Interface coming up like the image below.

{% include figure image_path="/assets/images/collections/simulation/isaac-sim/isaac-sim-host.png" alt="Isaac Sim from host" caption="Isaac Sim from host" %}

Now you can open a *new terminal* and switch on the robot with:

{% capture code %}nanosaur robot start{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

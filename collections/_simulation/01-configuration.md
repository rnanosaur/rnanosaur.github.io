---
title: "Nanosaur simulator configuration"
excerpt: "In this guide we configure the nanosaur cli to work with the right simulator"
permalink: simulation/configuration/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
header:
  teaser: /assets/images/collections/simulation/configuration/nanosaur-sim.png
---

How to work in simulation? In this guide we analyze all configuration you can setup on your computer.

**:memo: Note** Work is simulation is only allowed on your computer. This command is not available from your NVIDIA Jetson.
{: .notice}

{% capture code %}nanosaur simulation{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

**:memo: Note** This command has also the alias `nanosaur sim`.
{: .notice}

An help will appear on your terminal, with all options available

{% include figure image_path="/assets/images/collections/simulation/configuration/nanosaur-sim.png" alt="nanosaur simulation" caption="nanosaur simulation command" %}

# Start simulator

If you have [setup](#set-simulator) your machine with a simulator, this command execute the simulator with the configuration request.

{% capture code %}nanosaur simulation start{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

# Set simulator

This command set up nanosaur to start in simulation. There are two main options: [NVIDIA Isaac Sim](https://developer.nvidia.com/isaac/sim) and [Gazebo](https://gazebosim.org/).

{% capture code %}nanosaur simulation set{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

**:bulb: Hint** Pressing **ENTER** will be saved the new configuration. Pressing **CTRL-C** the operation will be interrupted.  
{: .notice--info}

{% include figure image_path="/assets/images/collections/simulation/configuration/nanosaur-sim-set.png" alt="nanosaur simulation set" caption="nanosaur simulation set command" %}

If on your computer is native installed current ROS 2 distribution, on your device will appear some extra questions, like the image below:

{% include figure image_path="/assets/images/collections/simulation/configuration/nanosaur-sim-set-host.png" alt="nanosaur simulation set on host" caption="nanosaur simulation set command on host" %}

The command will ask where you want to start the simulation, if native on your host or in a docker container.

If you select Isaac Sim, an extra menu will browse your computer to find an Isaac Sim installed. The `Custom Path` will be always available if you want manually set a folder.

**:memo: Note** *nanosaur-cli* browse in `~/.local/share/ov/pkg` and `~` folders.
{: .notice}

**:memo: Note** When you select `Custom Path` the *nanosaur-cli* check if the Isaac Sim version is complaint with the nanosaur distribution.
{: .notice}

# Set world

This command configure the world you want to use to test nanosaur. There are different options and you can choice.

{% capture code %}nanosaur simulation world{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

**:bulb: Hint** Pressing **ENTER** will be saved the new configuration. Pressing **CTRL-C** the operation will be interrupted.  
{: .notice--info}

{% include figure image_path="/assets/images/collections/simulation/configuration/nanosaur-sim-world.png" alt="nanosaur simulation world" caption="nanosaur simulation world command" %}

**:memo: Note** If you designed a new world you can use the special command `nanosaur simulation world --new NEW` to add in a customized setup.
{: .notice}

# Start simulation headless

You don't need to visualize what is going on the simulation, you can always set up the headless mode to disable the simulator user interface.

{% capture code %}nanosaur simulation headless{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

**:bulb: Hint** Pressing **ENTER** will be saved the new configuration. Pressing **CTRL-C** the operation will be interrupted.  
{: .notice--info}

{% include figure image_path="/assets/images/collections/simulation/configuration/nanosaur-sim-headless.png" alt="nanosaur simulation headless" caption="nanosaur simulation headless command" %}

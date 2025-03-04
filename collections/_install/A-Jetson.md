---
title: "Install an NVIDIA Jetson"
excerpt: "Simple how to quick start an NVIDIA Jetson"
permalink: install/jetson
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
header:
  teaser: /assets/images/collections/install/Jetson/jetson-orin-nano.png
---

Now nanosaur is almost done! You need only to setup the MicroSD card and start your robot.

# Format Micro SD

Go on [NVIDIA Jetpack](https://developer.nvidia.com/embedded/Jetpack) webpage and download the latest **SD Card Image** for your NVIDIA Jetson.

**:warning: WARNING** Please download the right version for your NVIDIA Jetson 2Gb or 4Gb
{: .notice--warning}

1. Download [NVIDIA Jetpack](https://developer.nvidia.com/embedded/Jetpack) **{{ site.nanosaur.requirements.jetpack }}**
2. Download, install, and launch [Etcher](https://www.balena.io/etcher)
3. Click “Select image” and choose the zipped image file downloaded earlier.
4. Insert your microSD card.
5. If you have no other external drives attached, Etcher will automatically select the microSD card as target device. Otherwise, click “Select drive” and choose the correct device.
6. Click “Flash!”

{% capture notice-text %}
**:bulb: Hint** For this, we'll assume you've set up your Jetson Nano using the online Getting Started guide.

* [Getting Started With Jetson Nano Developer Kit](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit)
* [Getting Started with Jetson Nano 2GB Developer Kit](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-2gb-devkit)
{% endcapture %}

<div class="notice--success">
  {{ notice-text | markdownify }}
</div>

{% include figure image_path="/assets/images/collections/install/Jetson/Etcher.png" alt="Etcher view" caption="Etcher view" %}

## Configuration Jetson

Remember to configure your NVIDIA Jetson with these parameters:

* Your name: *Chose your best user name*
* Your computer's name: *nanosaur (suggested)*
* Pick a username: *Usually the same of your name*
* Password: *Chose your best password*

Set: **Log in Automatically**

Will appear something like the picture below:

{% include figure image_path="/assets/images/collections/install/Jetson/05-User.png" alt="Configuration Jetson" caption="Configuration Jetson" %}

## Connect to WiFi

If you have not already connected your Jetson Nano to your Wi-Fi network, press the button below to follow this specific tutorial.

[Wi-Fi configuration](/install/wifi){: .align-center .btn .btn--info .btn--large}

# Update and clean your Jetson

First step connect to your NVIDIA Jetson and **update & upgrade** with the commands below:

{% capture code %}
sudo apt update
sudo apt -y full-upgrade
sudo apt -y autoremove
{% endcapture %}
{% include code.html code=code lang="sh" copyable=true %}

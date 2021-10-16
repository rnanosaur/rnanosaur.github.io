---
title: "Install"
permalink: /install/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
---

Now NanoSaur is almost done! You need only to setup the MicroSD card and start your robot.

# Format Micro SD

Go on [NVIDIA Jetpack](https://developer.nvidia.com/embedded/Jetpack) webpage and download the latest **SD Card Image** for your NVIDIA Jetson.

**:warning: WARNING** Please download the right version for your NVIDIA Jetson 2Gb or 4Gb
{: .notice--warning}

1. Download the last [NVIDIA Jetpack](https://developer.nvidia.com/embedded/Jetpack)
2. Download, install, and launch [Etcher](https://www.balena.io/etcher)
3. Click “Select image” and choose the zipped image file downloaded earlier.
4. Insert your microSD card.
5. If you have no other external drives attached, Etcher will automatically select the microSD card as target device. Otherwise, click “Select drive” and choose the correct device.
6. Click “Flash!”

**Hint** For this, we'll assume you've set up your Jetson Nano using the online Getting Started guide.<br/>* [Getting Started With Jetson Nano Developer Kit](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit)<br/>* [Getting Started with Jetson Nano 2GB Developer Kit](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-2gb-devkit)
{: .notice--success}

{% include figure image_path="/assets/docs/install/Etcher.png" alt="Etcher view" caption="Etcher view" %}

## Connect to WiFi

If you haven't already, connect your Jetson Nano to your Wi-Fi network.

[Follow this Wi-Fi setup guide](/extra/wifi).

# Install and run nanosaur

First step connect to your NVIDIA Jetson, **update & upgrade** the distribution and install **curl**

{% capture code %}sudo apt update && sudo apt -y full-upgrade && sudo apt -y autoremove && sudo apt -y install curl{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

When your machine will be up to date, we can run the Nanosaur installation script.

:clipboard: Copy and paste on the NVIDIA Jetson terminal the following line

{% capture code %}curl https://raw.githubusercontent.com/rnanosaur/nanosaur/master/nanosaur/scripts/nanosaur -o $HOME/nanosaur && chmod +x $HOME/nanosaur && $HOME/nanosaur install{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

Follow the instructions and reboot your board!

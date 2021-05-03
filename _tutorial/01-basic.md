---
title: "Hello NanoSaur"
excerpt: "Let's start with NanoSaur, manually control."
permalink: /tutorial/basic
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
---

Now you can manually drive 🦕 NanoSaur on your desktop.

If you are not familiar with it, please wait or join on [Discord](https://discord.gg/NSrC52P5mw)

There are few steps to follow to install the required packages on your Ubuntu desktop and drive Nanosaur by Keyboard or by Joystick

# Install on your desktop ROS2

Follow the ROS2 installation on this link

[ROS2 Installation](https://docs.ros.org/en/foxy/Installation.html)

When is done, will move forward installing the required 🦕 NanoSaur packages

## Setup Nanosaur

Like the nanosaur installation, download and run the Nanosaur script on your desktop following the line below

{% capture code %}curl https://raw.githubusercontent.com/rnanosaur/nanosaur/master/nanosaur_bringup/scripts/install.sh -o nanosaur_install.sh && chmod +x nanosaur_install.sh && ./nanosaur_install.sh --desktop{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

The script install in your desktop:
 * A new **nanosaur** command
 * In your home the nanosaur workspace called **nanosaur_ws**

# Move your nanosaur

From your shell run now:

{% capture code %}source nanosaur{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

Your shell now appear with this look
{% include figure image_path="/assets/tutorial/base/nanosaur_sheel.png" alt="NanoSaur desktop sheel" caption="Nanosaur desktop sheel" %}

## Move Nanosaur from joystick

Before to move nanosaur check:
 * Nanosaur is running (appears two eyes on the Nanosaur oleds)
 * Your desktop is connected

{% capture code %}ros2 launch teleop_twist_joy teleop-launch.py{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

Bring your Joypad and drive nanosaur, following this simple setup:

**Left Analog** joypad
 * Up/Down: speed
 * Left/Right: turn the robot
 * button: Enable the robot to move

Well done! Nanosaur is moving! :grinning:
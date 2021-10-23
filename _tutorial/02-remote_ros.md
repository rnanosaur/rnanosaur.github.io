---
title: "remote nanosaur"
excerpt: "Setup the remote connection on ROS2 and use rviz"
permalink: /tutorial/desktop
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  teaser: /assets/tutorial/remote/nanosaur_keyboard.png
  overlay_image: /assets/tutorial/remote/nanosaur_keyboard.png
---

Now you can manually drive 🦕 nanosaur on your desktop.

If you are not familiar with it, please wait or join on [Discord](https://discord.gg/NSrC52P5mw)

There are few steps to follow to install the required packages on your Ubuntu desktop and drive Nanosaur by Keyboard or by Joystick.

# Install on your desktop ROS2

Follow the ROS2 installation on this link

[ROS2 Installation](https://docs.ros.org/en/foxy/Installation.html)

When is done, will move forward installing the required 🦕 nanosaur packages

## Setup Nanosaur

Like the nanosaur installation, download and run the Nanosaur script on your desktop following the line below

{% capture code %}curl https://raw.githubusercontent.com/rnanosaur/nanosaur/master/nanosaur/scripts/nanosaur -o $HOME/nanosaur && chmod +x $HOME/nanosaur && $HOME/nanosaur install dev{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

The script install in your desktop:
 * A new [**nanosaur**](https://github.com/rnanosaur/nanosaur/wiki/script_nanosaur) command
 * In your home a new ROS2 nanosaur workspace **nanosaur_ws**

# Move your nanosaur

From your shell run now:

{% capture code %}source nanosaur{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

Your shell now appear with this look
{% include figure image_path="/assets/tutorial/remote/nanosaur_sheel.png" alt="nanosaur desktop sheel" caption="Nanosaur desktop sheel" %}

## Move Nanosaur from a keyboard

Before to move nanosaur check:
 * Nanosaur is running (appears two eyes on the Nanosaur oleds)
 * Your desktop is connected in the same wifi network

{% capture code %}ros2 run teleop_twist_keyboard teleop_twist_keyboard --ros-args --remap cmd_vel:=key_vel{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

Now you can drive nanosaur from your keyboard, following the instruction on terminal

{% include figure image_path="/assets/tutorial/remote/nanosaur_keyboard.png" alt="nanosaur keyboard navigation" caption="nanosaur keyboard navigation" %}

Well done! Nanosaur is moving! :grinning:
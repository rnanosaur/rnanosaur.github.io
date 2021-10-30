---
title: "Keyboard drive"
excerpt: "Drive by keyboard or watch nanosaur on rviz"
permalink: /tutorial/keyboard
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  teaser: /assets/tutorial/remote/nanosaur_keyboard.png
  overlay_image: /assets/tutorial/remote/nanosaur_keyboard.png
---

Now you can manually drive 🦕 nanosaur on your desktop.

If you are not familiar with it, please wait or join on [Discord](https://discord.gg/NSrC52P5mw)

There are few steps to follow to install the required packages on your Ubuntu desktop and drive Nanosaur by Keyboard or by Joystick.

<a href="/extra/install-desktop" class="btn btn--success">Install nanosaur workspace on Desktop</a>

# Setup shell

From your shell run now:

{% capture code %}source nanosaur{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

Your shell now appear with this look
{% include figure image_path="/assets/tutorial/remote/nanosaur_sheel.png" alt="nanosaur desktop sheel" caption="Nanosaur desktop sheel" %}

# Move Nanosaur with your keyboard

Before to move nanosaur check:
 * Nanosaur is running (appears two eyes on the Nanosaur oleds)
 * Your desktop is connected in the same wifi network

{% capture code %}ros2 run teleop_twist_keyboard teleop_twist_keyboard --ros-args --remap cmd_vel:=key_vel{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

Now you can drive nanosaur from your keyboard, following the instruction on terminal

{% include figure image_path="/assets/tutorial/remote/nanosaur_keyboard.png" alt="nanosaur keyboard navigation" caption="nanosaur keyboard navigation" %}

Well done! Nanosaur is moving! :grinning:
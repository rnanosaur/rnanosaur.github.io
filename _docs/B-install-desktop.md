---
title: "Install nanosaur workspace on Desktop PC"
excerpt: "Install nanosaur workspace on desktop PC"
permalink: /extra/install-desktop
classes: wide
---

Follow the ROS2 installation on this link

[ROS2 Installation](https://docs.ros.org/en/foxy/Installation.html)

When is done, will move forward installing the required 🦕 nanosaur packages

# Setup Nanosaur

Like the nanosaur installation, download and run the Nanosaur script on your desktop following the line below

{% capture code %}curl https://raw.githubusercontent.com/rnanosaur/nanosaur/master/nanosaur/scripts/nanosaur -o $HOME/nanosaur && chmod +x $HOME/nanosaur && $HOME/nanosaur install{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

The script install in your desktop:
 * A new [**nanosaur**](https://github.com/rnanosaur/nanosaur/wiki/script_nanosaur) command
 * A new ROS2 nanosaur workspace **nanosaur_ws** in your home folder

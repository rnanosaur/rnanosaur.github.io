---
title: "Nanosaur wake-up & shutdown"
excerpt: "All in one command to quickly to startup your robot!"
permalink: /tutorial/wake-up/
classes: wide
header:
  teaser: /assets/images/collections/tutorial/nanosaur-robot.png
---

There are two special commands to quickly start up your robot and use, without navigating around the `nanosaur-cli`.

These commands depending on which environment you are working will quickly start up everything, for mode details read:

* [nanosaur start & stop](/tutorial/start)
* [nanosaur simulation](/simulation/)

# Wake Up

The nanosaur wake up start up your robot such the same command of `nanosaur robot start --detach` and set all services to restart on boot of your Jetson.

This command is helpful, when you want to use nanosaur when you boot your board saving time to manually switch on the robot.

{% capture code %}nanosaur wake-up{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

## Wake up on desktop

If you are working on your desktop, this command execute also [`nanosaur simulation start`](/simulation/) but compare the robot version, in this case the execution will be not detached.

If you want to stop the system you need only to press the combination of **CTRL-C**.

# Shutdown

The shutdown command is exactly equivalent to the `nanosaur robot stop`.

{% capture code %}nanosaur shutdown{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

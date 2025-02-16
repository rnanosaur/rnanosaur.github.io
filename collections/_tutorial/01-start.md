---
title: "Nanosaur Start & Stop"
excerpt: "How to switch on your nanosaur in simulation or real"
permalink: /tutorial/start/
classes: wide
header:
  teaser: /assets/images/collections/tutorial/configure/nanosaur-robot-config.png
---

This command will start the robot with the selected configuration and all engines selected active.

It's a simple and powerful command to enable your robot and start to use it. This command works in simulation and on the real robot.

# Robot Start

If you want to start your robot you can simple execute the command below:

{% capture code %}nanosaur robot start{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

You will see a terminal prompt the status of all system turning up and the robot will start to work and if you want to stop the robot you will need only to press the combination of **CTRL-C**.

## Detached mode

In the case you want a returning terminal, you can add the option `--detach`. This configuration at the end of the robot start will return on your prompt.

{% capture code %}nanosaur robot start --detach{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

# Robot Stop

If you are working in `--detach` mode and you want to switch off the robot, the `stop` command will stop all system and the robot will be switched off.

{% capture code %}nanosaur robot stop{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

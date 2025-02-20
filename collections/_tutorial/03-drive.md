---
title: "Keyboard drive"
excerpt: "How to drive and control your nanosaur, real or simulated."
permalink: /tutorial/drive/
classes: wide
header:
  teaser: /assets/images/collections/tutorial/nanosaur-robot-drive.png
---

Not always you want an autonomous robot, sometimes you need to drive the robot or control before something dangerous is happening.

How to run a keyboard control?

{% capture code %}nanosaur robot drive{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

**:memo: Note** If your device has a valid version of ROS installed, you can choice to run instead in a docker, directly on your host. A question will appear everytime you type the command.
{: .notice}

The terminal will show something like the picture below:

{% include figure image_path="/assets/images/collections/tutorial/nanosaur-robot-drive.png" alt="nanosaur robot drive" caption="nanosaur robot drive command" %}

# What does it do?

This command launches the `teleop_twist_keyboard` node, which allows you to control a robot using keyboard inputs. It publishes `geometry_msgs/Twist` messages on the `nanosaur/key_vel` topic.

# How to use it?

After running the command, you'll see an interface with instructions showing which keys to press to move the robot forward, backward, turn left, turn right, and stop. The typical controls are:

* `i` → Move forward
* `,` → Move backward
* `j` → Turn left
* `l` → Turn right
* `k` → Stop

It also supports adjusting linear and angular speed using other key bindings.

---
title: "Nanosaur visualization"
excerpt: "How to debug and visualize what the robot is doing."
permalink: /tutorial/visualize/
classes: wide
header:
  teaser: /assets/images/collections/tutorial/nanosaur-rviz.png
---

What is going on my robot? Watching the robot moving autonomously is not enough and debugging from a User Interface can be the right solution to see what is going on the robot.

How to do that?

{% capture code %}nanosaur robot rviz{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

**:memo: Note** If your device has a valid version of ROS installed, you can choice to run instead in a docker, directly on your host. A question will appear everytime you type the command.
{: .notice--info}

The terminal will show something like the picture below:

{% include figure image_path="/assets/images/collections/tutorial/nanosaur-rviz.png" alt="nanosaur robot rviz" caption="nanosaur robot rviz command" %}

# What is RViz in ROS 2?

RViz (ROS Visualization) is a powerful 3D visualization tool for ROS (Robot Operating System). It allows you to visualize sensor data, robot models, navigation maps, and more.

# What you can do?

* Visualize sensor data (e.g., LiDAR, depth cameras, IMU).
* Display the nanosaur model.
* Show real-time transforms (TF frames).
* Overlay navigation maps and planned paths.
* Debug robot movement and localization.
* Use interactive markers to control the robot.

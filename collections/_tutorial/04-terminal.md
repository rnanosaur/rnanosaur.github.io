---
title: "Nanosaur terminal"
excerpt: "A prompt with a direct access to nanosaur can be the best choice if you need an deep debug!"
permalink: /tutorial/terminal/
classes: wide
header:
  teaser: /assets/images/collections/tutorial/terminal/nanosaur-terminal-rqt-graph.png
---

When the work becoming hard, it's time to directly access to a terminal to the robot! This command will always give you the access to control nanosaur even if anything is installed on your computer!

How to do it?

{% capture code %}nanosaur robot terminal{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

The terminal will show something like the picture below:

{% include figure image_path="/assets/images/collections/tutorial/terminal/nanosaur-terminal.png" alt="nanosaur robot terminal" caption="nanosaur robot terminal command" %}

From this prompt you have full access to a terminal with ROS 2 installed and a full diagnostic access to the robot.

# Example usage

Example you can read all topics running on your robot or open the `rqt_graph` to know if all node are well connected and running on your robot.

## Topic lists

`ros2 topic list` lists all active topics in your ROS 2 system. Topics are the communication channels through which ROS nodes exchange messages.

{% capture code %}ros2 topic list{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

{% include figure image_path="/assets/images/collections/tutorial/terminal/nanosaur-terminal-topics.png" alt="nanosaur topics" caption="nanosaur topics" %}

## rqt_graph

launches a graphical tool that visualizes the **ROS 2 computation graph**, showing nodes and the topics they communicate through.

What Does `rqt_graph` Show?

* **Nodes** (ROS 2 processes)
* **Topics** (communication channels between nodes)
* **Publishers & Subscribers** (who is sending and receiving data)

{% capture code %}rqt_graph{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

{% include figure image_path="/assets/images/collections/tutorial/terminal/nanosaur-terminal-rqt-graph.png" alt="nanosaur rqt graph" caption="nanosaur rqt graph" %}

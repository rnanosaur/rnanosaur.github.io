---
title: "Architecture"
excerpt: "nanosaur is based with ROS2 and Isaac ROS"
permalink: /architecture/
author_profile: false
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/nanosaur_arch.jpg
  teaser: /assets/images/nanosaur_arch.jpg
  actions:
    - label: ":sparkling_heart: Sponsor"
      url: "https://github.com/sponsors/rbonghi"
    - label: "👷 Project"
      url: /project/
    - label: "🚦 Status"
      url: /status/
sidebar:
  - nav: "about"
---

nanosaur is made with the same capabilities of a real industrial AMR robot. The main architecture is splitted in different parts.

# Architecture

The logic to drive and control this robot is the same of a control loop system. Where the driver and the mechanical parts are located on the left of the image below.

{% include figure image_path="/assets/docs/architecture/nanosaur.architecture.drawio.png" alt="nanosaur top architecture overview" %}

All perception is GPU accelerated to recognize and detect where nanosaur is moving and localize it in the world. This green block have different estimators for location, using the dead recognition from the cameras and motors (soon), mapping the environment and detection, object on the environment.

The blue block is all the control and navigation nanosaur system. The path planner is part of this block and same the object avoidance. To be enabled this block, read the input coming from the perception block and generate an output to drive the two nanosaur tracks.

The high level control (will be designed soon) is a supervision manager to make a task for a robot, example drive a robot to pick up something or move objects in a world. This Block take in inputs from the perception block and drive the control block.

A real nanosaur is a combination of all these blocks, in the parts below, the real architecture for each sensor used. All blocks are splitted in different docker containers, where the **perception** is always GPU accelerated and run on your robot.

There are mainly three types architectures, different for the camera in use, where the perception block change:
 * [Monocular camera](#monocular-camera)
 * [Realsense](#realsense)
 * [ZEDmini](#zedmini)

## Monocular camera

If you are building a nanosaur with a monocular camera, such a raspberry Pi camera or a fisheye camera, the architecture and all **ROS2** node are like the image below.

{% include figure image_path="/assets/docs/architecture/nanosaur-argus.architecture.drawio.png" alt="nanosaur architecture Argus camera" %}

* The **core** block is a set of package to control with path planners and low level controller the two motors of nanosaur. In this block there is also a joystick control and a board manager, with a twist_mux you are able to drive manually the robot with your joystick and in the same time enable the autonomous drive.

* The **diagnostic** block, is a web-interface to know realtime the status and set high level control to the robot. This block is also replicable on your desktop and you can use **rviz2** to read all status coming from the robot.

* The **perception** block read the stream of the monocular camera and with a set of Isaac ROS packages convert, resize and align the image to be used from the monocular localization. On the same block there is the apriltag detection.

## Realsense

{% include figure image_path="/assets/docs/architecture/nanosaur-realsense.architecture.drawio.png" alt="nanosaur architecture realsense camera" %}

* The **core** block is a set of package to control with path planners and low level controller the two motors of nanosaur. In this block there is also a joystick control and a board manager, with a twist_mux you are able to drive manually the robot with your joystick and in the same time enable the autonomous drive.

* The **diagnostic** block, is a web-interface to know realtime the status and set high level control to the robot. This block is also replicable on your desktop and you can use **rviz2** to read all status coming from the robot.

* The **perception** block differently from a monocular camera, use the [Isaac ROS visual slam](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_visual_slam) to localize the robot in the environment and generate an output instantaneously available for the navigation block. 

## ZEDmini

{% include figure image_path="/assets/docs/architecture/nanosaur-zed.architecture.drawio.png" alt="nanosaur architecture ZED mini camera" %}

* The **core** block is a set of package to control with path planners and low level controller the two motors of nanosaur. In this block there is also a joystick control and a board manager, with a twist_mux you are able to drive manually the robot with your joystick and in the same time enable the autonomous drive.

* The **diagnostic** block, is a web-interface to know realtime the status and set high level control to the robot. This block is also replicable on your desktop and you can use **rviz2** to read all status coming from the robot.

* The **perception** block is GPU accelerated and use the full [ZED SDK](https://www.stereolabs.com/developers/release/) capabilities to know realtime the localization, floor plan, pointcloud coming out from the [ROS2 ZED wrapper](https://github.com/stereolabs/zed-ros2-wrapper).

# Package architecture 

To build each docker container, nanosaur use a combination of different repositories, where are located different ROS2 packages:

{% include figure image_path="/assets/docs/architecture/packages.drawio.png" alt="nanosaur package architecture" %}


Following the picture above, there are:
## core

* [nanosaur](https://github.com/rnanosaur/nanosaur)
* [nanosaur_robot](https://github.com/rnanosaur/nanosaur_robot)

Extra packages:
* [ros2_jetson_stats](https://github.com/rbonghi/ros2_jetson_stats.git)
* [ros2_system_manager](https://github.com/rbonghi/ros2_system_manager.git)

## Perception

* [nanosaur](https://github.com/rnanosaur/nanosaur)
* [nanosaur_perception](https://github.com/rnanosaur/nanosaur_perception)

Extra packages:
* [Isaac ROS packages](https://github.com/NVIDIA-ISAAC-ROS)

## Simulations (simulators on desktop)

* [nanosaur](https://github.com/rnanosaur/nanosaur)
* [nanosaur_simulations](https://github.com/rnanosaur/nanosaur_simulations.git)

# Nanosaur robot hardware

This new architecture will be released in the new nanosaur software **v2.1**

**This picture can change!**

{% include figure image_path="/assets/docs/architecture/nanosaur_robot_new.architecture.drawio.png" alt="nanosaur robot package overview" %}
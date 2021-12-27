---
title: "Designing Robots with NVIDIA Isaac GEMs for ROS"
excerpt: "How to use AprilTags detection on nanosaur. Post from NVIDIA Developer blog."
classes: wide
link: https://developer.nvidia.com/blog/designing-robots-with-isaac-gems-for-ros/
categories:
  - Course
tags:
  - NVIDIA
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/tutorial/AprilTagROS/ApriltagROS.jpg
  teaser: /assets/tutorial/AprilTagROS/ApriltagROS.jpg
  actions:
    - label: "blog post"
      url: "https://developer.nvidia.com/blog/designing-robots-with-isaac-gems-for-ros/"
---

NVIDIA Isaac GEMs for ROS provides a set of GPU-accelerated packages for your ROS2 application, improving throughput on image processing and DNN-based perception models. These ROS2 packages are built from ROS2 Foxy, the first Long Stable Release (LTS) to come out of the robotics community.

This post investigates how you can accelerate your robot’s deployment by implementing NVIDIA Isaac ROS GEMs. The focus of this post is AprilTags detection using nanosaur, a simple open-source robot based on the NVIDIA Jetson platform.
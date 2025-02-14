---
title: "Changelog"
excerpt: "History of nanosaur updates"
permalink: /changelog/
author_profile: false
classes: wide
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
    - label: "📐 Architecture"
      url: /architecture/
sidebar:
  - nav: "about"
---

<!-- CHANGELOG START -->
# Changelog

## 2.0 (8th June 2022)

- Fully Isaac ROS integration
- New repository for perception https://github.com/rnanosaur/nanosaur_perception
- Release cover for:
  - Realsense d435
  - ZED mini camera
- New documentation

## 1.5 (15th Oct. 2021)

A new stable version of nanosaur docker, basic improvements:

- New nanosaur script for jetson and desktop
- New docker-compose with three containers (core,WebGUIi andauto-updaterr)
- Reshape packages

## 1.4 (13rd Aug. 2021)

Rearrange all nanosaur packages:

- nanosaur_hardware -> nanosaur_base
- Now you can edit all configuration of nanosaur from a yml file (inside or outside docker)
- nanosaur_camera fixed. Run and works on rviz2 using cyclonedds
- New dockerfile starting from dustynv/ros:foxy-ros-base-l4t-r32.5.0
- Dockerfile size only 1.8Gb

## 1.3 (4th July 2021)

General upgrades

## 1.2 (7th Apr. 2021)

Default ball bearings F686ZZ

## 1.1 (18th Feb. 2021)

Improve nanosaur layout for powerbanks with different size

## 1.0 (17th Feb. 2021)

First release of nanosaur software based on ROS2 Foxy
<!-- CHANGELOG END -->
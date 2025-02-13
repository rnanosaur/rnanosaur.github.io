---
title: "Status"
excerpt: "Current nanosaur software deploy status"
permalink: /status/
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

On this page are collected all Continuous Integration badges and Docker image size badges.

# Continuous Integration

**Latest** = ROS2 **_foxy_** at latest tag released

| 🏗️ CI            | latest* | foxy | galactic |
|:-------------:|:-------:|:----:|:--------:|
| 🧠 [core](https://github.com/rnanosaur/nanosaur.git) | [![Docker Builder CI](https://github.com/rnanosaur/nanosaur/actions/workflows/docker-image.yml/badge.svg?branch=master)](https://github.com/rnanosaur/nanosaur/actions/workflows/docker-image.yml) | [![Docker Builder CI](https://github.com/rnanosaur/nanosaur/actions/workflows/docker-image.yml/badge.svg?branch=foxy)](https://github.com/rnanosaur/nanosaur/actions/workflows/docker-image.yml) | [![Docker Builder CI](https://github.com/rnanosaur/nanosaur/actions/workflows/docker-image.yml/badge.svg?branch=galactic)](https://github.com/rnanosaur/nanosaur/actions/workflows/docker-image.yml) |
| 🖼️ [perception](https://github.com/rnanosaur/nanosaur_perception.git)   | [![Docker Builder CI](https://github.com/rnanosaur/nanosaur_perception/actions/workflows/docker-build.yml/badge.svg?branch=main)](https://github.com/rnanosaur/nanosaur_perception/actions/workflows/docker-build.yml) | [![Docker Builder CI](https://github.com/rnanosaur/nanosaur_perception/actions/workflows/docker-build.yml/badge.svg?branch=foxy)](https://github.com/rnanosaur/nanosaur_perception/actions/workflows/docker-build.yml) | [![Docker Builder CI](https://github.com/rnanosaur/nanosaur_perception/actions/workflows/docker-build.yml/badge.svg?branch=galactic)](https://github.com/rnanosaur/nanosaur_perception/actions/workflows/docker-build.yml) |

🏗️ **nanosaur_robot CI** [![nanosaur_robot rebuild](https://github.com/rnanosaur/nanosaur_robot/actions/workflows/root-update.yml/badge.svg)](https://github.com/rnanosaur/nanosaur_robot/actions/workflows/root-update.yml)

# Docker images

| 🐳 Docker        | latest* | foxy | galactic | Pulls |
|:-------------:|:-------:|:----:|:--------:|:-----:|
| 🧠 [core](https://github.com/rnanosaur/nanosaur.git) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/nanosaur/latest)](https://hub.docker.com/r/nanosaur/nanosaur) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/nanosaur/foxy)](https://hub.docker.com/r/nanosaur/nanosaur) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/nanosaur/galactic)](https://hub.docker.com/r/nanosaur/nanosaur) | [![Docker Pulls](https://img.shields.io/docker/pulls/nanosaur/nanosaur)](https://hub.docker.com/r/nanosaur/nanosaur) |
| 🖼️ [perception](https://github.com/rnanosaur/nanosaur_perception.git)    |  [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/perception/latest)](https://hub.docker.com/r/nanosaur/perception) <br/> zed <br/> [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/perception/latest-zed)](https://hub.docker.com/r/nanosaur/perception) <br/> realsense <br/> [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/perception/latest-realsense)](https://hub.docker.com/r/nanosaur/perception) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/perception/foxy)](https://hub.docker.com/r/nanosaur/perception) <br/> zed <br/> [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/perception/foxy-zed)](https://hub.docker.com/r/nanosaur/perception) <br/> realsense <br/> [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/perception/foxy-realsense)](https://hub.docker.com/r/nanosaur/perception) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/perception/galactic)](https://hub.docker.com/r/nanosaur/perception) | [![Docker Pulls](https://img.shields.io/docker/pulls/nanosaur/perception)](https://hub.docker.com/r/nanosaur/perception) |


**Latest** = ROS2 **_foxy_** at latest tag released

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
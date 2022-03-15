---
title: "Status"
excerpt: "Current nanosaur software deploy status"
permalink: /status/
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/intro.jpg
  teaser: /assets/images/intro.jpg
  actions:
    - label: ":sparkling_heart: Sponsor"
      url: "https://github.com/sponsors/rbonghi"
    - label: "🦕 About"
      url: /about/
    - label: "👷 Project"
      url: /project/
    - label: "📐 Architecture"
      url: /architecture/
sidebar:
  - nav: "about"
---

On this page are collected all Continuous Integration badges and Docker image size badges.

# Continuous Integration

| 🏗️ CI            | latest* | foxy | galactic |
|:-------------:|:-------:|:----:|:--------:|
| 🧠 [core](https://github.com/rnanosaur/nanosaur.git) | [![Docker Builder CI](https://github.com/rnanosaur/nanosaur/actions/workflows/docker-image.yml/badge.svg?branch=master)](https://github.com/rnanosaur/nanosaur/actions/workflows/docker-image.yml) | [![Docker Builder CI](https://github.com/rnanosaur/nanosaur/actions/workflows/docker-image.yml/badge.svg?branch=foxy)](https://github.com/rnanosaur/nanosaur/actions/workflows/docker-image.yml) | [![Docker Builder CI](https://github.com/rnanosaur/nanosaur/actions/workflows/docker-image.yml/badge.svg?branch=galactic)](https://github.com/rnanosaur/nanosaur/actions/workflows/docker-image.yml) |
| 🖼️ [perception](https://github.com/rnanosaur/nanosaur_perception.git)   | [![Docker Builder CI](https://github.com/rnanosaur/nanosaur_perception/actions/workflows/docker-build.yml/badge.svg?branch=main)](https://github.com/rnanosaur/nanosaur_perception/actions/workflows/docker-build.yml) | [![Docker Builder CI](https://github.com/rnanosaur/nanosaur_perception/actions/workflows/docker-build.yml/badge.svg?branch=foxy)](https://github.com/rnanosaur/nanosaur_perception/actions/workflows/docker-build.yml) | [![Docker Builder CI](https://github.com/rnanosaur/nanosaur_perception/actions/workflows/docker-build.yml/badge.svg?branch=galactic)](https://github.com/rnanosaur/nanosaur_perception/actions/workflows/docker-build.yml) |

**Latest** = ROS2 **_foxy_** at latest tag released

# Docker images

| 🐳 Docker        | latest* | foxy | galactic | Pulls |
|:-------------:|:-------:|:----:|:--------:|:-----:|
| 🧠 [core](https://github.com/rnanosaur/nanosaur.git) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/nanosaur/latest)](https://hub.docker.com/r/nanosaur/nanosaur) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/nanosaur/foxy)](https://hub.docker.com/r/nanosaur/nanosaur) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/nanosaur/galactic)](https://hub.docker.com/r/nanosaur/nanosaur) | [![Docker Pulls](https://img.shields.io/docker/pulls/nanosaur/nanosaur)](https://hub.docker.com/r/nanosaur/nanosaur) |
| 🖼️ [perception](https://github.com/rnanosaur/nanosaur_perception.git)    |  [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/perception/latest)](https://hub.docker.com/r/nanosaur/perception) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/perception/foxy)](https://hub.docker.com/r/nanosaur/perception) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/perception/galactic)](https://hub.docker.com/r/nanosaur/perception) | [![Docker Pulls](https://img.shields.io/docker/pulls/nanosaur/perception)](https://hub.docker.com/r/nanosaur/perception) |


**Latest** = ROS2 **_foxy_** at latest tag released

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
<!-- CI START -->
## CI & CD

List of all nanosaur software release and CI/CD status.

| 📦 package | 🏗️ CI | Status | Health |
|------------|-------|--------|--------|
| [![GitHub Release](https://img.shields.io/github/v/release/rnanosaur/nanosaur?label=nanosaur)](https://github.com/rnanosaur/nanosaur/releases) | [![Release nanosaur](https://github.com/rnanosaur/nanosaur/actions/workflows/release.yml/badge.svg)](https://github.com/rnanosaur/nanosaur/actions/workflows/release.yml) | [![GitHub forks](https://img.shields.io/github/forks/rnanosaur/nanosaur)](https://github.com/rnanosaur/nanosaur) | --- |
| [![PyPI - Version](https://img.shields.io/pypi/v/nanosaur?label=nanosaur-cli)](https://badge.fury.io/py/nanosaur) | [![Publish Python Package](https://github.com/rnanosaur/nanosaur_cli/actions/workflows/release.yml/badge.svg)](https://github.com/rnanosaur/nanosaur_cli/actions/workflows/release.yml) | [![PyPI - Downloads](https://img.shields.io/pypi/dm/nanosaur)](https://pypistats.org/packages/nanosaur) | [![nanosaur](https://snyk.io/advisor/python/nanosaur/badge.svg)](https://snyk.io/advisor/python/nanosaur) |
| [![Website Badge](https://img.shields.io/badge/Website-green)](https://nanosaur.ai) | [![pages-build-deployment](https://github.com/rnanosaur/rnanosaur.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/rnanosaur/rnanosaur.github.io/actions/workflows/pages/pages-build-deployment) | --- | --- |

### Docker Images

List of Docker images for nanosaur sorted by category and architecture supported. (The docker pulls are related to the Docker Hub repository)

|   | Platform | 🐳 Image | Pulls | Size |
|:---:|:-----:|---------|-------|------|
| 🦕 | 🖥️ x86_64 | [nanosaur/nanosaur:simulation](https://hub.docker.com/r/nanosaur/nanosaur) | [![nanosaur/nanosaur Pulls](https://img.shields.io/docker/pulls/nanosaur/nanosaur)](https://hub.docker.com/r/nanosaur/nanosaur) | [![nanosaur/nanosaur Size](https://img.shields.io/docker/image-size/nanosaur/nanosaur/simulation)](https://hub.docker.com/r/nanosaur/nanosaur) |
| 🦕 | 🕹️ Jetson | [nanosaur/nanosaur:robot](https://hub.docker.com/r/nanosaur/nanosaur) | [![nanosaur/nanosaur Pulls](https://img.shields.io/docker/pulls/nanosaur/nanosaur)](https://hub.docker.com/r/nanosaur/nanosaur) | [![nanosaur/nanosaur Size](https://img.shields.io/docker/image-size/nanosaur/nanosaur/robot)](https://hub.docker.com/r/nanosaur/nanosaur) |
| 🦕 | 🖥️🕹️ multi | [nanosaur/nanosaur:diagnostic](https://hub.docker.com/r/nanosaur/nanosaur) | [![nanosaur/nanosaur Pulls](https://img.shields.io/docker/pulls/nanosaur/nanosaur)](https://hub.docker.com/r/nanosaur/nanosaur) | [![nanosaur/nanosaur Size](https://img.shields.io/docker/image-size/nanosaur/nanosaur/diagnostic)](https://hub.docker.com/r/nanosaur/nanosaur) |
| 🖼️ | 🖥️ x86_64 | [nanosaur/perception:simulation](https://hub.docker.com/r/nanosaur/perception) | [![nanosaur/perception Pulls](https://img.shields.io/docker/pulls/nanosaur/perception)](https://hub.docker.com/r/nanosaur/perception) | [![nanosaur/perception Size](https://img.shields.io/docker/image-size/nanosaur/perception/simulation)](https://hub.docker.com/r/nanosaur/perception) |
| 🖼️ | 🕹️ Jetson | [nanosaur/perception:realsense](https://hub.docker.com/r/nanosaur/perception) | [![nanosaur/perception Pulls](https://img.shields.io/docker/pulls/nanosaur/perception)](https://hub.docker.com/r/nanosaur/perception) | [![nanosaur/perception Size](https://img.shields.io/docker/image-size/nanosaur/perception/realsense)](https://hub.docker.com/r/nanosaur/perception) |
| 🖼️ | 🕹️ Jetson | [nanosaur/perception:zed](https://hub.docker.com/r/nanosaur/perception) | [![nanosaur/perception Pulls](https://img.shields.io/docker/pulls/nanosaur/perception)](https://hub.docker.com/r/nanosaur/perception) | [![nanosaur/perception Size](https://img.shields.io/docker/image-size/nanosaur/perception/zed)](https://hub.docker.com/r/nanosaur/perception) |
| 👨‍💻 | 🖥️ x86_64 | [nanosaur/simulation:gazebo](https://hub.docker.com/r/nanosaur/simulation) | [![nanosaur/simulation Pulls](https://img.shields.io/docker/pulls/nanosaur/simulation)](https://hub.docker.com/r/nanosaur/simulation) | [![nanosaur/simulation Size](https://img.shields.io/docker/image-size/nanosaur/simulation/gazebo)](https://hub.docker.com/r/nanosaur/simulation) |
| 👨‍💻 | 🖥️ x86_64 | [nanosaur/simulation:isaac-sim](https://hub.docker.com/r/nanosaur/simulation) | [![nanosaur/simulation Pulls](https://img.shields.io/docker/pulls/nanosaur/simulation)](https://hub.docker.com/r/nanosaur/simulation) | [![nanosaur/simulation Size](https://img.shields.io/docker/image-size/nanosaur/simulation/isaac-sim)](https://hub.docker.com/r/nanosaur/simulation) |

<!-- CI END -->
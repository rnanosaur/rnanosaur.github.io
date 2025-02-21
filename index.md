---
layout: splash
excerpt: "nanosaur is the smallest <b>NVIDIA Jetson</b> dinosaur robot, fully 3D printable, open-source, ROS 2 & Isaac ROS based.<br/> <small>Designed & made by [Raffaello Bonghi](https://rnext.it)</small>"
tagline: "The smallest <b>NVIDIA Jetson</b> dinosaur robot, fully 3D printable, open-source, ROS 2 & Isaac ROS based.<br/> <small>Designed & made by [Raffaello Bonghi](https://rnext.it)</small>"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/banner.jpg
  caption: "[**Best ROS Robot 2022**](https://www.theconstructsim.com/ros-awards-2022/)"
  actions:
  - label: ":sparkling_heart: Sponsor"
    url: "https://github.com/sponsors/rbonghi"
  - label: ":star: Star"
    url: "https://github.com/rnanosaur/nanosaur"
intro: 
  - excerpt: '🦕 nanosaur is an open-source and 3D printable platform, designed to wander on your desk. With this platform, you learn the fundamentals of [ROS 2](https://www.ros.org/) and NVIDIA [Isaac ROS](https://developer.nvidia.com/isaac-ros-gems) GEMs. Learning how to use AI applied in robotics.'
about:
  - image_path: /assets/images/nanosaur_og.jpg
    alt: "nanosaur"
    title: "🦕 About"
    excerpt: "nanosaur is an 🇮🇹 italian open-source and 3D printable platform, designed to wander on your desk. With this platform, you learn the fundamentals of [ROS 2](https://www.ros.org/) and NVIDIA [Isaac ROS](https://developer.nvidia.com/isaac-ros-gems) GEMs. Learning how to use AI applied in robotics."
    url: "/about"
    btn_label: "📃 learn more"
    btn_class: "btn--success"
feature_row:
  - image_path: /assets/images/collections/tutorial/configure/nanosaur-robot-config-example-camera.png
    alt: "Quick Start with nanosaur"
    title: "🏃‍➡️ Quick Start"
    excerpt: "If you don't know how to make nanosaur or how to use it, follow this page, to quickly set up your environment and start with the course!"
    url: /quick-start/
    btn_label: "📃 learn more"
    btn_class: "btn--primary"
  - image_path: /assets/images/collections/courses/course.jpg
    alt: "nanosaur courses"
    title: "📚 Courses"
    excerpt: "Let's learn how is it work nanosaur and how to build a ROS 2 package and work with Isaac ROS"
    url: "/courses/"
    btn_label: "🎓 learn"
    btn_class: "btn--success"
  - image_path: /assets/images/nanosaur-wireframe-bw.png
    alt: "nanosaur"
    title: "📐 Architecture"
    excerpt: "nanosaur is designed like a real AMR robot, with a complete ROS 2 pipeline, high level controllers and AI,docker containers based."
    url: "/architecture"
    btn_label: "👷 Deep dive"
    btn_class: "btn--inverse"
award:
  - image_path: /assets/images/nanosaur-award-2022.jpg
    alt: "nanosaur Best ROS Robot 2022"
    title: "🏆 Best ROS Robot 2022"
    excerpt: "nanosaur is the winner of the [**Best ROS Robot 2022**](https://www.theconstructsim.com/ros-awards-2022/) Awarded from the ROS Developers Community"
    url: "https://www.theconstructsim.com/ros-awards-2022-results/"
    btn_label: "🥇 Read more"
    btn_class: "btn--success"
footer: 
  - excerpt: '🦕 **nanosaur** is proudly part of :pizza: [pizzarobotics](https://pizzarobotics.org) community'
---

{% include feature_row id="award" type="right" %}

{% include feature_row id="about" type="left" %}

{% include feature_row %}

{% include feature_row id="footer" type="center" %}

{% include discord.html %}

---
layout: splash
excerpt: "nanosaur is the smallest <b>NVIDIA Jetson</b> dinosaur robot, fully 3D printable, open-source, ROS 2 & Isaac ROS based.<br/> <small>Designed & made by [Raffaello Bonghi](https://rnext.it)</small>"
tagline: "The smallest <b>NVIDIA Jetson</b> dinosaur robot, fully 3D printable, open-source, ROS2 & Isaac ROS based.<br/> <small>Designed & made by [Raffaello Bonghi](https://rnext.it)</small>"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/banner.jpg
  caption: "[**Best ROS Robot 2022**](https://www.theconstructsim.com/ros-awards-2022/)"
  actions:
  - label: ":sparkling_heart: Sponsor"
    url: "https://github.com/sponsors/rbonghi"
  - label: ":tshirt: T-shirt"
    url: "https://teespring.com/nanosaur"
  - label: ":star: Star"
    url: "https://github.com/rnanosaur/nanosaur"
  - label: ":wrench: Make"
    url: "/quick-start/"
intro: 
  - excerpt: '🦕 nanosaur is an open-source and 3D printable platform, designed to wander on your desk. With this platform, you learn the fundamentals of [ROS2](https://www.ros.org/) and NVIDIA [Isaac ROS](https://developer.nvidia.com/isaac-ros-gems) GEMs. Learning how to use AI applied in robotics.'
about:
  - image_path: /assets/images/nanosaur_og.jpg
    alt: "nanosaur"
    title: "🦕 About"
    excerpt: "nanosaur is an 🇮🇹 italian open-source and 3D printable platform, designed to wander on your desk. With this platform, you learn the fundamentals of [ROS2](https://www.ros.org/) and NVIDIA [Isaac ROS](https://developer.nvidia.com/isaac-ros-gems) GEMs. Learning how to use AI applied in robotics."
    url: "/about"
    btn_label: "📃 learn more"
    btn_class: "btn--success"
feature_row:
  - image_path: /assets/images/nanosaur-wireframe-bw.png
    alt: "nanosaur"
    title: "📐 Architecture"
    excerpt: "nanosaur is designed like a real AMR robot, with a complete ROS2 pipeline, high level controllers and AI,docker containers based."
    url: "/architecture"
    btn_label: "👷 Deep dive"
    btn_class: "btn--inverse"
  - image_path: /assets/images/nanosaur_build.jpg
    alt: "nanosaur quick-start"
    title: ":wrench: Make"
    excerpt: "If you read this message, you want build or setup your nanosaur. There is only a button to press and follow the guide!"
    url: "/quick-start/"
    btn_label: "🚧 Let's go!"
    btn_class: "btn--warning"
  - image_path: /assets/images/nanosaur_follower.jpg
    alt: "nanosaur tutorials"
    title: ":school_satchel: Play"
    excerpt: "Learn Robotics with nanosaur, deepdive on ROS2 AI and other. Follow tutorials and courses to start in this world."
    url: "/tutorial/"
    btn_label: "💯 Tutorials"
    btn_class: "btn--success"
award:
  - image_path: /assets/posts/achievements/nanosaur-winner-2022.jpg
    alt: "nanosaur Best ROS Robot 2022"
    title: "🏆 Best ROS Robot 2022"
    excerpt: "nanosaur is the winner of the [**Best ROS Robot 2022**](https://www.theconstructsim.com/ros-awards-2022/) Awarded from the ROS Developers Community"
    url: "https://www.theconstructsim.com/ros-awards-2022-results/"
    btn_label: "🥇 Read more"
    btn_class: "btn--success"
footer: 
  - excerpt: '🦕 **nanosaur** is proudly part of :pizza: [pizzarobotics](https://pizzarobotics.org) community'
merch:
  - image_path: /assets/images/buy/merch/nanosaur-merch.gif
    alt: "nanosaur merchandising"
    title: "nanosaur style"
    excerpt: "nanosaur addicted! Pimp your day with T-Shirts, mugs, Hoodies and all for your robotic working day!"
    url: "https://teespring.com/nanosaur"
    btn_label: ":shopping_cart: Watch catalog"
    btn_class: "btn--inverse"
---

{% include feature_row id="about" type="left" %}

{% include feature_row %}

{% include feature_row id="award" type="right" %}

{% include feature_row id="footer" type="center" %}

{% include feature_row id="merch" type="left" %}

{% include discord.html %}

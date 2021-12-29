---
layout: splash
excerpt: "Designed & made <br/>by [Raffaello Bonghi](https://rnext.it)"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/intro.jpg
  actions:
  - label: ":sparkling_heart: Sponsor"
    url: "https://github.com/sponsors/rbonghi"
  - label: ":wrench: Make"
    url: "/quick-start/"
  - label: ":books: Wiki"
    url: "https://github.com/rnanosaur/nanosaur/wiki"
intro: 
  - excerpt: '🦕 nanosaur is the smallest NVIDIA Jetson dinosaur robot, fully 3D printable.<br/>In 10 x 12 x 6cm and 500g use only a power-bank and works in [ROS2](https://www.ros.org/) is simple to build and simple to use.'
feature_row:
  - image_path: /assets/images/nanosaur_build.jpg
    alt: "quick-start"
    title: ":wrench: Make"
    excerpt: "If you read this message, you want build or setup your nanosaur. There is only a button to press and follow the guide!"
    url: "/quick-start/"
    btn_label: "let's go!"
    btn_class: "btn--success"
  - image_path: /assets/images/tutorial.jpg
    alt: "tutorials"
    title: ":school_satchel: Play"
    excerpt: "Now switch on nanosaur open your PC and learn Robotics with ROS2, study Artificial Intelligence and other. Follow this tutorial to start in this world"
    url: "/tutorial/"
    btn_label: "tutorials"
    btn_class: "btn--warning"
  - image_path: /assets/images/repository.jpg
    alt: "repository"
    title: ":star: Star"
    excerpt: "If you are here, you want know how nanosaur works, and if you want help me to to improve the project you can star and fork the nanosaur repository"
    url: "https://github.com/rnanosaur/nanosaur"
    btn_label: ":star: Star and fork!"
    btn_class: "btn--primary"
footer: 
  - excerpt: '🦕 **nanosaur** is proudly part of :pizza: [pizzarobotics](https://pizzarobotics.org) community'
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include discord.html %}

{% include feature_row id="footer" type="center" %}
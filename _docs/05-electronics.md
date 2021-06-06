---
title: "Electronics"
permalink: /electronics/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
motor-control:
  - url: /assets/docs/electronics/01-motor-control.png
    image_path: /assets/docs/electronics/01-motor-control.png
    alt: "Assembly nanosaur power bank"
    title: "Assembly nanosaur power bank"
  - url: /assets/docs/electronics/02-motor-control.png
    image_path: /assets/docs/electronics/02-motor-control.png
    alt: "Mount XT-04 connectors"
    title: "Mount XT-04 connectors"
  - url: /assets/docs/electronics/03-motor-control.png
    image_path: /assets/docs/electronics/03-motor-control.png
    alt: "Mount I2C connectors"
    title: "Mount I2C connectors"
motor-wiring-steps:
  - url: /assets/docs/electronics/motor-parts.jpg
    image_path: /assets/docs/electronics/motor-parts.jpg
    alt: "Motor and cable"
    title: "Motor and cable"
  - url: /assets/docs/electronics/motor-plus.jpg
    image_path: /assets/docs/electronics/motor-plus.jpg
    alt: "Motor detail (+) symbol"
    title: "Motor detail (+) symbol"
motor-wiring:
  - url: /assets/docs/electronics/front-motor.jpg
    image_path: /assets/docs/electronics/front-motor.jpg
    alt: "Motor with cable"
    title: "Motor with cable"
---

In this page we will soldering the motor control and motors and will take a look of the Nanosaur wiring.

# Adafruit assembly

We should wire the [DC Motor + Stepper FeatherWing Add-on](https://www.adafruit.com/product/2927) following the picture below:

1. Soldering all XT connectors
2. Solder the electronic power at the end of the first row
3. Solder the I2C connector on the second row

{% include gallery id="motor-control" caption="Assembly adafruit motor controller" %}

The pinout of the [DC Motor + Stepper FeatherWing Add-on](https://www.adafruit.com/product/2927) will be the picture below

{% include figure image_path="/assets/docs/electronics/adafruit-pinout.png" alt="Adafruit DC Motor pintout" caption="Adafruit DC Motor pintout" %}

# Motor wiring

To soldering the motors you need to pay attention to the **(+)** symbol on the rear motor cover. You can wire the motors use a part of the 30cm flat ribbon cable that you use to assembly the [Nanosaur expansion board PCB](/expansion-board/#wiring-pcb)

| Symbol | Color   | Length  |
|:------:|:-------:|:-------:|
| +      | red     | 90mm    |
|        | brown   | 90mm    |

{% include gallery id="motor-wiring-steps" caption="Motor wiring steps" %}

The motor will look like this picture:

{% include gallery id="motor-wiring" caption="Motor assembled" %}

# Nanosaur wiring

The nanosaur expansion board connect the NVIDIA Jetson Nano to the Adafruit [DC Motor + Stepper FeatherWing Add-on](https://www.adafruit.com/product/2927) and two oled I2C Display 128x64px 0.06 inch. Following this bullet list

* I2C bus 0 (Pin 27, 28)
  * oled right
* I2C bus 1 (Pin 3, 5)
  * oled left
  * adafruit motor control
* 2 custom buttons
  * GPIO Pin 31
  * GPIO Pin 33

A schematic output has this output:

{% include figure image_path="/assets/docs/electronics/Nanosaur-wiring.png" alt="Nanosaur-wiring" caption="Nanosaur-wiring" %}
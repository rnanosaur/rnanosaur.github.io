---
title: "Assembly"
permalink: /assembly/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
flap:
  - url: /assets/docs/assembly/flap-01-parts.png
    image_path: /assets/docs/assembly/flap-01-parts.png
    alt: "Stick flap parts"
    title: "Stick flap parts"
  - url: /assets/docs/assembly/flap-02-assembly.png
    image_path: /assets/docs/assembly/flap-02-assembly.png
    alt: "Assembly flap"
    title: "Assembly expansion board to flap"
wheels:
  - url: /assets/docs/assembly/sprocket-A-wheel.png
    image_path: /assets/docs/assembly/sprocket-A-wheel.png
    alt: "Assembly wheel"
    title: "Assembly wheel"
  - url: /assets/docs/assembly/sprocket-B-sprocket.png
    image_path: /assets/docs/assembly/sprocket-B-sprocket.png
    alt: "Assembly sprocket"
    title: "Assembly sprocket"
tracks:
  - url: /assets/docs/assembly/tracks-01-left.png
    image_path: /assets/docs/assembly/tracks-01-left.png
    alt: "Assembly track left"
    title: "Assembly track left"
  - url: /assets/docs/assembly/tracks-02-right.png
    image_path: /assets/docs/assembly/tracks-02-right.png
    alt: "Assembly track right"
    title: "Assembly track right"
  - url: /assets/docs/assembly/tracks-03-nuts.png
    image_path: /assets/docs/assembly/tracks-03-nuts.png
    alt: "Assembly track nuts"
    title: "Assembly track nuts"
cover:
  - url: /assets/docs/assembly/cover-01-display.png
    image_path: /assets/docs/assembly/cover-01-display.png
    alt: "Cover assembly display"
    title: "Assembly display"
  - url: /assets/docs/assembly/cover-02-cam.png
    image_path: /assets/docs/assembly/cover-02-cam.png
    alt: "Cover assembly camera"
    title: "Assembly camera"
body-head:
  - url: /assets/docs/assembly/body-head-A.png
    image_path: /assets/docs/assembly/body-head-A.png
    alt: "Assembly NanoSaur head rear view"
    title: "Assembly NanoSaur head rear view"
  - url: /assets/docs/assembly/body-head-B.png
    image_path: /assets/docs/assembly/body-head-B.png
    alt: "Assembly NanoSaur head front view"
    title: "Assembly NanoSaur head front view"
power-bank:
  - url: /assets/docs/assembly/NanoSaur-power-bank.png
    image_path: /assets/docs/assembly/NanoSaur-power-bank.png
    alt: "Assembly NanoSaur power bank"
    title: "Assembly NanoSaur power bank"
  - url: /assets/docs/assembly/NanoSaur.png
    image_path: /assets/docs/assembly/NanoSaur.png
    alt: "NanoSaur done!"
    title: "NanoSaur done!"
---

If you are here, you are ready to mount NanoSaur!

{% include figure image_path="/assets/docs/assembly/NanoSaur-explode.png" alt="NanoSaur explode view" caption="NanoSaur explode view" %}

There are few steps to follow to mount NanoSaur only using the tools in list, remember to collect and buy all components listed in the [Bill of Materials](/02-bill-of-materials.md)

We can split the NanoSaur assembly in three parts:
* [Flap](#flap)
* [Body](#body)
* [Head](#head)

After mounts these three parts you can complete the NanoSaur assembly.
You need only:

| Tool               | Picture |
|--------------------|---------|
| Hex M2 arm wrench  | ![arm M2 wrench](/assets/docs/assembly/arm_wrench.jpg) |

# Flap

| Quantity | Part                |
|:--------:|---------------------|
| 1        | flap_top.stl        |
| 1        | flap_bottom.stl     |
| 1        | [Expansion board](/expansion-board) |
| 2        | Hex M2 10mm         |

{% include gallery id="flap" caption="Assembly NanoSaur flap" %}

# Body

## Motors block

| Quantity | Part                 |
|:--------:|----------------------|
| 1        | base_front.stl       |
| 2        | Pololu Micro Gearbox |

{% include figure image_path="/assets/docs/assembly/front.png" alt="NanoSaur motor block" caption="Assembly motors" %}

## Front and rear

| Quantity | Part                 |
|:--------:|----------------------|
| 1        | [Motors block](#motors-block) |
| 1        | base_rear.stl       |
| 4        | Hex M2 6mm          |

{% include figure image_path="/assets/docs/assembly/base.png" alt="NanoSaur assembly base" caption="Assembly base" %}

## Wheels and Sprocket

| Quantity | Part                |
|:--------:|---------------------|
| 2        | wheels.stl          |
| 2        | sprocket.stl        |
| 6        | Ball bearings       |

Repeat this step twice

{% include gallery id="wheels" caption="Assembly wheels" %}

## Tracks

| Quantity | Part                |
|:--------:|---------------------|
| 2        | [Wheel](#wheels-and-sprocket) |
| 2        | [Sprocket](#wheels-and-sprocket) |
| 2        | track_print.stl     |
| 6        | M2 nuts             |
| 6        | Hex M2 20mm         |

{% include gallery id="tracks" caption="Assembly tracks" %}

## Wiring and board

| Quantity | Part                |
|:--------:|---------------------|
| 1        | [Body](#tracks)     |
| 1        | [Flap](#flap)       |
| 1        | NVIDIA Jetson Nano 2Gb* |
| 1        | Adafruit motor control  |
| 8        | Hex M2 4mm          |

{% include figure image_path="/assets/docs/assembly/body.png" alt="NanoSaur assembly and wiring boards" caption="assembly and wiring boards" %}

# Head

Components to pick up

| Quantity | Part                |
|:--------:|---------------------|
| 1        | cover.stl           |
| 1        | Raspberry PI cam    |
| 2        | oLED display        |
| 12       | Hex M2 4mm          |

{% include gallery id="cover" caption="Assembly components head" %}

# Full assembly

Finally we are at the last step to build NanoSaur, we only need to mount the head and the NanoSaur, let's go!

## Build NanoSaur

| Quantity | Part                |
|:--------:|---------------------|
| 1        | [Body](#body)       |
| 1        | [Head](#head)       |
| 2        | Hex M2 6mm          |
| 1        | Hex M2 14mm         |

{% include gallery id="body-head" caption="Assembly NanoSaur head" %}

## Assembly power bank

| Quantity | Part                |
|:--------:|---------------------|
| 1        | [Body](#body)       |
| 1        | [Head](#head)       |
| 1        | pb_holder.stl       |
| 2        | Hex M2 6mm          |

{% include gallery id="power-bank" caption="Assembly NanoSaur power bank" %}

# Done

Finally NanoSaur is ready to be installed, let's go to flash the MicroSD and [install](/install) all software

{% include figure image_path="/assets/docs/assembly/NanoSaur.png" alt="NanoSaur" caption="NanoSaur" %}


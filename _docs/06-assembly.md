---
title: "Assembly"
permalink: /assembly/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
pbholder:
  - url: /assets/docs/assembly/pbholder.png
    image_path: /assets/docs/assembly/pbholder.png
    alt: "Assembly magnets on Power bank holder"
    title: "Assembly magnets on Power bank holder"
flap:
  - url: /assets/docs/assembly/flap-01-parts.png
    image_path: /assets/docs/assembly/flap-01-parts.png
    alt: "Stick flap parts"
    title: "Stick flap parts"
  - url: /assets/docs/assembly/flap-02-assembly.png
    image_path: /assets/docs/assembly/flap-02-assembly.png
    alt: "Assembly flap"
    title: "Assembly expansion board to flap"
motors:
  - url: /assets/docs/assembly/front-magnets.png
    image_path: /assets/docs/assembly/front-magnets.png
    alt: "Assembly magnets"
    title: "Assembly magnets"
  - url: /assets/docs/assembly/front-motors.png
    image_path: /assets/docs/assembly/front-motors.png
    alt: "Assembly motors front"
    title: "Assembly motors front"
base:
  - url: /assets/docs/assembly/base-parts.png
    image_path: /assets/docs/assembly/base-parts.png
    alt: "Assembly front part"
    title: "Assembly front part"
  - url: /assets/docs/assembly/base-magnets.png
    image_path: /assets/docs/assembly/base-magnets.png
    alt: "Assembly magnets base"
    title: "Assembly magnets base"
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
    alt: "Assembly track right - bolts"
    title: "Assembly track right - bolts"
wiring:
  - url: /assets/docs/assembly/body.png
    image_path: /assets/docs/assembly/body.png
    alt: "Assembly board and wiring"
    title: "Assembly board and wiring"
cover:
  - url: /assets/docs/assembly/cover-01-magnets.png
    image_path: /assets/docs/assembly/cover-01-magnets.png
    alt: "Cover assembly magnets"
    title: "Cover Assembly magnets"
  - url: /assets/docs/assembly/cover-02-display.png
    image_path: /assets/docs/assembly/cover-02-display.png
    alt: "Cover assembly display"
    title: "Cover Assembly display"
  - url: /assets/docs/assembly/cover-03-cam.png
    image_path: /assets/docs/assembly/cover-03-cam.png
    alt: "Cover assembly camera"
    title: "Assembly camera"
body-head:
  - url: /assets/docs/assembly/body-head.png
    image_path: /assets/docs/assembly/body-head.png
    alt: "Assembly nanosaur head rear view"
    title: "Assembly nanosaur head rear view"
power-bank:
  - url: /assets/docs/assembly/nanosaur-01-powerbank.png
    image_path: /assets/docs/assembly/nanosaur-01-powerbank.png
    alt: "Assembly nanosaur power bank"
    title: "Assembly nanosaur power bank"
  - url: /assets/docs/assembly/nanosaur-02-pbholder.png
    image_path: /assets/docs/assembly/nanosaur-02-pbholder.png
    alt: "nanosaur done!"
    title: "nanosaur done!"
---

If you are here, you are ready to mount nanosaur!

{% include figure image_path="/assets/docs/assembly/nanosaur-explode.png" alt="nanosaur explode view" caption="nanosaur explode view" %}

There are few steps to follow to mount nanosaur only using the tools in list, remember to collect and buy all components listed in the [Bill of Materials](/bill-of-materials)

We can split the nanosaur assembly into four parts:
* [Power Bank holder](#power-bank-holder)
* [Flap](#flap)
* [Body](#body)
* [Head](#head)

After mounts these three parts you can complete the nanosaur assembly.
You need only:

| Tool               | Picture |
|--------------------|---------|
| Hex M2 arm wrench  | ![arm M2 wrench](/assets/docs/assembly/arm_wrench.jpg) |

# Power Bank holder

| Quantity | Part                |
|:--------:|---------------------|
| 1        | [pb_holder.stl](/3d-print/#flap-and-power-bank-holder) |
| 2        | magnet 4x2mm        |

{% include gallery id="pbholder" caption="Assembly nanosaur power bank holder" %}

# Wheels and Sprocket

| Quantity | Part                 |
|:--------:|----------------------|
| 2        | [wheels.stl](/3d-print/#wheels-and-sprockets) |
| 2        | [sprocket.stl](/3d-print/#wheels-and-sprockets) |
| 6        | Ball bearings F686ZZ |

Repeat this step twice

{% include gallery id="wheels" caption="Assembly wheels" %}

# Flap

| Quantity | Part                |
|:--------:|---------------------|
| 1        | [flap_top.stl](/3d-print/#flap-and-power-bank-holder) |
| 1        | [flap_bottom.stl](/3d-print/#flap-and-power-bank-holder) |
| 1        | [Expansion board](/expansion-board) |
| 1        | USB cable           |
| 4        | Hex M2 10mm         |

To assembly the 

{% include gallery id="flap" caption="Assembly nanosaur flap" %}

# Body

## Motors block

| Quantity | Part                 |
|:--------:|----------------------|
| 1        | [base_front.stl](/3d-print/#base-front)       |
| 2        | Pololu Micro Gearbox |
| 3        | magnet 4x2mm         |

{% include gallery id="motors" caption="Assembly front part" %}

## Front and rear

| Quantity | Part                                  |
|:--------:|---------------------------------------|
| 1        | [Motors block](#motors-block)         |
| 1        | [base_rear.stl](/3d-print/#base-rear) |
| 4        | Hex M2 6mm                            |
| 2        | magnet 4x2mm                          |

{% include gallery id="base" caption="Assembly base" %}

## Tracks

| Quantity | Part                                       |
|:--------:|--------------------------------------------|
| 2        | [Wheel](#wheels-and-sprocket)              |
| 2        | [Sprocket](#wheels-and-sprocket)           |
| 2        | [track_print.stl](/3d-print/#print-tracks) |
| 6        | M2 nuts                                    |
| 6        | Hex M2 20mm                                |

{% include gallery id="tracks" caption="Assembly tracks" %}

## Wiring and board

| Quantity | Part                    |
|:--------:|-------------------------|
| 1        | [Body](#tracks)         |
| 1        | [Flap](#flap)           |
| 1        | NVIDIA Jetson Nano 2Gb* |
| 1        | Adafruit motor control  |
| 8        | Hex M2 4mm              |

{% include gallery id="wiring" caption="assembly and wiring boards" %}

# Head

Components to pick up

| Quantity | Part                |
|:--------:|---------------------|
| 1        | [cover.stl](/3d-print/#cover) |
| 1        | PI cam v2           |
| 2        | oLED display        |
| 12       | Hex M2 4mm          |
| 3        | magnet 4x2mm        |

{% include gallery id="cover" caption="Assembly components head" %}

# Full assembly

Finally we are at the last step to build nanosaur, we only need to mount the head and the nanosaur, let's go!

## Build nanosaur

| Quantity | Part                |
|:--------:|---------------------|
| 1        | [Body](#body)       |
| 1        | [Head](#head)       |

{% include gallery id="body-head" caption="Assembly nanosaur head" %}

## Assembly power bank

| Quantity | Part                |
|:--------:|---------------------|
| 1        | [Body](#body)       |
| 1        | [Head](#head)       |
| 1        | [Power Bank holder](#power-bank-holder) |

{% include gallery id="power-bank" caption="Assembly nanosaur power bank" %}

# Done

Finally nanosaur is ready to be installed, let's go to flash the MicroSD and [install](/install) all software

{% include figure image_path="/assets/docs/assembly/nanosaur.png" alt="nanosaur" caption="nanosaur" %}


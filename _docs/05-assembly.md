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
cover:
  - url: /assets/docs/assembly/cover-01-display.png
    image_path: /assets/docs/assembly/cover-01-display.png
    alt: "Cover assembly display"
    title: "Assembly display"
  - url: /assets/docs/assembly/cover-02-cam.png
    image_path: /assets/docs/assembly/cover-02-cam.png
    alt: "Cover assembly camera"
    title: "Assembly camera"
---

If you are here, you are ready to mount NanoSaur!

{% include figure image_path="/assets/docs/assembly/NanoSaur-explode.png" alt="NanoSaur explode view" caption="NanoSaur explode view" %}

There are few steps to follow to mount NanoSaur only using the tools in list, remember to collect and buy all components listed in the [Bill of Material](/02-bill-of-material.md)

# Tools

* Hex screwdriver M2

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

## Tracks

## Wiring

| Quantity | Part                |
|:--------:|---------------------|
| 1        | [Flap](#flap)       |

## Board

# Head

Components to pick up

| Quantity | Part                |
|:--------:|---------------------|
| 1        | cover.stl           |
| 1        | Raspberry PI cam    |
| 2        | oLED display        |
| 12       | Hex M2 4mm          |

{% include gallery id="cover" caption="Assembly NanoSaur head" %}

# Full assembly





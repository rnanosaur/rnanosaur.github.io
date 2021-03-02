---
title: "Expansion board"
permalink: /expansion-board/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
pcb_expansion_board:
  - url: /assets/docs/expansion-board/img/nanosaur-exp-board-Board_top.svg
    image_path: /assets/docs/expansion-board/img/nanosaur-exp-board-Board_top.svg
    alt: "Flap and power bank holder orientation"
    title: "Flap and power bank holder orientation"
  - url: /assets/docs/expansion-board/img/nanosaur-exp-board-Board_bottom.svg
    image_path: /assets/docs/expansion-board/img/nanosaur-exp-board-Board_bottom.svg
    alt: "Flap and power bank holder slicer support type tree"
    title: "Flap and power bank holder slicer support type tree"
---

**:construction: Page under construction** This page is under construction, will be update soon!
{: .notice--warning}

Before assembling NanoSaur you need to solder the expansion board to connect the NVIDIA Jetson Nano to the Adafruit motor board.

You have tree ways to build the expansion board:
1. Assembly on a matrix board the adapter
2. Make a PCB and solder it
3. Buy the adapter

If you chose the number **1.** follow this steps otherwise let's go to the [next step](/assembly).

# Layout

**:floppy_disk: Download** the Nanosaur expansion board [**schematics.pdf**](https://github.com/rnanosaur/nanosaur-exp-board/releases/latest/download/combined.pdf)
{: .notice--success}

The expansion board is a simple adapter to connect the motor controller and the LCDs to the NVIDIA Jetson.

* I2C bus 0
* I2C bus 1
* 2 GPIO

{% include figure image_path="/assets/docs/expansion-board/img/nanosaur-exp-board-Schematic.svg" alt="test svg" caption="test svg" %}

# Board

The PCB Layout will be like the pictures below:

{% include gallery id="pcb_expansion_board" caption="PCB expansion board" %}

The size is **20mm x 80mm** with 4 M2 mounting holes

## Gerbers

If you want print by yourself the expansion board, you need only to download the file below

# Assembly

To assembly the expansion board, is simple you need only to weld the female 2x20 connector and a switch.
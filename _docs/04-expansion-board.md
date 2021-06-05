---
title: "Expansion board"
permalink: /expansion-board/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
pcb_expansion_board_3d:
  - url: /assets/docs/expansion-board/nanosaur-exp-board-3dtop.png
    image_path: /assets/docs/expansion-board/nanosaur-exp-board-3dtop.png
    alt: "Nanosaur Expansion board PCB top"
    title: "Nanosaur Expansion board PCB top"
  - url: /assets/docs/expansion-board/nanosaur-exp-board-3dbottom.png
    image_path: /assets/docs/expansion-board/nanosaur-exp-board-3dbottom.png
    alt: "Nanosaur Expansion board PCB bottom"
    title: "Nanosaur Expansion board PCB bottom"
pcb_expansion_board:
  - url: /assets/docs/expansion-board/nanosaur-exp-board-Board_top.svg
    image_path: /assets/docs/expansion-board/nanosaur-exp-board-Board_top.svg
    alt: "Nanosaur Expansion board PCB top"
    title: "Nanosaur Expansion board PCB top"
  - url: /assets/docs/expansion-board/nanosaur-exp-board-Board_bottom.svg
    image_path: /assets/docs/expansion-board/nanosaur-exp-board-Board_bottom.svg
    alt: "Nanosaur Expansion board PCB bottom"
    title: "Nanosaur Expansion board PCB bottom"
wiring:
  - url: /assets/docs/expansion-board/nanosaur-expansion-board.jpeg
    image_path: /assets/docs/expansion-board/nanosaur-expansion-board.jpeg
    alt: "Nanosaur Expansion board"
    title: "Nanosaur Expansion board"
---

The expansion boars has size **20mm x 80mm** and have four M2 mounting holes, that perfectly fit inside the [Nanosaur flap](/assembly/#flap).

{% include gallery id="pcb_expansion_board_3d" caption="Nanosaur expansion board PCB" %}

This board is a simple adapter to connect the motor controller and the LCDs to the NVIDIA Jetson on your NanoSaur, this board connect:

* I2C bus 0 (Pin 27, 28)
  * oled right
* I2C bus 1 (Pin 3, 5)
  * oled left
  * adafruit motor control
* 2 custom buttons
  * GPIO Pin 31
  * GPIO Pin 33

There are two ways to Assembly the expansion board:
 * [PCB expansion board](#assembly-pcb) to support this project
 * [Assembly with a matrix board](#assembly-matrix-board)

# Components

The list of components that you need to have are in this table below

{% include kicad_bom.html table_name=site.data.nanosaur-exp-board %}

## Schematic

This expansion board is a simple connector for oleds and motor controller and works taking the power from the Power bank and power up the robot passing from a slide switch.

More detail are available on NanoSaur expansion board schematic.

{% include figure image_path="/assets/docs/expansion-board/Expansion board-Schematic.svg" alt="Nanosaur schematic expansion board" caption="NanoSaur schematic expansion board" %}

**:floppy_disk: Download** the NanoSaur expansion board [**nanosaur-schematic.pdf**](https://github.com/rnanosaur/nanosaur-exp-board/releases/latest/download/nanosaur-schematic.pdf)
{: .notice--success}

# Assembly PCB

To assembly the PCB, is simple, you need only a solder and some cables

## Wiring the PCB

{% include gallery id="wiring" caption="Nanosaur expansion board" %}

# Assembly matrix board

To assembly the expansion board, is simple you need only to weld the female 2x20 connector and a switch.

**:construction: This part will be updated soon.**<br/>For any issue join on [Discord](https://discord.gg/NSrC52P5mw)
{: .notice--warning}

# PCB Board

The size is **20mm x 80mm** with 4 M2 mounting holes, with PCB Layout will be like the pictures below

{% include gallery id="pcb_expansion_board" caption="PCB expansion board" %}

**:floppy_disk: Download** the Nanosaur expansion board **STEP** file [**nanosaur-exp-board.step**](https://github.com/rnanosaur/nanosaur-exp-board/releases/latest/download/nanosaur-exp-board.step)
{: .notice--success}

If you want print by yourself the expansion board, you can download the **gerber** file from this link

**:floppy_disk: Download** the Nanosaur expansion board **gerber** file [**nanosaur-gerber.zip**](https://github.com/rnanosaur/nanosaur-exp-board/releases/latest/download/nanosaur-gerber.zip)
{: .notice--success}
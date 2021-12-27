---
title: "Expansion board"
permalink: /expansion-board/
header:
  teaser: /assets/docs/expansion-board/nanosaur-exp-board-3dtop.png
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
pcb_expansion_steps:
  - url: /assets/docs/expansion-board/nanosaur-exp-board-01-resistors.png
    image_path: /assets/docs/expansion-board/nanosaur-exp-board-01-resistors.png
    alt: "Nanosaur Expansion board assembly resistors"
    title: "Nanosaur Expansion board assembly resistors"
  - url: /assets/docs/expansion-board/nanosaur-exp-board-02-resistors.png
    image_path: /assets/docs/expansion-board/nanosaur-exp-board-02-resistors.png
    alt: "Nanosaur Expansion board assembly resistors"
    title: "Nanosaur Expansion board assembly resistors"
  - url: /assets/docs/expansion-board/nanosaur-exp-board-03-switch.png
    image_path: /assets/docs/expansion-board/nanosaur-exp-board-03-switch.png
    alt: "Nanosaur Expansion board assembly switch"
    title: "Nanosaur Expansion board assembly switch"
  - url: /assets/docs/expansion-board/nanosaur-exp-board-04-connector.png
    image_path: /assets/docs/expansion-board/nanosaur-exp-board-04-connector.png
    alt: "Nanosaur Expansion board assembly connector"
    title: "Nanosaur Expansion board assembly connector"
  - url: /assets/docs/expansion-board/nanosaur-exp-board-05-assembled.png
    image_path: /assets/docs/expansion-board/nanosaur-exp-board-05-assembled.png
    alt: "Nanosaur Expansion board assembled"
    title: "Nanosaur Expansion board assembled"
  - url: /assets/docs/expansion-board/nanosaur-exp-board-06-assembled.png
    image_path: /assets/docs/expansion-board/nanosaur-exp-board-06-assembled.png
    alt: "Nanosaur Expansion board assembled"
    title: "Nanosaur Expansion board assembled"
pcb_expansion_wiring:
  - url: /assets/docs/expansion-board/wire-motor-control-01.png
    image_path: /assets/docs/expansion-board/wire-motor-control-01.png
    alt: "Wire motor control"
    title: "Wire motor control"
  - url: /assets/docs/expansion-board/wire-display.jpg
    image_path: /assets/docs/expansion-board/wire-display.jpg
    alt: "Wire display"
    title: "Wire display"
wiring:
  - url: /assets/docs/expansion-board/nanosaur-expansion-board.jpg
    image_path: /assets/docs/expansion-board/nanosaur-expansion-board.jpg
    alt: "Nanosaur Expansion board"
    title: "Nanosaur Expansion board"
usb-connector:
  - url: /assets/docs/expansion-board/usb-connector-parts.jpg
    image_path: /assets/docs/expansion-board/usb-connector-parts.jpg
    alt: "USB connector parts"
    title: "USB connector parts"
  - url: /assets/docs/expansion-board/usb-soldering-wires.jpg
    image_path: /assets/docs/expansion-board/usb-soldering-wires.jpg
    alt: "USB soldering wires"
    title: "USB soldering wires"
  - url: /assets/docs/expansion-board/usb-cover-B.jpg
    image_path: /assets/docs/expansion-board/usb-cover-B.jpg
    alt: "USB cover"
    title: "USB cover"
usb-connector-complete:
  - url: /assets/docs/expansion-board/usb-connector.jpg
    image_path: /assets/docs/expansion-board/usb-connector.jpg
    alt: "USB connector assembled"
    title: "USB connector assembled"
---

If you want buy the Nanosaur expansion board or you want support this project, please consider to watch the PCB project.
<a href="https://www.pcbway.com/project/shareproject/Nanosaur___The_smallest_NVIDIA_Jetson_dinosaur_robot.html"><img src="https://www.pcbway.com/project/img/images/frompcbway.png" alt="PCB from PCBWay" /></a>

The **Nanosaur Expansion-board** is under license [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].
{: .notice}

The expansion boars has size **20mm x 80mm** and have four M2 mounting holes, that perfectly fit inside the [Nanosaur flap](/assembly/#flap).

{% include gallery id="pcb_expansion_board_3d" caption="Nanosaur expansion board PCB" %}

This board is a simple adapter to connect the motor controller and the LCDs to the NVIDIA Jetson on your nanosaur, this board connect:

* I2C bus 0 (Pin 27, 28)
  * oled right
* I2C bus 1 (Pin 3, 5)
  * oled left
  * adafruit motor control
* 2 custom buttons
  * GPIO Pin 31
  * GPIO Pin 33

<!--
There are two ways to Assembly the expansion board:
 * [Nanosaur PCBs on PCBWay](#how-make-nanosaur-pcbs-on-pcbway) to support this project 
 * [Assembly with a matrix board](/option/assembly-matrix-board)
-->
# How make Nanosaur PCBs on PCBWay

- Register to PCBWay using [my refferer link](https://www.pcbway.com/setinvite.aspx?inviteid=472567)
- Upon you registered, go to the <a href="https://www.pcbway.com/project/shareproject/Nanosaur___The_smallest_NVIDIA_Jetson_dinosaur_robot.html">nanosaur <img src="https://www.pcbway.com/project/img/images/frompcbway.png" alt="PCB from PCBWay" /></a>
- Click on **"Add to Cart"** button on the right
- A pop-up will show up: all default settings are good. You must only select how many PCBs you want: the minimum quantity, by default, is 5. The first order of 5 PCBs is free on PCBWay: you must pay only the shipping costs

# Components

The list of components that you need to have are in this table below

{% include kicad_bom.html table_name=site.data.nanosaur-exp-board %}

You need to build your wires:

| Quantity | Part                                               | Notes     |
|:--------:|----------------------------------------------------|-----------|
| 1        | USB 2.0 connector Plug A, Type Male 4 pin          |           |
| 1        | 5m Flat ribbon cable 20P Rainbow IDC wire 1.27mm   | Only 30cm |
| 1        | **2Pin** 2.54mm female Dupont connector            |           |
| 1        | **3Pin** 2.54mm female Dupont connector            |           |
| 2        | **4Pin** 2.54mm female Dupont connector            |           |
| 15       | 2.54mm Dupont jumper wire cable                    |           |

All components are collected on picture below.

{% include figure image_path="/assets/docs/expansion-board/nanosaur-exp-board-components.jpg" alt="Nanosaur expansion board components" caption="Nanosaur expansion board components" %}

## Schematic

This expansion board is a simple connector for oleds and motor controller and works taking the power from the Power bank and power up the robot passing from a slide switch.

More detail are available on nanosaur expansion board schematic.

{% include figure image_path="/assets/docs/expansion-board/Expansion board-Schematic.svg" alt="Nanosaur schematic expansion board" caption="nanosaur schematic expansion board" %}

**:floppy_disk: Download** the nanosaur expansion board [**nanosaur-schematic.pdf**](https://github.com/rnanosaur/nanosaur-exp-board/releases/latest/download/nanosaur-schematic.pdf)
{: .notice--success}

# Assembly PCB

To assembly the PCB, you need only a solder all [components](#components) and follow the steps on the gallery below.

1. Resistors
2. Switch
3. Terminal block 1x02
4. PinHeader 2x20

The PCB will be like the last picture of the gallery

{% include gallery id="pcb_expansion_steps" caption="Nanosaur expansion board assembly" %}

## Wiring PCB

To wire bring your 30cm flat ribbon cable 20P Rainbow IDC wire 1.27mm and split in 3 different wires:

| Quantity | Name          | Length  | Color code      |
|:--------:|---------------|---------|-----------------|
| 1        | Conn_motors   | 210mm   | brown -> blue   |
| 2        | Conn_i2c_oled | 300mm   | violet -> black |
| 2        | motor         | 90mm    | red & brown     |
| 1        | USB connector | 120mm   | black & red     |

{% include figure image_path="/assets/docs/expansion-board/nanosaur-exp-board-wire-01.png" alt="wire color schematic" caption="wire color schematic" %}

Now pay attention to wire in the right order the motor control cable **(Conn_motors)** where:

| Num | Color   | Connection                          | Type        |
|:---:|:-------:|-------------------------------------|-------------|
| 1   | brown   | spare                               | Motor (+)   |
| 2   | red     | spare                               | Motor (-)   |
| 3   | amber   | **2Pin**  Dupont connector          | SDA         |
| 4   | yellow  | **2Pin**  Dupont connector          | SCL         |
| 5   | green   | **3Pin**  Dupont connector **side** | VCC (+3.3V) |
| 6   | blue    | **3Pin**  Dupont connector **side** | GND         |

For the both display follow this table

| Num | Color   | Connection                          | Type        |
|:---:|:-------:|-------------------------------------|-------------|
| 1   | black   | **2Pin**  Dupont connector          | GND         |
| 2   | white   | **2Pin**  Dupont connector          | VCC (+3.3V) |
| 3   | grey    | **2Pin**  Dupont connector          | SCL         |
| 4   | violet  | **2Pin**  Dupont connector          | SDA         |

The wiring will be like the pictures below:

{% include gallery id="pcb_expansion_wiring" caption="Nanosaur wires" %}

To wire the expansion board follow the picture below, where:

| Plug | Name                    | Note                                   |
|:----:|-------------------------|----------------------------------------|
| J3   | Conn_i2c_oled **right** | **Violet** wire on squared hole (pin 1) |
| J4   | Conn_i2c_oled **left**  | **Violet** wire on squared hole (pin 1) |
| J5   | Conn_motors             | **Brown** wire on squared hole (pin 1) |

{% include figure image_path="/assets/docs/expansion-board/nanosaur-exp-board-wires-02.jpg" alt="Soldering wires on nanosaur expansion board" caption="Soldering wires on nanosaur expansion board" %}

When the soldering is done you will obtain nanosaur expansion board ready to be assembled on Nanosaur

{% include gallery id="wiring" caption="Nanosaur expansion board" %}

## Wiring USB connector

Last plug, last wiring! It's almost done.

Bring your **120mm wires red and black** and solder to the USB connector following the USB pinout below

{% include figure image_path="/assets/docs/expansion-board/USB.jpg" alt="USB pinout" caption="USB pinout" %}

Now wire the USB connector follow this table

| Num | Color   | Type        |
|:---:|:-------:|-------------|
| 1   | red     | +           |
| 2   | -       | D+          |
| 3   | -       | D-          |
| 4   | black   | -           |

And follow the pictures below to make your USB wire for the Nanosaur expansion board.

{% include gallery id="usb-connector" caption="USB connector wiring" %}

Add an heat shrink to insulate the wires and the connector will look like the picture below

{% include gallery id="usb-connector-complete" caption="USB connector wired" %}

# PCB Board

The **Nanosaur Expansion-board** is under license [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].
{: .notice}

The size is **20mm x 80mm** with 4 M2 mounting holes, with PCB Layout will be like the pictures below

{% include gallery id="pcb_expansion_board" caption="PCB expansion board" %}

**:floppy_disk: Download** the Nanosaur expansion board **STEP** file [**nanosaur-exp-board.step**](https://github.com/rnanosaur/nanosaur-exp-board/releases/latest/download/nanosaur-exp-board.step)
{: .notice--success}

If you want print by yourself the expansion board, you can download the **gerber** file from this link

**:floppy_disk: Download** the Nanosaur expansion board **gerber** file [**nanosaur-gerber.zip**](https://github.com/rnanosaur/nanosaur-exp-board/releases/latest/download/nanosaur-gerber.zip)
{: .notice--success}

# LICENSE

The **Nanosaur Expansion-board** is under license [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
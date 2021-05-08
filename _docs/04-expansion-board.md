---
title: "Expansion board"
permalink: /expansion-board/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
pcb_expansion_board:
  - url: /assets/docs/expansion-board/nanosaur-exp-board-Board_top.svg
    image_path: /assets/docs/expansion-board/nanosaur-exp-board-Board_top.svg
    alt: "Flap and power bank holder orientation"
    title: "Flap and power bank holder orientation"
  - url: /assets/docs/expansion-board/nanosaur-exp-board-Board_bottom.svg
    image_path: /assets/docs/expansion-board/nanosaur-exp-board-Board_bottom.svg
    alt: "Flap and power bank holder slicer support type tree"
    title: "Flap and power bank holder slicer support type tree"
---

The expansion board is a simple adapter to connect the motor controller and the LCDs to the NVIDIA Jetson on your NanoSaur, this board connect:

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

<table>
  {% for row in site.data.nanosaur-exp-board %}
    {% if forloop.first %}
    <thead>
    <tr>
      {% for pair in row %}
        <th style="text-align: center">{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    </thead>
    {% endif %}

    {% tablerow pair in row %}
      {{ pair[1] }}
    {% endtablerow %}
  {% endfor %}
</table>

## Schematic

This expansion board is a simple connector for oleds and motor controller and works taking the power from the Power bank and power up the robot passing from a slide switch.

More detail are available on NanoSaur expansion board schematic.

{% include figure image_path="/assets/docs/expansion-board/nanosaur-exp-board-Schematic.svg" alt="Nanosaur schematic expansion board" caption="NanoSaur schematic expansion board" %}

**:floppy_disk: Download** the NanoSaur expansion board [**schematics.pdf**](https://github.com/rnanosaur/nanosaur-exp-board/releases/latest/download/combined.pdf)
{: .notice--success}

# Assembly PCB

**:construction: This part will be updated soon.**<br/>For any issue join on [Discord](https://discord.gg/NSrC52P5mw)
{: .notice--warning}

# Assembly matrix board

To assembly the expansion board, is simple you need only to weld the female 2x20 connector and a switch.

# PCB Board

The size is **20mm x 80mm** with 4 M2 mounting holes, with PCB Layout will be like the pictures below

{% include gallery id="pcb_expansion_board" caption="PCB expansion board" %}

**:floppy_disk: Download** the Nanosaur expansion board **STEP** file [**nanosaur-exp-board.step**](https://github.com/rnanosaur/nanosaur-exp-board/releases/latest/download/nanosaur-exp-board.step)
{: .notice--success}

If you want print by yourself the expansion board, you can download the **gerber** file from this link
---
title: "Bill of Materials"
excerpt: "Bill of Materials to build nanosaur."
permalink: /bill-of-materials/
redirect_from:
  - /extra/bom-countries
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
---

If you want make your nanosaur, it's simple and you can make directly at home, you only need few tools and print some parts to buy.

<!--
If you don't want print or you don't have a 3D printer you can buy all parts you need, simple going on the [buy](/buy) page.
-->

**:bulb: Hint** There is a component missing, do you need an help? Ask on [Discord](https://discord.gg/kgqW7Hrk3u)
{: .notice--info}

# BoM

This table is your necessary needed to make nanosaur. Few parts, starting from the NVIDIA Jetson, the PI camera, motors and the motor control.

| Qt       | Part                        | :us: USA  | :it: Italy | :uk: UK | :netherlands: NL | Notes                               |
|:--------:|-----------------------------|:---------:|:----------:|:-------:|:----------------:|-------------------------------------|
| 1        | NVIDIA Jetson Nano          | [NVIDIA store](https://developer.nvidia.com/embedded/buy/jetson-nano-devkit) |            |         |                  | You can use<br/> **2Gb** or **4Gb** version<br/>Buy this alternative carrier:<br/>[SEEED studio](https://www.seeedstudio.com/Jetson-10-1-H0-p-5335.html) |
| 1        | MicroSD card 64Gb           | :us: $9.99<br/>[Amazon](https://amzn.to/2X7rWpH) | :it:<br/>[Amazon](https://amzn.to/3mxPCR1) | :uk:<br/>[Amazon](https://amzn.to/3qv95mB) | :netherlands:<br/>[Amazon](https://amzn.to/3pw9FS1) |       |
| 1        | 128GB NVM3 M.2 PCLe SSD     |           |            |         |  | **Only for SEEED STUDIO carrier**<br/>[NVMe M.2](https://www.seeedstudio.com/M-2-2280-SSD-128GB-p-5332.html)     |
| 1        | Wi-Fi Dongle 5Ghz           | :us: $13.90<br/>[Amazon](https://amzn.to/3mDiBTE) | :it:<br/>[Amazon](https://amzn.to/3qOI3qP) | :uk:<br/>[Amazon](https://amzn.to/3sJXsen) | :netherlands:<br/>[Amazon](https://amzn.to/3HgC5FB) |       |
| 1        | Power Bank                  | :us: $29.99<br/>[Amazon](https://amzn.to/2X8RNha) | :it:<br/>[Amazon](https://amzn.to/3syJ4Wl) | :uk:<br/>[Amazon](https://amzn.to/3ey5bnm) | :netherlands:<br/>[Amazon](https://amzn.to/3mB7eMd) | [Power Bank dimensioning](/optional/power-bank) |
| 2        | Pololu Micro Gearbox        | :us: $25.75<br/>[Amazon](https://amzn.to/3hS4o1P) | :it:<br/>[Amazon](https://amzn.to/3JjEwZP) | :uk:<br/>[Amazon](https://amzn.to/3ey58YI) | :netherlands:<br/>[Amazon](https://amzn.to/3HgMG3j) | [Pololu 6V 150RPM](https://www.pololu.com/product/2368)<br/> **alternative**:<br/>[aliexpress.com](https://www.aliexpress.com/item/4000274747864.html) |
| 1        | Adafruit motor control      | :us: $29.10<br/>[Amazon](https://amzn.to/392GhZU) | :it:<br/>[Amazon](https://amzn.to/3psMwjk) | :uk:<br/>[Amazon](https://amzn.to/3162czI) | :netherlands:<br/>[Amazon](https://amzn.to/3H6VYPo) | [DC Motor + Stepper FeatherWing Add-on](https://www.adafruit.com/product/2927)<br/> **alternative**:<br/>[aliexpress.com](https://www.aliexpress.com/item/4001089410177.html) |
| 2        | oled display                | :us: $5<br/>[Amazon](https://amzn.to/3ocB3kJ) | :it:<br/>[Amazon](https://amzn.to/3EwAObC) | :uk:<br/>[Amazon](https://amzn.to/3HavufG) | :netherlands:<br/>[Amazon](https://amzn.to/3EwYaxK) | 128x64px 0.06in I2C<br/> Best price pack:<br/>[3 display](https://amzn.to/3d6Qgkv)  |
| 6        | Ball bearings **F686ZZ**    | :us: $7.49<br/>[Amazon](https://amzn.to/3dIs8DJ) | :it:<br/>[Amazon](https://amzn.to/3z0zeh4) | :uk:<br/>[Amazon](https://amzn.to/3qmJVqc) | :netherlands:<br/>[Amazon](https://amzn.to/3Hay856) | **alternative**:<br/>[aliexpress.com](https://www.aliexpress.com/item/32862353983.html)  |
| 10       | Magnets 4x2mm              | :us: $10.99<br/>[Amazon](https://amzn.to/3pwnnTp) |   |  | :netherlands:<br/>[Amazon](https://amzn.to/3z1FgOD) | **alternative**:<br/>[aliexpress.com](https://www.aliexpress.com/item/1005001530483863.html)                          |
| -        | Expansion board             |           |           |           |           | [Expansion board](#expansion-board) |
| -        | 3D parts                    |           |           |           |           | [3D filaments](#3d-filaments)               |
| -        | Hex M2 Screw set            | :us: $10*<br/>Amazon |            |           |           | [Screw set](#screw-set)             |

## Cameras

List of camera options available

| Cover                | Bill of Material |
|----------------------|------------------|
| ![Waveshare IMX219-160 Camera]({{ '/assets/docs/assembly/cover-fe/nanosaur-cover-fe-200.png' | relative_url }}) | [Waveshare IMX219-160 Camera](/optional/cover#wide-angle-camera-fish-eye) |
| ![Raspberry Camera v2]({{ '/assets/docs/assembly/cover-cam/nanosaur-cover-200.png' | relative_url }}) | [Raspberry Camera v2](/optional/cover#camera) |
| ![Stereolabs ZED mini]({{ '/assets/docs/assembly/cover-zedmini/nanosaur-cover-zedmini-200.png' | relative_url }}) | [Stereolabs ZED mini](/optional/cover#zed-mini) |
| ![Intel Realsense d435i]({{ '/assets/docs/assembly/cover-rs/nanosaur-cover-realsense-200.png' | relative_url }}) | [Intel Realsense d435i](/optional/cover#realsense) |

## Optionals

These parts are not really needed to build your robot, but suggested if you want speed up the NVIDIA Jetson or assembly the robot.

| Qt | Part                | :us: USA  | :it: Italy | :uk: UK | :netherlands: NL | Notes |
|:--:|---------------------|:---------:|:----------:|:-------:|:----------------:|-------|
| 1  | Noctua 4x4cm fan    | :us: $15<br/>[Amazon](https://amzn.to/32A9fku)  | :it:<br/>[Amazon](https://amzn.to/343mj2z) | :uk:<br/>[Amazon](https://amzn.to/3EyxSvh) | :netherlands:<br/>[Amazon](https://amzn.to/3qwxaJI) |       |
| 1  | M2 electric screwdriver      | :us:  $5<br/>[Amazon](https://amzn.to/3erJ1Dg)  | :it:<br/>[Amazon](https://amzn.to/3sDHQt4) | :uk:<br/>[Amazon](https://amzn.to/3z2QJgF) | :netherlands:<br/>[Amazon](https://amzn.to/3sD9pTh) |      |
| 1  | M2 allen key        |  |  |  |  |  |
| 1  | Gamepad Logitech F710      | :us:  $31<br/>[Amazon](https://amzn.to/3EBu9x1)  | :it:<br/>[Amazon](https://amzn.to/3pzo8N5) | :uk:<br/>[Amazon](https://amzn.to/3mAUaq8) | :netherlands:<br/>[Amazon](https://amzn.to/3ECxZWB) |      |
| 6  | Ball bearings - 1/4' x 1/2' | [Servocity](https://www.servocity.com/1-4-id-x-1-2-od-flanged-ball-bearing-2-pack/) |   |     |  | If you don't have the F686ZZ ball bearings  |

# 3D filaments

If you want print nanosaur, you should buy these spool. I suggest the Ninjatek TPU if you use a bowden 3D printer. Otherwise you can use other type of TPU.

| Qt | Part                | :us: USA  | :it: Italy | :uk: UK | :netherlands: NL | Notes |
|:--:|---------------------|:---------:|:----------:|:-------:|:----------------:|-------|
| 1  | PLA 1.75mm Eryone green    | :us: $15<br/>[Amazon](https://amzn.to/32D41EK)  | :it:<br/>[Amazon](https://amzn.to/3Ji6ghD) | :uk:<br/>[Amazon](https://amzn.to/3sBnrEN) |  | Other PLA/PLA+ are compatible |
| 1  | PLA 1.75mm Eryone black    | :us: $15<br/>[Amazon](https://amzn.to/3Hd2Pa3)  | :it:<br/>[Amazon](https://amzn.to/3qmRc9u) | :uk:<br/>[Amazon](https://amzn.to/3Hkrf1t) |  | Other PLA/PLA+ are compatible|
| 1  | TPU 1.75mm NinjaTek black  | :us: $40<br/>[Amazon](https://amzn.to/3sH4MYa)  | :it:<br/>[Amazon](https://amzn.to/3JmACPJ) | :uk:<br/>[Amazon](https://amzn.to/3pw8eCX) |  | TPU Sainsmart works, but it is more hard |

For more details follow [3D print](/3d-print) page to setup and print all 3D printed parts.

# Expansion board

First step, you need the **nanosaur-expansion-board** PCB

{% include figure image_path="/assets/docs/expansion-board/nanosaur-exp-board-Board_top.svg" alt="Nanosaur Expansion board PCB top" caption="Nanosaur Expansion board PCB top" %}

To obtain one and support this project follow these steps:

- Register to PCBWay using [my refferer link](https://www.pcbway.com/setinvite.aspx?inviteid=472567)
- Upon you registered, go to the <a href="https://www.pcbway.com/project/shareproject/Nanosaur___The_smallest_NVIDIA_Jetson_dinosaur_robot.html">nanosaur <img src="https://www.pcbway.com/project/img/images/frompcbway.png" alt="PCB from PCBWay" /></a>
- Click on **"Add to Cart"** button on the right
- A pop-up will show up: all default settings are good. You must only select how many PCBs you want: the minimum quantity, by default, is 5. The first order of 5 PCBs is free on PCBWay: you must pay only the shipping costs

The BoM below is to assembly the **nanosaur-expansion-board**:

{% include kicad_bom.html table_name=site.data.nanosaur-exp-board %}

To assembly the nanosaur expansion board follow [expansion-board](/expansion-board) documentation.

## Table connectors

In this table you can assembly all nanosaur connectors for [expansion-board](/expansion-board).

| Quantity | Part                                               | Note      |
|:--------:|----------------------------------------------------|-----------|
| 1        | USB 2.0 connector Plug A, Type Male 4 pin          | [aliexpress.com](https://www.aliexpress.com/item/32963245331.html) |
| 1        | 5m Flat ribbon cable **20P** Rainbow IDC wire 1.27mm   | Only 30cm<br/>[aliexpress.com](https://www.aliexpress.com/item/1005003596191061.html) |
| 1        | **2Pin** 2.54mm female Dupont connector            | [aliexpress.com](https://www.aliexpress.com/item/33035707563.html) |
| 1        | **3Pin** 2.54mm female Dupont connector            | [aliexpress.com](https://www.aliexpress.com/item/33035707563.html) |
| 2        | **4Pin** 2.54mm female Dupont connector            | [aliexpress.com](https://www.aliexpress.com/item/33035707563.html) |
| 15       | 2.54mm Dupont jumper wire cable                    | [aliexpress.com](https://www.aliexpress.com/item/32629953261.html) |

# Screw set

nanosaur use a short set of M2 screw, you can buy a set

| Quantity | Part                        | Note  |
|:--------:|-----------------------------|-------|
| 6        | M2 nuts                     |       |
| 20       | Hex M2 4mm                  |       |
| 4        | Hex M2 6mm                  |       |
| 4        | Hex M2 10mm                 |       |
| 6        | Hex M2 20mm                 |       |

If you are building nanosaur [**without** magnets](/optional/screw-assembly), you need other 3 extra screws

| Quantity | Part                        | Note  |
|:--------:|-----------------------------|-------|
| 1        | Hex M2 14mm                 |       |
| 4        | Hex M2 6mm                  |       |

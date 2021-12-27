---
title: "Bill of Materials"
permalink: /bill-of-materials/
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

# BOM

This table is your necessary needed to make nanosaur. Few parts, starting from the NVIDIA Jetson, the PI camera, motors and the motor control.

| Qt       | Part                        | :us: USA  | :it: Italy | :uk: UK | :netherlands: NL | Notes                               |
|:--------:|-----------------------------|:---------:|:----------:|:-------:|:----------------:|-------------------------------------|
| 1        | NVIDIA Jetson Nano          | :us: $59-$99<br/>[NVIDIA](https://developer.nvidia.com/embedded/buy/jetson-nano-devkit)| :it:<br/>[NVIDIA](https://developer.nvidia.com/embedded/buy/jetson-nano-devkit)| :uk:<br/>[NVIDIA](https://developer.nvidia.com/embedded/buy/jetson-nano-devkit) | :netherlands:<br/>[NVIDIA](https://developer.nvidia.com/embedded/buy/jetson-nano-devkit) | You can use<br/> **2Gb** or **4Gb** version |
| 1        | MicroSD card 64Gb           | :us: $9.99<br/>[Amazon](https://amzn.to/2X7rWpH) | :it:<br/>[Amazon](https://amzn.to/3mxPCR1) | :uk:<br/>[Amazon](https://amzn.to/3qv95mB) | :netherlands:<br/>[Amazon](https://amzn.to/3pw9FS1) |       |
| 1        | Power Bank                  | :us: $29.99<br/>[Amazon](https://amzn.to/2X8RNha) | :it:<br/>[Amazon](https://amzn.to/3syJ4Wl) | :uk:<br/>[Amazon](https://amzn.to/3ey5bnm) | :netherlands:<br/>[Amazon](https://amzn.to/3mB7eMd) | Size max:<br/>64mm x 94mm x 24mm<br/>(3in x 4in x 0.94in) |
| 1        | Raspberry PI camera         | :us: $23.50<br/>[Amazon](https://amzn.to/2LgasF5) | :it:<br/>[Amazon](https://amzn.to/3sDmw6P) | :uk:<br/>[Amazon](https://amzn.to/3mwzn71) | :netherlands:<br/>[Amazon](https://amzn.to/3qvbGNn) |                                    |
| 2        | Pololu Micro Gearbox        | :us: $25.75<br/>[Amazon](https://amzn.to/3hS4o1P) | :it:<br/>[Amazon](https://amzn.to/3JjEwZP) | :uk:<br/>[Amazon](https://amzn.to/3ey58YI) | :netherlands:<br/>[Amazon](https://amzn.to/3HgMG3j) | [Pololu 6V 150RPM](https://www.pololu.com/product/2368) |
| 1        | Adafruit motor control      | :us: $29.10<br/>[Amazon](https://amzn.to/392GhZU) | :it:<br/>[Amazon](https://amzn.to/3psMwjk) | :uk:<br/>[Amazon](https://amzn.to/3162czI) | :netherlands:<br/>[Amazon](https://amzn.to/3H6VYPo) | [DC Motor + Stepper FeatherWing Add-on](https://www.adafruit.com/product/2927) |
| 2        | oled display                | :us: $5<br/>[Amazon](https://amzn.to/3ocB3kJ) | :it:<br/>[Amazon](https://amzn.to/3EwAObC) | :uk:<br/>[Amazon](https://amzn.to/3HavufG) | :netherlands:<br/>[Amazon](https://amzn.to/3EwYaxK) | 128x64px 0.06 inch - I2C<br/>Best price pack [3 display](https://amzn.to/3d6Qgkv)  |
| 6        | Ball bearings **F686ZZ**    | :us: $7.49<br/>[Amazon](https://amzn.to/3dIs8DJ) | :it:<br/>[Amazon](https://amzn.to/3z0zeh4) | :uk:<br/>[Amazon](https://amzn.to/3qmJVqc) | :netherlands:<br/>[Amazon](https://amzn.to/3Hay856) |                                      |
| 10       | Magnets 4x2mm              | :us: $10.99<br/>[Amazon](https://amzn.to/3pwnnTp) |   |  | :netherlands:<br/>[Amazon](https://amzn.to/3z1FgOD) | 200Pcs box                          |
| -        | Expansion board             |           |           |           |           | [Expansion board](#expansion-board) | 
| -        | 3D parts                    |           |           |           |           | [3D parts](#3d-parts)               |
| -        | Hex M2 Screw set            | :us: $10*<br/>Amazon |           |           |           | [Screw set](#screw-set)             |

**Equivalent components**

| Quantity | Part                        | Cost     | URL       | Notes                               |
|:--------:|-----------------------------|:--------:|-----------|-------------------------------------|
| 6        | Ball bearings - 1/4' x 1/2' |          | [Servocity](https://www.servocity.com/1-4-id-x-1-2-od-flanged-ball-bearing-2-pack/) | If you don't have the F686ZZ ball bearings  |

## Screw set

nanosaur use a short set of M2 screw, you can buy a set 

| Quantity | Part                        | Notes |
|:--------:|-----------------------------|-------|
| 6        | M2 nuts                     |       |
| 6        | Hex M2 20mm                 |       |
| 6        | Hex M2 6mm                  |       |
| 20       | Hex M2 4mm                  |       |

If you are building nanosaur without magnets, you need other 3 extra screws

| Quantity | Part                        | Notes |
|:--------:|-----------------------------|-------|
| 1        | Hex M2 14mm                 |       |
| 2        | Hex M2 6mm                  |       |

## Expansion board

This last table is to build the expansion board to connect the NVIDIA Jetson to the motor control board and the 2 oled displays.

{% include kicad_bom.html table_name=site.data.nanosaur-exp-board %}

To build the expansion board follow [this page](/expansion-board)

## 3D parts

If you want print nanosaur, you should buy these spool. I suggest the Ninjatek TPU if you use a bowden 3D printer. Otherwise you can use other type of TPU.

| Qt | Part                | :us: USA  | :it: Italy | :uk: UK | :netherlands: NL | Notes |
|:--:|---------------------|:---------:|:----------:|:-------:|:----------------:|-------|
| 1  | PLA Eryone green    | :us: $15<br/>[Amazon](https://amzn.to/32D41EK)  | :it:<br/>[Amazon](https://amzn.to/3Ji6ghD) | :uk:<br/>[Amazon](https://amzn.to/3sBnrEN) |  | PLA Sunlu works as well |
| 1  | PLA Eryone black    | :us: $15<br/>[Amazon](https://amzn.to/3Hd2Pa3)  | :it:<br/>[Amazon](https://amzn.to/3qmRc9u) | :uk:<br/>[Amazon](https://amzn.to/3Hkrf1t) |  | PLA Sunlu works as well |
| 1  | TPU NinjaTek black  | :us: $40<br/>[Amazon](https://amzn.to/3sH4MYa)  | :it:<br/>[Amazon](https://amzn.to/3JmACPJ) | :uk:<br/>[Amazon](https://amzn.to/3pw8eCX) |  | TPU sainsmart works, but it is more hard |

The parts to print are [below](#components-to-print)

## Optionals

These parts are not really needed to build your robot, but suggested if you want speed up the NVIDIA Jetson or assembly the robot.

| Qt | Part                | :us: USA  | :it: Italy | :uk: UK | :netherlands: NL | Notes |
|:--:|---------------------|:---------:|:----------:|:-------:|:----------------:|-------|
| 1  | Noctua 4x4cm fan    | :us: $15<br/>[Amazon](https://amzn.to/32A9fku)  | :it:<br/>[Amazon](https://amzn.to/343mj2z) | :uk:<br/>[Amazon](https://amzn.to/3EyxSvh) | :netherlands:<br/>[Amazon](https://amzn.to/3qwxaJI) |       |
| 1  | M2 screwdriver      | :us:  $5<br/>[Amazon](https://amzn.to/3erJ1Dg)  | :it:<br/>[Amazon](https://amzn.to/3sDHQt4) | :uk:<br/>[Amazon](https://amzn.to/3z2QJgF) | :netherlands:<br/>[Amazon](https://amzn.to/3sD9pTh) | to speed up your build, you can use a screwdriver instead of an allen key  |
| 1  | M2 allen key        |  |  |  |  |       |

# Components to print

Well, you have all components, now you need only to 3D print the robot. All parts are simple to print but, need time to be done, below there is a short table with the average time for each part.

I recommend to print all STL part with:
* **Layer height**: 0.2mm
* **Print speed**: 50mm/s

Below the list of all parts, the time required for each part and the color suggested:

| Quantity | Part            | Material        | Time  | Notes |
|:--------:|-----------------|-----------------|:-----:|-------|
| 1        | base_rear.stl   | PLA green       | 5h    |       |
| 1        | base_front.stl  | PLA green       | 1:30h |       |
| 1        | cover.stl       | PLA green       | 1:45h |       |
| 2        | slider.stl      | PLA green       | 1h    |       |
| 1        | pb_holder.stl   | PLA green       | 20min |       |
| 1        | flap_top.stl    | PLA green       | 45min |       |
| 1        | flap_bottom.stl | PLA green       | 45min |       |
| 2        | sprocket.stl    | PLA green/black | 1h    |       |
| 2        | wheel.stl       | PLA green/black | 1h    |       |
| 2        | track_print.stl | TPU black/grey  | 1:30h | **Print speed**: 30mm/s |

You can reduce the time to print your nanosaur, printing some part together. For more details go to the [next page](/3d-print) of this guide to setup and print with your 3D printer.


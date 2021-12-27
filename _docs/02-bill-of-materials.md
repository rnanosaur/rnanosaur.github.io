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

| Quantity | Part                        | Cost     | :us: USA  | :it: Italy | :uk: UK | Notes                               |
|:--------:|-----------------------------|:--------:|-----------|------------|---------|-------------------------------------|
| 1        | NVIDIA Jetson Nano 2Gb*     | $59-$99  | [:us: NVIDIA](https://developer.nvidia.com/embedded/buy/jetson-nano-devkit)| [:it: NVIDIA](https://developer.nvidia.com/embedded/buy/jetson-nano-devkit)| [:uk: NVIDIA](https://developer.nvidia.com/embedded/buy/jetson-nano-devkit)|  |
| 1        | MicroSD card 64Gb           | $9.99    | [:us: Amazon](https://amzn.to/2X7rWpH) | [:it: Amazon](https://amzn.to/39015kN) | [:uk: Amazon](https://amzn.to/3rPYqCY) |        |
| 1        | Power Bank                  | $29.99   | [:us: Amazon](https://amzn.to/2X8RNha) | [:it: Amazon](https://amzn.to/3GpERJ8) | [:uk: Amazon](https://amzn.to/3rQr46R) | Size max:<br/>64mm x 94mm x 24mm<br/>(3in x 4in x 0.94in) |
| 1        | Raspberry PI camera         | $23.50   | [:us: Amazon](https://amzn.to/2LgasF5) | [:it: Amazon](https://amzn.to/2Mxc8uo) | [:uk: Amazon](https://amzn.to/2LehMAW) |                                     |
| 2        | Pololu Micro Gearbox        | $25.75   | [:us: Amazon](https://amzn.to/3hS4o1P) | [:it: Amazon](https://amzn.to/3tbVnp8) | [:uk: Amazon](https://amzn.to/3ogIyXZ) | [Pololu 6V 150RPM](https://www.pololu.com/product/2368) |
| 1        | Adafruit motor control      | $29.10   | [:us: Amazon](https://amzn.to/392GhZU) | [:it: Amazon](https://amzn.to/3mz3BFh) | [:uk: Amazon](https://amzn.to/3rKMiTI) | [DC Motor + Stepper FeatherWing Add-on](https://www.adafruit.com/product/2927) |
| 2        | oled display                | $5       | [:us: Amazon](https://amzn.to/3ocB3kJ) | [:it: Amazon](https://amzn.to/3d4FFWX) | [:uk: Amazon](https://amzn.to/3pQBH8b) | 128x64px 0.06 inch - I2C<br/>Best price pack [3 display](https://amzn.to/3d6Qgkv)  |
| 6        | Ball bearings **F686ZZ**    | $ 7.49   | [:us: Amazon](https://amzn.to/3dIs8DJ) | [:it: Amazon](https://amzn.to/2Q75LiZ) | [:uk: Amazon](https://amzn.to/3wzYiKf) |                                      |
| 10       | Magnets 4x2mm              | $ 10.99   | [:us: Amazon](https://amzn.to/3pwnnTp) |   |   | 200Pcs box                          |
| -        | Expansion board             |          |           |           |           | [Expansion board](#expansion-board) | 
| -        | 3D parts                    |          |           |           |           | [3D parts](#3d-parts)               |
| -        | Hex M2 Screw set            | $10*     | Amazon    |           |           | [Screw set](#screw-set)             |

(*) nanosaur works with the NVIDIA Jetson Nano 2Gb or an NVIDIA Jetson Nano 4Gb

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
| 1        | Hex M2 14mm                 |       |
| 8        | Hex M2 6mm                  |       |
| 20       | Hex M2 4mm                  |       |

## Expansion board

This last table is to build the expansion board to connect the NVIDIA Jetson to the motor control board and the 2 oled displays.

{% include kicad_bom.html table_name=site.data.nanosaur-exp-board %}

To build the expansion board follow [this page](/expansion-board)

## 3D parts

If you want print nanosaur, you should buy these spool. I suggest the Ninjatek TPU if you use a bowden 3D printer. Otherwise you can use other type of TPU.

| Quantity | Part                | Cost | URL | Notes |
|:--------:|---------------------|------|-----|-------|
| 1        | PLA green           | $15  |     |       |
| 1        | PLA black           | $15  |     |       |
| 1        | TPU NinjaTek black  | $40  |     |       |

The parts to print are [below](#components-to-print)

## Optionals

These parts are not really needed to build your robot, but suggested if you want speed up the NVIDIA Jetson or assembly the robot.

| Quantity | Part                | Cost | URL | Notes |
|:--------:|---------------------|------|-----|-------|
| 1        | Noctua 4x4cm fan    | $15  |     |       |
| 1        | M2 screwdriver      | $5   |     |       |

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


---
title: "Bill of Materials"
permalink: /bill-of-materials/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
---

If you want make your NanoSaur, it's simple and you can make directly at home, you only need few tools and print some parts to buy.

If you don't want print or you don't have a 3D printer you can buy all parts you need, simple going on the [buy](/buy) page.

# BOM

This table is your necessary needed to make NanoSaur. Few parts, starting from the NVIDIA Jetson, the PI camera, motors and the motor control.

| Quantity | Part                    | Cost | URL | Notes |
|:--------:|-------------------------|------|-----|-------|
| 1        | NVIDIA Jetson Nano 2Gb* | $49  |     |       |
| 1        | MicroSD card 64Gb       | $14  |     |       |
| 1        | Power Bank              | $11  |     |       |
| 1        | Raspberry PI camera     | $14  |     |       |
| 2        | Pololu Micro Gearbox    | $10  |     |       |
| 1        | Adafruit motor control  | $25  |     |       |
| 2        | oled display            | $5   |     |       |
| -        | Expansion board         |      |     | [Expansion board](#expansion-board) |
| -        | 3D parts                |      |     | [3D parts](#3d-parts) |
| 20       | M2 screw 4mm            | $1   |     |       |
| 4        | M2 screw 8mm            | $1   |     |       |
| 2        | M2 screw 10mm           | $1   |     |       |
| 10       | M2 screw 20mm           | $1   |     |       |

(*) NanoSaur works with the NVIDIA Jetson Nano 2Gb or an NVIDIA Jetson Nano 4Gb

## Expansion board

This last table is to build the expansion board to connect the NVIDIA Jetson to the motor control board and the 2 oled displays.

| Quantity | Part                    | Cost | URL | Notes |
|:--------:|-------------------------|------|-----|-------|
| 1        | Matrix board            | $3   |     |       |
| 1        | Flat ribbon             | $10  |     |       |
| 1        | Switch slim             | $2   |     |       |
| 1        | USB cable               | $3   |     |       |
| 1        | Female jack             | $3   |     |       |

To build the expansion board follow [this page](04-expansion-board)

## 3D parts

If you want print NanoSaur, you should buy these spool. I suggest the Ninjatek TPU if you use a bowden 3D printer. Otherwise you can use other type of TPU.

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

You can reduce the time to print your NanoSaur, printing some part together. For more details go to the [next page](/3d-print) of this guide to setup and print with your 3D printer.


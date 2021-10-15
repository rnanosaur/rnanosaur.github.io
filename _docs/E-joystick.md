---
title: "Joystick control"
permalink: /extra/joystick
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
joystick:
  - url: /assets/docs/joystick/F710-top.jpg
    image_path: /assets/docs/joystick/F710-top.jpg
    alt: "Joystick Logitech F710 top"
    title: "Joystick Logitech F710 top"
  - url: /assets/docs/joystick/F710-rear.jpg
    image_path: /assets/docs/joystick/F710-rear.jpg
    alt: "Joystick Logitech F710 rear"
    title: "Joystick Logitech F710 rear"
---

If you have a F710 joystick you don't need to do nothing, just only plug the dongle in a Jetson USB port and switch on the robot.

When the robot start you will be able to drive or manually control the robot.

{% include gallery id="joystick" caption="Joystick F710" %}

**Please Note: F710 works on ROS in Xinput (Select letter X)**

# Drive Robot

If you want drive and control nanoasur you have different commands:


## Manual control

If you want manually control nanosaur, there are two options:

* **LB** - (Always pressed) Slow speed
* **RB** - (Always pressed) Fast speed

To drive Nanosaur, you can use the **left joystick** to accelerate and twist the robot.

## Power off

If you want power off nanosaur you can simply press all **rear buttons** together for more than **3 seconds**, in detail:

* **LB**
* **LT**
* **RB**
* **RT**

# Jostick map

Reference number for buttons and analog joystick with ros joy topic:

## Buttons

| ID | Name      | Type   |
|----|-----------|--------|
| 0  | **A**     | button |
| 1  | **B**     | button |
| 2  | **X**     | button |
| 3  | **Y**     | button |
| 4  | **LB**    | button |
| 5  | **RB**    | button |
| 6  | **Back**  | button |
| 7  | **Start** | button |
| 8  | **Logo**  | button |
| 9  | **LJ**    | button |
| 10 | **RJ**    | button |

## Analog joystick

| ID | Name      | Type   |
|----|-----------|--------|
| 0  | **LJx**   | X axis |
| 1  | **LJy**   | Y axis |
| 2  | **LT**    |        |
| 3  | **RJx**   | X axis |
| 4  | **RJy**   | Y axis |
| 5  | **RT**    |        |
| 6  | **Pad X** | X axis |
| 7  | **Pad Y** | Y axis |
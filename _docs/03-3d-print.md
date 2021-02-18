---
title: "3D print"
permalink: /3d-print/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
base_front:
  - url: /assets/docs/3d-print/base_front_A.png
    image_path: /assets/docs/3d-print/base_front_A.png
    alt: "base_front.stl orientation"
    title: "base_front.stl orientation"
  - url: /assets/docs/3d-print/base_front_B.png
    image_path: /assets/docs/3d-print/base_front_B.png
    alt: "base_front.stl slicer support type tree"
    title: "base_front.stl slicer support type tree"
flaps_pb_holder:
  - url: /assets/docs/3d-print/flap_pb_holder_A.png
    image_path: /assets/docs/3d-print/flap_pb_holder_A.png
    alt: "Flap and power bank holder orientation"
    title: "Flap and power bank holder orientation"
  - url: /assets/docs/3d-print/flap_pb_holder_B.png
    image_path: /assets/docs/3d-print/flap_pb_holder_B.png
    alt: "Flap and power bank holder slicer support type tree"
    title: "Flap and power bank holder slicer support type tree"
---

If you are here you want 3D print NanoSaur, it's simple, but long.

I use [Cura slicer](https://ultimaker.com/software/ultimaker-cura), but all other slicer works fine. 
Following this guideline the total time to print NanoSaur will be:

| Parts | Time |
|-------|------|
| [Base rear](#base-rear) | **5h** |
| [Base front](#base-front) | **1h** and **30min** |
| [Wheels and sprockets](#wheels-and-sprockets) | **2h** |
| [Sliders](#sliders) | **2h** |
| [Cover](#cover) | **1h** and **45min** |
| [Flap and power bank holder](#flap-and-power-bank-holder) | **1h** and **45min** |
| [Track](#print-tracks) | 2x **1h** and **30min** |
| **Total** | **17h** |

**:floppy_disk: Download** you can obtain all Nanosaur parts only downloading this zip file [**nanosaur_stl.zip**](https://github.com/rnanosaur/nanosaur/releases/latest/download/nanosaur_stl.zip)
{: .notice--success}

# Print PLA parts

You can split all parts following this guideline and setup the printer using this profile:
* **Layer height**: 0.2mm
* **Print speed**: 50mm/s
* **Infill**: 15%

## Base rear

To print this parts you need a **PLA green**. The average time will be: **5h** 

| Quantity | Part            | 3D view |
|:--------:|-----------------|:-------:|
| 1        | [base_rear.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/base_rear.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/base_rear.stl?height=320&width=320"></script> |

I suggest orienting the STL following this picture and setup with:
* **Supports**: Disable

{% include figure image_path="/assets/docs/3d-print/base_rear.png" alt="base_rear.stl slicer" caption="base_rear.stl slicer" %}

## Base front

To print this parts you need a **PLA green**. The average time will be: **1h** and **30min**.

| Quantity | Part            | 3D view |
|:--------:|-----------------|:-------:|
| 1        | [base_front.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/base_front.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/base_front.stl?height=320&width=320"></script> |

I suggest orienting the STL following this picture and setup with:
* **Supports**: Enable
* **Support structure**: Tree

{% include gallery id="base_front" caption="base_front.stl slicer" %}

## Wheels and sprockets

To print this parts you need a **PLA green/black**. The average time will be: **2h**. 

| Quantity | Part            | 3D view |
|:--------:|-----------------|:-------:|
| 2        | [sprocket.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/sprocket.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/sprocket.stl?height=320&width=320"></script> |
| 2        | [wheel.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/wheel.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/wheel.stl?height=320&width=320"></script> |

I suggest orienting the STL following this picture and setup with:
* **Supports**: Disable

{% include figure image_path="/assets/docs/3d-print/wheel_sprocket.png" alt="wheels and sprockets slicer" caption="wheels and sprockets slicer" %}

## Sliders

To print this parts you need a **PLA green**. The average time will be: **2h**. 

| Quantity | Part            | 3D view |
|:--------:|-----------------|:-------:|
| 2        | [slider.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/slider.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/slider.stl?height=320&width=320"></script> |

I suggest orienting the STL following this picture and setup with:
* **Supports**: Disable
* **Displacement**:
  * **Left**: x=0 y=15
  * **Right**: x=0 y=-15

{% include figure image_path="/assets/docs/3d-print/sliders.png" alt="sliders slicer" caption="sliders slicer" %}

## Cover

To print this parts you need a **PLA green**. The average time will be: **1h** and **45min**.

| Quantity | Part            | 3D view |
|:--------:|-----------------|:-------:|
| 1        | [cover.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/cover.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/cover.stl?height=320&width=320"></script> |

I suggest orienting the STL following this picture and setup with:
* **Supports**: Disable

{% include figure image_path="/assets/docs/3d-print/cover.png" alt="cover.stl slicer" caption="cover.stl slicer" %}

## Flap and Power bank holder

To print this parts you need a **PLA green**. The average time will be: **1h** and **45min**.

| Quantity | Part            | 3D view |
|:--------:|-----------------|:-------:|
| 1        | [flap_top.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/flap_top.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/flap_top.stl?height=320&width=320"></script> |
| 1        | [flap_bottom.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/flap_bottom.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/flap_bottom.stl?height=320&width=320"></script> |
| 1        | [pb_holder.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/pb_holder.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/pb_holder.stl?height=320&width=320"></script> |

I suggest orienting the STL following this picture and setup with:
* **Supports**: Enable
* **Support structure**: Tree
* **Displacement**:
  * **flap_bottom.stl**: x=20 y=0
  * **flat_top.stl**: x=-20 y=0
  * **pb_holder.stl**: x=-55 y=0

{% include gallery id="flaps_pb_holder" caption="flap and pb_holder slicer" %}

# Print tracks

The NanoSaur tracks are the hardest to print. You need a good 3D printer, better if your printer is direct drive. Otherwise I suggest to use a Ninjatek TPU, sufficient elastic to make these tracks.

The average time will be: **1h** and **30min** for each track

| Quantity | Part            | 3D view |
|:--------:|-----------------|:-------:|
| 2        | [track_print.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/track_print.stl) | <script src="https://embed.github.com/view/3d/rnanosaur/nanosaur/master/nanosaur_description/meshes/track_print.stl?height=320&width=320"></script> |

I suggest orienting the STL following this picture and setup with:
* **Layer height**: 0.2mm
* **Print speed**: 30mm/s
* **Infill**: 10%
* **Supports**: Disable

{% include figure image_path="/assets/docs/3d-print/track_print.png" alt="track_print.stl slicer" caption="track_print.stl slicer" %}
---
title: "3D print"
permalink: /3d-print/
header:
  teaser: /assets/docs/3d-print-cura/base_rear.png
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
nav-base-rear:
  - name: "Cura"
    image:
      - image_path: /assets/docs/3d-print-cura/base_rear.png
    caption: "base_rear.stl slicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Supports**: Disable
  - name: "PrusaSlicer/SuperSlicer"
    image:
      - image_path: /assets/docs/3d-print-slicer/base-rear.png
    caption: "base_rear.stl slicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Supports**: Disable
nav-base-front:
  - name: "Cura"
    image: 
      - url: /assets/docs/3d-print-cura/base_front_A.png
        image_path: /assets/docs/3d-print-cura/base_front_A.png
        alt: "base_front.stl orientation"
        title: "base_front.stl orientation"
      - url: /assets/docs/3d-print-cura/base_front_B.png
        image_path: /assets/docs/3d-print-cura/base_front_B.png
        alt: "base_front.stl slicer support type tree"
        title: "base_front.stl slicer support type tree"
    caption: "base_front.stl slicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Supports**: Enable
        * **Support structure**: Tree
  - name: "PrusaSlicer/SuperSlicer"
    image: 
      - url: /assets/docs/3d-print-slicer/base_front_A.png
        image_path: /assets/docs/3d-print-slicer/base_front_A.png
        alt: "base_front.stl orientation"
        title: "base_front.stl orientation"
      - url: /assets/docs/3d-print-slicer/base_front_B.png
        image_path: /assets/docs/3d-print-slicer/base_front_B.png
        alt: "base_front.stl detail supports"
        title: "base_front.stl detail supports"
    caption: "base_front.stl slicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Generate support material**: Enable
        * **Support on build plate only**: Enable
        * **Don't support brides**: Disable
nav-wheels-sprokets:
  - name: "Cura"
    image: 
      - image_path: /assets/docs/3d-print-cura/wheel_sprocket.png
    caption: "wheels and sprockets slicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Use the auto arrange button**
        * **Supports**: Disable
  - name: "PrusaSlicer/SuperSlicer"
    image:
      - image_path: /assets/docs/3d-print-slicer/wheel-sproket.png
    caption: "wheels and sprockets slicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Use the auto arrange button**
        * **Supports**: Disable
nav-sliders:
  - name: "Cura"
    image: 
      - image_path: /assets/docs/3d-print-cura/sliders.png
    caption: "sliders slicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Supports**: Disable
        * **Displacement**:
          * **Left**: x=0 y=15
          * **Right**: x=0 y=-15
  - name: "PrusaSlicer/SuperSlicer"
    image:
      - image_path: /assets/docs/3d-print-slicer/sliders.png
    caption: "wheels and sprockets slicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Use the auto arrange button**
        * **Supports**: Disable
nav-flaps-pb-holder:
  - name: "Cura"
    image: 
      - url: /assets/docs/3d-print-cura/flap_pb_holder_A.png
        image_path: /assets/docs/3d-print-cura/flap_pb_holder_A.png
        alt: "Flap and power bank holder orientation"
        title: "Flap and power bank holder orientation"
      - url: /assets/docs/3d-print-cura/flap_pb_holder_B.png
        image_path: /assets/docs/3d-print-cura/flap_pb_holder_B.png
        alt: "Flap and power bank holder slicer support type tree"
        title: "Flap and power bank holder slicer support type tree"
    caption: "flap and pb_holder slicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Supports**: Enable
        * **Support structure**: Tree
        * **Displacement**:
          * **flap_bottom.stl**: x=20 y=0
          * **flat_top.stl**: x=-20 y=0
          * **pb_holder.stl**: x=-55 y=0
  - name: "PrusaSlicer/SuperSlicer"
    image: 
      - url: /assets/docs/3d-print-slicer/flap_pb_holder_A.png
        image_path: /assets/docs/3d-print-slicer/flap_pb_holder_A.png
        alt: "Flap and power bank holder orientation"
        title: "Flap and power bank holder orientation"
      - url: /assets/docs/3d-print-slicer/flap_pb_holder_B.png
        image_path: /assets/docs/3d-print-slicer/flap_pb_holder_B.png
        alt: "Upper flap - paint remove selection"
        title: "Upper flap - paint remove selection"
      - url: /assets/docs/3d-print-slicer/flap_pb_holder_C.png
        image_path: /assets/docs/3d-print-slicer/flap_pb_holder_C.png
        alt: "Power Bank holder - paint remove selection"
        title: "Power Bank holder - paint remove selection"
    caption: "flap and pb_holder slicer"
    excerpt: >
      Follow the images and using the **Paint-on supports tool** block all supports on:
        * Power bank holder
        * Upper flap

      I suggest orienting the STL following this picture and setup with:
        * **Generate support material**: Enable
        * **Support on build plate only**: Enable
        * **Don't support brides**: Disable
nav-tracks:
  - name: "Cura"
    image: 
      - image_path: /assets/docs/3d-print-cura/track_print.png
    caption: "track_print.stl slicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Print speed**: 30mm/s
        * **Infill**: 10%
        * **Supports**: Disable
        * **Retraction**: Disable
  - name: "PrusaSlicer/SuperSlicer"
    image: 
      - image_path: /assets/docs/3d-print-slicer/track_print.png
    caption: "track_print.stl slicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Print speed**: 30mm/s
        * **Infill**: 10%
        * **Supports**: Disable
        * **Retraction**: Disable
covers:
  - image_path: /assets/docs/assembly/cover-fe/coverFishEye.png
    alt: "Fish-eye cam"
    title: "Fish-eye cam"
    excerpt: "cover nanosaur for Fish-eye camera."
    url: "/optional/cover#3d-print-wide-camera-cover"
    btn_label: "3D print"
    btn_class: "btn--success"
covers-line2:
  - image_path: /assets/docs/assembly/cover-cam/cover.png
    alt: "PI cam v2"
    title: "PI cam v2"
    excerpt: "cover nanosaur for Raspberry Cam V2."
    url: "/optional/cover#3d-print"
    btn_label: "3D print"
    btn_class: "btn--success"
  - image_path: /assets/docs/assembly/cover-zedmini/cover_ZEDmini.png
    alt: "ZED mini"
    title: "ZED mini"
    excerpt: "cover nanosaur for ZED mini."
    url: "/optional/cover#3d-print-zed-mini-cover"
    btn_label: "3D print"
    btn_class: "btn--success"
  - image_path: /assets/docs/assembly/cover-rs/cover_RealSense.png
    alt: "Realsense"
    title: "Realsense"
    excerpt: "cover nanosaur for Realsense camera."
    url: "/optional/cover#3d-print-realsense-cover"
    btn_label: "3D print"
    btn_class: "btn--success"
---

If you are here you want 3D print nanosaur, it's simple, but long.

The **Nanosaur design** is under license [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].
{: .notice}

In this guide you will find two different guidelines for three popular slicers:

1. [**Cura**](https://ultimaker.com/software/ultimaker-cura)
2. [**PrusaSlicer**](https://www.prusa3d.com/page/prusaslicer_424/) or [**SuperSlicer**](https://github.com/supermerill/SuperSlicer)

Following this guideline the average time to print nanosaur is:

| Qt | Part            | Material        | Time  | Notes                                                     |
|:--:|-----------------|-----------------|:-----:|-----------------------------------------------------------|
| 1  | base_rear.stl   | PLA green       | 3h    | [Base rear](#base-rear)                                   |
| 1  | base_front.stl  | PLA green       | 1:30h | [Base front](#base-front)                                 |
| 1  | cover.stl       | PLA green       | 1:45h | [Cover](#cover)                                           |
| 2  | slider.stl      | PLA green       | 1h    | [Sliders](#sliders)                                       |
| 1  | pb_holder.stl   | PLA green       | 20min | A - Combined<br/>[Flap and power bank holder](#flap-and-power-bank-holder) |
| 1  | flap_top.stl    | PLA green       | 45min | A - Combined<br/>[Flap and power bank holder](#flap-and-power-bank-holder) |
| 1  | flap_bottom.stl | PLA green       | 45min | A - Combined<br/>[Flap and power bank holder](#flap-and-power-bank-holder) |
| 2  | sprocket.stl    | PLA green/black | 1h    | B - Combined<br/>[Wheels and sprockets](#wheels-and-sprockets)             |
| 2  | wheel.stl       | PLA green/black | 1h    | B - Combined<br/>[Wheels and sprockets](#wheels-and-sprockets)             |
| 2  | track_print.stl | TPU black/grey  | 1:30h | [Track](#print-tracks)                                   |
|    |                 | **Total**       | **15h** |                                                        |

**:floppy_disk: Download** you can obtain all Nanosaur parts only downloading this zip file [**nanosaur_stl.zip**](https://github.com/rnanosaur/nanosaur/releases/latest/download/nanosaur_stl.zip)
{: .notice--success}

**:bulb: Hint** On nanosaur_stl.zip you can find a folder **025in** for ball bearings with size *ID 1/4in x OD 1/2in*
{: .notice--info}

{% include video id="5cVNXbF6HzI" provider="youtube" %}

# Print PLA parts

You can split all parts following this guideline and setup the printer using this profile:

* **Layer height**: 0.2mm
* **Print speed**: 50mm/s
* **Infill**: 15%

## Base rear

To print this parts you need a **PLA green**. The average time will be: **5h**

| Quantity | Part            | 3D view |
|:--------:|-----------------|:-------:|
| 1        | [base_rear.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/base_rear.stl) | {% include 3dview.html username="rnanosaur" repo="nanosaur" path_to_file="nanosaur_description/meshes/base_rear.stl" %} |

{% include navtab id="nav-base-rear" %}

## Base front

To print this parts you need a **PLA green**. The average time will be: **1h** and **30min**.

| Quantity | Part            | 3D view |
|:--------:|-----------------|:-------:|
| 1        | [base_front.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/base_front.stl) | {% include 3dview.html username="rnanosaur" repo="nanosaur" path_to_file="nanosaur_description/meshes/base_front.stl" %} |

{% include navtab id="nav-base-front" %}

## Wheels and sprockets

**:bulb: Hint** On nanosaur_stl.zip you can find a folder **025in** for ball bearings with size *ID 1/4in x OD 1/2in*
{: .notice--info}

To print this parts you need a **PLA green/black**. The average time will be: **2h**.

| Quantity | Part            | 3D view |
|:--------:|-----------------|:-------:|
| 2        | [sprocket.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/sprocket.stl) | {% include 3dview.html username="rnanosaur" repo="nanosaur" path_to_file="nanosaur_description/meshes/sprocket.stl" %} |
| 2        | [wheel.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/wheel.stl) | {% include 3dview.html username="rnanosaur" repo="nanosaur" path_to_file="nanosaur_description/meshes/wheel.stl" %} |

{% include navtab id="nav-wheels-sprokets" %}

## Sliders

To print this parts you need a **PLA green**. The average time will be: **2h**.

| Quantity | Part            | 3D view |
|:--------:|-----------------|:-------:|
| 2        | [slider.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/slider.stl) | {% include 3dview.html username="rnanosaur" repo="nanosaur" path_to_file="nanosaur_description/meshes/slider.stl" %} |

{% include navtab id="nav-sliders" %}

## Flap and Power bank holder

To print this parts you need a **PLA green**. The average time will be: **1h** and **45min**.

| Quantity | Part            | 3D view |
|:--------:|-----------------|:-------:|
| 1        | [flap_top.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/flap_top.stl) | {% include 3dview.html username="rnanosaur" repo="nanosaur" path_to_file="nanosaur_description/meshes/flap_top.stl" %} |
| 1        | [flap_bottom.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/flap_bottom.stl) | {% include 3dview.html username="rnanosaur" repo="nanosaur" path_to_file="nanosaur_description/meshes/flap_bottom.stl" %} |
| 1        | [pb_holder.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/pb_holder.stl) | {% include 3dview.html username="rnanosaur" repo="nanosaur" path_to_file="nanosaur_description/meshes/pb_holder.stl" %} |

{% include navtab id="nav-flaps-pb-holder" %}

## Cover

nanosaur offers different covers for each camera or stereo camera choice. Select here which camera you prefer to print.

{% include feature_row id="covers" type="left" %}

{% include feature_row id="covers-line2" %}

**:bulb: Hint** A new cover for **OAK-D lite** will coming soon!
{: .notice--info}

# Print tracks

The nanosaur tracks are the hardest to print. You need a good 3D printer, better if your printer is direct drive. Otherwise I suggest to use a Ninjatek TPU, sufficient elastic to make these tracks.

The average time will be: **1h** and **30min** for each track

| Quantity | Part            | 3D view |
|:--------:|-----------------|:-------:|
| 2        | [track_print.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/track_print.stl) | {% include 3dview.html username="rnanosaur" repo="nanosaur" path_to_file="nanosaur_description/meshes/track_print.stl" %} |

{% include navtab id="nav-tracks" %}

# LICENSE

The **Nanosaur design** is under license [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

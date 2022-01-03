---
title: "nanosaur cover head"
permalink: /optional/cover
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
nav-cover-print:
  - name: "Cura"
    image: 
      - image_path: /assets/docs/3d-print-cura/cover.png
    caption: "cover.stl slicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Supports**: Disable
  - name: "PrusaSlicer/SuperSlicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Supports**: Disable
cover:
  - url: /assets/docs/assembly/cover-cam/cover-01-magnets.png
    image_path: /assets/docs/assembly/cover-cam/cover-01-magnets.png
    alt: "Cover assembly magnets"
    title: "Cover Assembly magnets"
  - url: /assets/docs/assembly/cover-cam/cover-02-display.png
    image_path: /assets/docs/assembly/cover-cam/cover-02-display.png
    alt: "Cover assembly display"
    title: "Cover Assembly display"
  - url: /assets/docs/assembly/cover-cam/cover-03-cam.png
    image_path: /assets/docs/assembly/cover-cam/cover-03-cam.png
    alt: "Cover assembly camera"
    title: "Assembly camera"
cover-complete:
  - url: /assets/docs/assembly/cover-cam/cover-04-assembled.jpg
    image_path: /assets/docs/assembly/cover-cam/cover-04-assembled.jpg
    alt: "Nanosaur cover assembled"
    title: "Nanosaur cover assembled"
nav-cover-fe-print:
  - name: "Cura"
    image: 
      - image_path: /assets/docs/3d-print-cura/coverFishEye.png
    caption: "cover-fe.stl slicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Supports**: Disable
  - name: "PrusaSlicer/SuperSlicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Supports**: Disable
cover-fe:
  - url: /assets/docs/assembly/cover-fe/01-coverFishEye.png
    image_path: /assets/docs/assembly/cover-fe/01-coverFishEye.png
    alt: "Cover assembly magnets"
    title: "Cover Assembly magnets"
  - url: /assets/docs/assembly/cover-fe/02-coverFishEye.png
    image_path: /assets/docs/assembly/cover-fe/02-coverFishEye.png
    alt: "Cover assembly display"
    title: "Cover Assembly display"
  - url: /assets/docs/assembly/cover-fe/03-coverFishEye.png
    image_path: /assets/docs/assembly/cover-fe/03-coverFishEye.png
    alt: "Cover assembly camera"
    title: "Assembly camera"
nav-cover-zedmini-print:
  - name: "Cura"
    image: 
      - image_path: /assets/docs/3d-print-cura/coverZEDmini.png
      - image_path: /assets/docs/3d-print-cura/coverZEDmini-detail.png
    caption: "cover-zedmini.stl slicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Supports**: Enable
        * **Support structure**: Normal
        * **Support placement**: Touching buildplate
  - name: "PrusaSlicer/SuperSlicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Supports**: Enable
        * **Support structure**: Normal
cover-zedmini:
  - url: /assets/docs/assembly/cover-zedmini/01-cover_ZEDmini.png
    image_path: /assets/docs/assembly/cover-zedmini/01-cover_ZEDmini.png
    alt: "Cover assembly magnets"
    title: "Cover Assembly magnets"
  - url: /assets/docs/assembly/cover-zedmini/02-cover_ZEDmini.png
    image_path: /assets/docs/assembly/cover-zedmini/02-cover_ZEDmini.png
    alt: "Cover assembly display"
    title: "Cover Assembly display"
  - url: /assets/docs/assembly/cover-zedmini/03-cover_ZEDmini.png
    image_path: /assets/docs/assembly/cover-zedmini/03-cover_ZEDmini.png
    alt: "Cover assembly ZEDmini"
    title: "Assembly ZEDmini"
nav-cover-rs-print:
  - name: "Cura"
    image: 
      - image_path: /assets/docs/3d-print-cura/coverRealSense.png
      - image_path: /assets/docs/3d-print-cura/coverZEDmini-detail.png
    caption: "cover-rs.stl slicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Supports**: Enable
        * **Support structure**: Normal
        * **Support placement**: Touching buildplate
  - name: "PrusaSlicer/SuperSlicer"
    excerpt: >
      I suggest orienting the STL following this picture and setup with:
        * **Supports**: Enable
        * **Support structure**: Normal
cover-rs:
  - url: /assets/docs/assembly/cover-rs/01-cover_RealSense.png
    image_path: /assets/docs/assembly/cover-rs/01-cover_RealSense.png
    alt: "Cover assembly magnets"
    title: "Cover Assembly magnets"
  - url: /assets/docs/assembly/cover-rs/02-cover_RealSense.png
    image_path: /assets/docs/assembly/cover-rs/02-cover_RealSense.png
    alt: "Cover assembly display"
    title: "Cover Assembly display"
  - url: /assets/docs/assembly/cover-rs/03-cover_RealSense.png
    image_path: /assets/docs/assembly/cover-rs/03-cover_RealSense.png
    alt: "Cover assembly Realsense D435i"
    title: "Assembly Realsense D435i"
---

The **Nanosaur design** is under license [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].
{: .notice}

There are many option for nanosaur.

# Camera

## 3D print

| Quantity | Part            | 3D view |
|:--------:|-----------------|:-------:|
| 1        | [cover.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/cover.stl) | {% include 3dview.html username="rnanosaur" repo="nanosaur" path_to_file="nanosaur_description/meshes/cover.stl" %} |

{% include navtab id="nav-cover-print" %}

[Return to 3D printing](/3d-print/#cover){: .btn .btn--primary .align-center}

## Assembly

Components to pick up

| Quantity | Part                          |
|:--------:|-------------------------------|
| 1        | [cover.stl](#3d-print) |
| 1        | PI cam v2                     |
| 2        | oLED display - 128x64px       |
| 12       | Hex M2 4mm                    |
| 3        | magnet 4x2mm                  |

**:bulb: Hint** If you don't want to use the magnets, but the screw, follow the optional guide [Screw Assembly](/optional/screw-assembly)
{: .notice--info}

**:bulb: Hint** To simplify the assembly, **dry-fit** of all screws after 3D print
{: .notice--info}

**:warning: WARNING** Check the magnets orientation before to stick it!
{: .notice--warning}

Now follow these steps to assembly this head.

1. Bring three magnets and stick on the cover following the picture below
2. Screw two 128x64px oLed display
3. Screw the PI Cam

{% include gallery id="cover" caption="Assembly PI cam V2 camera cover" %}

When the cover will be fully assembled, looks like the picture below. Remember to check that the flat cable look the base of the robot.

{% include gallery id="cover-complete" caption="Body assembled" %}

[Return to nanosaur assembly](/assembly/#head){: .btn .btn--info .align-center}

# Wide angle camera (Fish-eye)

## 3D print wide camera cover

| Quantity | Part            | 3D view |
|:--------:|-----------------|:-------:|
| 1        | [cover-fe.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/cover-fe.stl) | {% include 3dview.html username="rnanosaur" repo="nanosaur" path_to_file="nanosaur_description/meshes/cover-fe.stl" %} |

{% include navtab id="nav-cover-fe-print" %}

[Return to 3D printing](/3d-print/#cover){: .btn .btn--primary .align-center}

## Assembly wide camera cover

Components to pick up

| Quantity | Part                          |
|:--------:|-------------------------------|
| 1        | [cover-fe.stl](#3d-print-wide-camera-cover) |
| 1        | Waveshare IMX219-160 Camera   |
| 2        | oLED display - 128x64px       |
| 12       | Hex M2 4mm                    |
| 3        | magnet 4x2mm                  |

**:bulb: Hint** If you don't want to use the magnets, but the screw, follow the optional guide [Screw Assembly](/optional/screw-assembly)
{: .notice--info}

**:bulb: Hint** To simplify the assembly, **dry-fit** of all screws after 3D print
{: .notice--info}

**:warning: WARNING** Check the magnets orientation before to stick it!
{: .notice--warning}

1. Bring three magnets and stick on the cover following the picture below
2. Screw two 128x64px oLed display
3. Screw the Waveshare IMX219-160 Camera

{% include gallery id="cover-fe" caption="Assembly fish-eye camera cover" %}

[Return to nanosaur assembly](/assembly/#head){: .btn .btn--info .align-center}

# ZED mini

## 3D print ZED mini cover

| Quantity | Part            | 3D view |
|:--------:|-----------------|:-------:|
| 1        | [cover-zedmini.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/cover-zedmini.stl) | {% include 3dview.html username="rnanosaur" repo="nanosaur" path_to_file="nanosaur_description/meshes/cover-zedmini.stl" %} |

{% include navtab id="nav-cover-zedmini-print" %}

[Return to 3D printing](/3d-print/#cover){: .btn .btn--primary .align-center}

## Assembly ZED mini cover

Components to pick up

| Quantity | Part                          |
|:--------:|-------------------------------|
| 1        | [cover-zedmini.stl](#3d-print-zed-mini-cover) |
| 1        | ZED mini                      |
| 2        | oLED display - 128x64px       |
| 8        | Hex M2 4mm                    |
| 2        | Hex M2 8mm                    |
| 3        | magnet 4x2mm                  |

**:bulb: Hint** If you don't want to use the magnets, but the screw, follow the optional guide [Screw Assembly](/optional/screw-assembly)
{: .notice--info}

**:bulb: Hint** To simplify the assembly, **dry-fit** of all screws after 3D print
{: .notice--info}

**:warning: WARNING** Check the magnets orientation before to stick it!
{: .notice--warning}

Now follow these steps to assembly this head.

1. Bring three magnets and stick on the cover following the picture below
2. Screw two 128x64px oLed display
3. Screw the ZED mini

{% include gallery id="cover-zedmini" caption="Assembly ZED mini cover" %}

[Return to nanosaur assembly](/assembly/#head){: .btn .btn--info .align-center}

# Realsense

## 3D print Realsense cover

| Quantity | Part            | 3D view |
|:--------:|-----------------|:-------:|
| 1        | [cover-rs.stl](https://github.com/rnanosaur/nanosaur/raw/master/nanosaur_description/meshes/cover-rs.stl) | {% include 3dview.html username="rnanosaur" repo="nanosaur" path_to_file="nanosaur_description/meshes/cover-rs.stl" %} |

{% include navtab id="nav-cover-rs-print" %}

[Return to 3D printing](/3d-print/#cover){: .btn .btn--primary .align-center}

## Assembly Realsense cover

Components to pick up

| Quantity | Part                          |
|:--------:|-------------------------------|
| 1        | [cover-rs.stl](#3d-print-realsense-cover) |
| 1        | Realsense D435i               |
| 1        | Waveshare IMX219-160 Camera   |
| 2        | oLED display - 128x64px       |
| 12       | Hex M2 4mm                    |
| 3        | magnet 4x2mm                  |

**:bulb: Hint** If you don't want to use the magnets, but the screw, follow the optional guide [Screw Assembly](/optional/screw-assembly)
{: .notice--info}

**:bulb: Hint** To simplify the assembly, **dry-fit** of all screws after 3D print
{: .notice--info}

**:warning: WARNING** Check the magnets orientation before to stick it!
{: .notice--warning}

Now follow these steps to assembly this head.

1. Bring three magnets and stick on the cover following the picture below
2. Screw two 128x64px oLed display
3. Screw the Realsense

{% include gallery id="cover-rs" caption="Assembly Realsense D435i cover" %}

[Return to nanosaur assembly](/assembly/#head){: .btn .btn--info .align-center}

# OAK D-lite

**:bulb: Hint** New cover coming soon!
{: .notice--info}

# LICENSE

The **Nanosaur design** is under license [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
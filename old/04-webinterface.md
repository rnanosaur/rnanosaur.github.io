---
title: "Web interface"
excerpt: "How to visualize the nanosaur web interface"
# permalink: /tutorial/webinterface
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  teaser: /assets/tutorial/webinterface/nanosaur_webinterface_data.png
  overlay_image: /assets/tutorial/webinterface/nanosaur_webinterface_data.png
  actions:
    - label: "local website at nanosaur.local:8888"
      url: "http://nanosaur.local:8888/"
---

To connect on the nanosaur web interface you need only to connect at:

<a href="http://nanosaur.local:8888/" class="btn btn--success" target="_blank">http://nanosaur.local:8888/</a>
{: .text-center}

**Windows** If you are working on a windows operative system, check if is installed [**Bonjour**](https://support.apple.com/kb/dl999).<br/>[Bonjour](https://support.apple.com/kb/dl999) is an Apple a Print service, that provide the mDNS detection able to resolve .local addresses. 
{: .notice--primary}

You will be connected to a web browser on the nanosaur robot, and you will be able to read the status of the robot.

Pressing the menu button ![menu button](/assets/tutorial/webinterface/outline_menu_black_24dp.png) (top left) will appear a list of topics available, like the picture below.

{% include figure image_path="/assets/tutorial/webinterface/nanosaur_dashboar_topics.png" alt="nanosaur web interface topic list" caption="nanosaur web interface topic list" %}

This is an example with the final output, with these topics anabled:
* image_raw
* diagnostics
* cmd_vel

{% include figure image_path="/assets/tutorial/webinterface/nanosaur_webinterface_data.png" alt="nanosaur web interface final output" caption="nanosaur web interface final output" %}

This [rosboard](https://github.com/dheera/rosboard) is provided from an amazing open-source work, made by [@dheera](https://github.com/dheera)!
{: .notice}
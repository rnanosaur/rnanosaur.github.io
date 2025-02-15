---
title: "Command Line Interface (CLI)"
excerpt: "Install the nanosaur command line interface. With this tool we will be able to install all software on your computer or Jetson and configure the robot."
permalink: install/cli/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
header:
  teaser: /assets/images/collections/install/cli/nanosaur-cli.png
---

The nanosaur command Line Interface (CLI) is an all-in-one script to manage nanosaur, developing or running in simulation. 
This tool is extremely simple and need few steps to be used.

If you are working on NVIDIA Jetson please follow the guide below to install the latest NVIDIA Jetpack version.

[NVIDIA Jetson getting started](/install/jetson){: .align-center .btn .btn--info .btn--large}

# Prerequisites

First step, open your terminal and install [jetson-stats](https://rnext.it/jetson_stats/).

**:warning: WARNING** This command require **sudo**.
{: .notice--warning}

{% capture code %}sudo pip3 install -U jetson-stats{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

[Jetson-Stats (jtop)](https://rnext.it/jetson_stats/) is an intuitive and robust tool for monitoring and managing NVIDIA Jetson devices.
It offers an extensive, real-time overview of system performance, proving to be an essential asset for developers engaged in Jetson-based AI and robotics projects.

the main features are:

* Decode hardware, architecture, L4T and NVIDIA Jetpack
* Monitoring, CPU, GPU, Memory, Engines, fan
* Control NVP model, fan speed, jetson_clocks
* Importable in a python script
* Dockerizable in a container
* Do not need super user
* Tested on many different hardware configurations
* Works with all NVIDIA Jetpack

If pip3 is not installed please run also:

{% capture code %}sudo apt install python3-pip{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

After that you need to reboot your computer or your NVIDIA Jetson. After, when is done to check if jetson-stats is working run

**:warning: WARNING** Remember to logout or reboot your computer to run the command below.
{: .notice--warning}

{% capture code %}jtop{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

If you see this output from your terminal everything works properly!

{% include figure image_path="https://github.com/rbonghi/jetson_stats/raw/master/docs/images/jtop.png" alt="jtop" caption="jtop" %}

# Install nanosaur-cli

It's finally time to install, with a simple python package you will be able to install, drive and control nanosaur, easy not?

There are many configurations to do and you can jump on the tutorial page to tune and first test your robot, but now let's install the software:

{% capture code %}pip3 install nanosaur{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

## Check installation

Now we can test if the nanosaur CLI works on your prompt, try to type nanosaur and check the output.

{% capture code %}nanosaur{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

If you see an output like the image below, everything is working fine! We can type the first command to check the status of your device.

{% include figure image_path="/assets/images/collections/install/cli/nanosaur-cli.png" alt="nanosaur cli" caption="nanosaur Command Line Interface (CLI)" %}

Now check out the platform setup and configuration of your computer and like expected we will see few information now, but don't forget this command will be really helpful is something is going wrong on your installation or setup.

**:bulb: Hint** You can use the bash completion to quickly work with nanosaur!
{: .notice--info}

{% capture code %}nanosaur info{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

{% include figure image_path="/assets/images/collections/install/cli/nanosaur-cli-info.png" alt="nanosaur info" caption="nanosaur info command" %}

If you need more details you can run the same command with a verbose output:

{% capture code %}nanosaur info -v{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

The output will be something similar at this picture:

{% include figure image_path="/assets/images/collections/install/cli/nanosaur-cli-info-verbose.png" alt="nanosaur info verbose" caption="nanosaur info -v command" %}

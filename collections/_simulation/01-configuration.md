---
title: "Nanosaur simulator configuration"
excerpt: "In this guide we configure the nanosaur cli to work with the right simulator"
permalink: simulation/configuration/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
header:
  teaser: /assets/images/collections/simulation/configuration/nanosaur-sim.png
---

{% capture code %}nanosaur simulation{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

**:memo: Note** This command has also the alias `nanosaur sim`.
{: .notice--info}

An help will appear on your terminal, with all options available

{% include figure image_path="/assets/images/collections/simulation/configuration/nanosaur-sim.png" alt="nanosaur simulation" caption="nanosaur simulation command" %}

# Start simulator

**:memo: Note** If your device has a valid version of ROS installed, you can choice to run instead in a docker, directly on your host. A question will appear everytime you type the command.
{: .notice--info}

# Set simulator

{% capture code %}nanosaur simulation set{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

{% include figure image_path="/assets/images/collections/simulation/configuration/nanosaur-sim-set.png" alt="nanosaur simulation set" caption="nanosaur simulation set command" %}

# Set world

{% capture code %}nanosaur simulation world{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

{% include figure image_path="/assets/images/collections/simulation/configuration/nanosaur-sim-world.png" alt="nanosaur simulation world" caption="nanosaur simulation world command" %}

# Start simulation headless

{% capture code %}nanosaur simulation headless{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

{% include figure image_path="/assets/images/collections/simulation/configuration/nanosaur-sim-headless.png" alt="nanosaur simulation headless" caption="nanosaur simulation headless command" %}

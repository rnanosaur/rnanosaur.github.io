---
title: "Nanosaur configuration"
excerpt: "How to set up and configure nanosaur."
permalink: /tutorial/configuration/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
header:
  teaser: /assets/images/collections/tutorial/configure/nanosaur-robot-config.png
---

If you want enable or disable an engine, or you want to change the camera mounted on your robot, the robot configuration command help you to quickly change the configuration. Just only typing the command:

{% capture code %}nanosaur robot config{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

An help will appear on your terminal, with all options available

{% include figure image_path="/assets/images/collections/tutorial/configure/nanosaur-robot-config.png" alt="nanosaur robot config" caption="nanosaur robot config command" %}

# Set name

This command open a prompt to change the robot name.

**:warning: WARNING** Special characters are now allowed.
{: .notice--warning}

{% capture code %}nanosaur robot config name{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

**:bulb: Hint** Pressing **ENTER** will be saved the new configuration. Pressing **CTRL-C** the operation will be interrupted.  
{: .notice--info}

# Set domain id

This command open a prompt to change the ROS domain ID.

**:warning: WARNING** Only numbers are allowed.
{: .notice--warning}

{% capture code %}nanosaur robot config domain_id{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

**:bulb: Hint** Pressing **ENTER** will be saved the new configuration. Pressing **CTRL-C** the operation will be interrupted.  
{: .notice--info}

# Set simulation (only desktop)

This command set the type of robot. If is a real robot or a simulation. This configuration is necessary to properly setup the environments and variables when you work on your robot.

{% capture code %}nanosaur robot config simulation{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

**:bulb: Hint** Pressing **ENTER** will be saved the new configuration. Pressing **CTRL-C** the operation will be interrupted.  
{: .notice--info}

# Set camera

This command configure the camera the robot is using, there are multiple options available.

{% capture code %}nanosaur robot config camera{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

**:bulb: Hint** Using the arrows up and down you can select and pressing **ENTER** will be saved the new configuration. Pressing **CTRL-C** the operation will be interrupted.  
{: .notice--info}

**:memo: Note** If you designed a new camera you can use the special command `nanosaur robot config camera --new NEW` to add in a customize setup.
{: .notice}

{% include figure image_path="/assets/images/collections/tutorial/configure/nanosaur-robot-config-camera.png" alt="nanosaur robot config camera prompt" caption="nanosaur robot config camera prompt" %}

An example here when is selected the realsense camera.

{% include figure image_path="/assets/images/collections/tutorial/configure/nanosaur-robot-config-example-camera.png" alt="nanosaur with realsense camera" caption="nanosaur with realsense camera in simulation" %}

# Set lidar

This command configure the lidar assembled on your robot, you can find a selection of lidar avalable.

{% capture code %}nanosaur robot config lidar{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

**:bulb: Hint** Using the arrows up and down you can select and pressing **ENTER** will be saved the new configuration. Pressing **CTRL-C** the operation will be interrupted.  
{: .notice--info}

**:memo: Note** If you designed a new camera you can use the special command `nanosaur robot config lidar --new NEW` to add in a customize setup.
{: .notice}

{% include figure image_path="/assets/images/collections/tutorial/configure/nanosaur-robot-config-lidar.png" alt="nanosaur robot config lidar prompt" caption="nanosaur robot config lidar prompt" %}

An example here when is selected the LD06 lidar.

{% include figure image_path="/assets/images/collections/tutorial/configure/nanosaur-robot-config-example-lidar.png" alt="nanosaur with LD06 lidar" caption="nanosaur with LD06 lidar in simulation" %}

# Set engines

This command enable and disable specific functionalities on the robot, such localization, mapping or other engines.

{% capture code %}nanosaur robot config engines{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

**:bulb: Hint** Using the arrows up and down you can move between engines. Pressing **SPACE** you can enable and disable and engine and pressing **ENTER** will be saved the new configuration. Pressing **CTRL-C** the operation will be interrupted.  
{: .notice--info}

{% include figure image_path="/assets/images/collections/tutorial/configure/nanosaur-robot-config-engines.png" alt="nanosaur robot config engines prompt" caption="nanosaur robot config lidar prompt" %}

# Factory reset

This command will do a factory reset of the nanosaur configuration.

{% capture code %}nanosaur robot config reset{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

After this command only typing:

{% capture code %}nanosaur robot{% endcapture %}{% include code.html code=code lang="sh" copyable=true %}

Will start a wizard to setup the robot, like you have seen at the [nanosaur first installation](/install/nanosaur).

{% include figure image_path="/assets/images/collections/install/nanosaur/nanosaur-install-robot.png" alt="nanosaur info" caption="nanosaur info command" %}

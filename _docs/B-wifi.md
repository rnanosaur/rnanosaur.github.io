---
title: "WiFi configuration"
excerpt: "Setup and connect a WiFi on nanosaur"
permalink: /optional/wifi
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
header:
  teaser: /assets/tutorial/wifi/desktop_selecting_ssid.png
---

There are two ways to connect nanosaur on your Wi-Fi network using [Monitor-attached Mode](#monitor-attached-mode) or [USB device Mode](#usb-device-mode)

If you don't have a monitor and a keyboard near you, the [USB device Mode](#usb-device-mode) will be fast to set up the connection.

# Plug Wi-Fi dongle

**:bulb: Hint** You can find the **WiFi Dongle** in nanosaur [BoM](/bill-of-materials/#bom)
{: .notice--info}

Bring your Wi-Fi dongle and plug in one of the free USB port slot available.

# Monitor-attached Mode

For this you need to connect the following items on nanosaur's NVIDIA Jetson.
* HDMI monitor
* USB keyboard
* USB mouse

Now follow these steps:
1. Switch on nanosaur and wait to access to ubuntu desktop.
2. Open the network menu on the top right (like the picture below)
3. Setup your Wi-Fi

{% include figure image_path="/assets/tutorial/wifi/desktop_selecting_ssid.png" alt="Wi-Fi menu on Jetson Desktop" caption="Wi-Fi menu on Jetson Desktop" %}

# USB device Mode

With USB Device Mode, Jetson presents 3 different USB Device Class end-points to the PC that it got connected to.
For this you need a USB cable between your desktop and nanosaur.

They function as
* USB mass storage device (you see `L4T-README` drive mounted on your PC, like a USB thumbdrive)
* USB serial (like the common "FTDI" USB to serial adapter)
* USB network interface card (like a virtual Ethernet adapter)

With the virtual Ethernet adapter functionality, Jetson forms a virtual local Ethernet network with Jetson being `192.168.55.1` and your PC being `192.168.55.100`. So you can actually SSH login from your (laptop) PC by specifying `192.168.55.1`, if you have already set up your account (with username and password).

Now from the terminal write:

{% include code.html code="nmcli device" lang="sh" copyable=true %}

It will appear an output like this:

```console
$ nmcli device
DEVICE  TYPE      STATE         CONNECTION
l4tbr0  bridge    connected     l4tbr0
wlan0   wifi      disconnected  --
eth0    ethernet  unavailable   --
dummy0  dummy     unmanaged     --
rndis0  ethernet  unmanaged     --
usb0    ethernet  unmanaged     --
lo      loopback  unmanaged     --
```

Then you can list all the wireless networks (SSDI) in the area using:

{% include code.html code="nmcli device wifi list" lang="sh" copyable=true %}

It will appear an output like this:

```console
$ nmcli device wifi list
IN-USE  SSID                           MODE   CHAN  RATE        SIGNAL  BARS  SE
        --                             Infra  6     195 Mbit/s  82      ▂▄▆█  WP
        --                             Infra  6     195 Mbit/s  82      ▂▄▆█  WP
        --                             Infra  6     195 Mbit/s  75      ▂▄▆_  WP
        MY_WIFI_AP                     Infra  6     195 Mbit/s  70      ▂▄▆_  WP
        --                             Infra  6     195 Mbit/s  70      ▂▄▆_  WP
        *********                      Infra  1     405 Mbit/s  64      ▂▄▆_  WP
        ************                   Infra  153   405 Mbit/s  64      ▂▄▆_  WP
...
```

To connect to your wireless network (AP, access point), issue the commands below.

{% capture code %}sudo nmcli device wifi connect <MY_WIFI_AP> password <MY_WIFI_PASSWORD>{% endcapture %}
{% include code.html code=code lang="sh" copyable=true %}

It will appear an output like this:

```
$ sudo nmcli device wifi connect <MY_WIFI_AP> password <MY_WIFI_PASSWORD>
Device 'wlan0' successfully activated with '2a26d5ca-****-****-****-**************'.
```

Nanosaur now is connected on your WiFi!

If you are installing nanosaur, follow the [installation](/install#install-and-run-nanosaur)
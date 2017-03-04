Onion Pi
========
![logo](logo.png)

![license](https://img.shields.io/apm/l/vim-mode.svg)

Onion Pi configures your Raspberry Pi as portable WiFi-WiFi Tor proxy.

What it Sets Up
------------
* HostAPD (Access Point) on `wlan0`
* WiFi Connection on `wlan1`
* Tor Proxy

Requirements
------------

Onion Pi Requires:

* Raspbian Jessie ([PIXEL](https://www.raspberrypi.org/downloads/raspbian/))
* Two WiFi Cards (e.g. On-board chip + [TL-WN725N](https://www.amazon.com/gp/product/B008IFXQFU/ref=oh_aui_detailpage_o03_s00?ie=UTF8&psc=1))
* Micro-USB to USB 2.0/3.0 converter (e.g. [USB to Micro-USB Charge & Sync Cable](https://www.amazon.com/gp/product/B00SVVY844/ref=oh_aui_detailpage_o05_s00?ie=UTF8&psc=1))
* Portable Battery Bank (e.g. [Anker PowerCore 5000](https://www.amazon.com/gp/product/B01CU1EC6Y/ref=oh_aui_detailpage_o02_s00?ie=UTF8&psc=1))

Older versions may work but aren't regularly tested. Bug reports for older versions are welcome.

Install
-------

Download, review, then execute the script(s):

```
git clone git://github.com/NicholasAdamou/OnionPi.git && cd OnionPi && ./pifi.sh && ./tor.sh
```

Follow the on-screen directions.

It should take less than a minute to install.

License
-------

Onion Pi is © 2017 Nicholas Adamou.

It is free software, and may be redistributed under the terms specified in the [LICENSE] file.

[LICENSE]: LICENSE
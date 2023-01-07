---
layout: page
title: Homelab
permalink: /homelab/
---

Here is a photo of the current state of my homelab rack:

![Homelab 2023-01-05](/assets/homelab-2023-01-05.jpg)

It features the following from top to bottom:

* [StarTech 6U Wall Mount Network Rack](https://www.startech.com/en-us/server-management/wallmount6)
* [Cable Matters 24 port keystone patch panel](https://www.cablematters.com/pc-386-162-rack-or-wall-mount-24-port-blank-patch-panel.aspx)
    * Currently has six CAT6, one HDMI, and one USB 3.0 ports
* [Ubiquiti EdgeSwitch 24 500W](https://store.ui.com/collections/operator-edgemax-switches/products/edgeswitch-24-500w)
    * Obtained this very cheaply on eBay and it serves PoE to each Raspberry Pi to power them
* [Four Raspberry Pi 4B 8GB](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/) each having the following add-ons:
    * [PoE HAT](https://www.raspberrypi.com/products/poe-hat/) to power the unit
    * [Kingston 120GB A400](https://www.kingston.com/en/ssd/a400-solid-state-drive) SATA hard drive
    * [WAVLINK USB 3.0 to SATA Hard Drive Adapter Cable](https://www.amazon.com/gp/product/B09JSL3D6Q/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
    * These are rack mounted with the [UCTRONICS 1U Raspberry Pi Rack Mount](https://www.uctronics.com/raspberry-pi/1u-rack-mount/uctronics-19-1u-raspberry-pi-rack-mount-with-ssd-mounting-brackets.html)
* [Three Intel NUC11TNKI7](https://www.intel.com/content/www/us/en/products/sku/205599/intel-nuc-11-pro-kit-nuc11tnki7/specifications.html)
    * [Crucial RAM 32GB Kit](https://www.amazon.com/gp/product/B08C4X9VR5/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1)
    * [Seagate FireCuda 530 1TB Solid State Drive](https://www.amazon.com/gp/product/B08Q54CHS6/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1)
    * HDMI keystone jack with jumper cable to bring the IO to the front of the unit
    * These are rack mounted with the [UCTRONICS NUC Rack Mount](https://www.uctronics.com/other/for-nuc/nus-rack-mount-1u-rackmount-supports-3-units-low%20model-nuc.html)
* [APC NET9RMBLK Surge Protector](https://www.apc.com/us/en/product/NET9RMBLK/apc-black-rackmount-performance-surgearrest-9-outlet-120v/)
* [AC Infinity Vented Cantilever 1U Universal Rack Shelf](https://acinfinity.com/racks-accessories/rack-shelves/vented-cantilever-1u-rack-shelf-10/)
    * This currently holds the NUC's power adapters, but planning to use it for a Home Assistant Yellow when it arrives.

I purchased this particular rack because it will fit well in an upstairs closet. My intention was to primarily use it for holding my networking equipment so this size works well, and gives me a good place to get started. Eventually I will invest in more technology and will need to grow, and at that point I plan to find a 12U or 15U rack to use for my actual servers.

## Wish List

I'm keeping an eye out for the following to add to my rack, though I'm not sure exactly what options I want to use for each:

* 12U or 15U server rack
* Network router - Maybe the [Ubiquiti ER-4](https://store.ui.com/products/edgerouter-4)
* A Network Attached Storage device - Maybe the [Synology RS820+](https://global.download.synology.com/download/Document/Hardware/DataSheet/RackStation/20-year/RS820+/enu/Synology_RS820_RP__Plus_Data_Sheet_enu.pdf), or I'm also considering building my own
* Uninterruptible Power Supply
* Server fans
* Rack mount for a monitor - I have an older monitor which would be a great size for a server rack
* Rack drawer for holding a keyboard

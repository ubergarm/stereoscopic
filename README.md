stereoscopic
===
*adjective*

> relating to or denoting a process by which two photographs of the
> same object taken at slightly different angles are viewed together,
> creating an impression of depth and solidity.

## Goal
The `stereoscopic` project combines low-cost high-quality commercially
available hardware and open source software enabling a point-and-shoot
digital stereoscopic camera experience.

This rig could also be used for scanning books with some mounting
modifications.

Think digital Nimslo 3D to animated gif!

## Status
The `stereoscopic` project is currently in the ideation and requirements
gathering stage.

## Requirements
Category | Requirement | Bonus
--- | --- | ---
*Cost* | Between $150~$250 USD | All new hardware
*Sensors* | Two (2) | Expandable to four (4) sensors
*Baseline* | ~6cm | Adjustable up to 30cm
*Size* | 10MP per sensor | 16 MP per sensor
*Format* | JPG | RAW (e.g. DNG)
*Capture* | Synchronised external capture trigger dongle | WiFi trigger
*Wavelengths* | Standard RGB | Near InfraRed capability
*Processing* | Offline via scripts | Uploads finished images via WiFi

## Hardware
Qty | Component | Description | Price ea | Total
--- | --- | --- | --- | ---
2 | Camera | [Canon Powershot A3300 IS](http://gdlp01.c-wss.com/gds/9/0300004679/01/PSA3300IS_A3200IS_A2200_CUG_EN.pdf) | ~$40 used | ~$80
2 | SD Card | [SDSDUNC-016G-GN6IN](https://www.amazon.com/gp/product/B0143RTB1E) | $9 | $18
1 | Battery Charger Kit | [Powerextra 2x NB-8L Battery and Charger](https://www.amazon.com/gp/product/B00OFP9MNM) | $12 | $12
2 | USB Cables | [Type A Male - Mini Type B Male](https://www.amazon.com/gp/product/B00NH13S44) | $5 | $10
1 | USB in-line switch | [JBtek Type A Male to Female](https://www.amazon.com/gp/product/B00UR321B6) | $6 | $6
1 | USB Y Charge Splitter | [Onvian Male to 2x Female Type A](https://www.amazon.com/gp/product/B01KX4TKH6) | $6 | $6
1 | USB Power Bank | [Bonai Dual USB Charger](https://www.amazon.com/gp/product/B06Y58CXFZ) | $11 | $11
1 | Tripod | [Amazon Basics 50"](https://www.amazon.com/gp/product/B00XI87KV8) | $13 | $13
1 | Mount Bracket | [Neewer 8" Dual Camera Tripod Mount Bracket](https://www.amazon.com/gp/product/B00PAG93ES) | $8 | $8
1 | L-Brackets | [Limo 2x L Shape Bracket](https://www.amazon.com/gp/product/B01HH5NB2Y) | $10 | $10
1 | Misc Hardware | ??? | ??? | ???
1 | Lighting | ??? | ??? | ???
-- | -- | -- | TOTAL | <=~$175

## Software
TODO

## Discussion
#### Sensors
For `v1` I decided to go with the Canon Powershot A3300 IS plus CHDK
firmware due to low cost, feature set, availability, and prior art using
these cameras. For a higher budget version, I would opt for a DSLR camera
fully supported by `gphoto2` and a manual remote switch so no need to fuss
around with used equipment and potential firmware compatibility issues.

#### Full Spectrum
It may be possible to extend into UV and IR ranges by:
1. Remove camera Hot Filter and use neutral Full Spectrum glass
2. Purchase some filters

Or for such a cheap camera it may be possible to:
1. Use a dark room with long exposures
2. Expose to UV or IR light sources

* [395nm UV LED Flashlight](https://www.amazon.com/Escolite-Flashlight-Ultraviolet-Blacklight-Detector/dp/B008133KB4) ~$10
* [850nm IR LED Array](https://www.amazon.com/Power-Array-Illuminator-Vision-Camera/dp/B01D73XM24) ~$10
* [365nm 7W 25LED Bulb](https://www.amazon.com/Lixada-AC100V-240V-Ultraviolet-Sterilization-Fluorescent/dp/B06XKS9KRK)
* [850nm](https://www.amazon.com/Univivi-Infrared-Illuminator-Waterproof-Security/dp/B01G6K407Q)

####Filters
* [Clip Thingy](https://www.amazon.com/Cellphone-AFUNTA-Universal-Gooseneck-Blackberry/dp/B00KZH3K2S)
* [Square Filter Adapter](https://www.amazon.com/Neewer-Aluminum-Adapter-Singh-Ray-Filters/dp/B01N76EIHP)
* [72mm 850nm IR Pass](https://www.amazon.com/NEEWER®-72mm-850nm-Infrared-Filter/dp/B003TXZF8M)

#### Lighting
* [Dimmer](https://www.amazon.com/dp/B0000BYEF6)

## Documentation
* [CHDK A3300 IS Firmware](http://chdk.wikia.com/wiki/A3300IS)
* [Canon Powershot A3300 IS Manual](http://gdlp01.c-wss.com/gds/9/0300004679/01/PSA3300IS_A3200IS_A2200_CUG_EN.pdf)

## References
* [CHDK](http://chdk.wikia.com)
* [$400-96MP-array](http://www.tawbaware.com/vsa_camera_array.html)
* [pi-scan](https://github.com/Tenrec-Builders/pi-scan)
* [www.diybookscanner.org](https://www.diybookscanner.org/)
* [gphoto2](http://gphoto.org/proj/libgphoto2/support.php)
* [Full Spectum Photography](https://en.wikipedia.org/wiki/Full-spectrum_photography)
* [Nimslo](https://en.wikipedia.org/wiki/Nimslo)

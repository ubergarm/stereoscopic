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

## Documentation
* [CHDK A3300 IS Firmware](http://chdk.wikia.com/wiki/A3300IS)
* [Canon Powershot A3300 IS Manual](http://gdlp01.c-wss.com/gds/9/0300004679/01/PSA3300IS_A3200IS_A2200_CUG_EN.pdf)

## References
* [CHDK](http://chdk.wikia.com)
* [$400-96MP-array](http://www.tawbaware.com/vsa_camera_array.html)
* [pi-scan](https://github.com/Tenrec-Builders/pi-scan)
* [www.diybookscanner.org](https://www.diybookscanner.org/)
* [gphoto2](http://gphoto.org/proj/libgphoto2/support.php)
* [Nimslo](https://en.wikipedia.org/wiki/Nimslo)

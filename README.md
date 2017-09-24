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
Component | Description | Price
--- | --- | ---
Camera | ??? | ???
Tripod | ??? | ???
Custom Mount | ??? | ???
L-Brackets | ??? | ???
USB Cables | ??? | ???
Remote Switch | ??? | ???
Misc Hardware | ??? | ???

## Software

## Discussion
Currently deciding if its better to get 2x used CHDK supported cameras
and hope they have the correct firmware and build a simple USB power
based remote trigger capture.

-or-

See if there is a low cost gphoto2 available camera assuming trigger
latency is small enough for sufficient synchronicity between cameras.

## References
* [CHDK](http://chdk.wikia.com/wiki/CHDK)
* [gphoto2](http://gphoto.org/proj/libgphoto2/support.php)
* [pi-scan](https://github.com/Tenrec-Builders/pi-scan)
* [$400-96MP-array](http://www.tawbaware.com/vsa_camera_array.html)
* [Nimslo](https://en.wikipedia.org/wiki/Nimslo)

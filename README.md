# Lenovo-IdeaPad-Flex5-14IIL05-Hackintosh

[![Preview](https://raw.githubusercontent.com/BestRazer/Lenovo-IdeaPad-Flex5-14IIL05-Hackintosh/main/preview.png)](https://nodesource.com/products/nsolid)

First of all, you should definitely [build your own EFI](https://dortania.github.io/OpenCore-Install-Guide/) if you have the time.
If not, however, here's a prebuilt one.
## Specs of my IdeaPad Flex 5

| Component | Name |
|:--- |:---|
| Motherboard:  | LNVNB161216 **495** |
| CPU: | **Intel** i3-1005G1 |
| RAM: | **Micron** 4ATF51264HZ-3G2J1 2x4GB 3200Mhz |
| iGPU: | **Intel** GT2 32EU LM |
| Touch Display: | **Chi Mei** NMN1406 |
| NVMe: | **SKHynix** HFM512GDHTNI-87A0B 512GB |
| Wifi/BT: | **Intel** Wireless-AC 9560 160MHz (Type CNVi) |
| Audio: | **RealTek** ALC257 |
| Trackpad: | HID I2C Trackpad |
| Keyboard: | PS/2 Keyboard (ISO Spain)|
| Card Reader: | **RealTek** RTS522A|

## Features/Components that are/aren't working
| Name | Solution |
|:--- |:--- |
| Built-In Display  | Works thanks to `WhateverGreen.kext` *(iGPU Fixes)* and all DeviceProperties for the 10th Gen iGPU. |
| Jack 3.5mm, Speakers & Microphone | Thanks to `AppleALC.kext` *(Audio Driver)* however you need to search another layout because microphone is not working. |
| DC-IN & Battery| `VirtualSMC.kext` with `SMCBatteryManager.kext` allows management off charging and Battery Info. |
| Camera | Currently not working for me. |
| Keyboard | Thanks to `VoodooPS2.kext` (Driver for PS2 devices). |
| Trackpad | WORKING thanks to `SSDT-I2C-TPAD.aml` by [@Micael106](https://github.com/Micael106) |
| TouchScreen | Currently not working.|
| PowerOff, Reboot & Sleep | Currently not working. |
| WiFi | Thanks to [AirportItlwm.kext](https://github.com/OpenIntelWireless/itlwm/releases). |
| Bluetooth | Thanks to [IntelBluetoothFirmware.kext](https://github.com/OpenIntelWireless/IntelBluetoothFirmware/releases). |
| HDMI Port | Currently not working. |

## Credits

- [RobyRew](https://github.com/RobyRew) - Audio layout, iGPU fixes, README inspiration
- [Micael106](https://github.com/Micael106) - Trackpad fix (`SSDT-I2C-TPAD.aml`)
- [Dortania](https://github.com/dortania) - Hackintosh guide
- [Apple](https://github.com/apple) - macOS
- [CorpNewt](https://github.com/corpnewt) - lots of very helpful tools



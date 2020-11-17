# AMD Ryzen Hackintosh

**macOS version**: 11.0.1 (20B29)  
**OpenCore version**: 0.6.3 

![Screenshot][image-1]

## Specification
| Component        | Model                                  |
| ---------------- | -------------------------------------- |
| CPU              | AMD Ryzen 7 2700                       |
| MotherBoard      | ASUS ROG Strix X470-F BIOS V5603       |
| OS Disk (NVMe)   | 2x WD 500GB NVMe M.2 SSD               |
| RAM              | 4x 16gb Corsair Vengeance Pro 64GB Ram |
| GPU              | Sapphire Radeon Nitro+ RX 580          |
| Bluetooth        | BCM94360CD Native Airport WiFi BT 4.0  |
| Liquid Cooler    | Corsair h100i Pro                      |
| WiFi & Bluetooth | Fenvi FV-T919                          |

## Compatible macOS versions
 - High Sierra (10.13.x)
 - Mojave (10.14.x)
 - Catalina (10.15.x)
 - Big Sur (10.16/11.0)

**You CAN NOT use SMBIOS from this repository, it MUST be unique for every macOS installation**

## Credits

#### Software
 - [[Bootloader] OpenCore](https://github.com/acidanthera/OpenCorePkg)
 - [[Resources] Picker GUI](https://github.com/acidanthera/OcBinaryData/tree/master/Resources)
 - [[Patch] AMD_Vanilla](https://github.com/AMD-OSX/AMD_Vanilla)
 - [[SSDT] EC-USBX-DESKTOP](https://github.com/dortania/Getting-Started-With-ACPI/blob/master/extra-files/compiled/SSDT-EC-USBX-DESKTOP.aml)
 - [[SSDT] SLEEP-PTXH](./OC/ACPI/SSDT-SLEEP-PTXH.aml)
 - [[Driver] OpenRuntime](https://github.com/acidanthera/OpenCorePkg)
 - [[Driver] OpenCanopy](https://github.com/acidanthera/OpenCorePkg)
 - [[Driver] HFSPlus](https://github.com/acidanthera/OcBinaryData/blob/master/Drivers/HfsPlus.efi)
 - [[Kext] Lilu](https://github.com/acidanthera/Lilu)
 - [[Kext] VirtualSMC](https://github.com/acidanthera/VirtualSMC)
 - [[Kext] WhateverGreen](https://github.com/acidanthera/WhateverGreen)
 - [[Kext] AppleALC](https://github.com/acidanthera/AppleALC)
 - [[Kext] RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X)
 - [[Kext] AMDRyzenCPUPowerManagement](https://github.com/trulyspinach/SMCAMDProcessor)
 - [[Kext] SMCAMDProcessor](https://github.com/trulyspinach/SMCAMDProcessor)
 - [[Kext] AppleMCEReporterDisabler](https://github.com/AMD-OSX/AMD_Vanilla/blob/experimental-opencore/Extra/AppleMCEReporterDisabler.kext.zip)   

#### People
 - [Apple](https://apple.com) for macOS
 - [AMD-OSX Developers](https://github.com/AMD-OSX) for kernel patches for AMD CPUs
 - [Acidanthera](https://github.com/acidanthera) for OpenCore and most of used kexts
 - [Trulyspinach](https://github.com/trulyspinach) for Ryzen power management and monitoring kexts
 - [Mieze](https://github.com/Mieze) for RealtekRTL8111 kext
 - [Dortania](https://github.com/dortania) for OpenCore configuration guides
 - [XLNC](https://github.com/naveenkrdy) for Adobe patches for AMD CPUs
 - [AMD-OSX Community](https://amd-osx.com) for support while making my Hackintosh


## Working

- [x] Messaging
- [x] iCloud
- [x] Handoff
- [x] AirDrop
- [x] Bluetooth
- [x] Wifi
- [x] Ethernet

![Screenshot][image-2]



[17]:	https://apple.com


[image-1]:	https://github.com/kdbaustert/ryzen-hackintosh/blob/master/images/about-mac.png
[image-2]:	https://github.com/kdbaustert/ryzen-hackintosh/blob/master/images/IMG_5963.png
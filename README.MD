# Ready-to-use Opencore EFI for AMD Ryzen

## My build
| **Component** | **Model** |
| ------------- | --------- |
| CPU | AMD Ryzen 7 2700x |
| Motherboard | ASUS B350i Strix ITX |
| RAM | G.SKILL TridentZ RGB |
| Audio | ALC-1220 |
| GPU | Sapphire rx580 8G |
| NVME | ADATA XPG SX8200 Pro 1TB + ADATA XPG Gammix S11 Pro 1TB |

## OS Version

**OS version**: 10.15.6 Catalina
**OpenCore version**: 0.6.0  

## Drivers & Kexts (OC 0.6.0)
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
 - [[Kext] NVMEfix](https://github.com/acidanthera/NVMeFix)
 - [[Kext] smalltreeintel82576](https://github.com/khronokernel/SmallTree-I211-AT-patch/releases)

## What's working:
 - **Sleep/Wake works perfectly**(hibernatemode 3 required)
 - **All usb ports
 - All audio jacks
 - Wired network
 - All iServices
 - Hardware Acceleration

## Things that are not working：
 - Did not fix the wifi driver(with the mobo) since I dont use wifi on this hackintosh

## GUIDE
  1. Use this detailed guide as ref if you wanna make your own config [**this guide**](https://dortania.github.io/OpenCore-Install-Guide/)
  2.  [**GenSMBIOS**](https://github.com/corpnewt/GenSMBIOS) generate your own unique SMBIOS and put them in your config(use the guide above)
  3. BOOT
 - Post-Install: [**\*click\***](https://dortania.github.io/OpenCore-Post-Install/)
 

**You CAN NOT use SMBIOS from this repository, it MUST be unique for every macOS installation**




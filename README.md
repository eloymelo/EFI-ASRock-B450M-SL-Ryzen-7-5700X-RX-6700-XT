<!-- OpenCore version 1.0.0 -->

# ASRock B450M Steel Legend + Ryzen 7 5700X + RX 6700 XT

![about-12 3 1](Images/aboutthismac.png)

**SMBIOS: iMacPro1,1**
<br>
**Latest working macOS**: Sonoma 14.6.1
<br>
**Current OpenCore version**: 1.0.0

## Complete hardware specs
- AMD Ryzen 7 5700X
- ASRock B450M Steel Legend
- RX 6700 XT 12GB
- 4x 16Gb DDR4 3200Mhz
- Broadcom BCM4360 Wifi/Bluetooth

## What works
- macOS Monterey, macOS Ventura and macOS Sonoma
- Audio
- All USB/USB-C ports (they are mapped)
- iCloud related services (Drive, iMessage, Facetime, etc)
- Temperature monitoring for everything
- Shutdown/Reboot/Update to newer macOS builds over time
- AirDrop
- Wifi
- Bluetooth

## What doesn't work/Bugs
- DRM doesn't work properly
- Let me know what else is not working

## Kexts used:
- AMD-USB-Map.kext
- AMDRyzenCPUPowerManagement.kext
- AMFIPass.kext
- AppleALC.kext
- AppleMCEReporterDisabler.kext
- FeatureUnlock.kext
- HibernationFixup.kext
- IO80211FamilyLegacy.kext
- IOSkywalkFamily.kext
- Lilu.kext
- NVMeFix.kext
- RadeonSensor.kext
- RealtekRTL8111.kext
- RestrictEvents.kext
- SMCAMDProcessor.kext
- SMCRadeonGPU.kext
- VirtualSMC.kext
- WhateverGreen.kext
- XLNCUSBFix.kext

## Keep in mind:
- You need to add the [NootRX.kext](https://github.com/ChefKissInc/NootRX) after the install so you can get the hardware acceleration.

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- Gabriel Luchina - Universo Hackintosh (https://github.com/luchina-gabriel)

## Discord - Universo Hackintosh (With English Support)
- [Access Discord](https://discord.universohackintosh.com.br)

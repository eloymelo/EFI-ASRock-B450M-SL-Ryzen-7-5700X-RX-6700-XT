<!-- OpenCore version 1.0.0 -->

# ASRock B450M Steel Legend + Ryzen 7 5700X + RX 6700 XT

![about-12 3 1](https://github.com/eloymelo/EFI-ASRock-B450M-SL-Ryzen-7-5700X-RX-6700-XT/blob/5e968a20d1199585a25b58cc22a80b762c06d65f/Images/aboutthismac.png?raw=true)

**SMBIOS: iMacPro1,1**
<br>
**Latest working macOS**: Ventura 13.6.7
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
- Audio (USB Connection) **I haven't tested the audio jack**
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
- AppleALC.kext
- AppleMCEReporterDisabler.kext
- FeatureUnlock.kext
- HibernationFixup.kext
- Lilu.kext
- NootRX.kext
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
- You need to remove the NootRX.kext in order to have a successfully install. It will not work if you do not remove it before a fresh install of the macOS.

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- Gabriel Luchina - Universo Hackintosh (https://github.com/luchina-gabriel)

## Discord - Universo Hackintosh (With English Support)
- [Access Discord](https://discord.universohackintosh.com.br)

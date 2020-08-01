# HP-ProDesk600-G5-mini-OpenCore
Repository to hold the files needed to install and run macOS on HP ProDesk G5 mini
Change XX-MASKED-XX values in PlatformInfo section in config.plist file with your own values. Use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS).

## Tested versions
OpenCore: 0.5.9

MacOS: macOS Catalina 10.15.6

## Configuration information
Key | Value
--- | ---
CPU | Intel Core i5 9500T
iGPU | Intel Graphics UHD 630
RAM | Kingston HyperX DDR4 2666MHz 16GB *2
SSD | NVMe WD Black SN750 500GB 
Audio | Conexant CX20632
Wireless | BCM94352Zz (Lenovo)

## Working
Both DisplayPort Outputs with 4K HIDPI options

Graphics Acceleration

Sound

All USB including both USB-C ports

Sleep

Bluetooth and WiFi (changing wireless card with Lenovo BCM94352Zz)

## Not Working
Intel WiFi - Can work with new Intel WiFi kexts, but not for services like handoff, continuity, Apple Watch unlock, etc.

## Log
-2020.8.1
  -First 100% working version

## Thanks
-Apple
-[@Acidanthera](https://github.com/acidanthera)
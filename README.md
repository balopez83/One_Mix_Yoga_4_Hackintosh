# One Mix Yoga 4 Hackintosh
Project to implement macOS support on the One Mix Yoga 4

Initial support for macOS version 11.2.3 and above.

If you see anything that could be added or changed don't hesitate to make a pull request.


## *** NOTICE ***
### Initial support of macOS on the One Mix Yoga 4 has been achieved. Not for use yet as a daily driver. 
### Currently the Intel 11th generation CPU with integrated Intel Xe GPU is not supported by macOS.
### Do not update kexts labeled as "custom" manually, instead wait for us to update. Kexts have been modified to support the currently unsupported 11th gen chipset. Once 11th gen devices are supported natively we will remove this restriction.

## One Mix Yoga 4 Specifications:

| Model: | Black | Platinum |
|---|----------|----------|
|CPU| i5-1130G7 quad core 1.1-4 Ghz| i7-1160G7 quad core 1.2-4.4 Ghz|
|GPU| Xe 80 EU | Xe 96 EU |
|RAM| 8/16 GB | 16 GB |
|SSD| 256GB/512GB/1TB NVME | 512GB/1TB NVME |
|WiFi| Intel WiFi 6 | Intel WiFi 6 |
|Batt| 10,000 mAH | 10,000 mAH |
|USB| 2x USB-C, Thunderbolt 4 | 2x USB-C, Thunderbolt 4 |
|   | 1x USB-C, Type USB 3.0 | 1x USB-C, Type USB 3.0 |



## Instruction Guides (Placeholder)

### [Chapter 1) Quick Start Install](https://github.com/balopez83/One_Mix_Yoga_4_Hackintosh/blob/main/1-QuickStart.md)
### [Chapter 2) BootCamp Install](https://github.com/balopez83/One_Mix_Yoga_4_Hackintosh/blob/main/2-BootCamp.md)
### [Chapter 3) Quirks & Fixes](https://github.com/balopez83/One_Mix_Yoga_4_Hackintosh/blob/main/3-quirks&fixes.md)
### [Chapter 4) Additional Drivers](https://github.com/balopez83/One_Mix_Yoga_4_Hackintosh/blob/main/4-drivers.md)
### [Chapter 5) Booting Other OS's with OpenCore]
### [Chapter 6) Other Operating Systems]


## What works 

- macOS initial support. Installer works and will boot to macOS after installed. 
- SDcard is fully supported within macOS
- Wi-Fi native support (currently unreliable)
- Fan
- USB
- Preliminary HIDPI support without Graphics Acceleration
- Battery
- Trackpad
- TouchScreen / Stylus
- Keyboard Shut-off in tablet mode
- Windows Boot Support From OpenCore Bootloader
- Audio


## Planned Features


## What doesn't work

- Graphic Acceleration including 4K support. Screen runs and is in correct orientation.
- Bluetooth
- Brightness
- Power Management
- Sleep / Wake
- Thunderbolt
- FileVault
- Recovery
- Fingerprint Sensor
- Accelerometer


## Credits
Special thanks to [@THEDEVIOUS1](https://github.com/THEDEVIOUS1/CHUWI-MINIBOOK-HACKINTOSH) for all of his assistance <br>

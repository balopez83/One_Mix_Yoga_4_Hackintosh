# One Mix Yoga 4 (One Mix 4) Hackintosh
Project to implement macOS support on the One Mix Yoga 4

Initial support for macOS version 10.15.7 and above.

If you see anything that could be added or changed don't hesitate to make a pull request.


## *** NOTICE ***
### Initial support of macOS on the One Mix Yoga 4 has been achieved. Not for use yet as a daily driver. 
### Currently the Intel 11th generation CPU with integrated Intel Xe GPU is not supported by macOS.
### Do not update kexts labeled as "custom" manually, instead wait for us to update. Kexts have been modified to support the currently unsupported 11th gen chipset. Once 11th gen devices are supported natively we will remove this restriction.
### You may experience occasional sluggishness in the OS or when using the Toucscreen or Track Pad. This is due to a lack of graphics acceleration. Please do not file an issue on this as it is a known issue. 

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



## Instruction Guides

### [Chapter 1) Quick Start Install](https://github.com/balopez83/One_Mix_Yoga_4_Hackintosh/blob/main/1-QuickStart.md)
### [Chapter 2) BootCamp Install](https://github.com/balopez83/One_Mix_Yoga_4_Hackintosh/blob/main/2-BootCamp.md)
### [Chapter 3) Quirks & Fixes](https://github.com/balopez83/One_Mix_Yoga_4_Hackintosh/blob/main/3-quirks&fixes.md)
### [Chapter 4) Additional Drivers](https://github.com/balopez83/One_Mix_Yoga_4_Hackintosh/blob/main/4-drivers.md)
### [Chapter 5) Booting Other OS's with OpenCore](https://github.com/balopez83/One_Mix_Yoga_4_Hackintosh/blob/main/5-OtherOS%26OC.md)
### [Chapter 6) Other Operating Systems](https://github.com/balopez83/One_Mix_Yoga_4_Hackintosh/blob/main/6-OtherOS.md)


## What works 

- macOS 10.15.7 and above
- SDcard is fully supported within macOS
- Wi-Fi native Intel support
- Fan
- USB
- Preliminary HIDPI support without Graphics Acceleration
- Battery
- Trackpad
- TouchScreen / Stylus
- Keyboard Shut-off in tablet mode
- Windows Boot Support From OpenCore Bootloader
- Audio: Built-in & Headphone Jack
- Recovery
- FileVault
- Bluetooth
- Brightness Keys (This won't actually work until GPU Acceleration is achieved)



## What doesn't work

- Graphic Acceleration including 4K support.
- Audio: Built-in Microphone
- Brightness Adjustment
- Power Management
- Sleep / Wake
- Thunderbolt: Video currently unsupported, Audio Untested
- Fingerprint Sensor
- Accelerometer


## Credits
Special thanks to [@THEDEVIOUS1](https://github.com/THEDEVIOUS1/CHUWI-MINIBOOK-HACKINTOSH) for all of his assistance <br>

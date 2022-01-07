The “com.apple.recovery.boot” folder contains internet recovery images and should be used to install macOS without a USB disk like a real Mac. 

The folder should be copied to the root of your EFI partition. You should only copy the recovery needed and not all recoveries due to space limitations.

In order to have support for internet recovery you must have an EFI partition that is at least the size of the recovery DMG with .Chunklist plus an additional 100mb. It is recommended to set your EFI partition size to 1GB and ensure it is formatted to FAT32.
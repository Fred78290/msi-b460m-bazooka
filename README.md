
# Specifications
```
MSI B460M Bazooka
 - Audio: Realtek® ALC897 codec
 - Ethernet: Realtek 8111
 - iGPU UHD630
 - Intel Core i9 10850K
 - Ram 2 x 32GB Patriot
 - SAPLOS Radeon RX 560 Graphics Card, 4GB GDDR5 128-bit
 - SSD WD WDS500G2B0C 500 GB NVME PCIe Gen3 x4 (WDS250G3X0C)
 - Bluetooth: USB dongle
 - Dual monitor connected to RX560
```

# OpenCore (Version: 0.8.6 - stable) + macOS Ventura 13.01

- https://dortania.github.io/OpenCore-Install-Guide/
- https://github.com/acidanthera/OpenCorePkg/releases/tag/0.8.1

# Kexts include

- AppleALC
- BlueToolFixup
- BrcmFirmwareData
- BrcmPatchRAM3
- CPUFriend
- CPUFriendDataProvider
- HibernationFixup
- IntelBluetoothFirmware
- Lilu
- NVMeFix
- RealtekRTL8111
- SMCProcessor
- USBInjectAll
- VirtualSMC
- WhateverGreen
- XHCI-unsupported

## Work

- Intel Quick Sync
- Handoff, Air Drop
- Rear Jack Audio Output + Input and Front Jack
- Ethernet
- Wifi
- Bluetooth
- All USB Port
- Restart, Sleep and Shutdown 
- TRIM native 
- Etc...

# Not Work

- DRM (shikigva 11+ dropped support)

## MAG B460M BAZOOKA

<center>

![12](/images/msi.png)

</center>

# Patriot Viper Steel DDR4 64GB (2 x 32GB) 3200MHz Kit

<center>

![12](/images/ram.png)

</center>

# Radeon RX560 as main display

<center>

![12](/images/radeon.png)

</center>

# iGPU connector less

# Note For You

The file config.plist. Please change MLB, SystemSerialNumber, SystemUUID

# Result

<center>

![12](/images/about.png)

![12](/images/accel.png)

![12](/images/perf.png)

![12](/images/geekbench.png)

![12](/images/cinebench.png)

![12](/images/powergadget.png)

</center>
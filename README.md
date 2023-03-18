# Hackintosh-H470-i510400F-RX550

 OpenCore EFI backup (Ver.9.0)

## 配置详细信息

>[image](detiles.png)

>[image2]()

>[image3]()

### ACPI
>添加 AWAC/EC-USBX-DESKTOP/GPU-SPOOF/PLUG-DRTNIA/PMC/PHUB

### Kext
>添加 AGPMInjector.kext/AirportItlwm.kext/AppleALC.kext/HoRNDIS.kext/IntelMausi.kext/IntelSnowMausi.kext/Lilu.kext/SMCSuperIO.kext/USBInjectAll.kext/USBPorts.kext/VirtualSMC.kext/WhateverGreen.kext

### Drivers
>添加 Ext4Dxe/HfsPlus/OpenCanopy/OpenLinuxBoot/OpenRuntime/ResetNvramEntry/ToggleSipEntry

## 实现功能
>CPU 正常变频、GPU 通过定制 SSDT 文件解决仿冒 ID 问题、板载有线网卡正常驱动、板载声卡正常驱动、USB 已全定制、睡眠可用、OTA 更新可用、Apple ID 可用、iMessage 可用
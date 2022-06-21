# Hackintosh B460M Plus TUF Gaming  I5 10400


> 2022/6/21 first comit: OC 0.8.1 .

## Hardware

|    Device     |          Model           |
| :-----------: | :----------------------: |
|      CPU      |         I5-10500         |
|  Motherboard  | Asus B460M Plus WIFI Tuf |
|     GPU0      |  Intel UHD Graphics 630  |
|     GPU1      |   AMD Radeon RX 580 4G   |
|     Audio     |    Realtek ALCS1200A     |
| Ethernet Card |      Intel I219V12       |
| WiFI/BT Card  |      Wi-Fi 6 AX200       |


## What works

| Function      | Status                                     |
| ------------- | ------------------------------------------ |
| CPU           | Work.                                      |
| GPU           | DP, HDMI work. Hardware acceleration work. |
| Audio         | Work with layout-id 50.                    |
| Ethernet Card | Work.                                      |
| WIFI/BT       | Work.                                      |
| Sleep/Wake    | Work.                                      |
| USB Mapping   | Work.                                      |

**Note 1:** You should remap your own USB ports if the mapping does not work properly.

## Known issues

1. USB mapping 

## Kexts

|            Kext             |          Version           |
| :-------------------------: | :------------------------: |
|          Lilu.kext          |           1.6.0            |
|       VirtualSMC.kext       |           1.2.9            |
|     WhateverGreen.kext      |           1.5.8            |
|       IntelMausi.kext       |           1.0.7            |
| IntelBluetoothFirmware.kext |           2.1.0            |
|      Airportitlwm.kext      |           2.1.0 Monterey   |
|        AppleALC.kext        |           1.7.1            |
|           NVMeFix           |           1.0.9            |
|     BlueToolFixup.kext      |           2.6.1            |



## BIOS setting

|       Disable        |                 Enable                 |
| :------------------: | :------------------------------------: |
|      Fast Boot       |           Above 4G decoding            |
|     Secure Boot      |            Hyper-Threading             |
|   Serial/COM Port    |           EHCI/XHCI Hand-off           |
|         VT-d         |        OS type: Windows 10 WHQL        |
|         CSM          | DVMT Pre-Allocated(iGPU Memory): 128MB |
| Intel Platform Trust |            SATA Mode: AHCI             |
|       CFG Lock       |                                        |
|      Intel SGX       |                                        |

**Note 1:** The BIOS version is F3, and there is no CFG Lock option in Setting, **So you should select the CFG Lock.efi in OpenCore Picker menu before you try to install the macOS.**


## OpenCore/OS

|   Item   |        Version        |
| :------: | :-------------------: |
| OpenCore |         0.8.1         |
|  macOS   | Monterey 12.4 (21F79) |

## README Before Install

- Add Serial number, UUID and MLB by yourself.

## Preview

![](https://github.com/VanXNF/Hackintosh-Gigabyte-B460M-Aorus-Pro/raw/master/Images/Desktop.png)


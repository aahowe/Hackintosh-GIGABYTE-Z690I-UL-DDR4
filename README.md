# Hackintosh-GIGABYTE-Z690I-UL-DDR4

This repository is about hackintosh on **GIGABYTE Z690I AORUS ULTRA LITE DDR4**. All the hardware is working as expected, and it's ready for daily usage. 

Highly recommended reading the whole [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/) before start.

这是一个**技嘉 Z690I AORUS ULTRA LITE DDR4**主板的黑苹果仓库，所有的硬件都正确工作，日常使用无问题

在开始之前强烈建议完整阅读[OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/) 

## 主板介绍

[Z690I AORUS ULTRA LITE DDR4 (rev. 1.0)](https://www.gigabyte.com/Motherboard/Z690I-AORUS-ULTRA-LITE-DDR4-rev-10)

## 硬件列表

| 项目     | 型号                                      |
| -------- | ----------------------------------------- |
| 主板     | GIGABYTE 技嘉 Z690I AORUS Ultra LITE DDR4 |
| CPU      | Intel® Core™ i7-13700KF                   |
| 内存     | 光威(Gloway) 天策 32Gx2 DDR4 3200         |
| 硬盘     | 海力士 PC801 NVMe SK hynix 1TB            |
| 显卡     | AMD Radeon™ VII                           |
| 电源     | 海盗船 SF750 Platinum                     |
| 无线网卡 | 博通 BCM94360NG                           |
| 有线网卡 | Intel I225-V 2.5Gbit                      |
| 板载声卡 | Realtek® ALC4080 CODEC                    |
| 散热     | 瓦尔基里(VALKYRIE）C240-RGB               |
| 机箱     | 酷鱼G5 Plus 水冷版                        |

> 主板上的板载ax201**可以直接更换**为BCM94360NG网卡！

## 软件

* Bootloader: OpenCore 0.9.4-RELEASE
* OS: macOS Ventura 13.3 (MacPro7,1)

## 实现功能

- [x] CPU变频/大小核调度
- [x] Audio Realtek® ALC4080 CODEC
- [x] Intel I225-V 2.5Gb Ethernet
- [x] Wi-Fi/蓝牙 (BCM94352Z)
- [x] AirDrop
- [x] USB定制
- [x] 睡眠/唤醒
- [x] 原生电源管理

### BIOS

> Version: F22

- CFG-Lock - off
- Fast Boot - off
- VT-d - on
- CSM - off
- VT-x - on
- Above 4G decoding - on
- Re-Size BAR Support - off
- XHCI Hand-off - on

## 工具

* 编译 SSDT: [MaciASL](https://github.com/acidanthera/MaciASL)
* 编辑 plist: [OpenCore Auxiliary Tools (OCAT)](https://github.com/ic005k/OCAuxiliaryTools)
* 编辑 plist: [PropereTree](https://github.com/corpnewt/ProperTree)
* Dumping DSDT: [SSDTTime](https://github.com/corpnewt/SSDTTime)
* Toolbox: [Hackintool](https://github.com/headkaze/Hackintool)

## 参考

[Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)

[OpenCore bootloader](https://github.com/acidanthera/OpenCorePkg)

[OpenCore 简体中文参考手册](https://oc.skk.moe/)

[国光的黑苹果安装教程：手把手教你配置 OpenCore](https://apple.sqlsec.com/)

[大头蔡Cass](https://space.bilibili.com/16323318/)


# MSI-Z370-KRAIT-GAMING-OC0.7.4-Monterey
Hackintosh Monterey Opencore EFI

- **简体中文**
- [English](/.github/xxxx.md)

## EFI介绍

此EFI引导适用于微星Z370 Krait gaming主板
MacOS Monterey
Opencore版本:0.7.4
SMIBIOS19,2


## 工作状态

- [x] 声卡（板载）/ 网卡（板载）
- [x] 显卡（核显 + 独显）/ 硬解 4K（HEVC + H.264）
- [x] WiFi（PCI-E 设备） / 蓝牙（PEI-E 载 USB 设备）
- [ ] 隔空投送 / 接力 / 随航(需白果卡)
- [x] FaceTime / iMessage
- [x] 睿频 / HWP 变频 / 原生电源管理
- [x] 睡眠 / 键盘、鼠标唤醒
- [x] 定制USB,开启后置所有USB3/USB2,以及type-c,开启前置2个USB3
- [x] 其他白果功能（99%）

## 我的配置

|         硬件       |                   型号                     | 
|-------------------:|:------------------------------------------|
|               主板 | 微星 Z370 Krait Gaming 银环蛇               |
|             处理器 | 英特尔酷睿 i7-8700K                          |
|               显卡 | 迪兰 RX 590 8GB (免驱)                      |
|               硬盘 | 三星 PM9A1 1TB                             |
|               内存 | 影驰名人堂 HOF 8GB DDR4 3600MHz x 2          |
|        无线 + 蓝牙 | 英特尔 AX200  |
|             显示器 | AOC CU34G2X（34 英寸 3440x1440 分辨率 可开启Hidpi 144hz)             |

## BIOS设定
- Overclocking\CPU特征\CFG锁定--禁止
- Settings\高级\内建显示器配置\集成显卡多显示器--允许
- Settings\高级\内建显示器配置\集显共享显存--64M
- Settings\高级\USB设置\XHCI Hand-off--允许
- Settings\高级\USB设置\传统USB支持--允许
- Settings\高级\Windows操作系统的配置\Windows 10 WHQL支持--允许
- Settings\高级\Windows操作系统的配置\Windows 7安装--禁止
- Settings\高级\Windows操作系统的配置\MSI快速开机--禁止
- Settings\高级\整合周边设备\SATA模式--AHCI模式

## 注意
- 请自行注入三码,引导中三码已移除
- 强制开启显示器Hidpi请参照[Enable-HiDPI-OSX](https://github.com/syscl/Enable-HiDPI-OSX)(2k带鱼屏添加3440x1440,2560x1080,1720x720)
- 如需使用白果网卡蓝牙,请自行禁用BlueToolFixp.kext\IntelBluetoothFirmware.kext\Airportitlwm.kext
- 有偿协助QQ:1015404716

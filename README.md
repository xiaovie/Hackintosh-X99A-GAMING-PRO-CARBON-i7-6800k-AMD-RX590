# Hackintosh-X99A-GAMING-PRO-CARBON-i7-6800k-GTX1070


hackintosh


10.13.6 版本功能测试结果：
声卡显卡网卡均已驱动（显卡官方驱动）
CPU 处理器原生变频睿频，性能跑分正常（BIOS 可超频）
加载 XCPM 原生电源管理，睡眠唤醒正常（睡眠后按电源键唤醒）
USB2.0，3.0，3.1 均驱动正常使用
M2 nvme 固态硬盘内置正常使用
稳定性测试无死机重启
HDMI 接口 DP 接口测试正常，显示器音频输出未测（应该正常使用）




2019 年 11 月 30 日更新:



删除 NullCPUPowerManagement.kext，6800k 不需要这个驱动，其他 cpu 请自行添加

更换 VoodooTSCSync.kext 为最新版，自动检测 cpu 核心数

更新 VirtualSMC.kext 并添加周边传感器驱动

更新 applealc.kext 声卡驱动



2019 年 11 月 27 日更新：



更新 clover 到最新版本 v2.5k r5099

更新部分 clover efi 驱动（修复 HFS + 格式无法安装系统，强烈建议使用 apfs 格式安装系统）

更新 liu.kext 到最新 1.4.0 版本

更新 WhateverGreen.kext 到最新 1.3.4 版本

更改 黑苹果关键驱动 FakeSMC.kext 为 VirtualSMC.kext

添加部分 kext 驱动（**NullCPUPowerManagement.kext VoodooTSCSync.kext
PMDrvr.kext**）

默认 VoodooTSCSync.kext 驱动为 6 核处理器适配，视你当前 CPU 核心数请在驱动文件夹内解压缩对应 4 核或者 8 核处理器适配驱动

添加 PMDrvr.kext 拥有了更好的变频档位，实现 13 档频率变频，Geekbench4 多核跑分性能提升到 23 万

新版 clover 引导界面花屏已被修复

睡眠唤醒没有问题（本人机器由于不知名原因导致 windows 和 mac 均无法睡眠，网友测试反应睡眠正常）

更新 clover 主题 catalina2k&4k 请自行修改 config.plist 主题选项适配你到屏幕，默认 1080p

本次更新推荐大家更新，更换 EFI 文件后请使用 kext utility.app 重建缓存

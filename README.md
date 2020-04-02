# Hackintosh-X99A-GAMING-PRO-CARBON-i7-6800k-GTX1070


hackintosh


macOS 10.13.6 ：

声卡显卡网卡工作
Sound card graphics card works
CPU处理器睿频工作
CPU processor Turbo works
加载 XCPM 原生电源管理，睡眠唤醒正常
Load XCPM native power management sleep wakeup works
USB2.0，3.0，3.1工作
USB2.0, 3.0, 3.1 work
HDMI 输出 DP 输出测试正常
HDMI output DP output test is works

----------------------------------

X99A-GAMING-PRO-CARBON主板请使用这个版本X99A-GAMING-PRO-CARBON motherboard please use this version

       Hackintosh-X99A-GAMING-PRO-CARBON-i7-6800k-GTX1070-USBPorts.zip
       
USB端口定制版本
Custom version of USB port
----------------------------------

其他X99主板Other X99 motherboards

       Hackintosh-X99A-GAMING-PRO-CARBON-i7-6800k-GTX1070.zip
       
USBInjectAll.kext版本
USBInjectAll.kext version

# Hackintosh-X99A-GAMING-PRO-CARBON-i7-6800k-AMD RX590


macOS 10.14.6 ：

声卡显卡网卡工作
Sound card graphics card works
CPU处理器睿频工作
CPU processor Turbo works
加载 XCPM 原生电源管理，睡眠唤醒正常
Load XCPM native power management sleep wakeup works
USB2.0，3.0，3.1工作
USB2.0, 3.0, 3.1 work
HDMI 输出 DP 输出测试正常
HDMI output DP output test is works

Update 24th:

 Update CLOVER EFI bootloader r5107
 Update Lilu.kext to 1.4.3
 Update WhateverGreen.kext to 1.3.8
 Update AppleALC.kext to 1.4.8
 Change the memory correction driver to OsxAptioFix2Drv-64.efi (if you can't start, please see the memory correction section later)
 Changes to Mojave 10.14.6 on March 18:

 Added X99_SSDT-_L0D.aml patch, ACPI injected a related supporting patch
 Added X99_SSDT-IRQ.aml patch, ACPI injected four matching patches
 Added ALZA, HPET, PNLF, PRW, SMBS patches
 Add dsdt fix X99 Error-9 Address Min is greater than Address Max-Fixed by N. Mano
 Add device patch, system report PCI, rename display device to AMD Radeon RX 590, AMD Radeon RX 590 HDMI Audio
 Added CPUFriend.kext processor dynamic power injection

 Update CLOVER EFI bootloader r5105 latest version
 Update Lilu.kext to the latest version
 Update WhateverGreen.kext to the latest version
 Update AppleALC.kext to the latest version
 Update USBInjectAll.kext to the latest version
 
 Remove FakeSMC.kext and use VirtualSMC.kext and related sensor drivers
 Remove TSCAdjustReset.kext and use VoodooTSCSync.kext instead
 Remove CodecCommander.kext because this driver has been merged into AppleALC.kext
 
 Removed drives are moved to the Off directory for selection


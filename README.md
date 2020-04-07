http://xiaoviemc.vip/index.php/archives/194/
Details are available on my blog

hackintosh


macOS 10.13.6 ：

声卡显卡网卡工作
Sound card graphics card works<br>
CPU处理器睿频工作
CPU processor Turbo works<br>
加载 XCPM 原生电源管理，睡眠唤醒正常
Load XCPM native power management sleep wakeup works<br>
USB2.0，3.0，3.1工作
USB2.0, 3.0, 3.1 work<br>
HDMI 输出 DP 输出测试正常
HDMI output DP output test is works<br>

<br>       
USB端口定制版本
Custom version of USB port

X99A-GAMING-PRO-CARBON主板请使用这个版本X99A-GAMING-PRO-CARBON motherboard please use this version

       Hackintosh-X99A-GAMING-PRO-CARBON-i7-6800k-GTX1070-USBPorts.zip

<br>

其他X99主板Other X99 motherboards

       Hackintosh-X99A-GAMING-PRO-CARBON-i7-6800k-GTX1070.zip
       
<br>
# Hackintosh-X99A-GAMING-PRO-CARBON-i7-6800k-AMD RX590


#macOS 10.14.6 ：

声卡显卡网卡工作
Sound card graphics card works<br>
CPU处理器睿频工作
CPU processor Turbo works<br>
加载 XCPM 原生电源管理，睡眠唤醒正常
Load XCPM native power management sleep wakeup works<br>
USB2.0，3.0，3.1工作
USB2.0, 3.0, 3.1 work<br>
HDMI 输出 DP 输出测试正常
HDMI output DP output test is works<br>

#macOS 10.15.3：

声卡显卡网卡工作
Sound card graphics card works<br>
CPU处理器睿频工作
CPU processor Turbo works<br>
无法加载 XCPM 原生电源管理
Not Load XCPM native power management sleep wakeup works<br>
USB2.0，3.0，3.1工作
USB2.0, 3.0, 3.1 work<br>
HDMI 输出 DP 输出测试正常
HDMI output DP output test is works<br>


# Update 2020.04.07:

    Update CLOVER EFI bootloader r5109<br>
    Update Lilu.kext to 1.4.3<br>
    Update WhateverGreen.kext to 1.3.8<br>
    Update VirtualSMC.kext to 1.1.2<br>
    Change the memory correction driver to AptioMemoryFix.efi ，MemoryAllocation.efi (if you can't start, please see the memory correction section later)<br>
    Add SSDT to extract dsdt. aml, ssdt-hpet.aml and ssdt-plug.aml extracted from the section<br>
    
# Update 2020.04.02:

    Update CLOVER EFI bootloader r5107<br>
    Update Lilu.kext to 1.4.3<br>
    Update WhateverGreen.kext to 1.3.8<br>
    Update AppleALC.kext to 1.4.8<br>
    Change the memory correction driver to OsxAptioFix2Drv-64.efi (if you can't start, please see the memory correction section later)<br>
            
# Changes to Mojave 10.14.6 on March 18:

    Added X99_SSDT-_L0D.aml patch, ACPI injected a related supporting patch
    Added X99_SSDT-IRQ.aml patch, ACPI injected four matching patches
    Added ALZA, HPET, PNLF, PRW, SMBS patches
    Add dsdt fix X99 Error-9 Address Min is greater than Address Max-Fixed by N. Mano<br>
    Add device patch, system report PCI, rename display device to AMD Radeon RX 590, AMD Radeon RX 590 HDMI Audio
    Added CPUFriend.kext processor dynamic power injection<br>

    Update CLOVER EFI bootloader r5105 latest version<br>
    Update Lilu.kext to the latest version<br>
    Update WhateverGreen.kext to the latest version<br>
    Update AppleALC.kext to the latest version<br>
    Update USBInjectAll.kext to the latest version<br>
 
            Remove FakeSMC.kext and use VirtualSMC.kext and related sensor drivers<br>
            Remove TSCAdjustReset.kext and use VoodooTSCSync.kext instead<br>
            Remove CodecCommander.kext because this driver has been merged into AppleALC.kext<br>
 
            Removed drives are moved to the Off directory for selection<br>

![image](https://github.com/xiaovie/Hackintosh-X99A-GAMING-PRO-CARBON-i7-6800k-AMD-RX590/blob/master/info.png)
![image](https://github.com/xiaovie/Hackintosh-X99A-GAMING-PRO-CARBON-i7-6800k-AMD-RX590/blob/master/pci.png)
![image](https://github.com/xiaovie/Hackintosh-X99A-GAMING-PRO-CARBON-i7-6800k-AMD-RX590/blob/master/usb.png)
![image](https://github.com/xiaovie/Hackintosh-X99A-GAMING-PRO-CARBON-i7-6800k-AMD-RX590/blob/master/run.jpg)
![image](https://github.com/xiaovie/Hackintosh-X99A-GAMING-PRO-CARBON-i7-6800k-AMD-RX590/blob/master/HEVC.jpg)
![image](https://github.com/xiaovie/Hackintosh-X99A-GAMING-PRO-CARBON-i7-6800k-AMD-RX590/blob/master/cpu.png)

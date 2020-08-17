# AsRock-Z390m-Pro4-OpenCore-Hackintosh

sysInfo | neoFetch
:---:|:----:
![about](/images/about.png)|![neo](/images/neo.png)
### My Hardware

- **Mainboard**: AsRock Z390M Pro4

- **Processor**: Intel Core i7-9700K (8C 3.6GHz, 12MB)

- **Graphics**: Integrated Intel UHD Graphics 630

- **Graphics**: Radeon RX 580 8G Sapphire

- **Memory**: 8GBx4 DIMM 2133 MHz DDR4

- **Display**: 27" 4K (3840x2160) IPS

- **Storage**: 512GB SSD M.2 Intel 760P

- **WLAN + Bluetooth**: BCM94360CD

  ![cpu](/images/cpu.png)

### Kexts version
- **AirportBrcmFixup**: 2.0.9
- **AppleALC**: 1.5.2
- **IntelMausiEthernet**: 1.0.3
- **Lilu**: 1.4.7
- **NVMeFix**: 1.0.3
- **RTCMemoryFixup**: 1.0.6
- **VirtualSMC**: 1.1.6
- **WhateverGreen**: 1.4.2

### Compatible with Catalina and Big Sur

### BIOS Settings
- **BIOS Version** 4.30

| Disabled | Enabled |
|----|----|
| Fast Boot | VT-x |
| CFG Lock (MSR 0xE2 write protection) | Above 4G |
| VT-d | Hyper Threading (If you use a CPU with K) |
| CSM | Execute Disable Bit |
| | EHCI/XHCI Hand-off |
| | OS type: other types |

### Credits
* **OpenCore Bootloader** 0.6.1(2020-08-17) from [OpenCore Respository](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.6.0)
* **The best Installation guide I followed** from [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html)
* **Also followed** from [Xjn's Blog](https://blog.xjn819.com/?p=543)

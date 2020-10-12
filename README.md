# AsRock-Z390m-Pro4-OpenCore-Hackintosh

sysInfo | neoFetch
:---:|:----:
![about](/images/about.png)|![neo](/images/neo.png)

<details>
  <summary><strong>My Hardware</strong></summary>

- Mainboard: AsRock Z390M Pro4
- Processor: Intel Core i7-9700K (8C 3.6GHz, 12MB)
- Graphics: Integrated Intel UHD Graphics 630
- Graphics: Radeon RX 580 8G Sapphire
- Memory: 8GBx4 DIMM 2133 MHz DDR4
- Display: 27" 4K (3840x2160) IPS
- Storage: 512GB SSD M.2 Intel 760P
- WLAN + Bluetooth: BCM94360CD

![cpu](/images/cpu.png)
</details>
<details>
  <summary><strong>Kexts version</strong></summary>

- **AppleALC**: 1.5.3
- **IntelMausiEthernet**: 1.0.4
- **Lilu**: 1.4.8
- **VirtualSMC**: 1.1.7
- **WhateverGreen**: 1.4.3
### Compatible with Catalina and Big Sur
</details>

<details>
  <summary><strong>BIOS Settings</strong></summary>

- **BIOS Version** 4.30

| Disabled | Enabled |
|----|----|
| Fast Boot | VT-x |
| CFG Lock (MSR 0xE2 write protection) | Above 4G |
| VT-d | Hyper Threading (If you use a CPU with K) |
| CSM | Execute Disable Bit |
| | EHCI/XHCI Hand-off |
| | OS type: other types |
</details>

<details>
  <summary><strong>Credits</strong></summary>

  **OpenCore Bootloader** 0.6.2(2020-10-06) from [OpenCore Respository](https://github.com/acidanthera/OpenCorePkg/releases)

  **The best Installation guide** I followed from [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html)

  **Also followed** from [Xjn's Blog](https://blog.xjn819.com/?p=543)
</details>

# Hackintosh MS-Challenger B660M (macOS Sequoia)

Fully working OpenCore configuration for macOS Sequoia (macOS 15) on MAXSUN MS-Challenger B660M with Intel Core i5-12400F and 51RISC (MSI MECH 2X) AMD Radeon RX 6600.

## Specifications

- **Motherboard**: MAXSUN MS-Challenger B660M
- **CPU**: Intel Core i5-12400F (Alder Lake)
- **GPU**: 51RISC (MSI MECH 2X) AMD Radeon RX 6600 (Navi 23)
- **RAM**: MAXSUN MS-Avenger 32GB DDR4 3200MHz (2x16GB)
- **SSD**: Netac NV7000 1TB NVMe (PCIe 4.0 x4)
- **Wi-Fi/Bluetooth**: Fenvi T919 (BCM94360CD)
- **SMBIOS**: MacPro7,1 (Mac Pro (2019))

## Bootloader

- **OpenCore**: [1.0.3 (Release)](https://github.com/acidanthera/OpenCorePkg)
- **OpenCore Legacy Patcher**: [2.2.0](https://github.com/dortania/OpenCore-Legacy-Patcher)

## Drivers

- **AudioDxe**
- **HfsPlus**
- **OpenCanopy**
- **OpenRuntime**
- **ResetNvramEntry**

## Kexts

- **[AMFIPass](https://github.com/osy/AMFIPass)**
- **[AppleALC](https://github.com/acidanthera/AppleALC)**
- **[CpuTscSync](https://github.com/acidanthera/CpuTscSync)**
- **[IO80211FamilyLegacy](https://github.com/dortania/OpenCore-Legacy-Patcher/tree/main/payloads/Kexts/Wifi)**
- **[IOSkywalkFamily](https://github.com/dortania/OpenCore-Legacy-Patcher/tree/main/payloads/Kexts/Wifi)**
- **[Lilu](https://github.com/acidanthera/Lilu)**
- **[LucyRTL8125Ethernet](https://github.com/Mieze/LucyRTL8125Ethernet)**
- **[NVMeFix](https://github.com/acidanthera/NVMeFix)**
- **[RestrictEvents](https://github.com/acidanthera/RestrictEvents)**
- **[SMCProcessor](https://github.com/acidanthera/VirtualSMC)**
- **[SMCRadeonSensors](https://github.com/ChefKissInc/SMCRadeonSensors)**
- **[SMCSuperIO](https://github.com/acidanthera/VirtualSMC)**
- **[USBMap](https://github.com/corpnewt/USBMap)**
- **[USBWakeFixup](https://github.com/osy/USBWakeFixup)**
- **[VirtualSMC](https://github.com/acidanthera/VirtualSMC)**
- **[WhateverGreen](https://github.com/acidanthera/WhateverGreen)**

## Status

- **Working**: Everything
- **Not Working**: Nothing

## TODO

- [ ] Add BIOS settings
- [ ] Add screenshots

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

# Hackintosh ASUS B360M OpenCore

**macOS Version: Monterey 12.6 (21G115)**

**OpenCore Version: [0.8.0 Offical](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.8.0)**


## Configuration

| Specifications | Detail |
| :------------: | :------: |
| Motherboard | Asus PRIME B360M-A |
| Processor | Intel Core i5-8500 |
| iGPU | Intel UHD Graphics 630 |
| Sound Card | Realtek ALC 887 (Onboard) |
| Ethernet Card | Realtek RTL8111H (Onboard) |

## PlatformInfo (Setting up the SMBIOS info)

**Download CorpNewt's [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)**

**Choose Macmini8,1**

The Type part gets copied to Generic -> SystemProductName

The Serial part gets copied to Generic -> SystemSerialNumber

The Board Serial part gets copied to Generic -> MLB

The SmUUID part gets copied to Generic -> SystemUUID

## BIOS Setting
| Disabled | Enabled |
| :------: | :-----: |
| Fast Boot | VT-x |
| Secure Boot | Above 4G Decoding |
| VT-d | Execute Diable Bit |
| CSM | EHCI/XHCI Handoff |
| Intel SGX | OsType: UEFI |
| Intel Platform Trust | 顯存: 64MB |
| CFG Lock | |

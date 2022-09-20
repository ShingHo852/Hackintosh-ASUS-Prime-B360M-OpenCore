# Hackintosh ASUS Prime B360M OpenCore

**macOS Version: Monterey 12.6 (21G115)**

**OpenCore Version: [0.8.0](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.8.0)**


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

**Macmini8,1 for iGPU**

- The `Serial` part gets copied to Generic -> SystemSerialNumber

- The `Board` Serial part gets copied to Generic -> MLB

- The `SmUUID` part gets copied to Generic -> SystemUUID

## BIOS Setting

- Update to the latest BIOS

- Follow the [guide](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#intel-bios-settings) on OpenCore

Reminder: **Hyper-Threading & Execute Disable Bit** can be ignore if you can't find these options

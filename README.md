# hackintosh-thinkpad-e480
Hackintosh Thinkpad E480 MacOS 11.1 Big Sur 

## Computer Configuration

| Specifications | Details |
|:---|:---|
| Computer Model | ThinkPad E480 (2018) |
| CPU | Intel Core i5-8250U |
| Memory | DDR4 2400 Mhz. 2x4 GB |
| SATA SSD | Manually change to Samsung 860 Evo SATA 1 TB |
| Integrated Graphics | Intel UHD Graphics 620 |
| Ethernet | RTL8168/8111/8112 Gigabit Ethernet Controller |
| Sound Card | Conexant CX20753/4 (layout-id: 15) |
| Wireless Card | Manually change to BCM94352Z (DM1560) |

## Update

### 2021-01-07

* Support MacOS Big Sur 11.1
* Remove SMCSuperIO.kext failed to detect supported SuperIO Chip.
* Remove FakePCIID_Broadcom_WiFi.kext
* Block AirPortBrcm4360_Injector.kext

### 2021-01-06

* Update OpenCore to 0.6.5 to support MacOS Big Sur 11.1
* Update some kexts 
* Add CtlnaAHCIPort.kext MinKernel set to 20.0.0

## Current 
* Currently supports MacOS Catalina 10.15.6 and MacOS Big Sur 11.1.
* Keep up with the times and adopt OC guidance.
* The Cpu driver is loaded normally and the frequency conversion is normal.
* The battery display is normal.
* Wake up from sleep is normal.
* Replace the BCM94352Z network card, Bluetooth, Wireless, Handoff, and AirDrop are normal. Airplay not working.
* The wired network card isn't normal.
* The integrated graphics driver is normal, 4k is normal, and the independent graphics card is blocked.
* The sound card injects id14 and works normally.
* The USB port is normal.

## Recommended BIOS Config

- Security
  - Intel SGX: Disabled
- Boot
  - Boot Mode: Both UEFI and Legacy
  - Boot Priority: UEFI First
  - Fast Boot: Disabled

## Thanks

Thanks to SukkaW (https://github.com/SukkaW/) and Aliyoge (https://github.com/aliyoge/).

> [Personal Website](https://mahron.id) · GitHub [@mahronid](https://github.com/mahronid) · Twitter [@mahronid](https://twitter.com/mahronid) 

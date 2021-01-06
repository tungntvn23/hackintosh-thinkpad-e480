# hackintosh-thinkpad-e480
Hackintosh Thinkpad E480

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

### 2021-01-06

* Update OpenCore to 0.6.5
* Update some kexts 

* Currently supports the latest version 10.15.6.
* Keep up with the times and adopt OC guidance.
* The Cpu driver is loaded normally and the frequency conversion is normal.
* The battery display is normal.
* Wake up from sleep is normal.
* Replace the BCM94352Z network card, Bluetooth, Wireless, and AirDrop are normal (the built-in Realtek 8821CE has no solution).
* The wired network card is normal.
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

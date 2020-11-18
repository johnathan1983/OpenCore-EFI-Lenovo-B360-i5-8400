# OpenCore-EFI-Lenovo-B360-i5-8400
 Stable and self-use OpenCore EFI files for Lenovo B360 and i5-8400.



## Details of the PC Used in Debugging

| Items       | Model               |
| ----------- | ------------------- |
| Motherboard | Lenovo B360         |
| CPU         | Intel Core i5-8400  |
| RAM         | Galax 16G*2 2666 MHz |
| Hard Disk 1 | Hynix 128G M.2 NVMe SSD |
| Hard Disk 2 | Seagate BarraCuda 1T |
| GPU         | AMD Radeon RX5500XT 8G |
| Sound Card  | Realtek ALC235      |
| Ethernet    | Realtek RTL8111     |
| WLAN        | Realtek RTL8821CE   |
| Monitor     | AOC 27-inch QHD     |

## Problems still exist
- ~~Sound Card failed to drive~~
> AppleALC.kext with layout-id 16 is OK.
- WLAN failed to drive
- Bluetooth failed to drive
- ~~Can't turn off the power if you shutdown in macOS~~
> This problem is resolved after I change to OpenCore from Clover.

## Author
ThrRip  
Website (Chinese only): [ThrRip's Personal Homepage](https://thrrip.space)

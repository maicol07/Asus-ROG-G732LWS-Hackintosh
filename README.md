# Asus ROG Strix SCAR G732LWS

EFI folder for MacOS 13 Ventura and 14 Sonoma!

# Specs


| **Name**          | **Description**                  |
| ------------------- | ---------------------------------- |
| Mainboard         | Asus G732LWS                     |
| CPU               | Intel Core i7-10875H (CometLake) |
| IGPU              | Intel UHD 630                    |
| DGPU              | NVIDIA GeForce RTX 2070          |
| Wi-Fi / Bluetooth | Intel AX201 WLAN + Bluetooth 5.0 |
| Ethernet          | Realtek RTL8168/8111             |
| Audio             | Realtek HD Audio ALC294          |
| Touchpad          | ELAN1203                         |

# Features

- [X] **Intel UHD 630**
- [ ] NVIDIA GeForce RTX 2070 **(NOT supported by MacOS/Missing NVIDIA drivers)**
- [X] **Sound**
- [X] **WiFi (Ventura might require an older version of the AirportIntlBw kext)**
- [X] **Bluetooth**
- [X] Apple Store
- [X] USB 3.0
- [X] Adjust brightness
- [X] Fn feature
- [X] Led light keyboard
- [X] Sleep power
- [X] Battery
- [X] Trackpad
- [X] Full cores
- [ ] Temperature (Not tried)
- [ ] System Fan Control (Not tried)
- [X] Disabling discrete graphics GPU
- [ ] Ethernet (Not tried, but it should work)
- [X] Hardware Acceleration
- [ ] Power Management and P-States (Not tried)
- [X] iCloud

# INSTALLATION GUIDE

1. Make a recovery USB using [**gibMacOS**](https://github.com/corpnewt/gibMacOS) or macRecovery from OpenCore.
2. Using [**GenSMBIOS**](https://github.com/corpnewt/GenSMBIOS) or **OpenCore Configurator** or OCAuxiliaryTools to generate new SMBIOS
3. Copy **EFI** folder to your USB.
4. Boot to Mac Recovery using the usb you have just made
5. Turn on Wifi (or use Ethernet) and install macOS on your SSD.
6. Boot to macOS you've installed
7. Follow the dortania guide to copy the EFI into the local EFI partition: [Moving OpenCore from USB to macOS Drive | OpenCore Post-Install (dortania.github.io)](https://dortania.github.io/OpenCore-Post-Install/universal/oc2hdd.html)
8. Restart and enjoy your new hackintosh

***Notes:*** If your pc has different specs, try to read [**OpenCore guide**](https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Configuration.pdf) or [**Dortania guide**](https://dortania.github.io/OpenCore-Desktop-Guide/installer-guide/) for more details

# Known issues

* Booting sonoma may take more time than Ventura

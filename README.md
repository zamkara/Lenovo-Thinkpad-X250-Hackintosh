# Lenovo x250 EFI Opencore

## Specification
Spesifikasi | Keterangan
----------- | -----------
Processor | Intel Core i5-5300U
Integrated Graphics | Intel HD Graphics 5500
Memory | SK-Hynix 8GB DDR3L
Storage 1 | 512GB Toshiba HDD Sata
Storage 2 | 256GB Midasforce M2.2242 SSD
Wireless Card | Intel AC-7265 Dual Band + Bluetooth
Bootloader | OpenCore
Versi Bootloader | v0.7.9

## Screenshot
![img](https://img.shields.io/badge/Last%20Update-March-red) ![img](https://img.shields.io/badge/macOS%20Support-Monterey-purple) ![img](https://img.shields.io/badge/OpenCore%20Version-0.7.9-green)
<p align="left">
<a href="https://raw.githubusercontent.com/zamprjkt/Lenovo-Thinkpad-X250-Hackintosh/Opencore/screenshot/mvdsvcsdv.png" target="blank"><img align="center" src="https://raw.githubusercontent.com/zamprjkt/Lenovo-Thinkpad-X250-Hackintosh/Opencore/screenshot/Jepretan%20Layar%202022-03-30%20pukul%2000.43.29.png" /></a>
</p>

![img](https://img.shields.io/badge/Last%20Update-March-red) ![img](https://img.shields.io/badge/macOS%20Support-Bigsur-blue) ![img](https://img.shields.io/badge/OpenCore%20Version-0.7.9-yellow)
<p align="left">
<a href="https://raw.githubusercontent.com/zamprjkt/Lenovo-Thinkpad-X250-Hackintosh/Opencore/screenshot/2022-03-28.png" target="blank"><img align="center" src="https://raw.githubusercontent.com/zamprjkt/Lenovo-Thinkpad-X250-Hackintosh/Opencore/screenshot/Jepretan%20Layar%202022-03-28%20pukul%2001.14.04.png" /></a>
</p>

<p>You can download the MacOS installation at the following link</p>
##[Click here](https://sharing.zamprjkt.workers.dev/0:/OS/MacOS/)

## MacOS
- Monterey (Tested, OpenCore)
- Bigsur (Tested, OpenCore)
> AirpoAirportitwlm needs to be replaced according to the OS version used, the latest airportitwlm default is Monterey.
> To download Airportitwlm [click here](https://github.com/OpenIntelWireless/itlwm/releases)

# Bios
- `Security -> Security Chip`: **Disabled**;
- `Memory Protection -> Execution Prevention`: **Enabled**;
- `Virtualization -> Intel Virtualization Technology`: **Enabled**;
- `Virtualization -> Vt-directed IO`: **Disabled**;
- `Internal Device Access -> Bottom Cover Tamper Detection`: must be **Disabled**;
- `Anti-Theft -> Computrace -> Current Setting`: **Disabled**;
- `Secure Boot -> Secure Boot`: **Disabled**;
- `UEFI/Legacy Boot`: **UEFI Only**;
- `CSM Support`: **No**.

## What's Working?
- QE/CI Intel HD Graphics 5500 (BigSur,Monterey)
- Power Management (BigSur,Monterey)
- Sleep, Shutdown, Restart (BigSur,Monterey (sleep not tested))
- Audio Speaker & Earphone (BigSur,Monterey)
- Bluetooth (BigSur,Monterey)
- Trackpad, Trackball, Gestures (BigSur,Monterey)
- Indikator baterai (BigSur,Monterey)
- Camera (BigSur,Monterey)
- etc

## Credits:
- [Ikhsaan](https://github.com/exxncss) my cool teacher
- [Friction • RK800](https://t.me/gerobaksariroti) help fix some bugs
- [Irawan](https://t.me/irawansalt)
- [Racka](https://github.com/racka98)
- [Hackintosh Lover](https://t.me/HackintoshLover)

## Download
click the button below to download EFI
<p align="left">
<a href="https://github.com/zamprjkt/Lenovo-Thinkpad-X250-Hackintosh/releases" target="blank"><img align="left" src="https://raw.githubusercontent.com/zamprjkt/Lenovo-Thinkpad-X250-Hackintosh/Opencore/screenshot/down.png" /></a>
</p>

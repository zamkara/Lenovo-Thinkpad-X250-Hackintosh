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
Versi Bootloader | v0.8.6

## Screenshot
<p align="center">
  <kbd><br>M O N T E R E Y 12.6
  <br><br>
  <kbd><img src="https://github.com/zamprjkt/Lenovo-Thinkpad-X250-Hackintosh/raw/Opencore/screenshot/Screen%20Shot%202022-09-21%20at%2018.07.19.png"/></kbd></kbd>
  <br><br>
<p align="center">
  <kbd><br>B A T T E R Y
  <br><br>
  <kbd><img src="https://raw.githubusercontent.com/zamprjkt/Lenovo-Thinkpad-X250-Hackintosh/Opencore/screenshot/Jepretan%20Layar%202022-04-05%20pukul%2005.59.36.png"/></kbd></kbd>
</p>
<p align="center">
  <kbd><br>S O U N D
  <br><br>
  <kbd><img src="https://raw.githubusercontent.com/zamprjkt/Lenovo-Thinkpad-X250-Hackintosh/Opencore/screenshot/Jepretan%20Layar%202022-04-05%20pukul%2005.55.56.png"/></kbd></kbd>
</p>

### GetMacOS
You can download the MacOS installation at the following link, [`Download Here`](https://www.olarila.com/topic/6278-new-vanilla-olarila-images/)

## MacOS
- Monterey (Tested, OpenCore)
- Bigsur (Tested, OpenCore)
> AirpoAirportitwlm needs to be replaced according to the OS version used, the latest airportitwlm default is Monterey.
> To download Airportitwlm [`click here`](https://github.com/OpenIntelWireless/itlwm/releases)

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
- QE/CI Intel HD Graphics 5500 `BigSur` `Monterey`
- Power Management `BigSur` `Monterey`
- Sleep, Shutdown, Restart `BigSur` `Monterey` `[sleep not tested]`
- Audio Speaker & Earphone `BigSur` `Monterey`
- Bluetooth `BigSur` `Monterey`
- Trackpad, Trackball, Gestures `BigSur` `Monterey`
- Indikator baterai `BigSur` `Monterey`
- Camera `BigSur` `Monterey`
- etc

# Tips 

Help Fix Screen Sleep

```bash
sudo pmset autopoweroff 0
sudo pmset powernap 0
sudo pmset standby 0
sudo pmset proximitywake 0
sudo pmset tcpkeepalive 0
```

This will do 5 things for us:

- `Disables` **autopoweroff**: This is a form of hibernation
- `Disables` **powernap**: Used to periodically wake the machine for network, and updates(but not the display)
- `Disables` **standby**: Used as a time period between sleep and going into hibernation
- `Disables` wake from iPhone/Watch: Specifically when your iPhone or Apple Watch come near, the machine will wake
- `Disables` **TCP Keep Alive** mechanism to prevent wake ups every 2 hours

## Credits:
- [Ikhsaan](https://github.com/exxncss) my cool teacher
- [Friction • RK800](https://t.me/gerobaksariroti) help fix some bugs
- [Irawan](https://t.me/irawansalt)
- [Racka](https://github.com/racka98)
- [Vcyzteen](https://github.com/vcyzteen) wallpaper on Post
- [Hackintosh Lover](https://t.me/HackintoshLover)

## Download
click the button below to download EFI
<p align="left">
<a href="https://github.com/zamprjkt/Lenovo-Thinkpad-X250-Hackintosh/releases" target="blank"><img align="left" src="https://raw.githubusercontent.com/zamprjkt/Lenovo-Thinkpad-X250-Hackintosh/Opencore/screenshot/down.png" /></a>
</p>

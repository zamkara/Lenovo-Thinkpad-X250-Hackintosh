<p align="center">
 <img src="https://github.com/zamkara/Lenovo-Thinkpad-X250-Hackintosh/blob/Opencore/screenshot/Banner.webp" align="center" alt="ROG-STRIX-G513QC" />
 <h2 align="center">Lenovo ThinkPad X250</h2>
 <p align="center">OpenCore Config for Lenovo ThinkPad X250 🍏</p>

<br><br>

<img src="https://github.com/zamkara/Lenovo-Thinkpad-X250-Hackintosh/blob/Opencore/screenshot/Screenshot%202024-02-14%20at%2017.54.38.png" alt="img" align="right" width="350px">
<br/><br/>

## Disclaimer ⚠️

This EFI is based in [olarila](https://olarila.com/files/OPENCORE1/EFI.Opencore.NoteBook.Broadwell.zip) and [exxncss](https://github.com/exxncss/x250-hackintosh) repository, go and support them. This repository couldn't be done without their work any suggestion is acepted to improve the files.
<br>

## Configuration  
| **Category**   | **Details**                               |
| -------------- | ------------------------------------------|
| CPU            | Intel Core i5-5300U                       |
| GPU            | Intel HD Graphics 5500                    |
| Memory         | Kingston 8GB DDR3L                        |
| Storage 1      | 256GB Midasforce M2.2242 SSD              |
| Storage 2      | 512GB Toshiba HDD Sata                    |
| Wifi           | Intel AC-7265 Dual Band + Bluetooth       |

</p>

## Screenshot
<p align="center">
  <kbd><br>V E N T U R A 13.6.4
  <br><br>
  <kbd><img src="https://github.com/zamkara/Lenovo-Thinkpad-X250-Hackintosh/blob/Opencore/screenshot/Screenshot%202024-02-14%20at%2005.50.22.png"/></kbd></kbd>
  <br><br>

> [!Warning]
> When installing or updating the system, be sure to make sure and replace some kext that matches your macOS version, otherwise, some components will not run properly.

<a href="https://github.com/zamprjkt/Lenovo-Thinkpad-X250-Hackintosh/releases" target="blank"><img align="left" width="300px" src="https://github.com/zamkara/Lenovo-Thinkpad-X250-Hackintosh/blob/Opencore/screenshot/download.svg" /></a>
Download the MacOS installation at the following link, [`Download Here`](https://www.olarila.com/topic/6278-new-vanilla-olarila-images/), Or download it from the macOS terminal directly by following this guide [`osxdaily`](https://osxdaily.com/2020/04/13/how-download-full-macos-installer-terminal/)

<br><br>
## MacOS
- Ventura (Tested, OpenCore)
- Monterey (Tested, OpenCore)
- Bigsur (Tested, OpenCore)
> AirpoAirportitwlm needs to be replaced according to the OS version used, the latest airportitwlm default is Ventura.
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
- QE/CI Intel HD Graphics 5500 `BigSur` `Monterey` `Ventura`
- Power Management `BigSur` `Monterey` `Ventura`
- Sleep, Shutdown, Restart `BigSur` `Monterey` `Ventura`
- Audio Speaker & Earphone `BigSur` `Monterey` `Ventura`
- Bluetooth `BigSur` `Monterey` `Ventura`
- Trackpad, Trackball, Gestures `BigSur` `Monterey` `Ventura`
- Indikator baterai `BigSur` `Monterey` `Ventura`
- Camera `BigSur` `Monterey` `Ventura`
- etc

## Credits:
- [Ikhsaan](https://github.com/exxncss)
- [Friction • RK800](https://t.me/gerobaksariroti)
- [Irawan](https://t.me/irawansalt)

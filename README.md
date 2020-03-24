# EFI Partition for Mojave/Catalina

## What's Working
- Everything except audio (Displayport audio works tho)

## Specs
- CPU: **i7-7700k**
- GPU: **Sapphire AMD RX 580 8Gb**
- Motherboard: **MSI Z270 Gaming Pro Carbon**
- Disk: **Samsung 850 EVO**
- Bluetooth Dongle: **Off-brand Bluetooth 4.0**
- Monitor: **LG 29UM68-P**
- Bootloader: Clover 5103 using [Dids' repo](https://github.com/Dids/clover-builder)
- Kexts: latest applied from this [OneDrive folder](http://kexts.goldfish64.com/)

## Instructions:
- Create a USB Installer according to [Vanilla guide](https://hackintosh.gitbook.io/-r-hackintosh-vanilla-desktop-guide/)
- Copy the EFI from this repo in the installer's EFI partition
- Install OS
- Mount EFI partition of the system
- Copy the EFI in the EFI partition of the system

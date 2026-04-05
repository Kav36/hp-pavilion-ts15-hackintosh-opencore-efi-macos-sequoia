# Hackintosh EFI for HP Pavilion TS 15 (n230tx) – macOS Sequoia 15.7 | OpenCore

This repository provides a **fully working Hackintosh EFI** for installing and running **macOS Sequoia 15.7** on the **HP Pavilion TS 15 (n230tx)** laptop.

Designed for **Haswell-based systems** with:
- Intel Core i5-4200U  
- Intel HD 4400 Graphics (OCLP patched)  
- NVIDIA GT 740M (disabled)  

This EFI is based on the **OpenCore bootloader** and follows the **Dortania guide**, making it suitable for both **installation and daily use**.

---

## System Compatibility

- **Model:** HP Pavilion TS 15 (n230tx)  
- **CPU:** Intel Core i5-4200U (Haswell)  
- **iGPU:** Intel HD 4400 (patched with OCLP)  
- **dGPU:** NVIDIA GT 740M (not supported in macOS)  
- **macOS Version:** Sequoia 15.7  

---

## Working Features

The following components are tested and working:

- Intel HD 4400 Graphics (OCLP patched acceleration)  
- Keyboard & Trackpad  
- Touchscreen  
- Audio (AppleALC)  
- Ethernet (RealtekRTL8100)  
- SATA & Internal Storage  
- Brightness Keys *(slider may appear greyed out)*  

---

## EFI Folder Structure

### EFI (Main)
- Use this **after installing macOS**
- Copy to your EFI partition for **daily booting**

### EFI - Booted
- Used during **macOS installation**
- Known working configuration for initial setup

---

## Tools & Technologies

- OpenCore Bootloader  
- OpenCore Legacy Patcher (OCLP)  
- AppleALC (Audio)  
- RealtekRTL8100 (Ethernet)  

---

## Guides & Credits

- [Dortania OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)  
- [OpenCore Legacy Patcher (OCLP Team)](https://github.com/dortania/OpenCore-Legacy-Patcher)  

---

## Disclaimer

This project is for **educational purposes only**.

- Not affiliated with or endorsed by Apple Inc.  
- All trademarks belong to their respective owners  
- No macOS binaries or copyrighted Apple files are included  

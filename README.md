# Bambu Lab A1 Firmware & Configuration

![Image](https://github.com/user-attachments/assets/5cec90d7-92d0-4cfe-87ec-663438edcd18)

This repository contains custtom optimized print profiles & the last known version of the Bambu Lab A1 firmware that allows unrestricted access for third-party applications and speed up configuration for printing faster.

As of firmware versions after 01.04, Bambu Lab introduced restrictions that limit third-party software access unless connected via their Connect software. This version maintains full functionality for offline use and compatibility with third-party applications such as:

- OrcaSlicer
- Home Assistant integrations
- Custom print servers and scripts

## 🎯 Print Profiles for PETG/COPET (LBL)

This repository includes two finely tuned print profiles(Orca slicer) for **PETG/COPET LBL** (https://lbl-corp.com/) filament, optimized for Bambu Lab A1:

### 🔹 `PETG_COPET_LBL_BASE` – Balanced Performance & Quality

- **Speed**: +30% faster than stock PETG profiles without loss of quality
- **Quality**: Maintains excellent surface finish and dimensional accuracy
- **Use case**: Ideal for functional parts, visual models, and production-quality prints
- **Details**: nozzle 0.4, t/hotend - 245, t/bed - 70, layer width 0.4, layer height 0.2, maximum volume flow 12mm3/sec

### 🔹 `PETG_COPET_LBL_HYPER` – High-Speed Prototyping

- **Speed**: +170% faster than stock 0.2 PETG profiles
- **Quality**: Acceptable for drafts, fittings, and rapid iteration
- **Use case**: Best suited for early-stage prototyping where speed is critical,
- **Details**: nozzle 0.4, t/hotend - 255, t/bed - 70, layer width 0.4-0.6, layer height 0.28, maximum volume flow 23mm3/sec

Both profiles are designed to leverage the A1's motion system while ensuring optimal extrusion, cooling, and layer adhesion specific to LBL-grade PETG/COPET filament.
To improve print quality, **please calibrate the K-factor after setup.**

## 🔧 How to Install firmware

To install the firmware from this repository, follow these steps based on the official documentation:

1. **Download the Firmware folder**

   - Use the `firmware folder` folder provided in this repository and copy zip folder to the root directory of a microSD card (FAT32 format).

2. **Prepare the Printer**

   - Turn off the Bambu Lab A1 printer.
   - Insert the microSD card into the printer's card slot.

3. **Update the Firmware**

   - Power on the printer.
   - Settings > Firmware > Update Offline
   - Confirm the update and wait until the process completes.

4. **Post-Update**
   - Once the update is finished, the printer will reboot.
   - You can now use your printer with full access.

> For detailed step-by-step guide, refer to the official documentation:
> https://wiki.bambulab.com/en/a1/manual/a1-firmware-update-from-SD-card

## 📦 Navigation

- `/firmware` – folder with verified firmware
- `/orca-profile` – optimized configuration for printing

## 📚 Official Firmware Info

For a complete list of firmware versions and official changelogs, visit:
https://wiki.bambulab.com/en/a1/manual/a1-firmware-release-history

---

**Preserve functionality. Enable freedom.**

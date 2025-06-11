# Bambu Lab A1 Firmware & Configuration

![Image](https://github.com/user-attachments/assets/5cec90d7-92d0-4cfe-87ec-663438edcd18)

This repository contains the last known version of the Bambu Lab A1 firmware that allows unrestricted access for third-party applications and speed up configuration for printing faster.

As of firmware versions after 01.04, Bambu Lab introduced restrictions that limit third-party software access unless connected via their Connect software. This version maintains full functionality for offline use and compatibility with third-party applications such as:

- OrcaSlicer
- Home Assistant integrations
- Custom print servers and scripts

## 🔧 How to Install

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
- `/orca-config` – optimized configuration for printing

## 📚 Official Firmware Info

For a complete list of firmware versions and official changelogs, visit:
https://wiki.bambulab.com/en/a1/manual/a1-firmware-release-history

---

**Preserve functionality. Enable freedom.**

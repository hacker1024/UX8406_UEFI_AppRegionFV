# UX8406 UEFI App Region Firmware Volume

This repository contains files extracted from the UEFI firmware volume
containing applications and drivers used by the ASUS Zenbook Duo (2024) UX8406.

## Extraction guide

1. Download the ["BIOS for ASUS EZ Flash Utility"](https://www.asus.com/laptops/for-home/zenbook/asus-zenbook-duo-2024-ux8406/helpdesk_bios?model2Name=UX8406MA)
2. Extract the firmware components using the [AMI BIOS Guard Extractor](https://github.com/platomav/BIOSUtilities#ami-bios-guard-extractor)
3. Using the [Ghidra Firmware Utilities](https://github.com/al3xtjames/ghidra-firmware-utils) extension, export the files from the image in the `4f1c52d3-d824-4d2a-a2f0-ec40c23c5916` volume

   ![](https://github.com/hacker1024/UX8406_UEFI_AppRegionFV/assets/20849728/a782c770-1cbe-4dfd-8133-49941b1eedb7)
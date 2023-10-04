Why need to install display GPi Case patch for Retropie and Recalbox? 
Because Retropie and Recalbox system default display output is HDMI, GPi Case need to transfer display output to GPIO then can work correctly.

For Windows:
Install display patch for GPi Case
1. Copy CPi_Case_patch folder to SD root.
2. Enter GPi_Case_patch folder and run install_patch.bat
3. Patch done. SD card can be used for GPi Case cartridge.

Uninstall patch can transfer to HDMI output again
1. Enter GPi_Case_patch folder and run uninstall_patch.bat
-------------------------------------------------------------------------------
For MacOS/Linux:
1. Backup config.txt to a safe place.
2. Copy /GPi_Case_patch/patch_files/config.txt to SD card root.
3. Copy /GPi_Case_patch/patch_files/overlays/dpi24-GPI2W.dtbo and pwm-audio-pi-zero.dtbo to SD card /overlays folder.

Want to transfer to HDMI output again?
1. Copy the backup config.txt to SD card root.

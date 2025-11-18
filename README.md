# MAVERICK STORM1 FLEX

## Software Versions

[V1.251024 - Maverick Storm 1 Flex](https://github.com/Chauvet-Pro/MAVERICKSTORM1FLEX/blob/6284fcdc2dc532411d7b9f725dddceb1d11b6203/firmware/V1.251024.zip)
- Added Sky Tracker mode

[V1.250813 - Maverick Storm 1 Flex](https://github.com/Chauvet-Pro/MAVERICKSTORM1FLEX/blob/dce1ec0867ee3b310fc7dddb6c0c6bb816bdb5b7/firmware/V1.250813.zip)
- Fix the issue that ArtNet and sACN has no control
- Change ArtNet universe to be 32767 in webserver 
- Change address in webserver to be input box

[V1.250331 - Maverick Storm 1 Flex](https://github.com/Chauvet-Pro/MAVERICKSTORM1FLEX/blob/da54a4dae1a3994502c62035eda56ffb52e86313/firmware/V1.250331.zip)
- Released initial software version

  &nbsp; 

## USB Software Update Instructions
1. Power on the product and plug the flash drive into the USB port.
2. Go to settings and select “USB Update” then “Update me”
3. The next screen will show the software versions available for this fixture on the USB drive. For multiple versions of the software for the same fixture, use or to select the 
desired version.
4. The software Version you selected will reappear and ask to confirm “Yes or No”
5. The upgrade will start. DO NOT turn off the power or disconnect the USB while the USB LED is still blinking during the process. The screen display will read: “USB Update 
Wait”. USB update can take several minutes to complete.
   >When the USB firmware is done uploading, in some fixtures the display will change to: “**DO NOT UNPLUG, UPDATING**”.
6.	When the update is completed, the fixture will automatically reboot.
7.	Go to Fixture Information on the product’s menu map and confirm the firmware revision.
8.	When the boot-up process is finished, restart the product.

### Special Notes
* Place the .chl file in the root directory of the USB drive.
* The product's USB port supports up to 32GB capacity and only works with the FAT32 file format.
* It is possible to update multiple units with the USB if they are daisy-chained via DMX.
* Turning off the power or removing the USB while still blinking during the update will cause partial or total firmware failure in the targeted fixture(s). If this occurs, the user will need the UPLOAD 08 device to fix this.

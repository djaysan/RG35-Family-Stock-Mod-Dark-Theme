**A theme for Anbernic Rg35xx H & family**
Simply drag and drop to your "Roms" folder and merge the content.
Navigate to Apps and look for "**Theme - Absolute Black**"
Your new theme will instal with a useful RA shortcut screen on loading, cool gamboi logo at startup etc...

**Theme Preview:**

![Theme - Absolute Black](https://github.com/user-attachments/assets/989aaf62-c215-43ca-89c5-624f8c410bdc)


**RA shotcuts loadscreen:**

![Loading RA Shortcuts](https://github.com/user-attachments/assets/a483e3a8-90f0-4547-8c1b-cf3aa2c23907)

**Boot screen:**

![Boot](https://github.com/user-attachments/assets/40a4450c-9727-4779-8602-4c562e46b286)

**Install Stock Mod from here**: https://github.com/cbepx-me/Anbernic-H700-RG-xx-StockOS-Modification
If you are on Mac, use balena etcher and follow these steps: https://github.com/cbepx-me/Anbernic-H700-RG-xx-StockOS-Modification/issues/68
Pretty easy and straightforward:
Before flashing, take note of the drive letter (mine is dev/disk2 so i will use **disk2** in my example.
When Balena Etcher is done flashing & verifying, Open your terminal and enter these:

**sudo gdisk /dev/disk2**

Press enter and it will ask for your mac user password
Then enter the commands:

**p** to view the partition table. It should look similar to the one in the screenshot below

**x** for expert mode

**e** for relocating the backup data structure to the end of the disk

**w** to write the changed data

**y** to confirm you want to write

After that you can eject the disk and continue on the device.



Interested in Syncthing? 
**Install SSH from here:**:

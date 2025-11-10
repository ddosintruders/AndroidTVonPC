# Android TV on PC - Tutorial Made by ddosintruders

This project's base items and steps are provided by TulioDomingos and ISO files are provided by hmtheboy154

## Tutorial - Windows - Android TV on a USB Storage Medium

1. If Secure Boot is enabled on your system, disable it by going into your computer's BIOS and disable it.
2. Use a flash drive. (4GB is minimum, 32GB and 64GB is ideal). Use a USB 3.0 Flash Drive for faster and smoother experience.
3. Grab a copy of the latest Android TV ISO image from https://android-tvno-pc.my.canva.site/ and download it.
4. Grab a copy of Rufus from https://rufus.ie
5. Grab a copy of half of the storage device in the Storages folder of this repo (for example, if you have 32GB flash drive, grab the 16GB storage zip file)
6. Insert your USB and open Rufus.

### For Storage Mediums upto 4GB

1. Open Rufus, select your USB and head over to 'Boot Selection' and select 'Disk or ISO image' and next to it at the end, select the Android TV ISO file you downloaded.
2. Set 'Partition Scheme' to MBR or GPT. MBR is to be used in Legacy BIOSes and GPT for UEFI Systems. See 'System Information' on Windows to determine BIOS type.
3. You can give any name to the 'Volume Label' and select 'Start' to begin flashing of the USB device.
4. After the flahing is done, extract from the zip file of the storages you downloaded, and cut the 'data.img' file.
5. Once complete, open the root directory of your USB file, and paste in the 'data.img' file.
6. Boot from the USB by going into your BIOS Boot Selection and select the USB drive. If a Security Violation error pops up, confirm Secure Boot is disabled.
7. A splash screen with kernel versions will pop up. If you are using a laptop, select the first option you get. If you are using a desktop or similar, scroll down and select the kernel with has '(External Display)' beside it.
8. Test the Android TV's memory by installing apps or games, then rebooting back to the USB and see if the apps or games are still there. If not, check the 'data.img' file discussed in Step 4 and 5.

### For Storage Mediums above 4GB (8GB, 16GB, 32GB, 64GB, 128GB)

If you noticed, Android TV is written in FAT32, which means your maximum storage is 4GB due to FAT32's filesize limit. Microsoft made exFAT to overcome FAT32's filesize limit, so we will use that.

1. Open Rufus, select your USB and head over to 'Boot Selection' and select 'Disk or ISO image' and next to it at the end, select the Android TV ISO file you downloaded.
2. You will see a Persistence Partition Size beneath the selected USB Storage, drag the slider to the very end to allocate the maximum partiton image.
3. Set 'Partition Scheme' to MBR or GPT. MBR is to be used in Legacy BIOSes and GPT for UEFI Systems. See 'System Information' on Windows to determine BIOS type.
4. You can give any name to the 'Volume Label' and select 'Start' to begin flashing of the USB device.
5. After flashing, go to Disk Management or 'Create and format hard drive partitons' by searching it on your taskbar.
6. After opening it, you should see your USB drive will have 2 partitons, one will be FAT32 and the other will have an unrecognized filesystem (which is Persistence)
7. Select the larger partiton which we made the persistence for, right click it and select 'Delete Volume'
8. After the volume is deleted, right click on the same deleted partiton and select 'Create New Volume'
9. Follow the steps until you are given the option to choose a filesystem. Format it to FAT32.
10. After, right click on the same partiton and select 'Format'. This should give you an option to select the filesystem. Select the exFAT filesystem and let it format.
11. After the format is finished, go to your USB in File Explorer, you should see 2 partitions. Go to the FAT32 partiton.
12. You should see a file named 'system.sfs'. Cut it, and paste it in the exFAT partiton we made.
13. Now go to the Storage zip file you downloaded, extract it and place the 'data.img' file to the exFAT partition.
14. Your USB is now set to be used. Refer to the previous tutorial for 4GB Storage Mediums from Step 6 to 8

You should have a functional Android TV on a USB drive.


## Tutorial - Windows - Android TV on your PC's internal drive (To be updated)


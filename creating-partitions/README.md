# Creating Partitions | Sabian's I.T. HelpDesk
## "Partition" means to divide something. A "partition" is a divided part of that something.

With Internal Storage Devices, such as Hard Drives and Solid State Drives, and External/Removable Storage Devices, such as USB Drives and SD Cards, you have the ability to "partition" the one storage device into two or more. Doing this on Windows 10 is simple.

# How to Partition a Drive
1. Open the Start menu, type `control` and open the **Control Panel.**
2. On the Control Panel, go to **System and Security.**
3. Under **Administrative Tools,** select **Create and formart hard disk partitions.** If UAC asks **Yes** or **No,** select **Yes.**
4. In the **Disk Management** window, select the Disk you want to partition. You can identify it using its name and letter.
5. Right click the drive's volume and select **Shrink Volume.** 
The size of the volume is told in megabytes, so you can Google "mb to gb" to work it out in gigabytes. If you want two partitions, halve it. If you want three, get a third of it and create another two volumes with the same value. Obviously you get the idea.
6. When you shrink a volume, you will have some unallocated space. To allocate this, right-click on the unallocated storage and select **Create Volume.**
7. When you create a volume you'll be asked what to label it and to format it. If you're using an Internal Storage Device, format it to NTFS. If you're using an External/Removable Storage Device, I recommend you format it to **FAT32,** since then it will work with most devices such as the *Nintendo Wii,* TVs, DVD Players and, of course, PCs that don't work with NTFS as well as Windows such as Apple iMacs and some Linux distros. If you plan to only use it on Windows, however, and you also plan to install apps on it, format it to **NTFS.**

That's it! Now your drive should be split into multiple volumes.

If you think I missed anything, or you want to suggest a new tutorial, E-Mail me at [sabianroberts@gmail.com](mailto:sabianroberts@gmail.com).

Copyright © 2020 Sabian Roberts All Rights Reserved. "Sabian's IT Desk" is licensed under the BSD-3-Clause license.

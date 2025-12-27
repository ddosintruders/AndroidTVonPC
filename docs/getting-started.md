---
icon: material/star-three-points-outline
---

### Prerequisites

Before we dive into the technical stuff, you need the following:

!!! info "A PC"
    
    I won't be exact on the PC, any can work as long as it has Secure Boot disabled and has UEFI support. I have only tested this on UEFI systems, so I am unfamiliar with a Legacy BIOS system.
    You can check if your computer has these, using the following:
    === "Windows"

        Go to the Windows search bar or hitting the Windows Icon on your keyboard, search ```System Information``` and hit Enter. A window should open up and look for the fields
        saying ==BIOS Mode== and ==Secure Boot State==. BIOS State should read ```UEFI``` and Secure Boot State should read ```Off```
    === "How to disable Secure Boot"
        This is mostly done in the UEFI Settings of your system, so it's vendor-specific and different OEMs use different names and grouping, so you can search for your manufacturer's guide or a general guide on the internet.
    === "For extra functionality"
        Bluetooth Support

2. A Storage Medium. Select from the subheading.
-  [Rufus](https://rufus.ie) for making the bootable medium for both USB and External Storages.
-  A copy of [Android TV on PC](https://android-tvno-pc.my.canva.site) from Bruno's site
-  One of the Storages found [in this folder of my repo](https://github.com/ddosintruders/AndroidTVonPC/tree/main/Storages) that aligns with half of your storage medium's capacity (Example: If you have 4GB Capacity, use 2GB Data Storage)
        
#### Storage Medium Selection

Selecting a Storage Medium depends on your use case.

=== "USB Flash or Pendrive"
    1. Must be USB 3.0 for fast and responsive system.
    2. Must be greater or equal to 4GB in storage (32GB and 64GB are highly recommended)
=== "External Harddrive or SSD"
    1. Basics Storages are greater than 128GB or equal, so make sure it aligns in the same space.
=== "Internal Drive"
    1. For this, we will have to partition off from your exisiting internal storage, so skip the USB technique, and go to the [Internal Storage Setup](Setup and Installation/making-the-internal-drive.md) section to continue. Make sure to grab the [32GB Storage ISO file](https://github.com/ddosintruders/AndroidTVonPC/blob/main/Storages/DATA-32GB-EXT4.zip)

<div align=center>
  <script type='text/javascript' src='https://storage.ko-fi.com/cdn/widget/Widget_2.js'></script><script type='text/javascript'>kofiwidget2.init('Support me on Ko-fi', '#72a4f2', 'I2I51O7J3E');kofiwidget2.draw();</script> 
</div>
<p align="center">
 <img src="https://raw.githubusercontent.com/BatikRecovery/br_manifest/br/batik-recovery.png" > 
</p>

Overview
=======

Batik Recovery is Project Recovery developed by Batik Recovery Teamwork from Indonesia, this Batik Recovery is a derivative of the Official TWRP that was modified by the developer in accordance with the Indonesian characteristics. In Indonesia, batik is a motif that is considered quite famous for the beauty of its art. Therefore, the developer gave the name Batik Recovery and a touch of batik motifs in the Recovery, including splash, background, and icon. The goal of the developer to release the project is to further popularize batik, and especially to popularize the name of Indonesia.

Features
=======

* Support Treble (Vendor) or Non Treble
* Support GSI, Android Pie
* Support Miui OTA
* Support F2fs
* Ramdisk Cleaner
* Enable / Disable HAL3
* App Delete
* Enable / Disable Navbar
* Del Subs Overlay
* Lazy Flasher
* Reset Password
* Aroma FM
* Root / Unroot Magisk
* Mount Magisk
    
Changelog
=======    

~ Alpha-01 ~
* Initial Build

~ Alpha-02 ~
* Add Fitured

~ B v1.1 ~
* Upstreamed base TWRP 3.2.3-0
* Update Batik Theme v1.1
* Update Magisk 16.71
* Add Indonesia, Sunda Language
 
~ B 1.2 ~
* Overlay Reboot Menu
* Add some icon style
* Update Magisk 17.1
* Add Jowo Language
* Full Backup / Restore Partition
* Further ensure TWRP is not replaced by stock recovery
 
~ B 1.3 ~			
* Add Square Style, Circle Style Icon
* Add Change Color Theme (Header & Navbar)
* Change Themes without Reboot
* Update Magisk 17.2
* Add Mount Magisk (Tools)
* Merge September Security Patch (android-8.1.0_r46)	

~ S 1.4 ~

Changelog Xiaomi :
* Add Wipe Substratum on Page Wipe
* Add Automatic Disable DM-Verity
* Add OTA MIUI Support
* Update Magisk 17.3
* Update October Security Patch

Changelog Asus :
* Add Wipe Substratum on Page Wipe
* Update Kernel
* Update Magisk 17.3
* Fix Overlay on Menu Reboot
* Merge October Security Patch (android-8.1.0_r47)

Credits
=======
* [**TEAMWIN RECOVERY PROJECT (BASE)**](https://github.com/TeamWin)
* [**OMNIROM**](https://github.com/omnirom)
* [**REDWOLF RECOVERY PROJECT**](https://github.com/RedWolfRecovery)
* [**PITCHBLACK RECOVERY PROJECT**](https://github.com/PitchBlack-Recovery)
* [**DARK RECOVERY PROJECT**](https://github.com/DarkRecovery)
* [**ORANGEFOX RECOVERY PROJECT**](https://gitlab.com/OrangeFox)

Donation
=======

If you feel satisfied with the results of my work, and support my project so that it can be more developed, please donate to the BRI account, with the account number 3112-01-019706-53-4 in the name of "Muhammad Rifa'i Aziz" or through paypal - http://paypal.me/zhantech

* Join on grup ZHAN Project Tester and Report - http://t.me/ZHANreport
* Follow My Instagram - https://www.instagram.com/zhantech
* Like My Facebook Fan Page - https://m.facebook.com/zhantech


Getting Started
===============

To get started with OMNI sources to build TWRP, you'll need to get
familiar with [Git and Repo](https://source.android.com/source/using-repo.html).

Make Directory 

```bash
     mkdir <source-dir>
     cd <source-dir>
```

(For Example : batik)

```bash
     mkdir ~/batik
     cd ~/batik
```

To initialize Batik Recovery local repository, use this command :
```bash
    repo init -u git://github.com/BatikRecovery/br_manifest.git -b br
```

For Asus Device :

```bash
    repo init -u git://github.com/BatikRecovery/br_manifest.git -b br-asus
```

To initialize a shallow clone, which will save even more space, use a command like this:
```bash
    repo init --depth=1 -u git://github.com/BatikRecovery/br_manifest.git -b br
```

For Asus Device :

```bash
    repo init --depth=1 -u git://github.com/BatikRecovery/br_manifest.git -b br-asus
```

Then to sync up :
```bash
    repo sync
```

 Clone Device Tree Of Batik Recovery
=============================

Ceck on https://github.com/BatikRecovery/br_devices for your device

Example :

```bash
    git clone https://github.com/BatikRecovery/br_devices.git -b santoni device/xiaomi/santoni
```

 Compilation Of Batik Recovery
=============================
 
```bash
     cd <source-dir>
     export ALLOW_MISSING_DEPENDENCIES=true
     . build/envsetup.sh
```     
     
Change Maintainer
```bash
     export BR_MAINTAINER="your-name"
```
 
```bash
     lunch omni_<device>-eng
     mka recoveryimage
```

If it fails to compile
```bash
     export LC_ALL=C
```

[![Download BATIK-RECOVERY](https://a.fsdn.com/con/app/sf-download-button)](https://sourceforge.net/projects/batik-recovery/files/latest/download)

<p align="center">
 <img src="https://github.com/BatikRecovery/br_manifest/blob/br/batik-recovery.png" > 
</p>

Overview
=======

Batik Recovery is Project Recovery developed by Batik Recovery Teamwork from Indonesia, this Batik Recovery is a derivative of the Official TWRP that was modified by the developer in accordance with the Indonesian characteristics. In Indonesia, batik is a motif that is considered quite famous for the beauty of its art. Therefore, the developer gave the name Batik Recovery and a touch of batik motifs in the Recovery, including splash, background, and icon. The goal of the developer to release the project is to further popularize batik, and especially to popularize the name of Indonesia.


Features
=======

* Support Treble or Non Treble
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
    
Changelog
=======    

* Add Square Style, Circle Style Icon
* Add Change Color Theme (Header & Navbar)
* Change Themes without Reboot
* Update Magisk 17.2
* Add Mount Magisk (Tools)
* Merge September Security Patch (android-8.1.0_r46)

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

Exemple :

```bash
    repo clone git:https://github.com/BatikRecovery/br_devices -b santoni device/santoni
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

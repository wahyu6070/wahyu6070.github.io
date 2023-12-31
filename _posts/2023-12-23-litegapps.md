---
layout : post
type   : 
title  : LiteGapps Best Custom Gapps Android
date   : 2023-12-23
slug   : litegapps
categories: [Gapps]
tags      : [magisk, gapps, ksu, custom gapps, myproject]
keywords  : [magisk module, litegapps, lite gapps, Kernelsu]
author : wahyu6070
opengraph:
toc    :
excerpt:
ads: true
---


Google Apps is a collection of Google applications which are quite important in everyday life, for example every day we use applications such as YouTube to play videos, Google Translate to translate languages, Google Chrome for web browser browsing.  So Google Apps is important to install on our smartphones, especially for Android users.

Basically, Google Apps is installed on the stock ROM (vendor's default ROM) but there are also some that don't have Google Apps installed due to policy reasons or other reasons, for example **MIUI CHINA** and some custom ROMs such as Lineage OS or others.

So this time I will discuss Gapps (Google Apps) custom which is quite popular among the Android community, namely LiteGapps, let's review this interesting project.

litegapps is a dedicated gapps open source project developed by senior member xda-developer @wahyu6070, this project focuses on a minimal, efficient and complete gapps, capable of handling a wide range of user cases.  Litegapps has unique installation modes namely ``systemless`` and ``non systemless``, let's discuss more about these two modes:

#Systemless

The installation mode that installs on an Android partition fakely (files are not installed natively on the partition) uses the **Magisk module** or **KSU module** installation system which can even make fake modifications to the read only partition.

### Non systemless

namely the normal/old installation mode which installs files directly into the Android partition (files are installed natively), so to use this mode the Android partition must be able to read/write into the partition in order to modify or install Google Apps files.

*So which is better, systemless and non-systemless*


Both are actually the same depending on which mode we use and which is suitable for the ROM we use.

Litegapps offers 5 products to fulfill various cases of Google Apps on Android, namely: **litegapps**,**litegapps++**,**litegapps addon**,**litegapps remover**,**litegapps controller**.

## LiteGapps

**Regular LiteGapps** is the first product to offer complete Android version and architecture support, apart from that LiteGapps also provides 8 variants: ``Lite``,``Core``,``User``,``Go``  ,``Basic``,``Nano``,``Micro``,``Pixel``.

### link

Android 14.0 - [arm64](https://sourceforge.net/projects/litegapps/files/litegapps/arm64/34/) - [arm](https://sourceforge.net/projects/litegapps/files/litegapps/arm/34/)

Android 13.0 - [arm64](https://sourceforge.net/projects/litegapps/files/litegapps/arm64/33/) - [arm](https://sourceforge.net/projects/litegapps/files/litegapps/arm/33/)

Android 12.1 - [arm64](https://sourceforge.net/projects/litegapps/files/litegapps/arm64/32/) - [arm](https://sourceforge.net/projects/litegapps/files/litegapps/arm/32/)

Android 11.0 - [arm64](https://sourceforge.net/projects/litegapps/files/litegapps/arm64/31/) - [arm](https://sourceforge.net/projects/litegapps/files/litegapps/arm/30/)

Android 10.0 - [arm64](https://sourceforge.net/projects/litegapps/files/litegapps/arm64/29/) - [arm](https://sourceforge.net/projects/litegapps/files/litegapps/arm/29/)

## LiteGapps++

**Litegapps double plus** is the second product that offers one ``flashable.zip`` to be used on various devices, Android and Architecure versions, so you don't need to save lots of Litegapps files, you just need to save one.  but it has variants like **regular litegapps**, it has 3 types: ``litegapps++``,``litegapps LTS``,``litegapps MicroG``.

### link

LiteGapps++ - [regular](https://sourceforge.net/projects/litegapps/files/litegapps%2B%2B/regular/) - [lts](https://sourceforge.net/projects/litegapps/files/litegapps%2B%2B/lts/) - [microg](https://sourceforge.net/projects/litegapps/files/litegapps%2B%2B/microg/)

## LiteGapps controller

**LiteGapps Controller** is an additional feature of LiteGapps which has many features that can be used by users, for example **boost**, **gaming mode**, **battery**, **tweaks** and other features.

### How to install

You can be in magisk,ksu manager and recovery.

### How to use
- open terminal emulator
- ``su`` enter
- ``litegapps`` enter
 
### Links

[LiteGapps Controller](https://sourceforge.net/projects/litegapps/files/litegapps_controller/)

## LiteGapps Addon

**LiteGapps Addon** is a collection of packages from LiteGapps that can be installed independently, this is to address users who need applications they like that are not available in the LiteGapps or LiteGapps++ packages.

You can install **addon** without even installing LiteGapps, and it supports **systemless** and **systemless** installations.

### Links

[LiteGapps Addon](https://sourceforge.net/projects/litegapps/files/addon/)

## LiteGapps Remover

LiteGapps Remover functions to remove gapps from stock ROM or custom ROM, this was created to overcome ROMs that already have gapps installed and then delete them, before installing LiteGapps so that it doesn't conflict with existing gapps.

[LiteGapps Remover](https://sourceforge.net/projects/litegapps/files/litegapps_remover/)

## Conclusion

Litegapps has complete products and features for handling Google Apps on Android, so this is one of the custom GAPPS that you must have.

For a more complete documentation link, you can visit the official page [LiteGapps](https://litegapps.github.io)


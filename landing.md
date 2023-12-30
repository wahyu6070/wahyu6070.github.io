---
layout: landing
title: microsoft business
description:  best business
lang: en
landing: https://androidnews.gitlab.io/landing.html
tagline: wahyu6070
permalink: /landing
---


Poco X3 NFC is a mid-range smartphone from Xiaomi that offers a 6.67-inch FHD+ display, a Snapdragon 732G processor, a 64MP quad-camera setup, a 20MP selfie camera, a 5160mAh battery, and a 33W fast charging support. The device runs on MIUI 12 based on Android 10 out of the box, but if you want to try something different, you can install a custom ROM on your device. A custom ROM is a modified version of the Android operating system that gives you more features, customization options, and performance enhancements than the stock ROM. However, installing a custom ROM may void your warranty, erase your data, and cause unexpected issues. You should proceed at your own risk and backup your data before attempting any modification.

To install a custom ROM, you need to have an unlocked bootloader and a custom recovery like TWRP installed on your device. TWRP is a custom recovery that allows you to flash various files, such as custom ROMs, root packages, mods, etc. on your device. Rooting is a process that gives you full control over your device, allowing you to access and modify the system files, install apps that require root access, and more. In this article, we will show you how to install TWRP and root Poco X3 NFC using Magisk, a popular root solution that works systemlessly and supports OTA updates.

## Prerequisites

Before you proceed with the installation, make sure you have the following requirements:

- A Poco X3 NFC with an unlocked bootloader. You can follow [this guide](https://www.gusjigang.net/cara-pasang-twrp-dan-root-poco-x3-nfc-100-sukses/) to unlock the bootloader.
- A PC or laptop with ADB and Fastboot drivers installed. You can download them from [here](https://en.gizchina.it/2020/10/little-x3-nfc-unlock-bootloader-twrp-root-permissions-magisk-guide/).
- A USB cable to connect your device to your PC or laptop.
- A TWRP recovery image for Poco X3 NFC. You can download it from [here](https://unofficialtwrp.com/twrp-3-7-0-for-poco-x3-nfc-a12-1/).
- A Magisk zip file for root access. You can download it from here.
- A backup of your data, as the installation will wipe your internal storage. You can use TWRP to backup your data to an external SD card or a USB OTG drive.

## Steps to Install TWRP and Root Poco X3 NFC

Follow these steps to install TWRP and root Poco X3 NFC:

1. Copy the Magisk zip file to your device's internal storage or external SD card.
2. Turn off your device and boot it into Fastboot mode by holding the power and volume down buttons together for a few seconds. You will see a bunny logo on the screen.
3. Connect your device to your PC or laptop with a USB cable.
4. Open a command prompt or a terminal window on your PC or laptop and navigate to the folder where you have the TWRP recovery image. You can do this by typing "cd" followed by the path of the folder. For example, if the TWRP recovery image is in the Downloads folder, you can type "cd Downloads".
5. Verify that your device is detected by typing "fastboot devices". You should see an alphanumeric string followed by "fastboot".
6. Flash the TWRP recovery image by typing "fastboot flash recovery twrp.img". Replace "twrp.img" with the name of the TWRP recovery image file that you downloaded.
7. Once the flashing is done, type "fastboot reboot" to reboot your device.
8. As soon as your device reboots, press and hold the power and volume up buttons together to boot into TWRP recovery. You may need to swipe to allow modifications at the first boot.
9. In TWRP, tap on "Install" and navigate to the Magisk zip file that you copied to your device. Swipe to confirm the flash.
10. Once the flashing is done, tap on "Reboot System" to reboot your device.
11. After your device boots up, open the Magisk Manager app that should be installed on your device. If not, you can download it from here.
12. In Magisk Manager, check the status of your root access and the installed modules. You can also download and install various modules from the Magisk repository to enhance your device's functionality.

## Congratulations!

You have successfully installed TWRP and rooted Poco X3 NFC using Magisk. You can now enjoy the benefits of having a custom recovery and root access on your device. You can also install various custom ROMs, mods, and tweaks that are compatible with your device. However, be careful with what you flash and always make a backup before making any changes. Happy modding!

	

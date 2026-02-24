---
layout: post
title: "How to Safely Root LineageOS 23.2 with APatch"
date: 2026-02-24 21:00:00 +0530
categories: tutorial android
---

Basic tech blogs rarely cover the complex reality of modern Android rooting. If you are running custom ROMs like LineageOS 23.2 (based on Android 16), traditional rooting methods can sometimes lead to module compatibility issues or bootloops.

Today, we are looking at **APatch**—a modern alternative to Magisk and KernelSU that patches the kernel directly for root access.

### Why APatch over Magisk?
* **Kernel-level integration:** It operates at a deeper level, making it harder for banking apps to detect.
* **Module Support:** It supports KPMs (Kernel Patch Modules) while maintaining backward compatibility with many Magisk modules.

### Prerequisites for LineageOS
Before you begin, ensure you have:
1. Unlocked Bootloader
2. The exact `boot.img` from your current LineageOS build.
3. ADB and Fastboot installed on your PC.

### The Installation Process
*(Detailed steps on patching the boot image via the APatch manager and flashing it via Fastboot will go here.)*

### Recovering from Bootloops
If a rogue module causes a bootloop, don't panic. You can use ADB to boot into safe mode or flash your stock `boot.img` to recover without wiping your data.

Stay tuned for our next guide where we will build a custom APatch module from scratch!

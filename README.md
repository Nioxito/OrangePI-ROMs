# ROMs for OPi5 NORMAL
and possibly the Pro version (I don’t have it to test, but it should work). The Plus version probably won’t work, but you could try

If you want a ROM gsi based, contact me on **Discord: Niox07**

I’m going to try to maximize performance and make an overclocked version. If I see enough support, I’ll create a Discord server so people can vote on which GSI they want<3

Both images come with ROOT (Magisk). 
## RisingOS (Android 15 QPR1)
More customization, fewer pre-installed apps, and yes—the PS2 emulator is fixed.
Download RisingOS 15:

[Download RisingOS 15](https://www.mediafire.com/file/ngt66r9uiruk2gd/RisingOSV2.img/file) 

I fixed the bug that was crashing the system when playing videos

⚠️ **Note:**  
If you get an error during the Setup Wizard when setting up Wi-Fi (the screen stays black when you select the Offline option), just skip Wi-Fi or try simply restarting the Orange Pi. In later versions, I will remove the Setup Wizard

## LineageOS TV/Android TV A13
Works but has **HDMI-CEC issues** that also affect other bugs. Still available if you want to test. (idk who the GSI creator is, so I can’t fix those issues for now)
⚠️ **Note:**  
- Audio is low by default on LineageTV. To increase the volume, use:  
adb shell input keyevent 24

[Download Android TV A13](https://www.mediafire.com/file/2lgeu96dkb7ruy3/LineageTV(bugs).7z/file) 

## You need 7z or WinRAR to extract. If WinRAR gives errors, try 7z since it was compressed in that format.

## Installation
The installation steps are the **same as for normal Android**.

### Tutorials:
- **SD Card:** [YouTube Tutorial](https://www.youtube.com/watch?v=gxkNApGxfo4)  
- **NVMe:** [YouTube Tutorial](https://www.youtube.com/watch?v=Bet_plMIS30)

You can also use **RKDevTool**, which in my opinion, is faster.

---

# Android 15 QPR2 & Android 16
Currently don’t boot due to HAL/graphics conflicts with **Kernel 5.10**.  
*Android 16 Beta 3.1 might fix this, but it’s unlikely.*


**Credits:**  
- [GSI Update](https://t.me/GsiUpdate/602)  
- [Pixel Experience GSI](https://t.me/PixelExperienceGsi)


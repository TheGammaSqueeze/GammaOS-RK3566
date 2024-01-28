# Anbernic RG353P / RG353V / RG353M / RG ARC-D
# GammaOS + GammaOS Lite Android Custom Firmware - v1.5.1

- Like my work and want to buy me a coffee? Feel free to buy one here: https://ko-fi.com/thegammasqueeze


Download and instructions
----------------------------
- GammaOS v1.5.1 download: https://github.com/TheGammaSqueeze/GammaOS-RK3566/releases
- [(Changelog)](https://github.com/TheGammaSqueeze/GammaOS-RK3566#changelog)

Instructions:
- [Brand new install (Flash using SD Card)](https://github.com/TheGammaSqueeze/GammaOS-RK3566#instructions---brand-new-install-flash-using-sd-card)
- [Upgrade from existing GammaOS install (Flash using fastbootd)](https://github.com/TheGammaSqueeze/GammaOS-RK3566#instructions---upgrade-from-existing-gammaos-install-flash-using-fastbootd)
- [Help! My device is no longer booting! Or I want to go back to Stock OS!](https://github.com/TheGammaSqueeze/GammaOS-RK3566#help-my-device-is-no-longer-booting-or-i-want-to-go-back-to-stock-os)

Information
----------------------------
GammaOS is based on LineageOS 19.1 (Android 12). It provides a debloated and performance optimized experience for users who are looking to get the best Android experience out of their Anbernic RG353 and ARC devices.

**For the RK3566 series, it is recommended to use GammaOS Lite edition for further performance headroom.**
This replaces your built-in Android system for your device. Linux based CFW that boots from microSD are unaffected.

Features:
- Based on debloated and clean LineageOS 19.1 build, Android 12 for a smoother experience. Only comes with RetroArch for emulation, install standalone emulators as required.
  - GammaOS includes Google Services and Play Store.
  - GammaOS Lite excludes Google apps and services for extra performance headroom. (Recommended)
- Daijisho launcher as front-end, pre-configured with RetroArch for some systems. (Optimized settings for GB,GBC,GBA,NES,SNES,Genesis,PSX) (BIOS files need to be supplied by you).
- Aurora store included.
- Adguard ad blocking included as default (can be disabled via Private DNS settings).
- Magisk/root included.
- 60hz refresh rate fix for display (includes RG 353 V1 and V2 displays).
- Oversharpening display fixed.
- Analog stick calibration for more tighter controls.
- CPU, GPU, Memory now using performance governors for extra performance boost.
- L2/R2 fixed for apps and games with issues with those buttons. 
- Change between XBOX and NS button layout by holding L1+R1+L3/Z
- Swap DPAD and Left analog stick input by holding L1+R1+Y (useful for RG ARC)
- Toggle between performance modes by holding down L1+R1+R3/C 
    - Max Performance (everything set to max frequency, uses the most battery life)
    - Normal Performance (scales frequency according to load)
    - Power Save (lowers all frequencies to minimum for max battery life, useful for GBA and below). 
    - Recommend enabling threaded video in RetroArch for Power Save mode, or change emulators to less demanding ones (SNES9X EX+, Duckstation standalone run better)
- SafetyNet fix, present as Pixel phone: for fixing TMNT etc
    - (Activated by toggling Magisk > Settings > Enable Zygote and reboot your device).

Other Information:
- RetroArch menu toggle: Short press HOME/Back/FN button
- RetroArch quit game (and save progress): Long press HOME/Back/FN button
- RetroArch shortcuts **HOME/Back/FN** +
  - L1 = Slow Motion
  - L2 = Load State
  - R2 = Save State
  - R1 = Fast Forward
  - X = Show FPS
  - Y = Screenshot
  - Vol Up/Down = Adjust brightness

What's missing:
- Built-in button to on-screen mapping software, alternative solutions can be found in app store.


Instructions - Brand new install (Flash using SD Card)
----------------------------
This is a straightforward process for a new install. You will need a Windows machine, a spare microSD card (minimum of 4GB recommended), and a microSD card reader for your Windows machine. 
This will erase all your data currently on the device.
It is recommended that you remove your microSD card in slot TF2 on your Anbernic device until the install is complete and you have fully set up Android.

**NOTE: Do not try and use a tool like Win32DiskImager or balenaEtcher, this will not work.**


1) **Download the relevant release for your device, and extract the zipped file. You will end up with this folder**
     ![image](https://github.com/TheGammaSqueeze/GammaOS-RK3566/assets/116582950/436803a9-71cc-4396-bb3e-ec7ca1e68dbc)

2) **Insert your spare microSD card into your microSD card reader, insert this into your PC.**
   
3) **Open the SDDiskTool_v1.69 folder, then open the SD_Firmware_Tool.exe application.**
     ![image](https://github.com/TheGammaSqueeze/GammaOS-RK3566/assets/116582950/9c346722-ccc7-4c2b-ad8e-607308a098ac)

5) **Ensure that you select "Upgrade Firmware", then click the Firmware button.**
     ![image](https://github.com/TheGammaSqueeze/GammaOS-RK3566/assets/116582950/ac57b4f8-5a86-4a31-86bf-c1dcd1e65273)

6) **Locate your relevant GammaOS_RGXXX_XXXX_vXXX.img file that was in the folder that was extracted earlier, and open this**
     ![image](https://github.com/TheGammaSqueeze/GammaOS-RK3566/assets/116582950/a4010952-c36e-4e37-bc0d-9ac8df65683e)

7) **Click Create and let the process begin**
     ![image](https://github.com/TheGammaSqueeze/GammaOS-RK3566/assets/116582950/eed8c04e-f129-464a-b697-f95d1f44cbc1)
     ![image](https://github.com/TheGammaSqueeze/GammaOS-RK3566/assets/116582950/e53f312c-db5c-4d69-a6ea-9b348e3372e5)
     ![image](https://github.com/TheGammaSqueeze/GammaOS-RK3566/assets/116582950/656cd404-ce6c-427e-bd5e-1a8abc59678c)

8) **Once this is completed, remove your microSD card from the card reader, insert the microSD card into your Anbernic device (TF Slot 1) and restart/turn on. It will start updating the software.**
     ![image](https://github.com/TheGammaSqueeze/GammaOS-RK3566/assets/116582950/abdd9e4e-6939-4e10-91ff-0fea2eb691e9)

9) **Once the install is complete, you will be asked to remove the microSD card. Once this is done, you will boot into GammaOS. The microSD card is no longer required.**
      ![image](https://github.com/TheGammaSqueeze/GammaOS-RK3566/assets/116582950/80753b77-7892-4736-a236-ee164e2d4356)

Your first boot into GammaOS will take some time, so please be patient. Your screen may turn off and on during this process (sometimes it might stay off, just turn it back on), and the GammaOS logo may appear several times, this is normal.
**If signing into a Google account, initial updates may take some time and will install in the background. This may slow down the device until complete.**
Enjoy!

Instructions - Upgrade from existing GammaOS install (Flash using fastbootd)
----------------------------
Coming soon

Help! My device is no longer booting! Or I want to go back to Stock OS!
----------------------------
Anbernic provide factory images for the RK3566 devices. You can find downloads and instructions here:

RG353 Series: https://win.anbernic.com/download/233.html
RG ARC: https://win.anbernic.com/download/289.html

Alternatively, you can download these here: https://github.com/TheGammaSqueeze/GammaOS-RK3566/releases/tag/StockFirmware_RG

The instructions are the same as flashing GammaOS, only except we are using Anbernics own update.img

Changelog
----------------------------
- (v1.5.1) Fixed audio issues with headphones and HDMI.
- (v1.5.1) Updated Mali GPU drivers to latest version for smoother performance.
- (v1.5.1) Fixed holding F to boot into Android breaking Linux SD card (this functionality is only supported on stock Linux OS, not any Linux CFW)
- (v1.5) Moved everything to Quick settings tiles for Performance modes, ABXY layout changes, Adjusting analog stick sensitivity, invert axis for analog left/right, swap dpad and left analog input (useful for RG ARC). No more need to hold down button combos.
- (v1.5) Add aptX BT audio support.
- (v1.5) Improve battery standby time and reduced memory consumption.
- (v1.5) Enable home/back key to act as menu button in RA, as well as the hotkey for other shortcuts.
- (v1.5) Holding down home/back key will save your progress now in RA, and lets you quick resume games, similar to the MM OnionOS game switcher.
- (v1.5) Update all RA cores, but stick with RA 1.15 due to touch screen regression.
- (v1.5) Add Firefox alternative browser.
- (v1.5) Fixed scope storage issues, can now launch Yaba2 and Redream directly from Daijisho (need to enable Allow All Files access for the relevant emulator first).
- (v1.3.3) - Initial release

Credits
----------------------------
TheGammaSqueeze - Author - https://github.com/TheGammaSqueeze/

TacoPizza#4158 - Boot Logo

Andy Yan - Providing GSI builds: https://sourceforge.net/projects/andyyan-gsi/files/lineage-19.x/

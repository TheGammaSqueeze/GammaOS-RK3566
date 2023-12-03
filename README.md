# Anbernic RG353 / RG ARC
# GammaOS + GammaOS Lite Custom Firmware - v1.3.3

- Like my work and want to buy me a coffee? Feel free to buy one here: https://ko-fi.com/thegammasqueeze


Download and instructions
----------------------------
- GammaOS v1.3.3 download: https://github.com/TheGammaSqueeze/GammaOS-RK3566/releases
- [(Changelog)](https://github.com/TheGammaSqueeze/GammaOS-RK3566#changelog)

Instructions:
- [Brand new install (Flash using SD Card)](https://github.com/TheGammaSqueeze/GammaOS-RK3566)
- [Help! My device is no longer booting! Or I want to go back to Stock OS!](https://github.com/TheGammaSqueeze/GammaOS-RK3566#help-my-device-is-no-longer-booting-or-i-want-to-go-back-to-stock-os)

Information
----------------------------
GammaOS is based on LineageOS 19.1 (Android 12). It provides a debloated and performance optimized experience for users who are looking to get the best Android experience out of their Anbernic RG353 and ARC devices.

Features:
- Based on debloated and clean LineageOS 19.1 build, Android 12 for a smoother experience.
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



Help! My device is no longer booting! Or I want to go back to Stock OS!
----------------------------



Changelog
----------------------------
- (v1.3.3) - Initial release

Credits
----------------------------
TheGammaSqueeze - Author - https://github.com/TheGammaSqueeze/

TacoPizza#4158 - Boot Logo

Andy Yan - Providing GSI builds: https://sourceforge.net/projects/andyyan-gsi/files/lineage-19.x/

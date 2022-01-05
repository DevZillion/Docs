## Android Verified Boot vbmeta disabler

You can download the AVB vbmeta disabler images from here:
[Samsung](https://github.com/ZillionMuffin/AVB_Disabler/releases/download/vbmeta/vbmeta_disabled.tar)
[AOSP / Other](https://github.com/ZillionMuffin/AVB_Disabler/releases/download/vbmeta/vbmeta_disabled.img)

# How to flash - AOSP / Other
Reboot into bootloader ``adb reboot bootloader`` and then type:
```css
fastboot flash vbmeta vbmeta_disabled.img
```

# How to flash - Samsung - Odin
Boot into download mode and flash [vbmeta_disabled.tar](https://github.com/ZillionMuffin/AVB_Disabler/releases/download/vbmeta/vbmeta_disabled.tar) in the AP slot.

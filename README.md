# ADB-Google-Apps-Removal-Script

**Working: Most likely, depends on your device/ROM**

Copy-and-paste solution to "uninstall" Google Apps from your Android. Tested on Samsung Note20, Android 11, OneUI 3.1.

(Note that, since /system is r/o, using this script will *not* free space on your device; it only disables the apps from running.)

**Recommended Usage:**

0. Enable Developer Settings, enable ADB debugging.
1. Connect device via USB to PC.
2. Open Command Prompt, run "adb shell"
3. Once the shell is running, copy the script you want, right-click anywhere *inside* the command prompt window to paste the script.
   (You can copy/paste multiple lines to run it all at once.)

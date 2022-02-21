## Android-Pro
Recommended Settings Files to use GenyMotion in Game/App Development Mode

Make it easier!
Simple and Easy Instructions.

![aadn2](https://img.shields.io/github/checks-status/pnickolasubuntu/Android-Pro/master?style=plastic)

## Normal Installation.

Download The Latest .ZIP File 

Open A GENYMOTION VIRTUAL MACHINE

Drag The Arm File Corresponding To Your Android Version

And Put In The Virtual Machine Screen

Restart

Install OPENGAPPS

Follow The Instructions

Your Machine Is Ready To Go!

## [DEVELOPER MODE]
Download The Latest .ZIP File 

Install ADB 

`sudo apt install adb

Select Your Android SDK [ANDROID STUDIO]

Run Terminal

Type

```
adb shell
cd /sdcard/Download/
sh /system/bin/flash-archive.sh /sdcard/Download/Genymotion-ARM-Translation.zip`
adb reboot
```
Visit https://opengapps.org/

Select Plataform [x86]

Select the Android version corresponding to your virtual device

Select variant PICO

Download the selected Open GApps package

Drag and drop the open_gapps-x86-X.X-pico-XXXXXXXX.zip zip archive to the Genymotion virtual device display, or use the command line method.

## Command Line Method [ADB]

Upload the opengapps zip file:

```
adb push open_gapps-x86-X.X-pico-XXXXXXXX.zip /sdcard/Download/open_gapps-x86-X.X-pico-XXXXXXXX.zip
```

Flash the archive:

```
adb shell "/system/bin/flash-archive.sh /sdcard/Download/open_gapps-x86-X.X-pico-XXXXXXXX.zip"
```

When flashing is complete, reboot the virtual device.

## Youtube Tutorial



## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)











   



  

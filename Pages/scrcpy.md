# Scrcpy

Allows you to mirror your phone onto your desktop so you to present and control your phone. If you use it in conjunction with OBS, you can present your phone on your studio. If you're gaming, you can use your mouse and keyboard to interact with your phone or even a desktop controller to control your phone. 

## Setup

- You'll need to be able to have [developer mode](https://bonfirestar.com/pages/blog/developer-mode.html) enabled on your phone to use Scrcpy.
- With developer mode enabled, you need to find the new "developer mode" section in settings. 
- Once there, make sure you enable "USB debugging".
- Download the zip file on the [Genymobile's GitHub](https://github.com/Genymobile/scrcpy/blob/master/doc/windows.md)
- Extract and put uncompressed file somewhere like "C:\Program Files". 
- Go to the folder where "scrcpy.exe" is.

### Single Device

If you only have one device connected to your phone, all you need to do is double-click on scrcpy.exe and a mirror of your phone will display on your desktop. 

### Multiple Devices

If you have multiple phones attached to your desktop, it is a little tricker. From the exe folder, you'll want to go to the folder address bar and type "cmd". This will open command prompt at that folder. From there, you can find your device serial ID and then run the command to start the device. You'll need a separate command prompt window for each device you want to connect. 

- `adb devices`: This command will give you the phones that your computer can detect and their serial number. 
- `scrcpy --serial {serial}`:  This command will connect to the target phone.

## Camera

If you want to use your phone as a camera or webcam, you can run the command below.

```bash
scrcpy --video-source=camera
```

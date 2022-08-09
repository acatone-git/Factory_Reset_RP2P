# RP2+ Factory Reset Guide

How to restore a bricked Retroid Pocket 2 Plus to the factory default (1.0.0.7)

## Requirements

- The [recovery package](https://we.tl/t-vSNjxSNBtU) 
- A Good USB to USB-C Cable

## Setup

- Copy & extract the recovery package in your C:/ drive using [7zip](https://www.7-zip.org/download.html) or something similar
- Navigate to the "Drivers" Folder & Install the usb drivers (DPInst64.exe) as administrator
- Now Navigate to the "Tools" Folder & install [ADB & Fastboot++](https://forum.xda-developers.com/t/tool-windows-adb-fastboot-may-2022.3944288/)
- Select "Install Universal Adb Drivers" at the end of the setup wizard to install those drivers as well
- Finally install the two windows visual c++ 2010 redistributable (vcredist_x64.exe & vcredist_x86.exe) in the "Tools" folder

## Guide

- Navigate to Tools > SPD_Factory_Tool & launch "FactoryDownload" as an administrator
- Click on the gear icon (Load Packet) & select the file "U2.5_20211221_user.pac"
- Wait for the blue bar at the bottom to complete the loading & then press on the play icon (Start Downloading)
- Now connect a good USB to USB-C cable to your Laptop / PC (Poor quality cables will crash the application & fail the reset)
- Turn the RP2+ completely off ** VERY IMPORTANT **
- On the RP2+ press the volume down & the volume up simultaneously *BEFORE* connecting the USB-C Cable
- If everything goes well, the recovery process will begin shortly, the reset will be complete once "passed" appears under progress
- Unplug the RP2+ from the PC & turn it on, the first time boot after the reset will take a while but it's normal
- That's it!

## Credits & Thanks

https://www.youtube.com/user/HorreyForthenewstep (Flasher une stock rom sur le RP2+)

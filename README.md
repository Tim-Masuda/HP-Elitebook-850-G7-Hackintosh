Ventura/Sanoma EFI for HP Elitebook 850 G7 
![photo_2023-09-24_01-04-05](https://github.com/Tim-Masuda/HP-Elitebook-850-G7-Hackintosh/assets/104795041/2b42b291-3cb8-4d00-b274-95c7b209c14a)
=============

## Working:
- 
- iGPU
- Intel Wifi
- Bluetooth (tested only Apple devices, other should work too)
- Audio
- Keyboard & touchpad
- FileVault
- iMessage and FaceTime
- HDMI port (it is necessary to close and open the lid for 5 seconds so that the monitors stop flickering)
- Camera
- Battery
- and the rest

## Not working:
- sleep(someone can earn money, someone does not)



To disable sleep run:

```bash
sudo pmset -a sleep 0
sudo pmset -a hibernatemode 0
sudo pmset -a disablesleep 1
```


## BIOS:


![photo_2023-09-24_00-56-00](https://github.com/Tim-Masuda/HP-Elitebook-850-G7-Hackintosh/assets/104795041/a2fa2584-f8c8-4d4d-a7a5-738fc3a864ab)



## Other:

to make a USB flash drive, look for an image and a program, I used BDU
if airpods don't work for you, update kext for bluetooth both, it's not difficult just google



## Good Luck:
=============

# Portable Input Shaper

![](PIS.png)

## The start

Realize the idea of Nero3D of this video: https://www.youtube.com/watch?v=W_VHbT_tsZw, thanks for his sharing.

## Advantage

1. Base on popular RP2040 chip

2. Portable and you can use it on multiple Klipper firmware based 3D printer with same configuration file. Save your time.

3. Size is small and easy to dock on print head(AfterBurner, StealthBurner or even other print head) as we designed different holes on it with essential fasteners for you to install it on print head. 

4. USB-C port

## Firmware

### menuconfig

![](menuconfig.png)

### config

Use `PIS.cfg`, and add it to your `printer.cfg` by

```
[include PIS.cfg]
```

### how to flash

1. Press and hold the button

2. Connect it to your PC with USB-C cable

3. Release the button

4. Folder named RPI-RP2 popup, copy the klipper.uf2 to the folder

5. Wait for several seconds, when finished folder will closed automatically

6. Done

## Attention

Make sure you flash PIS the same Klipper version as your machine. I recommend you update Klipper to latest version. 

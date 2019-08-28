# ThinkPadx230Mojave
Fully working Clover EFI setup for Mojave on the ThinkPad x230

# What's working
- WiFi (with swapped card)
- Bluetooth
- Native power management
- Battery status
- Brightness control
- Audio
- Ethernet
- iMessage and FaceTime
- Laptop sleep/idle

# Any bugs
- VGA since no real Mac's have it
- Clover may not boot straight away

# Setup
Setup is easy, just replace the stock EFI folder with this one

# My specs
- i5 3320M
- 8GB of RAM
- 320GB HDD
- "Lenovo" Atheros AR9285

# WiFi Card swap
This card does **not** require you to flash your BIOS.  
Latest link: https://www.aliexpress.com/item/32841726254.html?spm=a2g0o.productlist.0.0.32e97c51X6YtgF&algo_pvid=0589832f-3229-4ce0-9598-cd6ed03d13fe&algo_expid=0589832f-3229-4ce0-9598-cd6ed03d13fe-0&btsid=b3521a7d-d01f-49da-954e-576a55b14da4&ws_ab_test=searchweb0_0,searchweb201602_10,searchweb201603_52    
Kext link can be found here: https://drive.google.com/open?id=1SMHw-egHM2lsSiBMZUvp06zbGQgUVMvu  

# Trackpoint workaround
For scrolling with the middle button on the trackpoint you can use smart scroll for macOS.  
Link: https://www.marcmoini.com/sx_en.html

# Basic trackpad gestures
To enable 2 finger scrolling gestures and some others you can use the ApplePS2SmartTouchPad kext.  
Link to that can be found here: https://github.com/linusyang92/macOS-ThinkPad-T480s/tree/master/EFI/CLOVER/kexts/Other/ApplePS2SmartTouchPad.kext

# Credits
- Me for finally updating the DSDT :D
- Bizarro for the LED and brightness control workarounds
- RehabMan for the USB and battery patches
- Apple for giving me a challenge this time round

> Bring on Catalina!

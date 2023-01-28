# Dell Inspiron 3437 OC EFI 
EFI for Dell Inspiron 3437 (i5 4200U and AR9565)
# Hardware Detail
- i5 4200U 1.6Ghz
- 8GB DDR3L 1600Mhz
- SSD or HDD (Need to know on your computer)
- Dell Wireless 1705 (AR9565) This'll get super juicy
# Problem
- Audio from AppleALCU not working [Aternetives from VoodooHDA-OC (Later in post-install)]
- Wifi on Catalina on Hardware properties will show version null
- Wifi will slow after post-install (Recommend to swap your old DW1705 to other Broadcom Wifi on Internet)
- SD Card reader not work (not important to me)
- Messages/FaceTime sometimes work (depend your luck :) )
# BIOS Settings
- UEFI Boot enabled
- Secure Boot disabled
# Prepare USB for installation
- Download EFI from Code
- 1. Install MacOS installation on USB via BalenaEtcher (Windows / MacOS)
- 2. Or use the MacOS recovery on OpencorePkg
- Boot it!
- Format the drive to APFS and install!
# Post-Install
Now once you set all up and get to the desktop you'll see some problem:
- Sound doesn't work (VoodooHDA)
- Backlight slider not working (Needs to be fix SSDT-PNLF)
- Bluetooth (USB mapping and install kext will works)
- Sleep (If you had a DVD drive like mine you should hear a DVD sound when sleep after amount of time)
Now let's go to some headache troubleshooting
# Trobuleshooting
Sound:
Use VoodooHDA-OC thanks Chris1111 to get this sound kext
https://github.com/chris1111/VoodooHDA-OC
Disclamier: Not work in Big Sur 11.3 and later but there is a workaround here:
https://www.insanelymac.com/forum/topic/314406-voodoohda-302/page/21/
. Okay now it's working! :)
Sleep:
I'll need to test later!
# Now you pretty much done! If you add any custom kext please install on L/E and rebuilt cache!
# Thanks to:
- Olarila to give me an opportunity to make my own EFI
- RehabMan for kexts
- Me for my hardwork of EFI

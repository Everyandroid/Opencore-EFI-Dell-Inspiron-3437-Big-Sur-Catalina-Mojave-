# Overview 
EFI for Dell Inspiron 3437 (i5 4200U and AR9565)
# Hardware Detail
- i5 4200U 1.6Ghz turbo boost to 2.6ghz
- 8GB DDR3L 1600Mhz
- Internal SSD or HDD (Recommend SSD) [Already have :)]
- Dell Wireless 1705 or AR9565 (Slow, Weak. Not Recommended) (But working if you're poor)
# Features
- IRQ Coflict intergrated (SSDT-HPET)
- SSDT-XOSI (Windows 2013)
- HS80211 and Atheros40 Patch
# Problem
- Wifi on Catalina on Hardware properties will show version null
- Wifi absolutely slowwww (Recommend install Intel Wireless AC/N 7260)
- SD Card reader not work (not important to me)
# BIOS Settings
- UEFI Boot enabled
- Secure Boot disabled
# Prepare USB for installation
- Download EFI from Releses
- 1. Install MacOS offline installation on USB via BalenaEtcher (Windows / MacOS)
- 2. Or use the MacOS internet recovery on OpencorePkg
- Boot into Installer!!!
- Format the drive to APFS and install (15-30 min on offline) (2-3h on internet recovery)
# Post-Install
Now once you set all up and get to the desktop you'll see some problem:
- Backlight slider not working (Will test on 0.9.2) (Will fix on newer OC releases)
- Bluetooth (Big Sur works but maybe unstable unlike Mojave or Catalina)
# Now you pretty much done! If you add any custom kext please install on E/O/K, Inject Config.plist and Reboot!
# Thanks to:
- Olarila for EFI
- Me for my hardwork of EFI

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
- Wifi absolutely slowwww (Because conflict with WPA and WPA2)
- SD Card reader not work (not important to me)
# BIOS Settings
- UEFI Boot enabled
- Secure Boot disabled
# Prepare USB for installation
- Download EFI from Releses
- 1. Install MacOS installation on USB via BalenaEtcher (Windows / MacOS)
- 2. Or use the MacOS recovery on OpencorePkg
- Boot into Install!
- Format the drive to APFS and install (take around 15-30 minutes)
# Post-Install
Now once you set all up and get to the desktop you'll see some problem:
- Backlight slider not working (PNLF doesn't work) (Will fix on newer OC releases)
- Bluetooth (Big Sur only but Mojave and Catalina already enabled)
Now let's go to some troubleshooting
# Now you pretty much done! If you add any custom kext please install on L/E and rebuilt cache!
# Thanks to:
- Olarila to give me an opportunity to make my own EFI
- RehabMan for kexts
- Me for my hardwork of EFI

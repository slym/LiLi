This is a beta version of LiLi USB Creator.

Most translations are incomplete. You can help me by translating the missing part. Please email me at translations@linuxliveusb.com.

Please report any bug you could encounter to this email : bugs-2.9-beta@linuxliveusb.com

================ CHANGELOG FOR LiLi 2.9 (changes since LiLi 2.8) ================
New Linux distributions ================
KNOPPIX 7.2.0g

================ CHANGELOG FOR LiLi 2.9 (changes since LiLi 2.8) ================

New Linux distributions ================ 
Lightweight Portable Security 1.4.1 (Deluxe)
Netrunner 13.12 (DVD)
Kali Linux 1.0.6
gNewSense 3.1 (GNOME)
CDlinux 0.9.7.1
Netrunner 13.12 (DVD)
Kali Linux 1.0.6
Ophcrack XP 3.6.0
Ophcrack Vista 3.6.0
GeexBox 3.1
Tails 0.22.1
Linux Deepin 2013
SystemRescueCD 4.0.0
Ubuntu 12.04.4 LTS and variants
Toutou Linux 2014
Removing unmaintained/unpopular distro : Meego / PearOS / WifiWay / LiveHacking /Elive / Vyatta / Vortexbox / VectorLinux / Zenwalk / Porteus / Zenix / SolusOS / PureOS / BlankOn

New major features ================
Support for ReactOS / OpenMandrivaLX / CDLinux
Smarter autodetection of INITRD and VMLINUZ files
Autorun creation has been disabled (can be re-enabled in the advanced options)
Code has been simplified and commented
Using windows 7/8 progress bar in taskbar
Storage controller in virtualbox is automatically changed to the best one(IDE or SCSI)


Improvements ================
Flush old logs (keep 1 month)
Latest AutoIT compiler 3.3.10.2
fat32Format 1.07 (GPT support + fix for boot sector when using Windows AIK's bootsect.exe)
Use a more reliable method to fetch UUID/MBRID and physical drive numbers
Recognition options can be changed without reselecting the ISO
changelog on website will give more info (new distribs, major features, improvements, fixed bugs and known bugs)
warning when selecting a ZIP file containing only an ISO
Improved sourceforge download from global mirrors
lighter compatibility list, should be faster to load


Fixed bugs ================
fix some crash when WMI was corrupted/not working
Could not cancel download when selecting the destination folder
Previous betas may not check for new beta availability (and option display was wrong)


Known Bugs ================
GUI can flicker when LiLi is busy
cannot stop a Linux download unless you shut LiLi's down
Asian characters not displaying in the progress bar
GUI may flickers or hang but usually it comes back 
# Klipper-for-3d-printer-on-Microsoft-Surface-RT

Donation PayPal: jeromest_gelais@hotmail.com

Don't forget that the surface RT must be jailbroken here is the link of the tutorial:

https://jwa4.gitbook.io/windows/tools/surface-rt-and-surface-2-jailbreak-usb

Guide and klipperRT.img to install klipper,moonraker,fluidd,klipperscreen on Microsoft Surface RT!

#1 Download link: https://mega.nz/file/rFd0RI5A#DObPZuLvSGqfHWrcKi6RA80uPuVN4racOqrgYy_ruJQ

#2 Write the klipperRT.img image with etcher or another application!

#3 Boot on the USB key on the RT surface! (Volume Down + Power)

#4 Wait 30-40 minutes after the installation is complete, the tablet will automatically shut down!

#5 Remove the USB stick and start Surface RT normally! (Without Volume Down + Power Combo)

#6 When klipperscreen opens, do ctrl+alt+F3 to get a terminal!

#7 Write the command: 

ls /dev/serial/by-id/

This will give you the link to write in [mcu] of printer.cfg

#8 Write in terminal: sudo raspi-config choose 1 (Otions system) and configure your WIFI

#9 Still in the raspi-config menu, go back to the first page and choose 6 then A1 Expand Filesystem.

Restart and you're done!

(Configure your printer.cfg in fluidd)



Jérôme St-gelais (2022)

# Klipper-for-3d-printer-on-Microsoft-Surface-RT

Don PayPal: jeromest_gelais@hotmail.com

Oublié pas que la surface RT doit être jailbreaké voici le lien du tutoriel :

https://jwa4.gitbook.io/windows/tools/surface-rt-and-surface-2-jailbreak-usb

Guide et klipperRT.img pour installer klipper,moonraker,fluidd,klipperscreen sur Microsoft Surface RT!

#1 Lien de téléchargement : https://mega.nz/file/rFd0RI5A#DObPZuLvSGqfHWrcKi6RA80uPuVN4racOqrgYy_ruJQ

#2 Écrire l'image klipperRT.img avec etcher ou autre application!

#3 Démarrer sur la clef USB sur la surface RT! (Volume Bas + power)

#4 Attender 30 a 40 minutes a la fin de l'installation la tablette va ce fermer automatiquement!

#5 Enlever la clef USB et démarrer la Surface RT normalement ! (Sans la combinaison Volume bas + power)

#6 Quand klipperscreen ouvre faite ctrl+alt+F3 pour avoir un terminal!

#7 Écrire la commande : 

ls /dev/serial/by-id/

Cela va vous donner le lien à écrire dans [mcu] de printer.cfg

#8 Écrire dans le terminal : sudo raspi-config choisire le 1 (system Otions) et configurer votre WIFI

#9 Toujours dans le menu de raspi-config reculé a la premiere page et choisissé 6 et ensuite A1 Expand Filesystem.

Redémarrer et c'est terminer!

(Configurer votre printer.cfg dans fluidd)



Jérôme St-gelais (2022) Don PayPal jeromest_gelais@hotmail.com

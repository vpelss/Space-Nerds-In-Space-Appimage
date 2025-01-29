# Space-Nerds-In-Space-Appimage

Space Nerds in Space is a linux only space bridge simulator.

You can build it yourself here:

https://smcameron.github.io/space-nerds-in-space/

I have created a Linux AppImage for Space Nerds In Space for those who can't compile it.

My AppImage version is here: https://github.com/vpelss/Space-Nerds-In-Space-Appimage/releases/tag/Newest

Note: It must be started in a Linux terminal

- Download
- open terminal at file path
- chmod +x Space_Nerds_in_Space-x86_64.AppImage
- ./Space_Nerds_in_Space-x86_64.AppImage

Tested succesfuly on:
- q4OS
- mint cinnamon
- mint xfce
- MiniOS

How it was built:

see [instructions.txt](https://github.com/vpelss/Space-Nerds-In-Space-Appimage/blob/main/instructions.txt)

We also have a flatpak version:
https://github.com/vpelss/snis_flatpak

See below for distributions that are having issues. You might need to install some libraries.

openSUSE

sudo zypper install libfuse2
sudo zypper install xorg-x11
sudo zypper install Mesa
sudo zypper install libportaudio2

Slakware

Debian

Arch

Kali



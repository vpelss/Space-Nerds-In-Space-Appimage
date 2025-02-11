# Space-Nerds-In-Space-Appimage

Space Nerds in Space is a linux only space bridge simulator.

You can build it yourself here:

https://smcameron.github.io/space-nerds-in-space/

I have created a Linux AppImage for Space Nerds In Space for those who can't compile it.

My AppImage version is here: https://github.com/vpelss/Space-Nerds-In-Space-Appimage/releases/tag/Newest

Note: It is easiest to start in a Linux terminal. Making a launchable icon is possible, but will vary depending on your gui. 

- Download
- open a terminal at the file path
- 
```
chmod +x Space_Nerds_in_Space-x86_64.AppImage
./Space_Nerds_in_Space-x86_64.AppImage
```

Tested succesfuly on:
- q4OS
- mint cinnamon
- mint xfce
- MiniOS
- for distributions that are having issues, see https://github.com/vpelss/snis_flatpak/blob/main/README.md  You might need to install some libraries.

Make a Desktop Icon

If you save Space_Nerds_in_Space-x86_64.AppImage in ~/AppImages/Space_Nerds_in_Space-x86_64.AppImage, then you would place a desttop file here: ~/.local/share/applications/snis.desktop and your snis.desktop file might contain the following. Also if you want the icon, download it also. Note that the paths MUST be absolute.

```
[Desktop Entry]
Name=Space Nerds in Space
GenericName=Space Nerds in Space
Comment=Networked spaceship bridge simulator
Exec=/home/{your login name}/AppImages/Space_Nerds_in_Space-x86_64.AppImage
Icon=/home/{your login name}/AppImages/icon.svg
Terminal=true
Type=Application
Categories=Game;
```
Your game icon should now show in your gui menu under Game

How it was built: [instructions.txt](https://github.com/vpelss/Space-Nerds-In-Space-Appimage/blob/main/instructions.txt)

We also have a flatpak version:
https://github.com/vpelss/snis_flatpak






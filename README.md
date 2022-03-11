# Fork of DWM For X

## Differences from the main repo
- The same as [Outlaw's fork](https://github.com/MentalOutlaw/dwm) except I added [hide vacant tags](https://dwm.suckless.org/patches/hide_vacant_tags/).
- Removed ttf-font-awesome dependancy and use numbers for tagging.
- Added screenshot commands. //change the screenshot directory in config.h before make install.

## dependancies
- Arch
```
sudo pacman -Syu base-devel xorg-xinit xorg-server libxft libxinerama libx11
```
- Gentoo
```
emerge --ask --autounmask-continue xorg-server xorg-drivers libXft libXinerama
```
For minimal base install, it is good to keep in mind that you need to install font package.
This usually bundled with your web browsers, but you can always install them separately.



## How to install for newbie.
```
git clone https://github.com/lunaere/dwm
cd dwm
sudo make install
```

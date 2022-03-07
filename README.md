# Fork of DWM For X

## Differences from the main repo
- The same as [Outlaw's fork](https://github.com/MentalOutlaw/dwm) except I added [hide vacant tags](https://dwm.suckless.org/patches/hide_vacant_tags/).
- Removed ttf-font-awesome dependancy and use numbers for tagging.
- Added screenshot commands

## dependancies
```
sudo pacman -Syu base-devel xorg-xinit xorg-server libxft libxinerama libx11 scrot
```


## How to install for newbie.
```
git clone https://github.com/lunaere/dwm
cd dwm
sudo make install
```

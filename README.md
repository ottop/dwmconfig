# My DWM configuration.

## Example screenshots:
![Screenshot from 2021-10-04 18-43-40](https://user-images.githubusercontent.com/60475104/135884651-1757a170-4c4c-47a8-a7ea-f093b5d1a5f3.png)
![Screenshot from 2021-10-04 18-58-25](https://user-images.githubusercontent.com/60475104/135884676-833527c8-57be-4de7-9991-65aea88f122e.png)

## What my configuration uses.
- [DWM](https://dwm.suckless.org/)
- The following patches:
  - [actualfullscreen](https://dwm.suckless.org/patches/actualfullscreen/)
  - [fancybar](https://dwm.suckless.org/patches/fancybar/) 
  - [gaplessgrid](https://dwm.suckless.org/patches/gaplessgrid/)
  - [layoutscroll](https://dwm.suckless.org/patches/layoutscroll/)
 - [Dmenu](https://tools.suckless.org/dmenu/)
 - [j4-dmenu-desktop](https://github.com/enkore/j4-dmenu-desktop) (modified in the way I outline in my SpectrWM config's README: https://github.com/ottop/spectrwmconfig/blob/main/README.md)
 - [slstatus](https://tools.suckless.org/slstatus/)

## How to use this configuration.
1. Put the config.h file of dwm in your dmenu directory along with the .diff patch files linked above. 
2. Run ```make clean install``` in the dwm directory.
3. Put the config.h file of slstatus in your slstatus directory.
4. Run ```make clean install``` in the slstatus directory.
5. Install dmenu along with j4-dmenu-desktop, including the customizations linked in the above section.

## The wallpaper.
Just download the png file.

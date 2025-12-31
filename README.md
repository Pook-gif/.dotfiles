# .dotfiles
### Dotfiles for my Gentoo desktop 
###### (they work on other devices + distros but require minor changes)
![alt text](2026-01-01-013946_hyprshot-1.png)

## Changes:
- Fixed a memory leak with swaync + mpc!!
- Made waybar detect music playing with MPD
- Polished up some code.. It's very weird lmao but not as bad
- Made waybar easier to configure + just better

## read me!!
The first thing you should check out before modifying any other file I provided is the hyprland config at ```~/.config/hypr/hyprland.conf```, I have some Nvidia environment variables there that you should disable if not using an Nvidia GPU. Also, please check out other config files if stuff isn't working (Like a black wallpaper, go check the hyprpaper config I provided)

## notes
I might make a script later on that automates installing these for you, whenever I have spare time. For now, I expect anyone to be using my dotfiles to be able to fix up some errors when installation like changing hyprpaper's directory to look for, from ```/home/Gentoo/path/to/image``` to ```/home/myusername/path/to/image```

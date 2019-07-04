i3
===

## Dependencies
`xcompmgr`: composite manager for shadows and transparency  
`xclip`: clipboard manager for sending screenshot to clipboard  
`pulseaudio-utils`: Sound system for POSTIX OSes
`graphicsmagick-imagemagick-compat`: to use `import` command for screenshots.  
`qalc`: command line calculator

```bash
sudo apt install xcompmgr xclip pulseaudio-utils graphicsmagick-imagemagick-compat qalc clipmenu
```

## Setup
`feh-rand`: same as `feh` but use a url to fetch random wallpapers. copy it to system `PATH` (/usr/local/bin).  
`i3lock-rand`: lock i3 with random images from a path. copy it to system `PATH`.  
`i3config`: my personal i3 config file. copy it to `~/.config/i3/config` (Debian) or `~/.i3/config` (Ubuntu).  

custom shortcuts:
* **CalculatorKey**: open qalc calculator
* **Super + Z**: go to workspace 16 (my personal workspace)
* **Super + PrintScreen**: create a screenshot and save it to `Pictures/date.jpg`
* **Super + Shift + PrintScreen**: create a screenshot and send it to clipboard
* **Super + Esc**: focus on child
* **Super + Pageup/Pagedown**: go to next/perv workspace
* **Super + /**: pause or play spotify (you need to install [sp](https://gist.github.com/fa6258f3ff7b17747ee3.git))
* **Super + <**: play previous song in spotify (you need to install [sp](https://gist.github.com/fa6258f3ff7b17747ee3.git))
* **Super + >**: play next in song spotify (you need to install [sp](https://gist.github.com/fa6258f3ff7b17747ee3.git))
* **[Super +] Volumeup/Volumedown**: volume up/down
* **Super + c**: clipboard manager (you should install [clipmenu](https://github.com/cdown/clipmenu))
* **Super + Shift + x**: move a window to scratchpad
* **Super + x**: show windows in scratchpad

`i3status.conf`: custom i3 bar status. this file auto loaded if copied to `~/.i3status.conf`  
`Xresources`: some custom config for better font rendering. copy it to `~/.Xresources` and restart your X session.  
`xorg.conf.d`: this directory contains some config files for device input management like synaptic touchpad manager (tap to click, two finger tap to right click) and etc. copy this folder to `/etc/X11/` and restart your X session.  

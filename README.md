# Meowdern
A hyperminimalist fork of the [ModernX](https://github.com/cyl0/ModernX) featuring only a seekbar and time displays. Designed for those who use keybinds almost-exclusively, but still want scrubbing functionality and [Thumbfast](https://github.com/po5/thumbfast) support.

![Screenshot of mpv with the meowdern OSC, also featuring the thumbfast integration](./Preview.png)

# How to install
## Linux
- Put `meowdern.lua` into `~/.config/mpv/scripts`. if the folder doesn't exist- create it!
- Put `Material-Design-Iconic-Font.ttf` into the `~/.config/mpv/fonts` folder.
- In `mpv.conf`, add:
    
    ```
    osc = no
    border = no # Optional, removes winodow borders

    # (Optional) Additional options for the OSD (On Screen Display) 
    osd-on-seek=no
    osd-border-size=1
    osd-bar-h=1
    ```
- `Material-Design-Iconic-Font.ttf` can also be downloaded from [here](https://zavoloklom.github.io/material-design-iconic-font/).
## Windows
- Put `meowdern.lua` into `\%APPDATA\mpv\scripts`. if the folder doesn't exist- create it!
- Put `Material-Design-Iconic-Font.ttf` into the `\%APPDATA\mpv\fonts` folder.
- In `mpv.conf`, add:
    
    ```
    osc = no
    border = no # Optional, removes winodow borders
    
    # (Optional) Additional options for the OSD (On Screen Display) 
    osd-on-seek=no
    osd-border-size=1
    osd-bar-h=1
    ```
- `Material-Design-Iconic-Font.ttf` can also be downloaded from [here](https://zavoloklom.github.io/material-design-iconic-font/).

# Configuration

Edit osc.conf in "~/.config/mpv/script-opts/" folder. Refer to the user_opts variable in the script file for details.

# Thumbnails

To enable thumbnails in timeline, install [thumbfast](https://github.com/po5/thumbfast). No other step necessary.

# Other features
## Seekbar
* Left mouse button: seek to chosen position.
* Right mouse button: seek to the head of chosen chapter
## Playback time
* Left mouse button: display time in milliseconds
## Duration
* Left mouse button: display total time instead of remaining time

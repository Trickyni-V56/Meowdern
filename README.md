# Meowdern
A hyperminimalist fork of the [ModernX](https://github.com/cyl0/ModernX) featuring only a seekbar and time displays. Designed for those who use keybinds almost-exclusively, but still want scrubbing functionality and [Thumbfast](https://github.com/po5/thumbfast) support.

![img](./Preview.png)

# How to install

Locate your MPV folder. It is typically located at `\%APPDATA%\mpv\` on Windows and `~/.config/mpv/` on Linux/MacOS. See the [Files section](https://mpv.io/manual/master/#files) in mpv's manual for more info.

Put mordenx.lua into your mpv "\~\~/scripts/" folder. Create the "\~\~/scripts/" folder if you don't already have one and remove any other OSC scripts,
then put `Material-Design-Iconic-Font.ttf` in the "\~\~/fonts" folder.

in mpv.conf:

```
osc = no
border = no # Optional, but recommended
```
`Material-Design-Iconic-Font.ttf` can also be downloaded from [here](https://zavoloklom.github.io/material-design-iconic-font/).

# How to config

edit osc.conf in "\~\~/script-opts/" folder, however many options are changed, so refer to the user_opts variable in the script file for details.

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

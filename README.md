# Suckless Terminal
+ font troubles\
If you encounter with some situation when some charactors (typically, cjk ones) fail to be rendered,
delete ~/.cache/fontconfig, remake and log back in X. (me personally don't know why...)\
Note that in arch-like distros, you can`yay -S wqy-microhei` to get a nice cjk font.

fonts: [firacode nerd(modified)](https://github.com/0n3W4y7ick3t/deployLinux/tree/main/firacode-nerd)

## Unique features (using dmenu)

+ **follow urls** by pressing `alt-l`
+ **copy urls** in the same way with `alt-y`
+ **copy the output of commands** with `alt-o`
+ **edit the output of commands** with `alt-e`

## keybindings
| shortcut               | action           |
|------------------------|------------------|
| alt-shift-k, alt-equal | zoom in          |
| alt-shift-j, alt-minus | zoom out         |
| alt-shift-home         | zoomreset        |
| alt-c                  | clipcopy         |
| alt-v                  | clippaste        |
| alt-k, alt-u           | scroll up        |
| alt-j, alt-d           | scroll down      |
| alt-s                  | alpha- (lighter) |
| alt-a                  | alpha+ (darker)  |
| alt-l                  | openurl          |
| alt-y                  | copyurl          |
| alt-o                  | copyoutput       |
| alt-e                  | editoutput       |
+ **use [sd](https://github.com/0n3W4y7ick3t/rice/blob/main/.local/bin/lukes/sd) to spawn a new instance with the same CWD, I bind it to `alt-shift-Return` in [dwm](https://github.com/0n3W4y7ick3t/dwm).**

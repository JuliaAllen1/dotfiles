# julia's dotfiles

this is my personal config. it's designed around a mix of Catppuccin and Dracula, and specifically suited to
i3 (though it works with Sway, too). 

## me-specific config; you should change it!

to be clear, change whatever you want, but you *need* to change these for them to work right, unless
you magically happen to have the same config as me.


- line 191 in i3/config; change that to wherever you store your backgrounds.

- line 195 in 13/config; change this to wherever your xborder config is,  or remove entirely if you like the default

- lines 45 and 189 in polybar/config.ini; change to whatever your primary/secondary monitors are.
  - remove 187-189 if you only have a single monitor

-


## Dependencies

Aside from those immediately listed in the root as directories, there are a few others.

### i3
- `feh`, for wallpaper management
- `xborders`, for pretty rounded corners
- `rofi`, as an app launcher

### kitty
- any font of your choice; i like NerdFonts, and specifically EnvyCodeR. use whatever, though. 

### polybar

- Symbols Nerd Font
- EnvyCodeR Nerd Font as-is, though of course you can change it to whatever you prefer. 


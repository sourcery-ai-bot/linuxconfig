# linuxconfig
Stuff for my workstations

## statusbar.py
Add the following config to your ~/.config/sway/config:  
```py
bar {
    position top
    status_command python3.7 ~/path/to/statusbar.py
    colors {
        statusline #ffffff
        background #323232
        inactive_workspace #32323200 #32323200 #5c5c5c
    }
}
``` 
Remember to install `pip install -r requirements.txt`  

## sway_config
Should be renamed to `config` and placed in `~/.config/sway/`
General sway config. Very work in progress. Some custom keybinds and a very specific worspace handling for my dock. 

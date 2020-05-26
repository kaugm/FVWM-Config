# FVWM-Config
Config and scripts for FVWM


Installation
------------

Install `fvwm`

`config` is the standard configuration\
`config_titlebar` includes a top title bar and close icon

    $ mkdir ~/.fvwm
    $ cp [config] ~/.fvwm
    $ cp crthumb ~/.bin/crthumb
    $ cp dethumb ~/.bin/dethumb
    $ cp theme ~/.bin/theme

Restart fvwm to see changes

`theme` is a script that downloads a random wallpaper from unsplash, sets it as the wallpaper, uses `wal` to update system colors, and then sets the new colors for fvwm

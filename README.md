# POLYHLWM

Config files and modules for herbstluftwm/polybar

Dependencies: herbstluftwm, polybar, xrdb, xgetres, xdotool, pywal, feh, dunst

# hcbar

**Herbstluftwm** tag bar.  
**Hcbar** uses **myhc** (see below).

## Features

* Empty tags are not shown.
* Display layout for individual frames:
```
--- vertical
||| horizontal
|M| max
[+] grid
```
* In *max* mode, display the actual number of clients.

# myhc

## Features

* Keep track of tags/monitors:  
```
myhc switch_to_tag
myhc cycle_monitor
```
* If a tag is empty and not focused, it will no longer be tracked.
* Floating terminal: toggle display of a screen centered terminal  
`myhc float`


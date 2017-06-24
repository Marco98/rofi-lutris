# rofi-lutris
A simple python script that creates a rofi menu for games in the Lutris Platform.
This is especially useful in tiling window managers like i3.

#### Dependencies
* python
* rofi
* lutris

#### Usage
i3wm sample config entry:
```
bindsym $mod+x exec rofi-lutris
```
In this example, the menu will trigger on pressing MOD+X

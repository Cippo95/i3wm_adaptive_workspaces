# i3wm adaptive workspaces

This repository contains my basic way of using i3wm.

## Inspiration

This way of using i3wm is inspired by GNOME DE's workflow. 

## Core concepts

- $mod is the Windows/Super key, it would be great to use Alt but there are many applications that use it for shortcuts.

- In i3wm you have workspaces linked to some particular key; here when you want a new workspace you just press $mod+i (i for **i**nsert).
When you want to go to the **n**ext workspace you press $mod+n, and $mod+p for the **p**revious workspace.

- In GNOME it is great to press the $mod button to open apps, here you have to press $mod+Enter.
> There's no terminal shortcut, you open it through the main launcher, which is rofi.

- Layout modifications are under a MODIFY mode, accessible with $mod+m (guess what m stands for).

- You can reload the config file, restart i3wm or exit with the ADMIN mode, accessible with $mod+slash (I have decided slash because it is easier to press then a while holding the $mod key).

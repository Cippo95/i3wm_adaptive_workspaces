# i3wm adaptive workspaces

This repository contains my basic way of using i3wm.
You can start from this and modify it as you please.

## Inspiration

This way of using i3wm is inspired by GNOME DE's workflow. 

## Core concepts

- The main modifier, `$mod`, is the Windows/Super key:
  - Since it is on the left I try to keep every shortcut composed with a key on the right (touch typing best practice).
  - It would be great to use Alt but there are many applications that use it for shortcuts.

- In i3wm you have workspaces linked to keys; here it different and inspired by GNOME (with different shortcuts): 
  - Insert new workspace: `$mod+i`.
  - Next workspace: `$mod+n`.
  - Previous workspace: `$mod+p`.

- Press `$mod+Enter` to open your app launcher (I use rofi):
  - I think that it is not smart to keep a shortcut only for the terminal, just open it as any other app.

- To modify the layout you have to enter the MODIFY mode: `$mod+m` (shortcuts similar to default i3wm).
  - `$mod+;` to switch beetween tabbed and splitted layout (I do this often so it is out of the mode).

- To reload, restart or exit you have to enter the ADMIN mode: `$mod+/`.
  - I have decided `/` instead of `a` (for admin) because of touch typing best practice.

- Enter USER mode, for any interesting binding that you need: `$mod+u`.
  - Using i3wm this way you could have workspaces number skip, you can sort them pressing `r` while being in USER mode.
  - For example in my full config I have stuff to move audio beetween headphones and speaker etc.

The scripts in `/scripts` are to insert a new workspace, move a container to the next workspace and sorting workspaces.

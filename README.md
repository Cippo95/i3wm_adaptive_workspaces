# i3wm adaptive workspaces

This repository contains my basic way of using i3wm.
It is a configuration with a different idea on how to use workspaces.  
You can start from this and modify it as you please.  

## Keyboard bindings
![keybord bindings](https://github.com/Cippo95/i3wm_adaptive_workspaces/blob/main/keyboard-layout.png)

## Inspiration

This way of using i3wm is inspired by GNOME DE's workflow and vim.

## Core concepts

The configuration file should be pretty easy to understand but here the main bindings and ideas:

- The main modifier, `$mod`, is the Windows/Super key:
  - Since it is used with the left hand primary shortcuts are composed with a right hand key (touch typing best practice).
  - It would be great to use Alt but there are many applications that use it for shortcuts.

- You move beetween containers with `$mod+``h`or `j` or `k` or `l` as in vim (h: left, j: down, k: up, l: right). 
  - Add `Ctrl` to move a containter, e.g. `$mod+Ctrl+h` moves a container on the left.

- In i3wm workspaces are linked to keys; here it is different and inspired by GNOME (with different shortcuts): 
  - Insert new workspace: `$mod+i`.
  - Next workspace: `$mod+n` (to move a container to the next workspace `$mod+Ctrl+n`).
  - Previous workspace: `$mod+p` (to move a container to the prev workspace `$mod+Ctrl+p`).

- Press `$mod+Enter` to open your app launcher (I use rofi):
  - I think that it is not smart to keep a shortcut only for the terminal, just open it as any other app.

- To modify the layout you have to enter the MODIFY mode: `$mod+m` (shortcuts similar to default i3wm).
  - `$mod+o` ('o' for on/off) to switch beetween tabbed and splitted layout (I do this often so it is out of the mode).

- To reload, restart or exit you have to enter the YAWN mode: `$mod+y`.
  - You are yawning because you are bored of your current configuration, or you want to exit (and uses y key which has a great position).

- Enter USER mode, for any interesting binding that you need: `$mod+u`.
  - Using i3wm this way you could have workspaces number skip, you can reorder them pressing `r` while being in USER mode.
  - For example in my full config I have stuff to move audio beetween headphones and speaker etc.

The scripts in `/scripts` are to insert a new workspace, move a container to the next workspace and reorder workspaces.

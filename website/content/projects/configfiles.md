---
author: "Javier de Marco"
date: "2020-05-11"
title: Dotfiles Project

---

# Dot Files

Author: Javier de Marco

## Description

This is my Dotfiles project, where i keep up to date my config files for most of the software i use
in linux.
<br>

## Software

* Window Manager: Openbox
* Terminal Emulator: Alacritty
* Shell: Zsh
* Dock: Plank
* Status bar: Polybar
* Application launcher: Rofi
* Editor: NeoVim

### Openbox

For my openbox config file i try to keep it simple but functional to my needs.
<br>
These are the config files:
1. autostart
Where i keep the applications i wish to start on bootup.
<br>
This will launch my compositor (Compton), statusbar (Polybar), wallpaper manager (Feh), dock (Plank), and cloud storage service (Pcloud)
<br>
2. RC file
How openbox behaves.
<br>
There is a separate post for this issue, as it is quite long.

### Alacritty

Alacritty is my terminal emulator of choice. It is a very fast, configurable and beatifull emulator.
<br>
These settings are almost default, except for: font (mononoki Nerd Font Mono), Nord theme, history length

### Zsh

Zsh is a powerfull and really configurable shell.
<br>
I am using a very minimal configuration of zsh. It is using vim like keybindings to navigate and input commands.
<br>
To make a modular aproach to this configuration i am using a loop to source config files in /.config/zsh directory.
<br>
This files are:
1. Alias: aliases that i wish to use
2. Zplug: Plugins installed using zplug manager
<br>
The plugins i am using are:
1. Git: aliases for git
2. Colored-man-pages
3. Command-not-Found
4. zsh-syntax-highlighting
5. zsh-autosuggestions
6. zsh-history-substring-search
7. zsh-completions
8. zsh-you-should-use: recommends aliases to use
9. zsh-async
10. pure: prompt theme

### Plank

Plank is a really good dock, for its minimal and easy of use. My configuration consist of a transparent theme with the programs i most use.

### Polybar

My Polybar configuration has its own project post, go there to know more about it.

### Rofi

My Rofi configuration is a minimal one, where i spawn a small square in the middle of the screen to search and launch applications. It is configured to be shown with the Nord theme.

### NeoVim

NeoVim configuration has its own project post, go there if you want to know more about my NeoVim configuration.

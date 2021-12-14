---
author: "Javier de Marco"
date: ""
title: Polybar
---
![Polybar](static/images/polybar.png)
## Introduction
Polybar is an highly configurable status bar that aims to help users create awesome personalized bars.

### Instalation
If you have Arch Linux, you have to get installed an AUR helper, in my case paru, from which polybar can be installed by executing the following commmand:
``` sh
paru polybar
```
After that you have to create the folder ~/.config/polybar in which the configuration file and the optional launcher script will be placed
## My Config
In my configuration i try to keep things simple without trading functionallity.
I like to mantain a good looking status bar that helps me keep track of the information i need and doesn't distract me much or take too much desktop space.

Currently there are two themes in the configuration file: One dark and Gruvbox.
The bar is set to occupy the entire width of the monitor and about 2.5% of the height, so it is easy to see the icons but not to demanding on the space required.
My current font is Fira Code Nerd Font which i support with Material Icons in case i need a special icons that it is not included in Nerd Fonts.
### Modules
The modules i use are:
* Launcher: a custom/text module that has the ability to launch scripts when clicked. Although i dont use it that often, the ability to click the icon to launch rofi (my application launcher) it is quite usefull when i am not feeling like using the keyboard for everything.
* Date: to show the current date. It has also the possibility to launch my calendar application (Morgen or Thunderbird) when clicked.
* Pulseaudio: module to see and control the volume of the current output. When clicked it muted the output sound.
* Backlight: screen light module to track the current level of brightness in the monitor.
* Memory: module to identify the percentage of memory usage of the system. It is really usefull to see if the system is overloaded or not. (TODO: script to launch a notification with the 5 most memory usage programs at the moment)
* CPU: like the memory module, it keeps track of the CPU usage of the system. (TODO: scripts to launch a notification with programs that are using the most of cpu)
* Battery: module to show the current power level of the battery.
* Powermenu: clickable module to launch a rofi script that can trigger suspend, logout, shutdown or restart of the system.

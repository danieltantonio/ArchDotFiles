# Arch Linux Files

## Introduction
The files found in here are configuration files for my Arch Linux setup. These are for my personal use but I feel like this can be used to help people get a grasp on what their configuration files would look like as well...

## Some Info
Basically putting this up to remind myself what files go where.

### .bashrc
The .bashrc file is used to create global environment variables within the terminal. The location for this file should be placed in the `$HOME` directory.

### xrandr
The xrandr package allows xorg to be set in a custom/proper screen resolution. \
The config file in this directory goes into: `/usr/share/X11/xorg.conf.d/`

### i3, & alacritty
*Personal Note*: Should've installed these during the Arch Linux Post Installation phase.\

i3 is a Windows Manager to snap windows against each other. This can be used to have both floating windows and tiling windows.

Alacritty is a terminal emulator that is also very customizable.

i3wm config file goes to: `$HOME/.config/i3/`\
alacritty config file goes to: `$HOME/.config/alacritty`

## TO DO
- [ ] Create script to automatically install required files **AFTER POST INSTALL**
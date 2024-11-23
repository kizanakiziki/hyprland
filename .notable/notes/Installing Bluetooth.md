---
title: Installing Bluetooth
created: '2024-10-24T16:36:28.487Z'
modified: '2024-11-05T23:00:02.353Z'
---

# Installing Bluetooth



## Install Bluetooth Packages
1. Install `bluez` `bluez-utils` `pipewire` `pipewire-pulse` `pipewire-alsa` `pipewire-jack`. This is required for dependencies. Like 'driver' on Windows.
```
sudo pacman -S `bluez` `bluez-utils` `pipewire` `pipewire-pulse` `pipewire-alsa` `pipewire-jack`
```
2. Install `blueman` to manage bluetooth device in GUI version.
```
sudo pacman -S blueman
```

## Start and Enable Bluetooth Service
``` bash
sudo systemctl enable --now bluetooth
```

## Connect to Bluetooth TWS via Blueman
1. Run in terminal.
``` bash
blueman-manager
```
2. Or just use `rofi` or `wofi`.

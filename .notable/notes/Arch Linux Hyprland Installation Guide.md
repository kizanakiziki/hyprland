---
title: Arch Linux Hyprland Installation Guide
created: '2024-10-24T16:02:20.147Z'
modified: '2024-11-05T23:17:40.877Z'
---

# Arch Linux Hyprland Installation Guide
## Pre Installation
1. Siapkan bootable Arch Linux.

## Installation
1. Install seperti biasa menggunakan `archinstall`. Ikuti [link](https://www.youtube.com/watch?v=4dKzYmhcGEU) untuk lebih instalasi Arch dual boot dengan Windows 11 lebih detail.
2. Pastikan menggunakan _desktop environment_ hyprland.
3. Tambah beberapa _Packages_ seperti `nano vim git curl btop htop neofetch` dll.

## Post Installation
1. Update repository.
```bash 
sudo pacman -Syu
```
2. Clone hyprland github repo 
``` bash
git clone <github repo links>
```
3. Install `waybar`
``` bash
sudo pacman -S waybar
```
4. [[Installing Bluetooth]]
5. Install `brightnessctl` to use brightness fn shortcut, and `pavucontrol` to use volume fn shortcut.
``` bash
sudo pacman -S brightnessctl pavucontrol
```
6. Install `firefox`.
``` bash
sudo pacman -S firefox
```
7. [[Install Yay]]
8. Install font e.g. `JetBrainsMono Nerd Font` for waybar. Need `yay`.
``` bash
yay -S jetbrainsmono
```
9. Install `zsh`, `oh-my-zsh`, `powerlevel10k` and config it.

---

## Wait List
1. [[Install and Configure Debtap]]
1. [[Install Ferdium]]
1. Install `alacritty`, `zed`, `notable`.

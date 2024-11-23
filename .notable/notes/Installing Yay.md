---
title: Installing Yay
created: '2024-10-24T17:03:16.413Z'
modified: '2024-11-05T23:08:43.571Z'
---

# Installing Yay

## 1. Install Required Dependencies:
``` bash
sudo pacman -S --needed base-devel git
```
## 2. Clone Yay Repository:
``` bash
git clone https://aur.archlinux.org/yay.git
```
## 3. Navigate to Yay Directory:
``` bash
cd yay
```
## 4. Build and Install Yay:
``` bash
makepkg -si
```
## 5. Verify Installation:
``` bash
yay --version
```

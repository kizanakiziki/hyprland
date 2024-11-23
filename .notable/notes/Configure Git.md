---
title: Configure Git
created: '2024-10-24T15:18:26.802Z'
modified: '2024-11-05T23:09:12.535Z'
---

# Configure Git

## 1. Install Git:
``` 
sudo pacman -Sy git
```
## 2. Check Git is installed: 
```
git --version
```
## 3. Configure Git
``` bash
# set username
git config --global user.name "usernamehere"

# set email
git config --global user.email "email@here"
```

## 4. Create Projects Folder
``` bash
# Create Projects Folder
mkdir ~/Projects/

# move to Projects Folder
cd ~/Projects/

# Create Folder to use Github Repository
mkdir hypr

# Or clone github repository in Projects folder
git clone <your github repository link>
```

## 5. Initialize Git:
```
git init
# this will make folder .git in that directory
```
```
git status
# To show the status after use init
```

---
6. Create new files with `touch` or whatever you want
7. Check status with `git status`. Now git is aware with new files. 
8. Git Staging Environment:
```
# This is the core function of Git.
git add .
# or
git add --all
# . will add all files from the folder.
# to add folder or files, just use git add <folder name> or git add <filesname>

# check status
git status
``` 
9. Git Commit
```
# after adding files to staging, make sure to commit to repository.
git commit -m "leave messages here"
# leaving messages is a must~
```

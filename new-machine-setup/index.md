---
title: New machine setup
nav: 2
---

# Software installations

## Visual Studio Code
[Visual Studio Code setup](https://code.visualstudio.com/docs/setup/windows)

## Visual Studio Community
[Visual Studio Community Setup](https://visualstudio.microsoft.com/)

## Git Setup
Visual Studio will install Git by default.  To confirm type: `git -v`

1. Configure user name and user email

    `git config --global user.name "First Last"`
    `git config --global user.email "your.email@example.com"`

2. Setup SSH Key

    `ssh-keygen -t rsa -b 4096 -C "your.email@example.com"`

3. Extract public key

    `notepad %USERPROFILE%\.ssh\id_rsa.pub`

4. Add the key to Git

    Profile -> Settings -> SSH and GPG keys

## Install Windows Subsystem for Linux (WSL)

[How to install WSL](https://learn.microsoft.com/en-us/windows/wsl/install)

1. From powershell this will install WSL with an Ubuntu distro

    `wsl --install`

2. Reboot

## Install Docker in WSL

I found the eaiest way is from VS Code

1. click the Open a Remote Window in the bottom left
2. select New Dev Container
3. you will be promoted to install Docker in WSL



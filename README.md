# wsl_config
I recently moved from a MacBook Pro to a Windows machine. I've always been a fan on Linux Systems, and espessially the terminals and shells. I've recently learned of WSL as a solution to be able to use linux tools on my Windows system without setting up a full Linux VM or dual booting Windows and Linux on disk. My goal is to have my complete setup as I had it on my MacBook using fish shell, vim and tmux.
This repositry attempts to record the various steps in setting up WSL on Windows for those fanboys out there.

## Step 1 - Getting Windows Terminal and WSL
To get Windows Terminal, check out the Microsoft Store, which should have the latest stable version. Windows Terminal is decent replacement for the typical linux terminal, or iTerm 2 which I used on the Mac.

I'll glace over the WSL steps. First you need to enable the following Windows features: Virtual Machine Platform; Windows Subsystem for Linux.

![Windows Feature](https://github.com/SteveCadaver/wsl_config/raw/master/resources/windows_feature.PNG)


Next you need to find a prefered distro WSL, which you may find by searching WSL in the Microsoft Store. Common distros include Ubuntu 20.04 LTS, Debian and Alphine. Im currently testing the Debian WSL.

An optional setting is to set WSL 2 as the default:
```
wsl --set-default-version 2
```

## Step 2 - 

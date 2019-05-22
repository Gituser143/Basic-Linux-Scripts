# Basic Linux Scripts Along with one liners
Scripts to do those basic tasks that are quite tedious...
Keep these scripts in a custom bin folder and add this folder to $PATH

How to add this folder? 

gedit .profile and then 
#### export PATH="$PATH:/root/bin"

So here's how we start :

#### #!/bin/bash

#### #Enter your bash commands, lines preceeded with a '#' are comments.

# Scripts : 
## i) dpkg_lock for the dpkg frontend lock error
## ii) update for full system update and upgrade
## iii) bitlocker for decrypting and mounting devices
first use fdisk -l to find the drive location. If drive is in sdb1, then run "bitlocker b1"

# One liners :
## i) gets the gedit preferences tab back
#### gsettings set org.gnome.settings-daemon.plugins.xsettings overrides '@a{sv} {"Gtk/ShellShowsAppMenu": <int32 0>}'

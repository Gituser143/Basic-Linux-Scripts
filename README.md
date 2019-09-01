# Basic Linux Scripts Along with one liners
Scripts to do those basic tasks that are quite tedious...
Keep these scripts in a custom bin folder and add this folder to $PATH

How to add this folder? 

    gedit .profile 
    add this line => export PATH="$PATH:/root/bin"

So here's how we write a script :

    #!/bin/bash
    #Enter your bash commands, lines preceeded with a '#' are comments.

# Scripts : 
## i) dpkg_lock for the dpkg frontend lock error
    Just run the script, but be cautious. Run it only if error is thrown.
## ii) update for full system update and upgrade
    Just run, if dpkg lock error comes up, use the above script and then run.
## iii) bitlocker for decrypting and mounting devices
    If dislocker is not installed, then run "apt-get install dislocker".
    First use "fdisk -l" to find the drive location. 
    If drive is in sdb1, then run "bitlocker b1". If drive is in sdc2, then run "bitlocker c2".


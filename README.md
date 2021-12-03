
# Arch Rice


## Update mirrors

    sudo reflector --latest 20 --protocol https --sort rate --save /etc/pacman.d/mirrorlist
 
 ## Update system

    sudo pacman -Syu
**reboot**

## Download base-devel & xorg

    sudo pacman -S --needed base-devel
    
    sudo pacman -S xorg
   **reboot**

## Update Paru

    paru
**reboot**

##  Install all the packages

    sudo pacman -S --needed --noconfirm --sudoloop <packges>
**reboot**

## Install grub theme

    cd Downloads
    git clone https://github.com/vinceliuice/grub2-themes.git
    cd grub2-themes
    sudo ./install.sh


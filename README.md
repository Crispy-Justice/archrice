# Arch Rice


## Update mirrors

    sudo reflector --latest 20 --protocol https --sort rate --save /etc/pacman.d/mirrorlist

## Download base-devel & xorg

    sudo pacman -S --needed base-devel
    
    sudo pacman -S xorg

## Update Paru

    paru

##  Install all the packages

    sudo pacman -S --needed --noconfirm --sudoloop <packges>


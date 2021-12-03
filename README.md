
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

## Install oh-my-zsh

    sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
    git clone --depth 1 https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

  
## Personalize

    cd Downloads
    git clone https://github.com/Crispy-Justice/archrice.git
    cd archrice
    chmod +x install.sh
    ./install.sh

## Install grub theme

    cd Downloads
    git clone --depth 1 https://github.com/vinceliuice/grub2-themes.git
    cd grub2-themes
    sudo ./install.sh


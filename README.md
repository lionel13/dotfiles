# my dotfiles



`sudo pacman -S git less neovim xdg-user-dirs xorg-server xorg-xinit xorg-setxkbmap xorg-xsetroot bspwm sxhkd dmenu picom alacritty neofetch feh polybar zsh zsh-syntax-highlighting zsh-autosuggestions ttf-meslo-nerd firefox-i18n-fr firefox-ublock-origin`


## Xorg

1. Install Xorg packages

    `sudo pacman -S xorg-xinit xorg-server xorg-xsetroot`

## Zsh

1. install zsh packages
  
  `sudo pacman -S zsh zsh-syntax-highlighting zsh-autosuggestions`

2. create directories

  `mkdir $HOME/.local/state/zsh`

  `mkdir $HOME/.cache/zsh`

## Installation lf

installer lf zathura zathura zathura-pdf-poppler
installer le package AUR : ctpv-git 
cp /usr/share/doc/lf/lfrc.example to ~/.config/lf/lfrc
ajouter les lignes suivantes au fichier ~/.config/lf/lfrc :
set previewer ctpv
set cleaner ctpvclear
&ctpv -s $id
&ctpvquit $id



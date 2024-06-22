# GruvboxDWM
My Dwm simple and basic rice 🌱

# Updating your system

```
sudo pacman -Syyu
```

# Installing essentials
```
sudo pacman -S wget curl
```
# Installing JetBrainsMono Nerd Fonts
```
sudo pacman -S ttf-jetbrains-mono-nerd 3.2.1-2
```
# Installing kitty
```
sudo pacman -S kitty
cp $HOME/GruvboxDWM/kitty/ $HOME/.config
```
# Installing FastFetch
```
sudo pacman -S fastfetch
cp $HOME/GruvboxDWM/fastfetch/ $HOME/.config/
```
# Installing Neovim
```
sudo pacman -S neovim
git clone https://github.com/NvChad/starter ~/.config/nvim 
```
# Installing lxappearance 
```
sudo pacman -S lxappearance
```
# Installing DWM, Dmenu amd Slstatus (I don't use St) ##
```
cp $HOME/GruvboxDWM/dwm $HOME/.config/
cp $HOME/GruvboxDWM/dmenu $HOME/.config
cp $HOME/GruvboxDWM/slstatus $HOME/.config
```
```
cd $HOME/.config/
```
```
cd dwm/
make
sudo make install
```
```
cd ..
```
```
cd /dmenu/
make
sudo make install
```
```
cd /slstatus/
make
sudo make install
```
```
cd ..
cd ..
```
```
mkdir /usr/share/xsessions/ 
cp $HOME/GruvboxDWM/dwm.desktop /usr/share/xsessions/
```
## DWM, Dmenu and Slstatus installation completed ##
```
cd $HOME 
```
# installing pfetch
```
cd $HOME/GruvboxDWM/pfetch
make 
sudo make install
```
# installing hsetroot
```
sudo pacman -S hsetroot
```
# installing starship
```
curl -sS https://starship.rs/install.sh | sh
```
Add the following to the end of ~/.bashrc:
```
eval "$(starship init bash)"
```

If you are using Zsh then Add the following to the end of ~/.zshrc:
```
eval "$(starship init zsh)"
```
Installing Gruvbox Rainbow Preset 
```
cp $HOME/GruvboxDWM/starship/gruvbox-rainbow.toml $HOME/.config/
cp $HOME/GruvboxDWM/starship/starship.toml $HOME/.config/ 
```
```
starship preset gruvbox-rainbow -o ~/.config/starship.toml
```
# installing vscode
```
sudo pacman -S code
```
Theme to install in VScode
```
Gruvbox Material
```
# Installation has been Completed

# GruvboxDWM
🌟 Welcome to My Gruvbox DWM Rice! 🌟

Hey there! 👋

I'm super excited to share my Gruvbox DWM rice setup with you! 🎨✨ As a self-proclaimed noob, there might be a few quirks and errors here and there. 😅 So, please give it a whirl in a VM first to avoid any unexpected surprises! 🖥️🔍

This setup is a labor of love, filled with all the colors and tweaks that make my desktop a joy to use. 🌈💻 I'm still learning and growing, so your feedback and patience are greatly appreciated! 🙌

Dive in, have fun, and happy ricing! 🛠️🎉

Cheers! 🥳🍀

Happy ricing! 🛠️🎉
# Showcase 💫✨
![DWM Showcase](https://github.com/SarthakTechie/GruvboxDWM/blob/main/Preview/240622_14h53m19s_screenshot.png)
![DWM Showcase](https://github.com/SarthakTechie/GruvboxDWM/blob/main/Preview/240622_14h45m37s_screenshot.png)

# Updating your system 🔧
```
sudo pacman -Syyu
```

# Installing essentials 💾
```
sudo pacman -S base-devel git libx11 libxft xorg-server xorg-xinit terminus-font wget curl
```
# Installing JetBrainsMono and Awesome Fonts 📝
```
sudo pacman -S ttf-jetbrains-mono-nerd ttf-font-awesome 
```
# Installing kitty 🐱‍💻
```
sudo pacman -S kitty
cp $HOME/GruvboxDWM/kitty/ $HOME/.config
```
# Installing FastFetch & Pfetch 📊
```
sudo pacman -S fastfetch
cp $HOME/GruvboxDWM/fastfetch/ $HOME/.config/
```
```
cd $HOME/GruvboxDWM/pfetch
make 
sudo make install
```

# Installing Neovim ✍️
```
sudo pacman -S neovim
git clone https://github.com/NvChad/starter ~/.config/nvim && nvim
```
For neovim themes do space + t + h
```
gruvbox
```
# Installing lxappearance 🗂️
```
sudo pacman -S lxappearance
```
```
 Icon theme --> Install --> select $HOME/GruvboxDWM/gruvbox-plus-icon-pack.5.4.tar.gz
```
# Installing DWM, Dmenu amd Slstatus 📥 
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
## DWM, Dmenu and Slstatus installation completed ☑️

# installing hsetroot for wallpaper 🖼️
```
sudo pacman -S hsetroot
```
# you can also use nitrogen as an alternative 
```
sudo pacman -S nitrogen
```

# installing starship 🚀
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
# installing vscode </>
```
sudo pacman -S code
```
Theme to install in VScode
```
Gruvbox Material
```
# Basic Shortcuts ⌨

| Shotcut keys  | Funtions      |
| ------------- | ------------- |
| Super + Q     | Quiting apps or Kill |
| Super + Shift + Q  | Killing DWM  |
| Super + P     | Dmenu_run |
| Super + Shift + Enter  | Terminal (Kitty)  |

# Congratulation Installation has been Completed! 🥳🎉

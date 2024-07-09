# GruvboxDWM
🌟 Welcome to My Gruvbox DWM Rice! 🌟

Hey there! 👋

I'm super excited to share my Gruvbox DWM rice setup with you! 🎨✨ As a self-proclaimed noob, there might be a few quirks and errors here and there. 😅 So, please give it a whirl in a VM first to avoid any unexpected surprises! 🖥️🔍

This setup is a labor of love, filled with all the colors and tweaks that make my desktop a joy to use. 🌈💻 I'm still learning and growing, so your feedback and patience are greatly appreciated! 🙌

Dive in, have fun, and happy ricing! 🛠️🎉

Cheers! 🥳🍀

Happy ricing! 🛠️🎉
# Showcase 💫✨
![DWM Showcase](https://github.com/SarthakTechie/GruvboxDWM/blob/main/ShowCase/Screenshot_20240623_083752.png)
![DWM Showcase](https://github.com/SarthakTechie/GruvboxDWM/blob/main/ShowCase/rest.png)

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
cp -r $HOME/GruvboxDWM/kitty/ $HOME/.config
```
# Installing FastFetch & Pfetch 📊
```
sudo pacman -S fastfetch
cp -r $HOME/GruvboxDWM/fastfetch/ $HOME/.config/
```
```
cd $HOME/GruvboxDWM/pfetch
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

# Installing SuperFile 📁
```
bash -c "$(wget -qO- https://superfile.netlify.app/install.sh)"
```
change theme = 'gruvbox' ~/.config/superfile/config.toml
```
to run super file type 'spf'

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
cp -r $HOME/GruvboxDWM/dwm $HOME/.config/
cp -r $HOME/GruvboxDWM/dmenu $HOME/.config
cp -r $HOME/GruvboxDWM/slstatus $HOME/.config
```
```
cd $HOME/.config/
```
```
cd dwm/
sudo make install
```
```
cd ..
```
```
cd /dmenu/
sudo make install
```
```
cd /slstatus/
sudo make install
```
```
cd ..
cd ..
```
``` 
sudo cp -r $HOME/GruvboxDWM/dwm.desktop /usr/share/xsessions/
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
cp -r $HOME/GruvboxDWM/gruvbox-rainbow.toml $HOME/.config/
cp -r $HOME/GruvboxDWM/starship.toml $HOME/.config/ 
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

## License

This project is licensed under the MIT License.

## Contact

For any questions or feedback, feel free to contact me!

# Congratulation Installation has been Completed! 🥳🎉

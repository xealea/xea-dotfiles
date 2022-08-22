<p align="center">
  <kbd><br>Xea Red
  <br><br>
  <kbd><img src="https://i.postimg.cc/ht5SDgP7/IMG-20220821-153644-489.png"/></kbd>
  <br><br>Openbox WM<br><br>
  </kbd>

#### installasion
```bash
rsync -avxHAXP --exclude '.git*' .* ~/
```

#### enable mpd on systemd
```bash
systemctl enable mpd
```

#### music for mood booster
```bash
cp -r Music $HOME
```

#### linked font to system
```bash
pushd ~/.fonts/ && sudo ln -vs ~/.fonts/* /usr/share/fonts/* && popd
```

#### linked icons to system
```bash
pushd ~/.icons/ && sudo ln -vs ~/.icons/* /usr/share/icons/* && popd
```

#### linked themes to system
```bash
pushd ~/.themes/ && sudo ln -vs ~/.themes/* /usr/share/themes/* && popd
```

#### refresh font cache
```bash
fc-cache -rv
```

#### Install depedencies archlinux
```yay
sudo paru -S brightnessctl openbox obconf obmenu-generator perl-linux-desktopfiles kvantum xfce4-settings xfce4-power-manager xfce4-terminal neovim nitrogen ncmpcpp alacritty thunar geany rofi pulseaudio python2 polybar dunst mpd mpc feh ffmpeg maim xclip viewnior ksuperkey betterlockscreen networkmanager-dmenu-git xorg-xsetroot xmlstarlet gpick qt5 viewnior rofi exo-utils yad
```

#### Install depedencies debian
```apt
sudo apt-get -y install openbox obconf xfce4-settings xfce4-power-manager xfce4-terminal neovim nitrogen ncmpcpp alacritty thunar geany rofi pulseaudio python2 polybar dunst mpd mpc ffmpeg maim xclip viewnior gpick qtbase5-dev qt5ct qt5-style-kvantum viewnior rofi exo-utils yad feh brightnessctl
```

#### Install depedencies voidlinux
-

#### Optional
Do you use `debian?` You can try my kernel if you want
```sh
wget https://github.com/xealea/xea-linux-x86/releases/download/Linux-5.19.2-xea-xo1-v1/linux-image-5.19.2-xea-xo1.deb
```
```sh
wget https://github.com/xealea/xea-linux-x86/releases/download/Linux-5.19.2-xea-xo1-v1/linux-headers-5.19.2-xea-xo1.deb
```
```sh
sudo dpkg -i linux-headers-5.19.2-xea-xo1.deb linux-image-5.19.2-xea-xo1.deb
```
You can port my kernel/build localy the kernel if you want to try

We'll install this complete setup for hyprland and it involves a few steps, just follow every step.

# install programs using pacman
- flatpak
- git
- curl
- wget
- btop
- nautilus
- kitty
- bluez bluez-utils blueman
- starship
- fastfetch
- nm-connection-editor
- network-manager-applet
- netctl
- dialog
- gnome-text-editor
- grim slurp

Install them all using:
```
sudo pacman -Syu
sudo pacman -S --noconfirm flatpak git curl wget btop nautilus kitty bluez bluez-utils blueman starship fastfetch nm-connection-editor network-manager-applet netctl dialog gnome-text-editor grim slurp
```

# Install an aur helper
### Yay

run this command to install the required packages for yay

```
sudo pacman -S --needed base-devel git
```

now you have those, you can run the following commands to install yay

```
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
```

You just installed yay!

### Paru

run this command to install the required packages for paru

```
sudo pacman -S --needed base-devel git
```

now you have those, you can run the following commands to install paru

```
git clone https://aur.archlinux.org/paru.git
cd paru
makepkg -si
```

You just installed paru!

# GTK theming

### Install nwg-look-bin with your AUR-helper
```
yay -S nwg-look-bin
or
paru -S nwg-look-bin
```

### Install your deisred gtk theme
Just download the theme from github or somewhere else and execute the install.sh file or follow the installation instructions on the site where you found the theme

### Apply the theme
You can now apply the theme and or icons with the nwg-look-bin app you installed, you'll find it as GTK Settings in your apps and if you don't see it, just logout and log back in again.

# Install some apps using flatpak
```
flatpak install flathub com.microsoft.Edge -y
flatpak install flathub md.obsidian.Obsidian -y
flatpak install flathub io.gitlab.idevecore.Pomodoro -y
flatpak install flathub org.audacityteam.Audacity -y
flatpak install flathub com.obsproject.Studio -y
flatpak install flathub org.kde.kdenlive -y
flatpak install flathub org.libreoffice.LibreOffice -y
flatpak install flathub com.mojang.Minecraft -y
flatpak install flathub io.github.ec_.Quake3e.OpenArena -y
flatpak install flathub com.spotify.Client -y
flatpak install flathub com.vscodium.codium -y
```

# Install the core programs for your setup
We'll install these applications that are basically the core of your system

- waybar
- hyprland
- wofi
- kitty
- starship

So most of these should already be installed but if that's not the case, just run:
```
sudo pacman -S --noconfirm waybar hyprland wofi kitty starship
```

Now reboot once you can do that by running: `sudo reboot now`

---


! The keyboard in this setup is set to AZERTY (be) , so change the keyboard layout in the input section of the hyprlannd.conf if you use a QWERTY keyboard !

### 5. Install the config files
- move all the contents of the .config folder to the .config folder in your home directory
- place all the other files and folders except the README and LICENSE files to your home directory



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
'''bash
sudo pacman -Syu
sudo pacman -S --noconfirm flatpak git curl wget btop nautilus kitty bluez bluez-utils blueman starship fastfetch nm-connection-editor network-manager-applet netctl dialog gnome-text-editor grim slurp
'''

# Install an aur helper
### Yay

run this command to install the required packages for yay

'''sh
sudo pacman -S --needed base-devel git
'''

now you have those, you can run the following commands to install yay

'''sh
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
'''

You just installed yay!

### Paru

run this command to install the required packages for paru

'''sh
sudo pacman -S --needed base-devel git
'''

now you have those, you can run the following commands to install paru

'''sh
git clone https://aur.archlinux.org/paru.git
cd paru
makepkg -si
'''

You just installed paru!

---

- starship
- kitty
- waybar
- hyprland
- wofi
- bashrc
- fastfetch

! The keyboard in this setup is set to AZERTY (be) , so change the keyboard layout in the input section of the hyprlannd.conf if you use a QWERTY keyboard !

### 1. Install some apps using pacman:
- yay

### 2. Install nwg-look-bin using an AUR-Helper
- yay -S nwg-look-bin
- paru -S nwg-look-bin

### 3. Install some apps using flatpak
- flatpak install flathub com.microsoft.Edge
- flatpak install flathub md.obsidian.Obsidian
- flatpak install flathub io.gitlab.idevecore.Pomodoro
- flatpak install flathub org.audacityteam.Audacity
- flatpak install flathub com.obsproject.Studio
- flatpak install flathub org.kde.kdenlive
- flatpak install flathub org.libreoffice.LibreOffice
- flatpak install flathub com.mojang.Minecraft
- flatpak install flathub io.github.ec_.Quake3e.OpenArena
- flatpak install flathub com.spotify.Client
- flatpak install flathub com.vscodium.codium

### 4. Reboot your system once

### 5. Install the config files
- move all the contents of the .config folder to the .config folder in your home directory
- place all the other files and folders except the README and LICENSE files to your home directory

### 6. Install and apply your desired gtk theme for other apps
- My themes
   - graphite dark theme https://github.com/vinceliuice/Graphite-gtk-theme 
   - fluent icon theme https://github.com/vinceliuice/Fluent-icon-theme/
- Apply them using the GTK settings app (nwg-look-bin you installed via yay or paru)

### 7. Reboot your system once and you'll be set!

# My Hyprland keybinds


# Hyprconfigs
Everything I need to deploy my arch hyprland ricing setup, complete configs and css files

# Installation
### 1. Install some apps using pacman:
- yay
- flatpak
- git
- curl
- wget
- cmatrix
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

### 4. Install the config files
- move all the contents of the .config folder to the .config folder in your home directory
- place all the other files and folders except the README and LICENSE files to your home directory

### 5. Install and apply your desired gtk theme for other apps
- My themes
   - graphite dark theme https://github.com/vinceliuice/Graphite-gtk-theme 
   - fluent icon theme https://github.com/vinceliuice/Fluent-icon-theme/
- Apply them using the GTK settings app (nwg-look-bin you installed via yay or paru)

### 6. Reboot your system once and you'll be set!

# My Hyprland keybinds
### General
- Mod + Enter -> kitty terminal
- Mod + Space -> Wofi drun
- Mod + CTRL + W -> kill focused app
- Mod + V -> Toggle Floating
- Mod + F -> Files (nautilus)
- Mod + J -> Togglesplit # dwindle
- Mod + K -> Pseudo # dwindle
- Mod + E -> Microsoft Edge (I know I'm stupid)

### Power
- Mod + P -> Shutdown
- Mod + SHIFT + P -> Reboot
- Mod + L -> Lock

### Windows
- Mod + Arrows -> Move window focus
- Mod + SHIFT + Arrows -> Move window
- Mod + Mouse-drag -> Move window
- Mod + SHIFT + Mouse-drag -> Resize window

### Workspaces
- Never use them so not setup at all, (DIY project for you!)

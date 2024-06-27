# Hyprconfigs

# Quick note

! The keyboard in this setup is set to AZERTY (be) , so change the keyboard layout in the input section of the hyprlannd.conf if you use a QWERTY keyboard !

On this page you can find all the info that's needed to setup this complete setup from scratch on a fresh arch linux install
Prequisites: arch linux, wayland, hyprland

# Info

This whole setup includes the following:
- A hyprland config file with custom keyboard shortcuts
- A waybar configuration that looks way too pretty
- A wofi configuration
- A nice kitty terminal config, it's just to get some colors
- A .bashrc file, to get starship working
- A starship configuration to make it pretty
- A fastfetch configuration to make it just like neofetch (completely optional like everythink actually but this really doesn't add much to the setup so I'll forgive you if you don't use it)

I'll put the keyboard shortcuts in here immediately so you can start using the system right when it's installed:
- General
   - Mod = super = Windows
   - Mod + Return -> Terminal
   - Mod + W -> close current app
   - Mod + F -> open files (nautilus)
   - Mod + V -> toggle floating window
   - Mod + E -> open browser, in my case Edge, it's also configured for edge in the config file so change it if you don't like edge.
   - Mod + Space -> wofi drun
- Power
   - Mod + P -> shutdown
   - Mod + Shift + P -> reboot
   - Mod + L -> logout
- Workspaces
   - Mod + Arrows -> switch window
   - Mod + Shift + Arrows -> move window
   - Mod + CTRL + Y -> workspace 1
   - Mod + CTRL + U -> workspace 2
   - Mod + CTRL + I -> workspace 3
   - Mod + CTRL + O -> workspace 4
   - Mod + CTRL + Shift + Y -> move app to workspace 1
   - Mod + CTRL + Shift + U -> move app to workspace 2
   - Mod + CTRL + Shift + I -> move app to workspace 3
   - Mod + CTRL + Shift + O -> move app to workspace 4
   - Mod + mouse drag -> move window
   - Mod + Shift + mouse drag -> resize window

# Installation

### Automatic installation (experimental)
Look in the Automatic.md file and follow the instructions to execute the setup.sh file

### Manual installation (recommended)
Look in the Manual.md file and follow the instructions to get setup

---

# Useful links
Handy pages for if you want to customize this for yourself or if you want to fork this project.
- https://github.com/Alexays/Waybar/wiki/Configuration
- https://github.com/Alexays/Waybar/wiki/Styling
- https://wiki.hyprland.org/
- https://sw.kovidgoyal.net/kitty/
- https://starship.rs/guide/
- https://starship.rs/config/

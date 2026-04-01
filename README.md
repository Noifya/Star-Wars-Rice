# Star Wars Rice

![Desktop Screenshot](https://raw.githubusercontent.com/Zeibytes/Star-Wars-Rice/showcase/desktop/desktop.jpg)
![Desktop Screenshot](https://raw.githubusercontent.com/Zeibytes/Star-Wars-Rice/showcase/desktop/desktop-1.png)

## Installation

### Prerequisites

Install the following dependencies:

```bash
stow                    # For managing symlinks
hyprland                # The window manager duh
fastfetch               # For system information display
kitty                   # Terminal emulator
rofi                    # App launcher
waybar                  # Status bar
waypaper                # GUI wallpaper setter for Wayland and Xorg window managers.
zsh                     # shell
swaybg                  # Wallpaper daemon
playerctl               # Audio
brightnessctl           # ✨
nemo                    # Filemanager
firefox                 # Default browser
network-manager-applet
```

### Quick Start

1. **Clone the repository:**
```bash
git clone --depth=1 https://github.com/Zeibytes/Star-Wars-Rice.git ~/.local/share/Star-Wars-Rice
cd ~/.local/share/Star-Wars-Rice
```

2. **Install dotfiles with stow:**
```bash
stow -v -t ~/.config .config
```
This creates symlinks from the repository to your home directory. If you have existing config files, stow will warn you before proceeding.

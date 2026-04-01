# Star Wars Rice

![Desktop Screenshot](https://raw.githubusercontent.com/Noifya/Star-Wars-Rice/showcase/desktop/desktop.jpg)

## Installation

### Prerequisites

Install the following dependencies:

```bash
stow          # For managing symlinks
hyprland
fastfetch     # For system information display
```

### Quick Start

1. **Clone the repository:**
```bash
git clone --depth=1 https://github.com/noifya/Star-Wars-Rice.git ~/.local/share/Star-Wars-Rice
cd ~/.local/share/Star-Wars-Rice
```

2. **Install dotfiles with stow:**
```bash
stow -v -t ~/.config .config
```
This creates symlinks from the repository to your home directory. If you have existing config files, stow will warn you before proceeding.

# Universal Trainee Saki - Hyprland Dotfiles

## Screenshot

![1](screenshot/img0.png)
![10](screenshot/img1.png)
![10](screenshot/img2.png)
![10](screenshot/img3.png)
![10](screenshot/img4.png)

## Install

If you're using Arch, adding Chaotic-AUR repo is recomended.
To set up your environment using these dotfiles, follow these steps:

1. **Install the required packages using** `pacman`:

```bash
sudo pacman -S hyprland hyprpaper waybar xdg-desktop-portal-hyprland wlogout pavucontrol ttf-fira-sans ttf-font-awesome ttf-jetbrains-mono-nerd alacritty cava fastfetch rofi
```

1.1. **Install Spotify**:

```bash
sudo pacman -S spotify-launcher
curl -fsSL https://raw.githubusercontent.com/spicetify/cli/main/install.sh | sh
```

2. **Clone the Repository**:

```bash
git clone https://github.com/furinalover8236/UTS-Hyprland.git
cd UTS-Hyprland
```

3. **Copy New Configurations**:
Remember you must in `UTS-Hyprland` folder to run following commands

```bash
cp -r .config ~/
cp -r .local ~/
cp -r .spicetify ~/
cp -r wallpaper ~/
cp -r .zshrc ~/
cp -r .bashrc ~/
```

4. **Apply Spicetify theme** (only for those has Spotify installed):
Remember you must in `UTS-Hyprland` folder to run following commands

```bash
spicetify config current_theme pinkyellow
spicetify apply
```

Congratulations! You have successfully completed the installation.

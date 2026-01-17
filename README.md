# dotfiles_laptop_old

### [russian readme version / русская версия readme](./README_RU.md)

my hyprland dotfiles for my HONOR FRI-F56 (MagicBook X14) laptop on Gentoo
[for now, i using CachyOS]

![](images/rice.jpeg "screenshot")

## Installation

**Warning:**  
if you have folders with the same names as in this repository inside your `~/.config/` directory (e.g., `rofi`, `waybar`, `kitty`), they **will be overwritten** during the installation process.  
please make sure to back up these existing configuration folders manually before proceeding to avoid data loss.

1. Clone the repository:
```
git clone https://github.com/entitybtw/dotfiles_laptop_old.git
```

2. copy the contents of the `.config` folder to your local `.config` directory:
```
cp -r dotfiles_laptop_old/.config/* ~/.config/
```

3. remove the cloned repository folder:
```
rm -rf dotfiles_laptop_old
```

4. restart your session or relevant applications to apply the new configurations.
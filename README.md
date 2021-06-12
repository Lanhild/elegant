1. [Components](#components)
2. [Mandatory Packages](#packages)
3. [Installation](#installation)

# elegant-dotfiles
This repository contains the dotfiles necessary to reproduce the look of one of my Arch Linux installation.

# components
To reproduce the same look on your system, you might want to use my [auto-installation](https://github.com/Lanhild/arch-install-script) script. Itdoes everything needed to be done **automatically**.

If you do not wish to use my [script](https://github.com/Lanhild/arch-install-script), then follow the instructions below.

---

# packages
|Packages|Description|Dependencies|
|---|---|---|
|`rofi`|[An application launcher, has many other functions](https://github.com/davatorium/rofi)|Installable via Arch repos
|`mpd`|[Music Player Daemon](https://github.com/MusicPlayerDaemon/MPD)|Installable via Arch repos
|`ncmpcpp`|[CLI Music player daemon front-end](https://github.com/ncmpcpp/ncmpcpp)|Installable via Arch repos
|`zathura`|[PDF reader](https://github.com/pwmt/zathura)|`girara glib gtk3 meson gettext`
|`pywal`|[Colorschemes generation on the fly](https://github.com/dylanaraps/pywal)|`python3 imagemagick procps feh`
## Additionnal informations about packages
A list of the mandatory packages is in the `pkgs.txt` file.

# installation
## Installation with automatic script
```
git clone https://github.com/Lanhild/arch-install-script.git
cd arch-install-script
sudo chmod +x setup.sh
./setup.sh

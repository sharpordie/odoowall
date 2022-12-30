# <samp>ODOOWALL</damp>

Unofficial wallpapers for any Odoo enthusiasts.

## <samp>OVERVIEW</damp>

### Corner variant

<a href="src/odoo-corner-bright.png"><img src="src/odoo-corner-bright.svg" width="49.25%"/></a><img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/1x1.png" width="1.5%"/><a href="src/odoo-corner-darken.png"><img src="src/odoo-corner-darken.svg" width="49.25%"/></a>

### Higher variant

<a href="src/odoo-higher-bright.png"><img src="src/odoo-higher-bright.svg" width="49.25%"/></a><img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/1x1.png" width="1.5%"/><a href="src/odoo-higher-darken.png"><img src="src/odoo-higher-darken.svg" width="49.25%"/></a>

### Middle variant

<a href="src/odoo-middle-bright.png"><img src="src/odoo-middle-bright.svg" width="49.25%"/></a><img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/1x1.png" width="1.5%"/><a href="src/odoo-middle-darken.png"><img src="src/odoo-middle-darken.svg" width="49.25%"/></a>

## <samp>GUIDANCE</damp>

### Set Wallpaper on macOS

```shell
address="https://github.com/sharpordie/odoowall/raw/main/src/odoo-corner-bright.png"
picture="$HOME/Pictures/Backgrounds/odoo-corner-bright.png"
mkdir -p "$(dirname $picture)" && curl -Ls "$address" -o "$picture"
osascript -e "tell application \"System Events\" to tell every desktop to set picture to \"$picture\""
```

### Set Wallpaper on Ubuntu

```shell
address="https://github.com/sharpordie/odoowall/raw/main/src/odoo-corner-bright.png"
picture="$HOME/Pictures/Backgrounds/odoo-corner-bright.png"
mkdir -p "$(dirname $picture)" && curl -Ls "$address" -o "$picture"
gsettings set org.gnome.desktop.background picture-uri "file://$picture"
gsettings set org.gnome.desktop.background picture-options "zoom"
gsettings set org.gnome.desktop.screensaver picture-uri "file://$picture"
gsettings set org.gnome.desktop.screensaver picture-options "zoom"
```

### Set Wallpapers on Windows

```shell

```

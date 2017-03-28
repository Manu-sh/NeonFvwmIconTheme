# NeonFvwmIcon

NeonFvwmIcon is a fork of [Archdroid](https://github.com/GreenRaccoon23/archdroid-icon-theme)
you can found the gtk theme [here](https://github.com/Manu-sh/NeonFvwmGtkTheme)

![screenshot](https://anonimag.es/i/22_02_2017-155501_xorg902fa.png)

### Installation
```bash
git clone https://github.com/Manu-sh/NeonFvwmIconTheme
cd NeonFvwmIconTheme
sudo cp -R NeonFvwmIcon /usr/share/icons
sudo gtk-update-icon-cache -ftq /usr/share/icons/NeonFvwmIcon
```

### Configuration
for setting a theme as default there are two common way

* one way is using theme manager
* another way is using the [default files readed by gtk](https://wiki.archlinux.org/index.php/GTK%2B)

an example of .gtkrc-2.0 file

```
gtk-icon-theme-name = "NeonFvwmIcon"
gtk-theme-name = "NeonFvwmGtk"
gtk-font-name = "Terminus 8"
```

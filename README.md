# theme-switcher
A theme switcher i made for hyprland

## requirements
* swww
* imagemagick
* hyprland

## the file directories
The set-theme script looks in the directory: ~/.local/share/themes

The themes in the directory should have two folders = hypr & kitty

The set-theme script has a command called "make", it has two arguments to it: picture, theme-name

* picture - path to a valid img file (png, jpg, etc.)
* theme-name - the name of the theme
a `set-theme make` command should look like this:
```
set-theme make /path/to/pic.png name-of-theme
```

## must do's

* put the color-get and set-theme scripts in /usr/bin/, the make command on set-theme depends on the color-get script

## ok thats it, i hope you have fun!

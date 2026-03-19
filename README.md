# theme-switcher
A theme switcher i made in bash, for hyprland

## requirements
* swww
* imagemagick
* hyprland

## usage
```
set-theme [theme]
#or
set-theme ls # to list themes in ~/.local/share/themes
```

## the file directories
The set-theme script looks in the directory: ~/.local/share/themes

The themes in the directory should have two folders = hypr & kitty

The set-theme script has a command called "make", it has two arguments to it: picture, theme-name

* picture - path to a valid img file (png, jpg, etc.)
* theme-name - the name of the theme
a `set-theme make` command should look like this:
```
set-theme make /path/to/pic.png [name-of-theme]
```
run this command before doing `set-theme make`:
```
mkdir -p ~/.config/hypr/wall ~/.config/kitty/themes ~/wall
```
and add this to your hyprland conf:
```
source = ~/.config/hypr/wall/wall.conf #if you have a wall.conf there if you set a theme
```
and this for the kitty conf:
```
include ~/.config/kitty/themes/theme.conf #if you have a theme.conf file there if you set a theme
```
## must do's

* put the color-get and set-theme scripts in /usr/bin/, the make command on set-theme depends on the color-get script

## ok thats it, i hope you have fun!

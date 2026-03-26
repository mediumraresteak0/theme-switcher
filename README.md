# Theme-switcher

# A theme switcher in bash for hyprland

## Dependencies
* awww
* hyprland
* kitty
* rofi
* a brain
* bash

## Do this
* make directories > ~/.local/share/themes and ~/.local/share/current-theme
* make a colors.css file in your waybar config and include that file in your waybar style.css
* put scripts set-theme and color-get in /usr/bin/bash

## How to make themes

You have to do it yourself, make a theme directory in ~/.local/share/themes
```
$ mkdir ~/.local/share/themes/[theme name] ~/.local/share/themes/[theme name]/wallpapers
```
Fill the theme's wallpaper dir with your desired wallpapers

And you're done! You made your own theme!

## usage

```
$ set-theme [theme name] # set-theme looks in  ~/.local/share/themes
$ set-theme background # launches rofi and lists the wallpapers in the theme
$ set-theme ls# lists the themes in ~/.local/share/themes
```

## I hope you have fun with my project!

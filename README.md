# Vapor KDE
This repo provides the files needed to use Valve's custom KDE style in use by the Steam Deck's desktop mode. It also
provides custom Firefox CSS to better match the theme.

# Installation
## KDE Theme
* Copy Vapor.colors into ~/.local/share/color-schemes
* Copy the Vapor folder (desktop theme) into ~/.local/share/plasma/desktoptheme (creating any missing folders)
* Log out then back in to refresh available themes
* In system settings:
  * Under "Colors", select Vapor as the color scheme
  * Under "Plasma Style", select Vapor as the theme

## Firefox
* Follow the instructions at https://www.reddit.com/r/FirefoxCSS/wiki/index/tutorials/ to set up/find your
userChrome.css file
* Copy userChrome.css from this folder to replace your userChrome.css
* Copy the contents of "KDE Stuff" to the same folder as the userChrome.css you just copied over
* Make sure you use this with the "Dark" theme on Firefox directly, not "System Auto" as that breaks a lot of styles

# Copyright
Copyright for the theme files belong to Valve (see Valve Stuff/README.md), but they are licensed under GPL version 3.
As such, this repository is also licensed under GPL version 3.

The titlebar icons are from KDE (located at /usr/share/themes/Breeze/assets/) and are licensed under LGPL-3.0-only (see KDE Stuff/README.md)

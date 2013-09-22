# Phosphene
A GNOME 3.8 theme for GNOME Shell, GTK 3, Mutter, and Firefox. [See the preview](http://hdni.github.io/rice/assets/phosphene_preview.png).

## Installation
### GNOME Shell, GTK 3, Mutter
* Put the entire repository in `/usr/share/themes/`
* You can then use the Tweak Tool to set the themes.

### Firefox
* Install the [Stylish](https://addons.mozilla.org/en-US/firefox/addon/stylish/) extension.
* Install the [FXChrome](https://addons.mozilla.org/en-US/firefox/addon/fxchrome/) theme.
* Go to your [Add-ons Manager](about:addons), select the User Styles page and then write a new style.
* Give the style a name and paste the contents of firefox.css.
* You will need to set to tabs to be on the bottom. To do so, set browser.tabs.onTop to "false" in [about:config](about:config).
* Also, right click the tab bar, open the Customize window, and toggle the "Use small icons" option.
* This style works well with the [Movable Firefox Button](https://addons.mozilla.org/en-us/firefox/addon/movable-firefox-button/), [Favicon Restorer](https://addons.mozilla.org/en-us/firefox/addon/favicon-restorer/?src=search), and [Hide Tabbar](https://addons.mozilla.org/en-us/firefox/addon/hide-tabbar/?src=ss) extensions.

### GNOME Terminal
* Download the [gnome-terminal.xml](https://github.com/hdni/dotfiles/blob/master/gnome-terminal.xml) file and run the following command: `gconftool-2 --load gnome-terminal.xml`. Keep in mind that this will **erase your previous settings**.
* Set the profile to "phosphene" by right-clicking on your terminal window and choosing it from the Profiles menu.

## Notes
* This theme is not complete yet, and still has bugs. If you find any, please use the issues tracker!
* The GNOME Shell theme uses Akzidenz Grotesk. If you do not have it installed, you can change the font to your liking in the `gnome-shell.css` file.

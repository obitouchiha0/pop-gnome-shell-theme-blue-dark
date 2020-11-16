# pop-shell-theme-blue-dark

This is a modified version of pop-shell theme to match pop-blue-gtk-theme<br>
Currently it do not have a light variant 😔.<br>

⚠ this only works with pop os, with pop-shell-theme set as default shell theme<br>

## Screenshots
<p align="center">
 <img src="https://raw.githubusercontent.com/obitouchiha0/pop-gnome-shell-theme-blue-dark/main/Screenshot-1.png"/>
 <img src="https://raw.githubusercontent.com/obitouchiha0/pop-gnome-shell-theme-blue-dark/main/Screenshot-2.png"/>
</p>

## How to install<br>

$ glib-compile-resources gnome-shell-theme.gresource.xml<br>
$ sudo cp ./gnome*.gresource /usr/share/gnome-shell/theme/Pop<br>

This will replace default pop-gnome-shell-theme<br>
To revert back,<br>
$ sudo apt reinstall pop-gnome-shell-theme<br>

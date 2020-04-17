# arcolinuxd-iso

With this github you can build your own ArcoLinuxD version.

This dedicated version is for developing ArcoLinux with Spectrwm as its window manager.

Beta config.

yay cherrytree

Issues so far: Kdenlive and Google Earth Pro do not load from autostart into assigned workspaces.

Dmenu continues to load from CLI but not from the config.

Feh breaks the config, and Nitrogen only loads manually.

Picom does not load in autorun but does from CLI.

There is no tray implemented, though alternative bars are available ...

Addendum 01: Dmenu working with MOD+F12. Since workspaces up to 22 use keybinds that can be re-assigned, immediately some Arco standard bindings can be assigned, and will be. (Since removed while tracking down exceptions.

Addendum 02: Capable of taking screenshots from the script in terminal, but not from keybind. Picom might be the culprit for breaking the config. Many lines commented out to get back in.

Addendum 03: Breakthrough - the bar is functional. Colorizing it is over my head for now, but doable. Does not show CPU temp, but that's my system. Not reading packages or upgrades. RAM and Kernel displayed.

Addendum 04: Borked when changing keybindings from Spectrwm defaults to ArcoLinux defaults. Careful with thy keybinds.

Addendum 05: Logged in on bare metal dual monitor and ran Spectrwm in VirtualBox.

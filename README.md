# arcolinuxd-iso

With this github you can build your own ArcoLinuxD version.

This dedicated version is for developing ArcoLinux with Spectrwm as its window manager.

Initial config only. Issues will come and go.

Application(s) required for this edition not normally in an ArcoLinux ISO: CherryTree

Issues so far: Kdenlive and Google Earth Pro do not load from autostart.

Addendum 01:

After some tinkering on other parts of the config and a reboot in VB, Kdenlive and Google Earth Pro autorun worked, but the apps did not go to their assigned workspaces, but workspace 1 instead.

Dmenu continues to load from CLI but not from the config.

Addendum 02:

Variety and Feh not working. Parcellite installed and also unavailable since there is no tray implemented.

Addendum 03: Feh working when files in Download directory, but not /usr/share/...

Addendum 04: Dmenu working with MOD+F12. Since workspaces up to 22 use keybinds that can be re-assigned, immediately some Arco standard bindings can be assigned, and will be.

Addendum 05: Capable of taking screenshots from the script in terminal, but not from keybind. Picom might be the culprit for breaking the config. Many lines commented out to get back in.

Addendum 06: Breakthrough - the bar is functional. Next is to colorize it. Does not show CPU temp, but that's my system. Not reading packages or upgrades (yet). RAM and Kernel displayed. Feh is working again. I corrected the typo behind that.

Addendum 07: Borked when changing keybindings from Spectrwm defaults to ArcoLinux defaults.

Addendum 08: Chased down the keybinding(s), sloppy copy paste(s), and glaring oversights that prevented loading. It is not advised to tinker with stock keybindings without explicitly releasing them.

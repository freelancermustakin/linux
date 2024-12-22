# linux
Linux info &amp; more. etc 

# Ubuntu basic command
> ubuntu `` full update and upgrade ``
```
$ sudo apt update
$ sudo apt upgrade
$ sudo apt full-upgrade
```
### Unable to access location problems fixed
> ubuntu ssd/hdd access problems fixed
```
$ sudo apt-get install nfs-common
$ sudo apt-get install cifs-utils
$ sudo ntfsfix -d /dev/sdb1
```

### Linux internet speed meter
> ubuntu `` live net speed on ubuntu panel ``
```
$ sudo apt install gnome-shell-extensions
$ sudo apt-get install chrome-gnome-shell
https://addons.mozilla.org/en-US/firefox/addon/gnome-shell-integration/

internet speed meter extensions link
https://extensions.gnome.org/extension/4478/net-speed/
https://extensions.gnome.org/extension/7565/network-speed-monitor/ (best tools)
https://extensions.gnome.org/extension/2980/internet-speed-meter/
https://extensions.gnome.org/extension/6733/crazy-internet-speed-meter/
```
### GDM Settings install/Uninstall
> any linux distributions support
```
$ sudo apt install gdm-settings libglib2.0-dev-bin
$ gdm-settings
$ sudo apt remove --autoremove gdm-settings
```

### gnome-tweaks
> any linux distributions support
```
$ sudo apt install gnome-tweaks
$ gnome-tweaks
```

### Java install
```
$ sudo apt install openjdk-11-jdk
$ java -version
```

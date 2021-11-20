# linux-tricks-and-howto
A collection of tricks and good packages for linux

### [greetd](https://wiki.archlinux.org/index.php/Greetd)
Allows you start any application after login

### Audio
Installing `alsa-utils` allows you to use ´alsamixer´ in the command line and adjust the volume

### Wireless
Install `NetworkManager`, enable and start NetworkManager with `systemctl` and connect to a network with the interface by typing ´nmtui´ in the command line. For more advanced connections, install and use ´nm-connection-editor´ (require window manager).

### Disable beep
Create the file `/etc/profile.d/disable-beep.sh` and insert the following
```
  setterm -blength 0
```

### xrandr
Set frame rate
```
xrandr --output DP-1 --mode 1920x1080 --rate 144
```

For changing multi screen settings, use `arandr` (a GUI for `xrandr`).

### Nvidia
```
nvidia-xconfig
```

### Setup scripts

https://github.com/ChrisTitusTech/ArchTitus

# transmissionbt-desktop-tak
[![transmissionbt-desktop-tak](https://snapcraft.io/transmissionbt-desktop-tak/badge.svg)](https://snapcraft.io/transmissionbt-desktop-tak)
![snap arch](https://badgen.net/snapcraft/architecture/transmissionbt-desktop-tak)
![snap size](https://badgen.net/snapcraft/size/transmissionbt-desktop-tak/amd64/stable)

## Snap Description
UnOfficial release of Transmission bittorrent for Desktop (with graphical UI)\
https://snapcraft.io/transmissionbt-desktop-tak

(For Server edition see [transmissionbt-tak](https://github.com/TehAppKiller/transmissionbt-tak))

## qBittorrent Description
<img src="/icon.svg" width="100">
Transmission is a Fast, Easy and Free Bittorrent Client.

See https://transmissionbt.com for more details.

## Information
Transmission BT Release\
Utils (transmission-create, -edit, -show) are accessible directly\
Snap dependencies required: mesa-2404, gnome-xx-2404, gtk-common-themes

**!!! Files can only be written in a directory owned by `user` !!!**

This is due to current behavior and restrictions of snaps by Canonical.\
Please use Server edition if you need to write in `root`-owned folders: https://snapcraft.io/transmissionbt-tak

## FAQ
See my common doc about [FAQ](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#FAQ).

### How to access Configuration file
You can access the snap data in 2 ways:

#### - Directly
With default snapd installation:
```
/root/snap/transmissionbt-tak/current/.config/transmission-daemon/settings.json
```

#### - Via shell
In shell mode you can edit the file with Vim:
```
sudo snap run --shell transmissionbt-tak.qbittorrent
vi $HOME/.config/transmission-daemon/settings.json
```
One help sheet of Vim commands available [here](https://devhints.io/vim).

## Building
See my common doc about [building a snap](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#Building).

## Versionning
See my common doc about [versionning](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#Versionning).

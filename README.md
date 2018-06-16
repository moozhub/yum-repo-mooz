# yum-repo-mooz
The mooz repo

### MOOOOOoo?

The repository has moved to [Copr](https://copr.fedorainfracloud.org/coprs/mooz/yum-repo-mooz/). If you're using this repository, re-run the instructions below.

### Overview

My attempts at building RPM packages for programs I need. Hopefully they are of use to others.

Using this repository assumes that you are also using the [EPEL](https://fedoraproject.org/wiki/EPEL) repo.

### Repository highlights

* [kodi-17.6](https://github.com/xbmc/xbmc/tree/Krypton) - Kodi Home Theater Software
* [openrazer-2.3.0](https://github.com/openrazer/openrazer) - A collection of Linux drivers for Razer devices
* [polychromatic-0.3.12](https://github.com/lah7/polychromatic) - Graphical front end and tray applet for configuring Razer peripherals on GNU/Linux
* [rtorrent:master](https://github.com/rakshasa/rtorrent) - rTorrent BitTorrent client
* [signal-desktop-1.12.1](https://github.com/signalapp/Signal-Desktop) - Signal — Private Messenger for Windows, Mac, and Linux
* [solaar-0.9.2](https://github.com/pwr/Solaar) - Linux devices manager for the Logitech Unifying Receiver

### Instructions

CentOS / EL7

`sudo yum -y install yum-utils`

`sudo yum-config-manager --add-repo=https://raw.githubusercontent.com/moozhub/yum-repo-mooz/master/elmooz.repo`

### Install packages

`sudo yum install signal-desktop`

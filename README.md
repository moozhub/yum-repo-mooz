# yum-repo-mooz
The mooz repo

### Overview

My attempts at building RPM packages for programs I need. Hopefully they are of use to others.

Using this repository assumes that you are also using the [EPEL](https://fedoraproject.org/wiki/EPEL) repo.

### Repository highlights

**Kodi requires the ffmpeg package which I cannot host at the moment. Consider enabling the [epel-multimedia](https://negativo17.org/multimedia/) repository in this case.**

**The openrazer driver has known problems with the stock CentOS kernel. In order for the driver to function properly on the stock kernel a workaround must be put in place (see [#3](https://github.com/moozhub/yum-repo-mooz/issues/3#issuecomment-408646741)). However, installing the latest `kernel-ml` package from [Elrepo](http://elrepo.org/tiki/kernel-ml) is another easier option if you're not interested in setting any workarounds.**

* [kodi-17.6](https://github.com/xbmc/xbmc/tree/Krypton) - Kodi Home Theater Software
* [openrazer-2.5.0](https://github.com/openrazer/openrazer) - A collection of Linux drivers for Razer devices
* [polychromatic-0.3.12](https://github.com/lah7/polychromatic) - Graphical front end and tray applet for configuring Razer peripherals on GNU/Linux
* [rtorrent-0.9.7](https://github.com/rakshasa/rtorrent) - rTorrent BitTorrent client
* [signal-desktop-1.15.0](https://github.com/signalapp/Signal-Desktop) - Signal — Private Messenger for Windows, Mac, and Linux
* [solaar-0.9.2](https://github.com/pwr/Solaar) - Linux devices manager for the Logitech Unifying Receiver

### Instructions

CentOS / EL7

`sudo yum -y install yum-utils`

`sudo yum-config-manager --add-repo=https://raw.githubusercontent.com/moozhub/yum-repo-mooz/master/elmooz.repo`

### Install packages

`sudo yum install signal-desktop`

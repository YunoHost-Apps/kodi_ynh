Kodi for YunoHost
---------------------

**This package is currently under development, install it at your own risk.**

[Kodi](https://kodi.tv) transform your YunoHost server on media center that is designed to look great on your big screen TV but is just as home on a small screen.

**Shipped version:**
* 16.1 on Debian from jessie backports
* 17.3 on Raspberry from official raspbian repo

[![Install Kodi with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=kodi)

## Current package status
* The scprit use jessie backports to install Kodi 16 (We have to wait for Debian Strech officialy install Kodi 17)
* A dedicated kodi user is create
* Use of systemd
* You can launch Kodi with the ```sudo systemctl start kodi``` command or stop Kodi with ```sudo systemctl stop kodi```
* You can choose if you want that Kodi start at YunoHost server statup
* You can access to the control web interface only if you choose a "/" path (Reverse proxy issue)
* Kodi directly start after package installation

## To do
* Add the control web interface to YunoHost user interface
* Maybe we can launch Kodi from YunoHost web interface instead of SSH

## Links

 * Report a bug: Use GitHub issues
 * Kodi website: https://kodi.tv
 * YunoHost website: https://yunohost.org/
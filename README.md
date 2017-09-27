Kodi for YunoHost
---------------------

**This package is currently under development, install it at your own risk.**

[Kodi](https://kodi.tv) transform your YunoHost server on media center that is designed to look great on your big screen TV but is just as home on a small screen.

**Shipped version:** 16.1 from jessie backports

[![Install Kodi with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=kodi)
![](https://github.com/nextcloud/screenshots/blob/master/files/filelist.png)

## Current package status
* The scprit use jessie backports to install Kodi 16 (We have to wait for Debian Strech officialy install Kodi 17)
* A dedicated kodi user is create
* Use of systemd
* You can launch Kodi with the ```sudo systemctl start kodi``` command

## To do
* Test package on Raspberry (maybe Kodi is avaible in v17 on raspbian repo instead of v16 in debian jessie backports)
* Add option to launch Kodi at server startup
* Add the control web interface to YunoHost user interface
* Maybe we can launch Kodi from YunoHost web interface instead of SSH

## Links

 * Report a bug: Use GitHub issues
 * Kodi website: https://kodi.tv
 * YunoHost website: https://yunohost.org/
Kodi for YunoHost
---------------------

**This package is currently under development, install it at your own risk.**

[Kodi](https://kodi.tv) transform your YunoHost server on media center that is designed to look great on your big screen TV but is just as home on a small screen.

**Shipped version:**
* 16.1 on Debian from jessie backports
* 17.3 on Raspberry from official raspbian repo

[![Install Kodi with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=kodi)

## Current package status
* The scprit use jessie backports to install Kodi 16 on x86 machines (We have to wait for YunoHost Debian Strech support or use testing source)
* A dedicated kodi user is create
* Use of systemd
* You can launch Kodi with the ```sudo systemctl start kodi``` command or stop Kodi with ```sudo systemctl stop kodi```
* You can choose if you want that Kodi start at YunoHost server statup
* You can access to the control web interface from the YunoHost pannel
* Kodi directly start after package installation
* Start and stop Kodi from Admin YunoHost services tab
* SSOWat pannel

## To do
* Test control web interface on Raspberry
* Switch from skipped_uri to protected_uri and try if it still works for jsonrpc and image location
* Check if a "/" path still works
* Write the upgrade and backup script
* Check if webserver port (8080) is free

## Links

 * Report a bug: Use GitHub issues or dedicated forum
 * YunoHost forum thread: [Kodi package](https://forum.yunohost.org/t/kodi-package-yunohost-as-a-media-center/3561/17)
 * Kodi website: https://kodi.tv
 * YunoHost website: https://yunohost.org/
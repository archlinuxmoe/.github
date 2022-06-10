### Moezee
This is a repository of Arch Linux packages that was created for personal use. Contains packages from AUR.

#### Want to use?

First, add the key to the pacman keyring.
```
sudo pacman-key --recv-key 37DA55952430078E --keyserver hkps://keyserver.ubuntu.com
sudo pacman-key --lsign-key 37DA55952430078E
```
Add the following lines to the end of `/etc/pacman.conf`:
```
[moezee]
Server = https://repo.moezee.space/$arch
```
And, then:
```
sudo pacman -Syu
```

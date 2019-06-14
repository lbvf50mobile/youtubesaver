## How do save playlist on yandex disk.

- https://www.youtube.com/playlist?list=PLpXHf5lOtZEkb4y-shvwGoLE7TylmLagL playlist
- https://yandex.ru/support/disk/webdav/webdav-linux.html webdav docs

## Instaling wedav disk on a Ubuntu

- http://techiech.blogspot.com/2013/04/mounting-webdav-directory-in-linux.html
- https://help.ubuntu.ru/wiki/davfs2

- `sudo apt-get install davfs2`
- `sudo dpkg-reconfigure davfs2`
- `sudo chmod 4755 /usr/sbin/mount.davfs`
- `sudo usermod -aG davfs2 $USER`
- `/home/$USER/yandexdisk`
- `mkdir $HOME/.davfs2`
- `vim $HOME/.davfs2/secrets`
- `$PathToMountPoint $USER $PASSWORD`
- `chmod 600 $HOME/.davfs2/secrets`
- `sudo vim /etc/fstab`
- `https://webdav.yandex.ru:443 /home/$USER/yandexdisk davfs user,rw,noauto 0 0`
- **NEED TO RELOGING TO GET INTO THE GROUP!** thanks for Node

### Now just using disk.

- `mount yandexdisk`
- `umount yandexdisk`

[back](README.md)
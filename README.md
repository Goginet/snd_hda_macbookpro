# snd_hda_macbookpro

Compiling and installing driver:
-------------

**fedora package install**
```
dnf install wget make gcc kernel-devel
```
**ubuntu package install**  
```
apt install wget make gcc linux-headers-generic
```
**arch package install**
```
pacman -S wget make gcc linux-headers
```

**build driver**  
```
git clone https://github.com/leifliddy/snd_hda_macbookpro.git
cd snd_hda_macbookpro/
#run the following command as root or with sudo
./install.cirrus.driver.sh
reboot
```

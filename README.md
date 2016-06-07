# flapjack-jessie
Flapjack jessie deb

apt-get install build-essential debhelper config-package-dev git ruby bundler golang

## Replace systemd with sysvinit
apt-get install sysvinit-core sysvinit sysvinit-utils -y

reboot

apt-get remove --purge --auto-remove systemd -y

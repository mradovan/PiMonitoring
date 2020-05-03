# PiMonitoring
Easy way to install Raspberry Pi Monitoring in just few minutes and 5 commands

Install:
sudo apt-get install dirmngr
sudo apt-key adv --recv-keys --keyserver keyserver.ubuntu.com 2C0D3C0F
sudo wget http://goo.gl/vewCLL -O /etc/apt/sources.list.d/rpimonitor.list
sudo apt-get update
sudo apt-get install rpimonitor

Update:
sudo /etc/init.d/rpimonitor update

Automatic update:
sudo /etc/init.d/rpimonitor install_auto_package_status_update

Remove automatic update:
sudo /etc/init.d/rpimonitor remove_auto_package_status_update

Upgrade:
sudo apt-get update
sudo apt-get upgrade
sudo /etc/init.d/rpimonitor update

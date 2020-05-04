# PiMonitoring
Easy way to install Raspberry Pi Monitoring in just few minutes and 5 commands

##Install:<br/>
sudo apt-get install dirmngr<br/>
sudo apt-key adv --recv-keys --keyserver keyserver.ubuntu.com 2C0D3C0F<br/>
sudo wget http://goo.gl/vewCLL -O /etc/apt/sources.list.d/rpimonitor.list<br/>
sudo apt-get update<br/>
sudo apt-get install rpimonitor<br/>

##Update:<br/>
sudo /etc/init.d/rpimonitor update<br/>

##Automatic update:<br/>
sudo /etc/init.d/rpimonitor install_auto_package_status_update<br/>

##Remove automatic update:<br/>
sudo /etc/init.d/rpimonitor remove_auto_package_status_update<br/>

##Upgrade:
sudo apt-get update
sudo apt-get upgrade
sudo /etc/init.d/rpimonitor update

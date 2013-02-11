Bandwidth monitoring script
===========================


This script allows you to monitor and get alerts once you reached the bandwidth limit of your server.


Requirements :
--------------

- postfix (send alers)
- screen (the script is running in a screen)
- vnstat (is used to check the bandwidth)

Installing dependencies :
-------------------------

Ubuntu / Debian Distro:

apt-get install postfix vnstat screen

CentOS / RedHat / Fedora & Co

yum install -y postfix vnstat screen

Usage :
-------

- wget https://raw.github.com/mariusv/bandwidth-monitoring/master/bandwidth.sh
- edit bandwidth.sh and go to MAX ='10' line and just replace 10 with the maximum value you want(the value MUST be in MB)
- chmod +x bandwidth.sh
- ./bandwidth.sh (the script will start a new screen session and as soon as you reached the limit you established will send you an alert email) 

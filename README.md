Bandwidth monitoring script
===========================


This script allows you to monitor and get alerts once you reached the bandwidth limit of your server.


Requirements:
-------------

- postfix (send alers)
- screen (the script is running in a screen)
- vnstat (is used to check the bandwidth)

Installing dependencies:
------------------------

Ubuntu / Debian Distro:

apt-get install postfix vnstat screen

CentOS / RedHat / Fedora & Co

yum install -y postfix vnstat screen

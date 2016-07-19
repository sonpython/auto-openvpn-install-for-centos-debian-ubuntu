# auto-openvpn-install-for-centos-debian-ubuntu
auto-openvpn-install-for-centos-debian-ubuntu inspired by Nyr
##openvpn-install
OpenVPN [road warrior](http://en.wikipedia.org/wiki/Road_warrior_%28computing%29) installer for Debian, Ubuntu and CentOS.

This script will let you setup your own VPN server in no more than a minute, even if you haven't used OpenVPN before. It has been designed to be as unobtrusive and universal as possible.

###Installation
Run the script and follow the assistant:

`wget https://git.io/vpn -O ~/openvpn-install.sh && bash ~/openvpn-install.sh`

For Debian users running the script with "sh" instead of bash

`wget https://git.io/vpn -O ~/openvpn-install.sh && sh ~/openvpn-install.sh`

Once it ends, you can run it again to add more users, remove some of them or even completely uninstall OpenVPN.


`bash ~/openvpn-install.sh`

The menu option as bellow:

    What do you want to do?
        1) Add a cert for a new user
        2) Revoke existing user cert
        3) Remove OpenVPN
        4) Exit
    Select an option [1-4]: 

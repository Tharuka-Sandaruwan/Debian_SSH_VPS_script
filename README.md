# Debian_SSH_VPS_script


SSH+SSL+DROPBEAR+SQUID autoscript for Debian VPS 

Tested on Debian10 (Buster)  X64 

To install
     wget https://raw.githubusercontent.com/Tharuka-Sandaruwan/Debian_SSH_VPS_script/main/autoscript && chmod +x autoscript && ./autoscript

  PORTS

    OpenSSH Port : 22
    Nginx Port : 80
    Privoxy Port : 8181 8086
    Dropbear Port: 442 555
    OpenVPN Port : 110. 25000
    Stunnel Port : 443 445
    Squid Port : 3128 8000 8080
    Badvpn Port : 7300

  * you can change the ports by changing the config files                        
  * can use https://html-online.com/editor/ to make a server banner.         
  * Please add auto reboot after completion(if you need)
        
        sudo nano /etc/crontab
        0 0 * * * root reboot 

  Script by: Tharuka Sandaruwan

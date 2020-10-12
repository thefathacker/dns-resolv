# dns-resolv
Configuration for DNS resolution

## Installation
```
sudo apt install -y bind9
cd /etc/bind
sudo rm named.*
sudo git init
sudo git pull https://github.com/thefathacker/dns-resolv
sudo systemctl restart bind9
sudo cp /etc/bind/rndc.cron /etc/cron.d/rndc.cron
```
## Update
```
cd /etc/bind
sudo git pull https://github.com/thefathacker/dns-resolv
sudo cp /etc/bind/rndc.cron /etc/cron.d/rndc.cron
sudo systemctl restart bind9
```
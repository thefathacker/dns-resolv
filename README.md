# dns-resolv
Configuration for DNS resolution

## Installation

sudo apt install -y bind9
cd /etc/bind
sudo rm named.*
sudo git init
sudo git pull https://github.com/thefathacker/dns-resolv
sudo systemctl restart bind9
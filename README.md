# XtreamCodes 2.9 Admin UI

## What is this?

A web interface that connects with the database of XtreamCodes 2.9 for adminsa

#### Features:

- Add Load-Balancer
- Add Streams
- Add Bouquets

## How to install

```
apt install python -y
wget https://raw.githubusercontent.com/tweakunwanted/xc-2.9-admin/master/install.py 
python install.py
```

## Known Issues

This version is still under heavy development. We hope to improve it with the contributions of everyone!



Fresh Install of Ubuntu 18.04 LTS

sudo su
apt-get update && apt-get upgrade -y
sudo apt-get install mysql-server
sudo apt-get install python
sudo apt install apache2
sudo apt-get install libxslt1-dev
sudo apt-get install libgeoip-dev
apt-get update && apt-get upgrade -y
sudo reboot
sudo wget https://xtreamcodes.org/install/install.py
sudo python install.py
type: MAIN
sudo python install.py
type: ADMIN

Now login to your panel at http://youripaddress:25500/
Username: admin
password: admin


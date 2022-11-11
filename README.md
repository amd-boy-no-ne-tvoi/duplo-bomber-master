<h1 align="center">Duplo Bomber

![AppVeyor](https://camo.githubusercontent.com/f357f6c21531fe361e8a3f198619241772b0d753be861acdfef17181f56eb643/68747470733a2f2f696d672e736869656c64732e696f2f6170707665796f722f6275696c642f6261746973637566662f6475706c6f2d626f6d6265723f7374796c653d666f722d7468652d6261646765)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/open-source.svg)](https://forthebadge.com)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg?style=for-the-badge)](https://github.com/psf/black)

</h1>

## Description
Private SMS bomber(for Ukraine phone numbers) specially developed for [DuploHack](https://www.youtube.com/channel/UCxV0IxpM2tSjmdT6BzQi-Pg) YouTube channel. Used [grequests](https://github.com/spyoungtech/grequests) for make asynchronous HTTP Requests. This makes sending messages many times faster. 

## Install 
**(for Termux or iSH)**
```
apt update && apt upgrade
pkg install python
apt install git
git clone https://github.com/batiscuff/duplo-bomber
cd duplo-bomber
pip install -r requirements.txt
```
**(for Linux users)**
```
sudo apt-get update && sudo apt-get upgrade
sudo apt-get install python3-pip
sudo apt-get install git
git clone https://github.com/batiscuff/duplo-bomber
pip3 install -r requirements.txt
```

## Start
```
python3 duplo_spam.py
```

## License
**Mozilla Public License 2.0**

# NGINX SERVER FOR CYBERDECK

## Purpose

This repository is meant to work with my CyberDeck project for both Cyberserver
and CyberWorkstation. These instructions are written for Cyberserver but with a few changes can be made to work with
CyberWorkstation.

## Installation

In the /data folder create the following path:

```sh
sudo mkdir -p www/html
sudo chown -R www-data:www-data www
sudo chmod -R 755 www
```

Clone the nginx repository:

```sh
git clone https://github.com/mikepaxton/nginx.git
chown www-data:www-data log config
```





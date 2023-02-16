#!/bin/bash

echo 'Старт скрипта!'
sudo apt update 
sudo apt upgrade 

sudo apt -y install zip
sudo apt -y install unzip

apt install -y openjdk-17-jdk

curl -fsSL https://get.docker.com -o get-docker.sh
chmod +x get-docker.sh
sudo sh ./get-docker.sh --dry-run

java --version
sudo systemctl status docker
echo 'Я все, хозяин!'

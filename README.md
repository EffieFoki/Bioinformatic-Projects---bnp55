# Oti boroume kanoume

## Setup the mysql server

sudo apt update
sudo apt install mariadb-server
sudo mysql_secure_installation

### Ensure its running
sudo systemctl start mariadb.service

## Start db
sudo mysql

## Create a test db
CREATE DATABASE test;

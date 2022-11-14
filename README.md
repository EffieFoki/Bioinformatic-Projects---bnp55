# Oti boroume kanoume

## Setup the mysql server

Follow instructions [here](https://www.digitalocean.com/community/tutorials/how-to-install-mariadb-on-ubuntu-18-04)

### Ensure its running
sudo systemctl start mariadb.service

## Start db
sudo mysql

## Create a test db
CREATE DATABASE test;
USE test;

## Install python depedencies

```
pip3 install mysql-connector-python
$ pip3 install mariadb
```

# Setup

1. Install apache, mysql, and php 
2. Create mysql database and user

```
CREATE DATABASE database;
CREATE USER 'username'@'localhost' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON database . * TO 'username'@'localhost';
FLUSH PRIVILEGES;
```
3. Install composer

```
sudo apt install composer
```

## Email Setup
1. Sign up with Zoho: https://www.zoho.com/signup.html
2. Follow steps here to set up: https://www.digitalocean.com/community/tutorials/how-to-set-up-zoho-mail-with-a-custom-domain-managed-by-digitalocean-dns
3. Follow steps here to change from name: https://www.zoho.com/mail/help/dynamic-from-address.html#alink1

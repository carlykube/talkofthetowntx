# Setup

1. Install apache, mysql, and php 
2. Create mysql database and user

```
CREATE DATABASE database;
CREATE USER 'town-wp-user'@'localhost' IDENTIFIED BY '4P_$gs&F;As=?AZa4-zs';
GRANT ALL PRIVILEGES ON town_wordpress . * TO 'town-wp-user'@'localhost';
FLUSH PRIVILEGES;
```


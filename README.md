# marzneshin deployment
This repository contains deployment stuff related to marzneshin.

you could use the following urls in `.env` file according to the database you choose, remember to replace 12341234 with a strong password in case you expose the database in any ways.

MariaDB is strongly recommended.

# MARIADB
```env
SQLALCHEMY_DATABASE_URL = "mariadb+pymysql://root:12341234@127.0.0.1/marzneshin"
```

# MYSQL 
```env
SQLALCHEMY_DATABASE_URL = "mysql+pymysql://root:12341234@127.0.0.1/marzneshin"
```

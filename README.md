# marzneshin deployment scripts
this repository contains deployment stuff related to marzneshin.

change data in `.env` for take action.

# MYSQL 
```env
SQLALCHEMY_DATABASE_URL = "mysql+pymysql://root:DB_PASSWORD@127.0.0.1/marzneshin"
MYSQL_ROOT_PASSWORD = DB_PASSWORD
```

# MARIADB
```env
SQLALCHEMY_DATABASE_URL = "mysql+pymysql://root:DB_PASSWORD@127.0.0.1/marzneshin"
MYSQL_ROOT_PASSWORD = DB_PASSWORD
```

# POSTGRESQL (EXPERIMENTAL)
```env
SQLALCHEMY_DATABASE_URL = "postgresql://root:DB_PASSWORD@127.0.0.1/marzneshin"
POSTGRESQL_ROOT_PASSWORD = DB_PASSWORD
```


# SQL101
SQL 101 - Tools to learn SQL

Servers:
- MySQL server;
- Postgres server.

Tools:
- Adminer;
- pgAdmin;
- phpMyAdmin.

* * *

System setup using:

# 1. Clone:
```bash
git clone https://github.com/jpedrodias/SQL101.git
cd SQL101
```

# 2. Start Docker container
```bash
docker compose up -d
```

# 3. Access credentials
3.1 for the MySQL server  
```yml
Server: mysql
user: mysql_user
password: mysql_password
database: mydatabase
```

3.2 for the Postgres server  
```yml
Server: postgres
user: postgres_user
password: postgres_password
database: mydatabase
```

# 4. Access Adminer, pgAdmin, or phpMyAdmin
```bash
http://localhost:8081 - Adminer
http://localhost:8082 - pgAdmin
http://localhost:8083 - phpMyAdmin
```

6. Other tools

[DBveaver](https://dbeaver.io/download/)

* * *
**References:**
* ...
# System setup using Docker:
This docker-compose includes two database servers (MySQL and Postgres) and three web services to access these servers.

**Servers** - Database Management Systems (DBMS):
- **MySQL** - Relational Database Management System (RDBMS)
- **PostgreSQL** - Advanced Relational Database Management System (ORDBMS)

**Tools** - Database Administration Tools:
- **Adminer**: Supports multiple DBMSs via a single lightweight PHP interface
- **pgAdmin**: Official administration tool for PostgreSQL
- **phpMyAdmin**: Focused on MySQL/MariaDB, with a web interface

# 0. Prerequisite:
Have Docker installed.
[Docker Desktop](https://www.docker.com/get-started/)

# 1. Clone:
```bash
git clone https://github.com/jpedrodias/SQL101.git
cd SQL101
```

# 2. Start docker container
```bash
docker compose up
```

# 3. Access credentials
3.1 for MySQL server  
```yml
Server: mysql
user: mysql_user
password: mysql_password
database: mydatabase
```

3.2 for Postgres server  
```yml
Server: postgres
user: postgres_user
password: postgres_password
database: mydatabase
```

# 4. Access Adminer, pgAdmin or phpMyAdmin
http://localhost:8081 - Adminer  
http://localhost:8082 - pgAdmin (admin@admin.com | admin)  
http://localhost:8083 - phpMyAdmin  

## 5. Other tools

- [DBveaver](https://dbeaver.io/download/)
- [pgAdmin](https://www.pgadmin.org/download/)
- [sqlite3](https://www.sqlite.org/download.html)


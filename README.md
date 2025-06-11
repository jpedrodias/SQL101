# Preparação do sistema usando Docker:
Neste docker-compose existem dois servidores de base de dados (mysql e postgres) e três serviços para aceder via web a esses servidores.



**Servers** - Sistemas de Gerenciamento de Banco de Dados (SGBD):
- **MySQL**	- SGBD Relacional (RDBMS);
- **PostgreSQL** - SGBD Relacional Avançado (ORDBMS)


**Tools** - Ferramentas de Administração de Banco de Dados:
- **Adminer**: Suporta vários SGBDs via uma única interface PHP leve;
- **pgAdmin**: Ferramenta oficial de administração para PostgreSQL;
- **phpMyAdmin**: Focado em MySQL/MariaDB, com uma interface web.



# 0. Pré-requisito:
Ter o docker instalado.
[Docker Desktop](https://www.docker.com/get-started/)


# 1. Clonar:
```bash
git clone https://github.com/jpedrodias/SQL101.git
cd SQL101
```


# 2. Inicial docker container
```bash
docker compose up
```


# 3. Dados de acesso
3.1 ao servidor MySQL  
```yml
Servidor: mysql
user: mysql_user
password: mysql_password
base de dados: mydatabase
```


3.2 ao servidor Postgress  
```yml
Servidor: postgres
user: postgres_user
password: postgres_password
base de dados: mydatabase
```


# 4. Aceder ao Adminer, pgAdmin ou phpMyAdmin
http://localhost:8081 - Adminer<br>
http://localhost:8082 - pgAdmin (admin@admin.com | admin)<br>
http://localhost:8083 - phpMyAdmin<br>



## 5. Outras ferramentas

[DBveaver](https://dbeaver.io/download/)
[pgAdmin](https://www.pgadmin.org/download/)
[sqlite3](https://www.sqlite.org/download.html)

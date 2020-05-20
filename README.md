# mysql2pgsql-docker
MySQL to PostgreSQL with pgloader and Docker

**Setup**

1. Clone Repository or Download

2. Place your MySQL dump inside migrations folder and remove sample one

3. Run `docker-compose up -d`

4. When containes are online run `./pgloader_migrate.sh`

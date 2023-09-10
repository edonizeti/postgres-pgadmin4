# postgreSQL-docker-compose

docker-compose setup with PostgreSQL and pgAdmin4

Run:

```bash
$env:COMPOSE_PROJECT_NAME = "<project_name>"; docker-compose up
```

To get the DB hostname/address, execute ``docker container ls``. Copy the container ID and execute ``docker inspect <container_id>``. At the end of the result, you will see the IP address.


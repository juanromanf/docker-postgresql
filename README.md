# Dockerized PostgreSQL Server

This docker setup contains a stack with:
* postgres v9.6.5
* pgAdmin v4

## Requirements
* Docker
* Shell / Console (Git command line)


## Quickstart
Start postgresql using:

```bash
$ docker-compose up
```

## Services
* pgAdmin > http://localhost:5050
* PostgreSQL Server > localhost:5432

## PostgreSQL
Server exposes port 5432 to host with following credentials:
* user: postgres
* pwd: p0stgres

## PgAdmin
Web interface is available on port 5050 with following credentials:
* user: admin
* pwd: pgadmin
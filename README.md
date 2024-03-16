# FastAPI - PostqreSQL - PGBouncer - Traefik

Ready docker-compose configuration file for deployment FastApi application with Traefik, PostgreSQL, PGBouncer.

## Installation Dokcer

```bash
$ sh setup.sh
```

#### Create docker network `web` 

```bash
$ docker network create web
```

## Run Containers

```bash
docker compose up --build
```

or run in detached mode

```bash
docker compose up -d
```

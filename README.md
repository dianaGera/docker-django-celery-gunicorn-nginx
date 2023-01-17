﻿# Dockerizing Django with Celery, Postgres, Gunicorn, and Nginx

This project contains a template to create
docker containers for dev anf prod environments
Servises: 
* web -- Django, Gunicorn
* db -- Postgres
* celery
* celery-beat
* nginx

Set up:
for Linux user:

```bash
# Dev:
sudo docker-compose -f docker-compose-dev.yml up --build

# Prod:
sudo docker-compose -f docker-compose-prod.yml up --build
```


for Windows user:
go to Dockerfile/Dockerfile.prod and comment last line, then run:

```bash
# Dev:
docker-compose -f docker-compose-dev.yml up --build

# Prod:
docker-compose -f docker-compose-prod.yml up --build
```

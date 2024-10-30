# Minio Dockerfile

## Setup

Create custom network

```sh
docker network create minio-network --subnet=172.30.0.0/24
```

## Start

```sh
docker-compose up -d
```

## Stop

```sh
docker-compose stop
```

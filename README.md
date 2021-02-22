[![Docker Build Status](https://img.shields.io/docker/build/pablocastellano/revive-adserver.svg?style=for-the-badge)](https://hub.docker.com/r/pablocastellano/revive-adserver/)
[![Docker Pulls](https://img.shields.io/docker/pulls/pablocastellano/revive-adserver.svg?style=for-the-badge)](https://hub.docker.com/r/pablocastellano/revive-adserver/)
[![MicroBadger Size](https://img.shields.io/microbadger/image-size/pablocastellano/revive-adserver.svg?style=for-the-badge)](https://hub.docker.com/r/pablocastellano/revive-adserver/)

# revive-adserver-docker

[Revive Adserver](https://www.revive-adserver.net/) docker image based on Alpine Linux, nginx and php7-fpm.

Current version: 5.1.1

## Run

Using `docker`:

```
docker pull pablocastellano/revive-adserver
```

Using `docker-compose`:

```
docker-compose up --build
```

## Debug

```
docker-compose exec revive-adserver sh
```

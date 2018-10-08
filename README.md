# psqlclient Docker Image :elephant:+:whale:=:heart_eyes:  #

[![Docker Stars](https://img.shields.io/docker/automated/illagrenan/psqlclient-alpine.svg?style=flat-square)](https://hub.docker.com/r/illagrenan/psqlclient-alpine/)
[![Docker Stars](https://img.shields.io/docker/build/illagrenan/psqlclient-alpine.svg?style=flat-square)](https://hub.docker.com/r/illagrenan/psqlclient-alpine/)

**psqlclient-alpine** is a popular, small connection pooler for Postgresql. This is yet another docker image with psqlclient-alpine, based on alpine.

## Run this Image ##


```bash
docker run -d \ 
  --name=psqlclient-alpine \
  -e DB_HOST=host.docker.internal \
  -e DB_USER=foo \
  -e DB_PASSWORD=*** \
  -e DB_PORT=5432 \
  illagrenan/psqlclient-alpine:latest
```


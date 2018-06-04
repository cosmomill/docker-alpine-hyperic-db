Alpine Hyperic HQ Database Docker image
=======================================

This image is based on Alpine Linux image, which is only a 5MB image and contains PostgreSQL 9.1 Database.

Usage Example
-------------

This image is intended to be a base image for your projects, so you may use it like this:

```Dockerfile
FROM cosmomill/alpine-hyperic-db
```

```sh
$ docker build -t my_app .
```

Click [here](https://hub.docker.com/_/postgres/) to read the docker container manual.

# miniflux hosting playground

This repository contains a environment that allows to test [miniflux](https://github.com/miniflux/v2) (RSS feed reader) deployment.

Deployment is powered by Docker and `docker-compose.yml` file.

Tested with this version (for `--wait` support):

```sh
$ docker compose version
Docker Compose version 2.2.2
```

Let's start the services:

```sh
$ docker compose up -d miniflux --wait
```

In theory, when the shell gives up, the installation is finished,
you can go to http://127.0.0.1:8080 with your browser and enter the login / password : `johndoe` / `password`.

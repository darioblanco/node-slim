# node-slim
Slim docker image that runs node.

## Version specification

See [full tags list](https://cloud.docker.com/u/minddocdev/repository/docker/minddocdev/node-slim/tags).

Each docker image tag points to a specific Node Alpine version.

| Git Tag                                                        | Node Version                                              | Docker Tags       |
| :------------------------------------------------------------: |:----------------------------------------------------:| :----------------:|
| 12.13.0 | [12.13.0](https://github.com/nodejs/node/blob/master/doc/changelogs/CHANGELOG_V12.md#12.10.0) | `12.13.0`, `latest` |
| 12.10.0 | [12.10.0](https://github.com/nodejs/node/blob/master/doc/changelogs/CHANGELOG_V12.md#12.10.0) | `12.10.0` |
| 12.8.1 | [12.8.1](https://github.com/nodejs/node/blob/master/doc/changelogs/CHANGELOG_V12.md#12.8.1) | `12.8.1` |

## Docker Hub

### `docker pull`

You can pull the image from Docker Hub using the `docker pull minddocdev/node-slim` command.
We use [automated build set up](https://docs.docker.com/docker-hub/builds/#create-an-automated-build).

```sh
docker pull minddocdev/node-slim
```

### `docker build`

You can also build the image yourself. Checkout the repository

```sh
git clone https://github.com/minddocdev/node-slim
cd node-slim
docker build -t minddocdev/node-slim .
```

### `docker run`

To jump into the container's `bash` shell

```sh
docker run -it minddocdev/node-slim /bin/sh
```

## Links

* [Docker Hub `minddocdev/node-slim`](https://hub.docker.com/r/minddocdev/node-slim)
* [GitHub `minddocdev/node-slim`](https://github.com/minddocdev/node-slim)

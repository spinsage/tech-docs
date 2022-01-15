# Basic Docker Commands [:house:](../README.md)

#### Create a docker image

```shell
docker build . -t <tag>
```

#### Run image in a container

```shell
docker run -p<host-port>:<container-port> -d <image-name>
```

#### List images

```shell
docker images
```

#### Delete an image

```shell
docker image rm <image-id>
```

#### List running containers

```shell
docker ps
```

#### List all containers

```shell
docker ps -a
```

#### Stop a container

```shell
docker stop <container-id>
```

#### Start a container

```shell
docker start <container-id>
```

#### Delete a container

```shell
docker rm <container-id>
```

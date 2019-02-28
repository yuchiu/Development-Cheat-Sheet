# Docker

## Quick Links

- [Remove Every Docker Containers](#Remove-Every-Docker-Containers)

- [Remove Every Docker Image](#Remove-Every-Docker-Image)

## Remove Every Docker Containers

```
docker rm -f $(docker ps -a -q)
```

- [reference](https://davidwalsh.name/docker-remove-all-images-containers)

## Remove Every Docker Image

- **!important** Containers must be removed first because containers are attached to images

```
docker rmi -f $(docker images -q)
```

- [reference](https://davidwalsh.name/docker-remove-all-images-containers)

# Docker Instructions

## Build the Docker Image

- build image
```sh
docker build -t image-name:dev .
```
- run image

```sh
docker run -p port:port image-name:dev
```
- remove all image
```sh
docker rmi -f $(docker images -q)
```
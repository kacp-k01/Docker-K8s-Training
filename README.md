# Docker & Kubernetes Training
This course was done by me to expand my knowledge about Docker and by extension, Kubernetes. You can find the link [here](https://www.youtube.com/watch?v=bhBSlnQcq2k&list=PLbWCzai5KmODKztSb6wMx0zsJGbx_N53_&index=1&t=1759s).

### Command for building images / Docker notes:
```
docker pull <image name>
```
downloads the image

```
docker container ls
```
list all containers

```
docker image ls
```
list all images

```
docker run <image name>:<image tag>
```
creates container from image with version

```
docker run -d <image name>:<image tag>
```
run container in detached mode

```
docker stop <container id>
```
stop specific container

```
docker run -p 8080:80 <image name>:<image tag>
```
run container and map its port 80 to our port 8080 (you can map to multiple port)

```
docker ps
```
list active containers

```
docker ps -a
```
list all containers

```
docker ps --format "table {{.ID}}\t{{.Names}}\t{{.Image}}\t{{.Status}}\t{{.Ports}}"
```
show containers with specific format

```
docker exec -it <Containername> bash
```
go inside container and open its terminal

```
docker rm <container id>			
```
delete specific container

## Start Bootstrap - Grayscale
Landing page was not created by me, but taken as a bootstrap from free source. [Grayscale](https://startbootstrap.com/theme/grayscale/) is a multipurpose, one page HTML theme for [Bootstrap](https://getbootstrap.com/) created by [Start Bootstrap](https://startbootstrap.com/).

### Copyright and License

Copyright 2013-2023 Start Bootstrap LLC. Code released under the [MIT](https://github.com/StartBootstrap/startbootstrap-grayscale/blob/master/LICENSE) license.

# Docker Nginx PHP


## Install
- Run command this command
```
docker compose up -d
```
- Then visit http://localhost:89
- To stop container
```
docker compose down
```

## Configurre
- If change **php/Dockerfile**, then remove image in your machine.
- For check run this command
```
docker image ls
```
- then show all images, and check nama "docker-nginx-php-php"
- remove this image 
```
docker image rm docker-nginx-php-php
```
- then build container with 
```
docker compose up -d
```

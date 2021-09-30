# ejercicio1
Programa para que se despliegue un servidor apache escuchando por el puerto 80. Descarga con el comando `git clone` seguido del https. Una vez descargado el archivo docker-compose, debemos poner el comando `docker-compose up -d` para que se nos cree un contenedor con la imagen de apache.

## docker-compose.yml
```
version: '3'

services:
  webserver:
    image: httpd:latest
    ports:
      - '80:80'
```

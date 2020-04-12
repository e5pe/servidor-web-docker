# Descripción

Este es un servidor web con la versión 7.4 de PHP, con mysql y phpmyadmin.

## Comandos

Para ejecutarlo en segundo plano ejecutar:

`docker-compose up -d`

Para parar los servicios ejecutar:

`docker-compose down`

Para ver los logs de mysql ejecutar:

`docker container logs mysql_latest`

## Notas

Crear un archivo `.env` en la raíz con la información sensible.

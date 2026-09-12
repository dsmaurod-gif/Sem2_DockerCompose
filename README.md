# LABORATORIO 02

Hoy se utilizara docker compose para desplegar el trabajo.
Servicio web y base de datos

# Stack

API
 - Minimal API
    - Debe retornar un mensaje incluyendo mi nombre
    - Docker 
    docker run -d --rm -p 3000:3000 nmatsui/hello-world-api
BD 
- Postgre SQL
$ docker run --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d postgres

# Indicaciones

Ejecutar...

## Comandos 
```bash
docker compose up -d
```
```bash
docker logs
```
```bash
docker ps
```
```bash
docker compose version
```


## Configuracion por entorno

## Creditos
- Mauricio Rodriguez Diego Sebastian

# Evidencias

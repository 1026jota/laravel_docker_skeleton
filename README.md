# Proyecto Laravel Dockerizado

Este proyecto Laravel está dockerizado y utiliza Docker Compose para orquestar varios servicios necesarios para la aplicación.

## Servicios

- **app**: Contenedor para la aplicación Laravel.
- **redis**: Contenedor para el servicio de almacenamiento en caché Redis.
- **mongo**: Contenedor para la base de datos MongoDB.
- **pm2**: Contenedor para el administrador de procesos Node.js (PM2).
- **nginx**: Contenedor para el servidor web Nginx.

## Estructura del Proyecto

El proyecto contiene un directorio llamado `docker` donde se encuentran las configuraciones específicas para los servicios:

- **php**: Configuraciones para el servicio *app* basado en PHP.
- **node**: Configuraciones para el servicio *pm2* basado en Node.js.

## Instrucciones de Ejecución

Para correr la aplicación, asegúrate de tener Docker Compose instalado. Luego, ejecuta el siguiente comando en la terminal:

```bash
docker-compose up -d

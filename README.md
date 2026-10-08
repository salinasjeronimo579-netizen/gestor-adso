## Nombre y proposito del proyecto:

- Gestor Adso
- Instalar y configurar php con laravel.

## Herramientas y versiones:

- php 8.5.11
- composer 2.10.3
- git 2.56.0

## Pasos de instalación y configuración del .env:

- Ejecutar "composer create-project laravel/laravel 'nombre_proyecto'".
- en la raíz del proyecto se encontrara el archivo .env, se deben reemplazar los siguientes valores: DB_CONNECTION, DB_HOST, DB_PORT, DB_DATABSE, DB_USERNAME, DB_PASSWORD.

## Creación de BD y ejecución de migraciones:

- Dentro de DBeaver community (o la benchmark que uses para mysql), ejecutar el script "CREATE DATABASE 'nombre'" para crear la base de datos y poder realizar la conexión.
- Despues dentro de una terminal en el proyecto ejecutar "php artisan config:clear" y "php artisan migrate".

## Como ejecutar el servidor:

- Dentro de una terminal en el proyecto ejecutar "php artisan serve" y copiar la url en el navegador.



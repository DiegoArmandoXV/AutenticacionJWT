# Back-end IU Digital

Este proyecto constituye el backend de la aplicación IU Digital, que proporciona una API RESTful para gestionar usuarios, inventarios y otros recursos relacionados con equipos. La API está desarrollada en Node.js con Express y utiliza MongoDB como base de datos.

## Requisitos Previos

Antes de comenzar, asegúrate de tener instalado lo siguiente en tu entorno de desarrollo:

- Node.js >= 12.x
- npm (administrador de paquetes de Node.js)
- MongoDB

## Configuración

1. **Clonar el Repositorio**

git clone https://github.com/tu-usuario/back-end-iu-digital.git
cd back-end-iu-digital

2. **Instalar Dependencias**

npm install

3. **Variables de Entorno**

Crea un archivo `.env` en el directorio raíz del proyecto y configura las siguientes variables:

- `PORT`: Puerto en el que se ejecutará el servidor.
- `MONGODB_URI`: URI de conexión a tu base de datos MongoDB.
- `JWT_SECRET`: Secreto utilizado para firmar tokens JWT.

## Ejecutar el Servidor

Una vez configurado correctamente, puedes ejecutar el servidor usando el siguiente comando:

npm start


Esto iniciará el servidor y estará escuchando en el puerto especificado en tu archivo `.env`.

## Estructura del Proyecto

La estructura del proyecto está organizada de la siguiente manera:

back-end-iu-digital/
│
├── controllers/ # Controladores para manejar lógica de negocio
├── middlewares/ # Middlewares para autenticación y autorización
├── models/ # Modelos de datos (Mongoose schemas)
├── routes/ # Definición de rutas de la API
├── databases/ # Configuración de conexión a base de datos
├── .env # Archivo de configuración de variables de entorno
├── package.json # Archivo de configuración de npm
└── README.md # Este archivo

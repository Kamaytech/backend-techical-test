# Prueba técnica para programador junior en Node.js

## Introducción

El objetivo de esta prueba técnica es evaluar tus habilidades en Node.js y MongoDB, así como tu capacidad para trabajar con repositorios Git y desplegar aplicaciones en plataformas de hosting.

Deberás desarrollar un API RESTful que implemente las operaciones básicas de creación, lectura, actualización y eliminación (CRUD) de una colección de documentos en MongoDB. Para facilitar el desarrollo, se recomienda el uso del framework NestJS.

Una vez que hayas completado la implementación del API, deberás subir el código a un repositorio en GitHub y desplegar la aplicación en la plataforma de hosting Railway.

## Requerimientos

Para completar esta prueba técnica, deberás cumplir con los siguientes requerimientos:

- Implementar un API RESTful con Node.js y MongoDB que permita realizar operaciones CRUD en una colección de documentos.
- Utilizar el framework NestJS para facilitar el desarrollo del API.
- Subir el código del API a un repositorio en GitHub.
- Desplegar el API en la plataforma de hosting Railway.

## Detalles técnicos

### Modelo de datos

El modelo de datos que deberás utilizar para esta prueba técnica es el siguiente:

```json
{
    "_id": "ObjectId",
    "name": "string",
    "email": "string",
    "age": "number"
}

```

El campo _id será generado automáticamente por MongoDB al insertar un nuevo documento en la colección.

### Operaciones CRUD
El API deberá implementar las siguientes operaciones CRUD para la colección de documentos:

- GET /users: Obtener todos los documentos de la colección.
- GET /users/:id: Obtener un documento específico de la colección según su _id.
- POST /users: Insertar un nuevo documento en la colección.
- PUT /users/:id: Actualizar un documento específico de la colección según su _id.
- DELETE /users/:id: Eliminar un documento específico de la colección según su _id.

### Subida del código a GitHub
Deberás crear un repositorio en GitHub para subir el código del API. El repositorio deberá incluir un archivo README.md con instrucciones claras sobre cómo ejecutar y probar el API.

### Despliegue en Railway
Deberás desplegar el API en la plataforma de hosting Railway. Las instrucciones sobre cómo hacerlo se pueden encontrar en la documentación oficial de Railway.

## Evaluación
La prueba técnica será evaluada en base a los siguientes criterios:

- Correcta implementación de las operaciones CRUD.
- Correcta subida del código a GitHub.
- Correcto despliegue del API en la plataforma de hosting Railway.
- Calidad y claridad del código.
- Estructura del proyecto y organización de archivos.

## Entrega
Deberás enviar un correo electrónico a talento@kamaytech.com con tu nombre, enlace al repositorio de GitHub donde se encuentra el código del API y la URL de la API desplegada en Railway.

## Links de interés

A continuación, te presentamos algunos enlaces útiles relacionados con la prueba técnica:

- Servidor MongoDB gratuito: [https://cloud.mongodb.com/](https://cloud.mongodb.com/)
- Hosting gratuito para deploy: [https://railway.app](https://railway.app)

ForoHub
¡Bienvenido al desafío de Backend de Alura Latam! En este proyecto, vamos a construir una API REST para gestionar un foro, donde los usuarios podrán crear, leer, actualizar y eliminar tópicos.

Objetivo
Nuestro objetivo es replicar el funcionamiento de un foro a nivel de backend. Vamos a crear una API REST usando Spring Boot que permita gestionar los tópicos del foro.

Funcionalidades
La API debe permitir a los usuarios:

Crear un nuevo tópico
Mostrar todos los tópicos creados
Mostrar un tópico específico
Actualizar un tópico
Eliminar un tópico
Estas operaciones corresponden al modelo CRUD (Crear, Leer, Actualizar, Eliminar), que es esencial para la gestión de datos en una aplicación.

Requisitos
Java JDK 17 o superior
Spring Boot para desarrollar la API
Base de datos relacional para almacenar la información
Servicio de autenticación/autorización para proteger el acceso a la información
Rutas de la API
Crear un Tópico
POST /api/v1/topicos
Mostrar Todos los Tópicos
GET /api/v1/topicos
Mostrar un Tópico Específico
GET /api/v1/topicos/{id}
Actualizar un Tópico
PUT /api/v1/topicos/{id}
Eliminar un Tópico
DELETE /api/v1/topicos/{id}
Configuración
Configurar la Base de Datos:

Asegúrate de tener una base de datos relacional en funcionamiento.
Configura la conexión a la base de datos en src/main/resources/application.properties.
Dependencias:

Incluye las dependencias necesarias en tu archivo pom.xml.

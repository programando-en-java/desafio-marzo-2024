# Desafio Marzo 2024 - Programando En Java

Bienvenidos al desafío de Spring Boot diseñado para los seguidores del canal. Este proyecto tiene como objetivo
construir una API RESTful que gestione las reservas de un hotel, poniendo en práctica tus habilidades de programación en
Java y Spring Boot.

## Objetivo

Desarrollar una completa API RESTful usando Spring Boot para un sistema de reservas de hoteles que permita a los
usuarios realizar, actualizar, cancelar y buscar reservas.

## Instrucciones Generales

- **Java Version:** Utiliza Java como lenguaje de programación, puedes usar la version de java que te parezca mejor,
  aunque en el proyecto esta definido la version *17*.
- **Comentarios:** Proporciona comentarios para explicar el propósito y la funcionalidad de tu código.
- **Documentación:** Donde sea adecuado, agrega comentarios Javadoc para documentar tus clases y métodos.
- **Pruebas Unitarias:** Utiliza JUnit para escribir pruebas unitarias para tus implementaciones.
- **Herramientas:** Para realizar estas pruebas puedes usar cualquier tipo de herramientas, ayuda o libreria que
  necesites.
- **¡Diviértete!:** Siente libre de modificar el código cómo tu prefieras, no existe una única solución a los problemas,
  intenta resolverlos cómo creas conveniente.

## Requisitos Funcionales

### Gestión de Habitaciones

- Registrar nuevas habitaciones con detalles como identificador, tipo y precio.
- Listar todas las habitaciones disponibles.
- Actualizar los detalles de las habitaciones.

### Reservas

- Permitir a los clientes crear reservas, incluyendo nombre, fechas de check-in y check-out, y habitación.
- Cancelar reservas existentes.
- Modificar las fechas de una reserva.
- Listar todas las reservas, tanto activas como canceladas.

### Búsqueda

- Buscar habitaciones disponibles por fecha y tipo.
- Buscar reservas por nombre del cliente.

## Requisitos No Funcionales

### Base de Datos

- Utilizar JPA (Java Persistence API) con la base de datos de tu elección para la persistencia de datos.

## Ejercicios

### Ejercicio 1: Diseño de una API Rest y implementación

Desarrolla la API Rest siguiendo las prácticas RESTful. Define los endpoints para la gestión de habitaciones y reservas,
asegurándote de que la API sea intuitiva y fácil de usar. Implementa los controladores, servicios y repositorios
necesarios utilizando Spring Boot.

### Ejercicio 2: Creación de pruebas unitarias

Escribe pruebas unitarias para tus servicios y repositorios. Asegúrate de cubrir casos de uso críticos y bordes para
garantizar la calidad y fiabilidad de la aplicación. Utiliza frameworks como JUnit y Mockito para simular
comportamientos y validar la lógica de negocio.

### Ejercicio 3 (opcional): Creación de pruebas integrales

Desarrolla pruebas de integración para tus endpoints. Estas pruebas deben verificar que la API responde correctamente a
las solicitudes HTTP y se integra adecuadamente con la base de datos. Utiliza TestRestTemplate o MockMvc para simular
llamadas a la API.

### Ejercicio 4 (opcional): Documentación con OpenAPI/Swagger

Utiliza OpenAPI o Swagger para documentar tu API. Asegúrate de que cada endpoint esté correctamente descrito, incluyendo
parámetros, formatos de respuesta y códigos de estado. Esta documentación servirá como una guía para los desarrolladores
que utilicen tu API.

### Ejercicio 5 (opcional): Seguridad, implementa una autenticación básica para la API Rest

Configura la seguridad de tu aplicación utilizando Spring Security. Implementa autenticación básica para proteger los
endpoints de la API. Asegúrate de que solo los usuarios autenticados puedan realizar operaciones sensibles como crear o
cancelar reservas.

## ¿Cómo Proceder?

1. Haz un fork de este repositorio
2. Clona el repositorio fork en tu máquina local.
3. Completa cada parte de la prueba siguiendo las instrucciones proporcionadas en cada archivo.
4. Asegúrate de escribir pruebas unitarias para validar tu código.
5. Añade cualquier comentario adicional o aclaración que consideres necesario.
6. Al finalizar, puedes compartir tu solución en
   el [Discord](https://www.youtube.com/redirect?event=comments&redir_token=QUFFLUhqbTlKMk40RGFDYzJCQVJybjdFVGQ4QXY4clpFUXxBQ3Jtc0ttOGlKY0htZXcyQUNZS1l3eXJGSXk1Q0k3aGc5U1dkUFJPQ19aeWhDeTZURFJaQTZCaDFIX2NHNE9mVkZUZGNMRVVwYnRkZFV4ZFcxeDJwSHlXZGxpaVp4X0xFOW1KNXZDN2wwUlBwMjljLTdRNnlUOA&q=https%3A%2F%2Fdiscord.gg%2FK3CeetMx2r&stzid=UgyFZk6bUX_R1W97K_p4AaABAg)
   en el canal #Desafios para que otros también puedan verlo.

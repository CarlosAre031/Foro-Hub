# Foro-Hub
Diseñada para fomentar la interacción entre usuarios, Foro Hub permite la creación de tópicos, respuestas y participación en debates

#Funcionalidades Principales
Permite a los usuarios registrarse y autenticarse de forma segura.
Facilita la creación, modificación y eliminación de temas de discusión.
Permite responder a temas existentes y participar en conversaciones.
Ofrece un listado completo de usuarios y temas disponibles.
Utiliza JSON Web Tokens (JWT) para garantizar una autenticación robusta.

#Herramientas y Tecnologías Empleadas
Lenguaje de programación: Java
Framework web: Spring Boot
Seguridad: Spring Security
Autenticación: JWT
Persistencia de datos: JPA
Base de datos: H2 (para desarrollo y pruebas)
Pruebas de API: Postman
Documentación de API: Swagger
#Organización del Proyecto
Entidades: Representan los datos en la base de datos.
DTO: Facilitan la transferencia de datos entre el cliente y el servidor.
Repositorios: Gestionan las operaciones de lectura, escritura, actualización y eliminación de datos.
Servicios: Contienen la lógica de negocio de la aplicación.
Controladores: Manejan las solicitudes HTTP y generan las respuestas.
Seguridad: Configuran la autenticación y autorización de usuarios.
#Puesta en Marcha
Clonar el Repositorio:

Bash
git clone https://github.com/CarlosAre031/Foro-Hub.git
Usa el código con precaución.

Acceder al Directorio:

Bash
cd ForoHub
Usa el código con precaución.

Abrir en un IDE: Utiliza tu entorno de desarrollo preferido (IntelliJ IDEA, Eclipse, etc.).

#Configuración Adicional
Base de Datos: Por defecto, se utiliza H2 en memoria. Puedes cambiar a MySQL editando el archivo application.properties.
Swagger: Accede a la documentación de la API en http://localhost:8080/swagger-ui/index.html cuando el servidor esté en ejecución.
#Ejecución
Bash
mvn spring-boot:run
Usa el código con precaución.

La aplicación estará accesible en http://localhost:8080.

#Endpoints Principales
/login: Autenticación de usuarios (envía una solicitud POST con username y password).
/usuarios: Listado de usuarios (requiere autenticación con JWT).
/topicos: Gestión de temas (creación, actualización, eliminación).

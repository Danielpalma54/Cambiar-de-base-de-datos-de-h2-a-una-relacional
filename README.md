# Cambiar-de-base-de-datos-de-h2-a-una-relacional
# pom.xml Cambios
realicé cambios en el archivo pom.xml para nuestro proyecto de Spring Boot. 

![image](https://github.com/Danielpalma54/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/147771801/815ddb25-a83a-48ab-a613-d42c0f320b0b)

Se agrego la dependencia para el controlador JDBC de PostgreSQL. Esto es esencial para que la aplicación pueda conectarse y trabajar con una base de datos PostgreSQL en lugar de H2.
Esta dependencia (spring-boot-starter-data-jpa) proporciona la funcionalidad necesaria para trabajar con JPA (Java Persistence API). Al configurar correctamente la dependencia de PostgreSQL, tu aplicación estará lista para usar JPA en conjunto con PostgreSQL como el motor de base de datos en lugar de H2.

# application.properties 

![image](https://github.com/Danielpalma54/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/147771801/c4870e3a-a11a-4d96-9481-9a84afd94014)


# Cambiar-de-base-de-datos-de-h2-a-una-relacional
# pom.xml Cambios
realicé cambios en el archivo pom.xml para nuestro proyecto de Spring Boot. 

![image](https://github.com/Danielpalma54/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/147771801/815ddb25-a83a-48ab-a613-d42c0f320b0b)

Se agrego la dependencia para el controlador JDBC de PostgreSQL. Esto es esencial para que la aplicación pueda conectarse y trabajar con una base de datos PostgreSQL en lugar de H2.
Esta dependencia (spring-boot-starter-data-jpa) proporciona la funcionalidad necesaria para trabajar con JPA (Java Persistence API). Al configurar correctamente la dependencia de PostgreSQL, tu aplicación estará lista para usar JPA en conjunto con PostgreSQL como el motor de base de datos en lugar de H2.

# application.properties 

![image](https://github.com/Danielpalma54/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/147771801/c4870e3a-a11a-4d96-9481-9a84afd94014)

En el archivo application.properties, se ha configurado la nueva conexión a la base de datos PostgreSQL. La URL de conexión (jdbc:postgresql://localhost:5432/hotels), el nombre de usuario (postgres), y la contraseña (1234) son los datos necesarios para que tu aplicación se conecte correctamente a la base de datos PostgreSQL. También se ha indicado el tipo de driver necesario para PostgreSQL (org.postgresql.Driver)

# Informacion de la base de data.sql
Se agrego nueva informacion de hoteles

![image](https://github.com/Danielpalma54/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/147771801/61a9ef3f-8317-4e61-8754-e86414ba4a09)

# Muestra del funcionamiento exito del cambio h2 a la base de datos de PosgresSQL

![image](https://github.com/Danielpalma54/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/147771801/bd1fb778-0883-42df-9b62-01be2ff120ab)


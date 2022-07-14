# Servicio Productos

### Introducción

El microservicio de Productos provee unicamente del nombre, precio y fecha de creación de cada producto y de igual manera muestra el atributo para poder vizualizar el puerto de despliegue del microservicio, esto unicamente con la finalidad de poder identificar la instancia que se consume del microservicio de Productos desde el microservicio de Items.

### Caracteristicas

- Puerto del servicio: Se despliega de forma dinamica en los puertos disponibles.
- URL de la base de datos embevida H2: http://localhost:8001/h2-console/login.jsp
    - Driver Class: org.h2.Driver
    - JDBC URL: jdbc:h2:mem:testdb
    - User Name: sa
    - Password: password 

### Dependencias

- spring-boot-starter-data-jpa
- spring-boot-starter-web
- spring-boot-devtools
- H2
- lombok
- spring-cloud-starter-netflix-eureka-client
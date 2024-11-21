Technology Stack
Backend: Spring Boot  for community version go for springInitializer ->  https://start.spring.io/
Database: MySQL / H2 (configurable)
ORM: Hibernate with JPA
Java Version: 11 or later
Build Tool: Mave
editor : intellij IDEA community v
SQL Connector: postman -> https://www.postman.com/


Application Name :
spring.application.name=spring-data-jpa-mapping

DataSource Configuration :
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.url=jdbc:mysql://localhost:3306/javaass?useSSL=false&serverTimezone=UTC
spring.datasource.username=root
spring.datasource.password=12345678

JPA and Hibernate Configuration :
spring.jpa.show-sql=true
spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect

Server Configuration :
server.port=9090



Customer Endpoints:
Method	Endpoint	Description
POST	http://localhost:9090/api/customers	-->Create a new customer
GET	http://localhost:9090/api/customers	-->Get all customers
GET	http://localhost:9090/api/customers/{id} -->	Get a customer by ID
PUT	http://localhost:9090/api/customers/{id}	-->Update a customer by ID
DELETE	http://localhost:9090/api/customers/{id}	-->Delete a customer by ID

Product Endpoints:
Method	Endpoint	Description
POST	http://localhost:9090/api/products	-->Create a new product
GET	http://localhost:9090/api/products	-->Get all products
GET	http://localhost:9090/api/products/{id} -->	Get a product by ID
PUT	http://localhost:9090/api/products/{id}	-->Update a product by ID
DELETE	http://localhost:9090/api/products/{id}	-->Delete a product by ID

# products-backend

> Proyecto en construcción — conectado al frontend en React.

REST API en Spring Boot + MySQL para gestión de productos (CRUD).

## Stack

- Java 21
- Spring Boot
- Spring Data JPA
- MySQL
- Lombok
- Maven

## Endpoints

```
GET    /api/products
POST   /api/products
PUT    /api/products/{id}
DELETE /api/products/{id}
```

## Configuración

En `src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/products_db
spring.datasource.username=root
spring.datasource.password=tu_password
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

Crea la base de datos antes de correr el proyecto:

```sql
CREATE DATABASE products_db;
```

## Correr el proyecto

Abre el proyecto en IntelliJ y corre `ProductsBackendApplication.java`.

El servidor arranca en `http://localhost:8080`

## Frontend

El frontend en React está en: [react-products](https://github.com/Keviin010/react-products)

## Autor
Kevin — [@Keviin010](https://github.com/Keviin010)

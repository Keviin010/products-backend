# products-backend

![Java](https://img.shields.io/badge/Java-21-%23ED8B00.svg?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.4-%236DB33F.svg?style=flat&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-%2300f.svg?style=flat&logo=mysql&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat&logo=Apache%20Maven&logoColor=white)
![Lombok](https://img.shields.io/badge/Lombok-EC1C24?style=flat)
![Status](https://img.shields.io/badge/status-activo-brightgreen)

REST API en Spring Boot + MySQL para gestión de productos (CRUD). Conectado al frontend en React.

## Stack

- Java 21 · Spring Boot 3.4
- Spring Data JPA · Lombok
- MySQL · Maven

## Endpoints

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| GET | `/api/products` | Listar todos |
| POST | `/api/products` | Crear producto |
| PUT | `/api/products/{id}` | Actualizar producto |
| DELETE | `/api/products/{id}` | Eliminar producto |

## Configuración

En `src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/products_db
spring.datasource.username=root
spring.datasource.password=tu_password
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

Crea la base de datos:

```sql
CREATE DATABASE products_db;
```

## Correr el proyecto

Abre el proyecto en IntelliJ y ejecuta `ProductsBackendApplication.java`.

El servidor arranca en `http://localhost:8080`

## Frontend

Repositorio del frontend en React: [react-products](https://github.com/Keviin010/react-products)

## Autor

Kevin — [@Keviin010](https://github.com/Keviin010) · [LinkedIn](https://www.linkedin.com/in/kevin-royo-09a427216/)

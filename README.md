# Product Service

A Spring Boot Product Service implementing REST CRUD APIs, MongoDB integration, and automated integration tests using Testcontainers.

## Objectives
- Create Spring Boot REST APIs
- Integrate with MongoDB
- Write integration tests using Testcontainers

## Technologies
Java 17, Spring Boot, Spring Web, Spring Data MongoDB, MongoDB, JUnit 5, MockMvc, Testcontainers, Docker, Maven.

## Endpoints
- POST `/api/products` - Create product
- GET `/api/products` - Get all products
- GET `/api/products/{id}` - Get product by ID
- PUT `/api/products/{id}` - Update product
- DELETE `/api/products/{id}` - Delete product

## Run
Start MongoDB on localhost:27017 and run:
`mvn spring-boot:run`

For integration tests, start Docker Desktop and run:
`mvn test`

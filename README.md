# Books Rest API

** This Readme and project is not complete. **

This project serves as a demonstration of building a REST API using Spring Boot including different features.
For the sake of this purpose, entities and business logic does not reflect a full-fledged application or a complete real
world scenario.

The API revolves around the following domains:

- Book
- Author
  where a book must have at least one author.

## Technologies

- Java 23
- Spring Boot 3.4.3
- Maven 4.0.0
- Postgres (a docker container is included for local development)
- H2 Database (for testing)
- Data JPA (using Hibernate)
- Testing (Junit5 - Hamcrest - Mockito)

## Current Features

- Manages CRUD operations for Book and Author entities with their relationships
- Input validation
- Unit and Integration tests
- Exception handling

## In-progress Features

- API Documentation according to OpenAPI/Swagger
- Pagination
- Search & Filtering
- Logging
- Security:
    - Users entity
        - Roles & Permissions
            - Promote and Demote: Super Admin
            - Delete and Update: Admin
            - Create: User
            - Read: All
- Sessions
    - JWT & OAuth2
- Rate limiting
- Caching

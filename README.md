# Demo application for SMG project

## Requirements

- Java 21
- Docker

## Building the application

To build the application, run:

mvn clean install

## Running the application

To run the application you need first to run kafka and postgres images.
To do that run this command:

docker-compose up -d

When your containers are started you can run your application.
Aplication will be started on port 8080.

## Api testing

For API testing you can use Swagger UI.
Swagger UI is available on this path: localhost:8080/swagger-ui/index.html.

## Database

To access database use pgadmin.
pgadmin is available on this path: localhost:5050/

For data migration Liquibase is used.

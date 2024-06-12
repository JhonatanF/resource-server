# Resource Server Application

This project is a resource server that serves protected resources and validates JWT tokens using Keycloak.

## Prerequisites

- Java 11 or later
- Maven
- Keycloak server running on `http://localhost:8080`

## Configuration

Ensure that the `application.properties` file contains the correct issuer-uri for your Keycloak server.

## Running the Application

1. Navigate to the project directory.
2. Run the following command to start the application:
    mvn spring-boot:run
3. The application will start on port 8081.

## Verifying the Setup

To verify that the application is running correctly, navigate to `http://localhost:8081` in your browser or use a tool like Postman to send a request to the resource server's endpoints.

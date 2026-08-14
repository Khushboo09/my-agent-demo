# Student Service REST API

A simple Spring Boot based RESTful service that manages student records. The project demonstrates CRUD operations, Docker containerization, and Kubernetes deployment configurations.

## Key Features
- Create, read, update, and delete student information via HTTP endpoints.
- Uses Spring Data JPA with an embedded MySQL database.
- Dockerfile for building a lightweight container image.
- Kubernetes manifests for deployment, service, HPA, and ingress.
- Configuration profiles for development and production environments.

## Tech Stack
- **Java 17**
- **Spring Boot**
- **Spring Data JPA**
- **MySQL**
- **Docker**
- **Kubernetes**

## Getting Started
1. Build the project with Maven: `./mvnw clean package`.
2. Build the Docker image: `docker build -t student-service .`.
3. Deploy to Kubernetes using the YAML files in the `Yaml Files/` directory.

For detailed API documentation, refer to the Swagger UI when the application is running.
# Student Service REST API

A simple Spring Boot based RESTful service that manages student records. The project demonstrates CRUD operations, Docker containerization, and Kubernetes deployment configurations.

## Key Features
- Create, read, update, and delete student information via HTTP endpoints.
- Uses Spring Data JPA with an embedded MySQL database.
- Dockerfile for building a lightweight container image.
- Kubernetes manifests for deployment, service, HPA, and ingress.
- Configuration profiles for development and production environments.

## Tech Stack
- **Java 17**
- **Spring Boot**
- **Spring Data JPA**
- **MySQL**
- **Docker**
- **Kubernetes**

## Getting Started
1. Build the project with Maven: `./mvnw clean package`.
2. Build the Docker image: `docker build -t student-service .`.
3. Deploy to Kubernetes using the YAML files in the `Yaml Files/` directory.

For detailed API documentation, refer to the Swagger UI when the application is running.
# Eventsourcing-CRQS-Application
# Spring CQRS and Event Sourcing Microservice Example

This project demonstrates a microservice architecture utilizing CQRS (Command Query Responsibility Segregation) and Event Sourcing patterns. The backend is implemented using Java Spring Boot, and it integrates various technologies to provide a robust, scalable, and traceable system.

## Key Features
- **Backend**: Developed with Java Spring Boot and Spring Data JPA for data access.
- **Database**: Uses PostgreSQL for persistent storage.
- **Event Sourcing**: Implements event sourcing to store and retrieve state changes.
- **CQRS**: Separates read and write operations to optimize performance and scalability.
- **Messaging**: Integrates Apache Kafka for reliable event streaming.
- **Tracing**: Uses Jaeger for distributed tracing.
- **Monitoring**: Incorporates Prometheus and Grafana for monitoring and visualization.
- **Migration**: Utilizes Flyway for database migrations.
- **Resilience**: Employs Resilience4j for fault tolerance.
- **API Documentation**: Automates API documentation with Swagger OpenAPI 3.
- **Containerization**: Dockerized setup for consistent development and deployment environments.

## Technologies Used
- **Spring Boot**
- **Spring Data JPA**
- **Spring Data MongoDB**
- **Spring Cloud Sleuth**
- **Apache Kafka**
- **PostgreSQL**
- **Jaeger**
- **Docker**
- **Prometheus**
- **Grafana**
- **Flyway**
- **Resilience4j**
- **Swagger OpenAPI 3**

## Prerequisites
- Docker Desktop
- Java JDK (compatible version)
- Maven
- Node.js and npm 

## Getting Started

### Clone the Repository
```bash
git clone <repository_url>
cd <project_directory>

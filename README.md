# DevOps and AWS Hands-on Project Repository

This repository contains hands-on projects and examples implemented as part of the **DevOps Tools and AWS for Java Microservice Developers**. 
These projects are designed to demonstrate real-world scenarios for building, deploying and managing Java microservices using DevOps tools and AWS cloud services.

## Projects Overview

### Coupon Service
The **Coupon Service** is a Java-based microservice designed to manage discount coupons. Key features include:
- **CRUD Operations**: Create, update, and delete coupons through REST APIs.
- **Database Integration**: Uses MySQL for persistent storage, with JPA/Hibernate for ORM.
- **Spring Boot Features**: Leverages Spring Boot's dependency injection, validation, and exception handling.

### Docker Compose Demo
The **Docker Compose Demo** demonstrates how to use Docker Compose for orchestrating multi-container applications. Highlights include:
- **Service Composition**: Configure multiple containers such as application services, databases, and proxy servers in a single `docker-compose.yml` file.
- **Networking**: Automatic network creation and service discovery.
- **Volume Management**: Persistent storage configuration using Docker volumes.

### Flight Services
The **Flight Services** microservice focuses on managing flight-related operations. It provides:
- **Booking and Scheduling APIs**: REST endpoints for flight management.
- **Integration**: Connects with external systems for payment and notifications.
- **Spring Boot Features**: Uses Spring Data JPA for database interactions and Spring Security for securing endpoints.

### Kubernetes Configurations
The **Kubernetes Configurations** directory contains manifests for deploying and managing microservices in a Kubernetes cluster. Features include:
- **Pod and Deployment YAMLs**: Defines application deployments with replicas for high availability.
- **Service Definitions**: Configures cluster networking with LoadBalancer and ClusterIP services.
- **Scaling and Monitoring**: Includes configurations for horizontal pod autoscalers and readiness/liveness probes.

### Product Service
The **Product Service** is a Java-based microservice for managing product details. Key aspects include:
- **REST APIs**: Endpoints for creating, retrieving, updating, and deleting product information.
- **Database Management**: Uses Spring Data JPA for database CRUD operations.
- **Integration**: Extensible architecture to integrate with inventory or pricing systems.

## SQL Scripts
The **SQL** directory contains scripts for setting up the databases used by the microservices. Key elements include:
- **Schema Definition**: SQL scripts to create tables, relationships, and constraints.
- **Seed Data**: Prepopulated data for testing and development purposes.

## Configuration Files
- **`.gitignore`:** Specifies files and directories to be excluded from version control.
- **`demo.yml`:** A sample YAML configuration for orchestrating services or defining application environments.
- **`firstpod.yml`:** A Kubernetes manifest for deploying a basic Pod as an introductory example.

## Technologies Learned
This repository incorporates a wide range of technologies and tools, including:

- **Java Spring Boot**: Building scalable, production-ready microservices with RESTful APIs.
- **Docker**: Containerizing microservices and creating reproducible environments.
- **Docker Compose**: Simplifying multi-container orchestration and dependency management.
- **Kubernetes**: Managing containerized applications with features like scaling, load balancing, and self-healing.
- **MySQL**: Relational database management with integration through JPA and Hibernate.
- **YAML**: Configuration files for Docker Compose and Kubernetes manifests.
- **Spring Data JPA**: Simplifying database interactions with an abstraction layer.
- **Spring Security**: Implementing authentication and authorization for microservices.
- **CI/CD Concepts**: Automating the build, test, and deployment pipelines.
- **DevOps Practices**: Enhancing software delivery processes and infrastructure management.



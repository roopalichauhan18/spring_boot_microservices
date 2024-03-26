# Spring Boot Microservices
-> This repository contains a Spring Boot microservices project, leveraging the microservices architecture to modularize and scale the application effectively.
-> Utilized Spring Cloud for service discovery, configuration management, and centralized logging, ensuring seamless communication and management across microservices.
-> Implemented containerization with Docker and orchestration with Kubernetes for efficient deployment, scaling, and management of microservices in a distributed environment.


## How to run the application using Docker

1. Run `mvn clean package -DskipTests` to build the applications and create the docker image locally.
2. Run `docker-compose up -d` to start the applications.

## How to run the application without Docker

1. Run `mvn clean verify -DskipTests` by going inside each folder to build the applications.
2. After that run `mvn spring-boot:run` by going inside each folder to start the applications.


# Product Ordering System (Microservices)

A **Microservices-based Product Ordering System** built with **Spring Boot**, **Eureka Service Discovery**, **API Gateway**, and **Keycloak** for authentication and authorization.

## Features

- Product catalog and inventory management via REST APIs
- Order placement and tracking (planned)
- Service registration and discovery using Eureka
- Centralized routing via API Gateway
- Authentication and role-based authorization with Keycloak
- Modular and scalable microservices architecture

## Tech Stack

- Java 17+
- Spring Boot
- Spring Cloud Netflix Eureka
- Spring Cloud Gateway
- Spring Security
- Keycloak
- Maven
- H2 Database (for local testing)

## Architecture Overview

```plaintext
[Client] --> [API Gateway] --> [Product Service]  
                             --> [Order Service (future)]  
                             --> [Inventory Service (future)]  
                             ↑
                      [Eureka Server] (Service Registry)
                     
Authentication → Managed by [Keycloak]
```

[View Full Architecture Diagrams Here](https://miro.com/app/board/uXjVPpWfmhA=/?share_link_id=286933154034)

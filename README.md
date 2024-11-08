# MiniEcom Backend Application

Welcome to the **MiniEcom Backend Application**! This project provides a scalable and efficient backend architecture for an eCommerce platform, built using a microservices approach with Spring Boot.

## Features

- **Microservices Architecture**: Independent services for **Product**, **Order**, **Inventory**, and **Notifications**.
- **RESTful APIs**: Robust API endpoints for each service to allow easy communication and extensibility.
- **API Gateway**: Implemented with **Spring Cloud Gateway MVC** to handle routing and ensure secure communication.
- **Asynchronous Messaging**: Leveraging **Kafka** for improved performance and reliability of service interactions.
- **Authentication and Authorization**: Secured using **Keycloak** for managing user roles and access.
- **Monitoring and Analytics**: Integrated **Grafana Stack** for real-time monitoring and performance tracking.

## Table of Contents

- [Architecture](#architecture)
- [Tech Stack](#tech-stack)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Architecture

This project uses a **microservices architecture** where each service operates independently, making the system scalable and easy to maintain. Here’s a breakdown of the main components:

1. **Product Service**: Manages product information.
2. **Order Service**: Handles customer orders.
3. **Inventory Service**: Tracks stock levels.
4. **Notifications Service**: Sends notifications on events like order status updates.

![Architecture Diagram](path/to/your/architecture-diagram.png) <!-- Optional: Add a link to an architecture diagram image -->

## Tech Stack

- **Spring Boot**: For building each microservice.
- **Spring Cloud Gateway**: For API Gateway functionality.
- **Kafka**: As a messaging queue for asynchronous communication.
- **Keycloak**: For authentication and authorization.
- **Grafana Stack**: For monitoring, including Grafana, Prometheus, and Loki.

## Setup

### Prerequisites

- **Java** 17 or above
- **Docker** and **Docker Compose**
- **Maven**
- **Kafka** (can be set up via Docker)
- **Keycloak** (can be set up via Docker)
- **Prometheus and Grafana** (can be set up via Docker)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/eCom-Application/MiniEcom-Backend.git
   cd MiniEcom-Backend

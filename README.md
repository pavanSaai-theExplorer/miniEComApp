# MiniEcom Backend Application

Welcome to the **MiniEcom Backend Application**! This project is a scalable backend solution for an eCommerce platform, structured as a microservices architecture with Spring Boot.

## Table of Contents

- [Features](#features)
- [Architecture](#architecture)
- [Tech Stack](#tech-stack)
- [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Configuration](#configuration)
- [API Endpoints](#api-endpoints)
- [Monitoring](#monitoring)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Microservices Architecture**: Independent services for **Product**, **Order**, **Inventory**, and **Notifications** for modularity and scalability.
- **API Gateway**: Built with **Spring Cloud Gateway MVC** for secure and efficient routing of requests.
- **Asynchronous Messaging**: Utilizes **Kafka** for asynchronous, reliable interactions between services.
- **Authentication and Authorization**: Secured with **Keycloak** for managing user access and roles.
- **Monitoring and Analytics**: Integrated with **Grafana Stack** (Grafana, Prometheus, Loki) for comprehensive monitoring and analytics.

## Architecture

The **MiniEcom Backend Application** is designed using a microservices architecture, enabling each service to function independently for easier scaling and maintenance.

### Main Services

1. **Product Service**: Manages product catalog, details, and pricing.
2. **Order Service**: Handles order creation, processing, and tracking.
3. **Inventory Service**: Manages stock levels and product availability.
4. **Notifications Service**: Sends notifications to users on significant events, such as order updates.

![Architecture Diagram](path/to/your/architecture-diagram.png) <!-- Replace with the actual path if available -->

Each service communicates via RESTful APIs and asynchronous Kafka messaging, while an API Gateway serves as a unified entry point for requests, simplifying client interactions with the system.

## Tech Stack

- **Backend Framework**: Spring Boot
- **API Gateway**: Spring Cloud Gateway
- **Messaging Queue**: Kafka
- **Authentication**: Keycloak
- **Monitoring**: Grafana, Prometheus, and Loki

## Setup

### Prerequisites

- **Java** 17 or higher
- **Docker** and **Docker Compose**
- **Maven**
- **Kafka** (can be run via Docker)
- **Keycloak** (can be run via Docker)
- **Grafana and Prometheus** (can be run via Docker)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/eCom-Application/MiniEcom-Backend.git
   cd MiniEcom-Backend

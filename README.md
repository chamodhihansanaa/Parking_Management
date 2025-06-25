# Smart Parking Management System (SPMS)

### A microservice-based application for managing parking spaces efficiently in urban environments.
# Project Overview

### The Smart Parking Management System (SPMS) is a cloud-native, microservice-based platform designed to offer real-time management and monitoring of parking spaces. It allows users to easily locate, reserve, and pay for parking while helping parking owners manage their spaces effectively.
# Architecture

### The system consists of the following microservices:

    Eureka Server - Service registry for dynamic service discovery
    Config Server - Centralized configuration management
    API Gateway - Single entry point for all client requests
    Parking Space Service - Manages parking spaces and availability
    Vehicle Service - Handles vehicle operations and tracking
    User Service - Manages user and owner information
    Payment Service - Handles payment transactions

### Technology Stack

    Java 17
    Spring Boot 3.2.3
    Spring Cloud 2023.0.0
    Spring Cloud Eureka
    Spring Cloud Config
    Spring Cloud Gateway
    Maven
    Lombok

### Prerequisites

    Java 17 or higher
    Maven 3.6 or higher
    Git

### Getting Started

    Clone the repository:

git clone :


    Build the project:

### mvn clean install

    Start the services in the following order:
        Eureka Server
        Config Server
        API Gateway
        Other microservices

### API Documentation

The API documentation is available in the Postman collection: Postman Collection


### Features

    Real-time parking space availability tracking
    Dynamic space allocation
    Digital transactions and booking receipts
    User authentication and authorization
    Vehicle tracking and management
    Payment processing
    Historical logs and analytics

 ###   Service Registry
The Eureka dashboard showing all registered services: 

![eurekaDashboard](https://github.com/user-attachments/assets/7bfea30c-595f-4952-ac67-c65c40793436)


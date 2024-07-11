# Capstone: E-Commerce Backend Microservice Project

## Overview
Capstone is a scalable and maintainable e-commerce backend project built using a microservice architecture. The project is composed of three main services: Product Service, User Service, and Payment Service. The microservices communicate with each other using REST APIs and are optimized for performance and security using Redis and Kafka.

## Services

### 1. Product Service
- **Description:** Manages product data and integrates with third-party APIs.
- **Database:** MySQL for storing and fetching product information.
- **Features:**
    - CRUD operations for products.
    - Integration with external APIs for additional product data.
- **Repository:** [Product Service](https://github.com/VijayantShri/Product-Service.git)

### 2. User Service
- **Description:** Handles user authentication and profile management.
- **Authentication:** JWT (JSON Web Token) for secure authentication.
- **Features:**
    - User registration and login.
    - Profile management.
- **Repository:** [User Service](https://github.com/VijayantShri/User-Service.git)

### 3. Payment Service
- **Description:** Processes payments securely using Stripe API.
- **Integration:** Stripe API for handling payments.
- **Features:**
    - Payment processing.
    - Secure transactions.
- **Repository:** [Payment Service](https://github.com/VijayantShri/Payment-Service.git)

## Architecture
- **Tech Stack:** Java, Spring Boot, Docker, Redis, Kafka
- **Communication:** REST APIs
- **Database:** MySQL for product data, Redis for caching
- **Message Broker:** Kafka for optimizing API performance

## Key Features
- **Third-Party Integrations:**
    - Product Service integrates with external APIs.
    - Payment Service integrates with Stripe for secure payments.
- **Security:** JWT authentication for User Service.
- **Optimization:** Redis for caching, Kafka for message brokering.
- **Testing:** Comprehensive test cases covering most functionalities.

## How to Run
1. **Clone the repositories:**
   ```bash
   git clone https://github.com/YOUR_GITHUB_USERNAME/product-service.git
   git clone https://github.com/YOUR_GITHUB_USERNAME/user-service.git
   git clone https://github.com/YOUR_GITHUB_USERNAME/payment-service.git

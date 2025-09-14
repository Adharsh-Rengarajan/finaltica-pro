# FinalticaPro – Smart Expense and Investment Management System

FinalticaPro is a backend-focused, microservices-based FinTech application designed to help users manage their personal finances. It supports logging income and expenses, setting and tracking financial goals, generating monthly reports, and receiving rule-driven financial recommendations.

## Features

- User registration and JWT-based authentication
- Income and expense logging with categorization
- Custom goal creation and progress tracking
- Monthly financial report generation (PDF)
- Rule-based financial advisor engine
- Microservice architecture with Spring Cloud Gateway and Eureka
- Cloud-ready deployment using AWS EC2, RDS, and S3

## Tech Stack

### Backend Technologies
- Java 17
- Spring Boot 3
- Spring Security (JWT)
- Spring Data JPA (PostgreSQL)
- Spring Cloud Gateway & Eureka
- Python 3.10 (FastAPI)

### Tools and Infrastructure
- PostgreSQL
- AWS EC2 (for service hosting)
- AWS RDS (PostgreSQL)
- AWS S3 (for storing reports)
- Swagger/OpenAPI
- Maven

## Microservices Overview

- **User Service**: Handles registration, login, authentication, and roles
- **Transaction Service**: Records income/expenses with category and timestamp filters
- **Goal Service**: Manages financial goals and tracks completion
- **Report Service**: Generates PDF reports and uploads to S3
- **Advisor Service** (Python): Offers rule-based financial suggestions
- **API Gateway**: Routes requests and validates security tokens

## Getting Started

### Prerequisites

- Java 17
- Python 3.10
- Maven
- PostgreSQL
- AWS account (with EC2, RDS, S3 setup)

### Clone the Repository

```bash
git clone https://github.com/yourusername/FinalticaPro.git
cd FinalticaPro

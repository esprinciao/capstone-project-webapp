
### Urban Safety & Well-Being Web Application


## Problem Statement
In today’s urban environments, personal safety and well-being are major concerns, especially for individuals living or working in high-risk areas. Threats like crime, harassment, accidents, and the stresses of daily life can negatively affect mental and emotional well-being. While there are apps available for safety tracking or mental health support, few provide an integrated solution that addresses both safety and well-being in a user-friendly way.

## Project Overview
This project provides a comprehensive web-based solution that combines personal safety and well-being features. It is designed to help users respond to emergencies, manage daily stresses, and improve their overall well-being. The platform has the following main features:

## Key Features
Safety Microservice: Emergency contact management, SMS & location sharing, SOS message customization, safety tips, guidelines, and access to help videos.
Well-Being Microservice: Daily well-being tests, AI-powered well-being assistant (Gemini API), features for diet tracking, sleep scheduling, screen time monitoring, and zen mode for mindfulness.
API Gateway: Manages user authentication and authorization with JWT tokens. Handles user login and signup.
Eureka Service Registry: Manages service discovery for the microservices architecture.

## Architecture
The application follows a microservices architecture with the following key components:

API Gateway for authentication and routing.
Safety Microservice for handling emergency features.
Well-Being Microservice for managing personal well-being tools.
Eureka Service Registry for service discovery.

Frontend
Built using Angular, the frontend is a user-friendly interface for interacting with the safety and well-being features of the platform.
Features modern design, with responsive layouts to ensure usability on different devices.
Backend
Built using Spring Boot, the backend handles the API requests, manages the PostgreSQL database, and communicates with external services such as SMS and location APIs.
Implements a secure JWT authentication mechanism for all microservices.
Installation & Setup
Prerequisites:
Node.js for the Angular frontend.
Java 17 for the Spring Boot backend.
PostgreSQL for database management.


# Pomodoro Timer - Backend API

This repository contains the Backend service for the **Pomodoro Timer** application. It is a RESTful API built to manage the logic, user sessions, and data persistence of the Pomodoro system.

##  Project Overview

The backend serves as the core engine for the Pomodoro Timer, handling the communication between the client-side interface and the database. It is designed to be scalable and is currently prepared for containerized deployment.

* **Purpose:** Manage user data and application state.
* **Architecture:** REST API.
* **Deployment:** Hosted on **Railway** using Docker containers.

##  Tech Stack

The service is developed with a robust set of technologies for backend development:

* **Java & Spring Boot:** Main framework for application logic.
* **Spring Data JPA:** For Object-Relational Mapping (ORM).
* **PostgreSQL:** Primary relational database for data persistence.
* **Maven:** Dependency management and project build tool.
* **Docker:** Containerization for consistent deployment environments.

##  Repository Structure

Key components of the backend:
* `src/`: Contains the main Java source code and application configurations.
* `pom.xml`: Project Object Model file with all dependencies (Spring Boot, PostgreSQL driver, etc.).
* `Dockerfile`: Instructions for building the container image for Railway.
* `.mvn/wrapper`: Maven Wrapper to ensure the project builds with a specific Maven version.

##  Deployment and Database

The application is configured to be deployed on **Railway**. It utilizes a **PostgreSQL** database to store relevant information. Recent updates include:
* Migration to PostgreSQL for improved data handling.
* Optimization of the Docker configuration for production environments.

##  Related Repositories

This project works in conjunction with the frontend:
* **Frontend Repository:** [Pomodoro-Timer](https://github.com/Yandell-code-master/Pomodoro-Timer)

---
Developed by [Yandell-code-master](https://github.com/Yandell-code-master)
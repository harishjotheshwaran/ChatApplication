# Spring Boot Web Application

This is a demo web application built with Spring Boot 3.5.3, supporting MVC web pages, RESTful APIs, and WebSocket communication. The project uses Maven for build and dependency management.

# Technologies Used

- Java 21
- Spring Boot 3.5.3
- Spring Web (REST and MVC)
- Thymeleaf (Template Engine)
- WebSocket (Real-time communication)
- Lombok (Reducing boilerplate code)
- Maven (Build Tool)

# Project Structure

├── src
│ ├── main
│ │ ├── java/... → Java source code
│ │ └── resources/... → Application resources
│ └── test → Test cases
├── pom.xml → Maven configuration
├── mvnw / mvnw.cmd → Maven wrapper scripts
├── HELP.md → Reference and usage guides
├── .gitignore → Ignored files for VCS


# Features

- RESTful API endpoints using Spring MVC
- Dynamic web content rendering with Thymeleaf
- Real-time bidirectional messaging with WebSocket
- Integrated testing with Spring Boot Test
- Build and run with Maven Wrapper

# How to Run

# Prerequisites
- Java 21+
- Git (optional, for cloning)
- No need to install Maven manually (uses Maven Wrapper)

# Steps

bash
# Clone the repository
git clone <your-repo-url>
cd <your-project-folder>

# Run with Maven Wrapper:
./mvnw spring-boot:run
./mvnw test

The app will be available at http://localhost:8080.

Resources:
Spring Boot Web Docs
Thymeleaf Reference
WebSocket with Spring
Maven Documentation


Architecture Diagram Description:
        +----------------------+
        |   Web Browser (UI)   |
        |   HTML / JS / CSS    |
        +----------+-----------+
                   |
                   v  (HTTP / WebSocket)
        +----------+-----------+
        |   Spring Boot App    |
        |  (Controller Layer)  |
        +----------+-----------+
                   |
        +----------+-----------+
        |  Service Layer (Optional) |
        +----------+-----------+
                   |
        +----------+-----------+
        | Repository / DAO (Future) |
        +----------------------+

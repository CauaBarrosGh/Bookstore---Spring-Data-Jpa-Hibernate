# Bookstore

![Java](https://img.shields.io/badge/Java-17-blue)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.1.4-green)
![JPA/Hibernate](https://img.shields.io/badge/JPA/Hibernate-orange)
![Maven](https://img.shields.io/badge/Maven-red)

## 📖 About the Project

Bookstore is a bookstore management system developed as part of my backend development studies with Java and Spring Boot. The RESTful API allows performing CRUD operations (Create, Read, Update, Delete) to manage books, authors, publishers, and their respective reviews.

The project was built with a focus on development best practices, such as separation of responsibilities across layers (Controllers, Services, Repositories), the use of DTOs (Data Transfer Objects) for client communication, and entity mapping with JPA/Hibernate.o foi construído com foco em boas práticas de desenvolvimento, como a separação de responsabilidades em camadas (Controllers, Services, Repositories), o uso de DTOs (Data Transfer Objects) para comunicação com o cliente e o mapeamento de entidades com JPA/Hibernate.

---

## ✨ Features

- Book Management: Full CRUD for books.

- Relationships: Mapping of complex relationships:

  -  One-to-One: Book → Review

  -  Many-to-One: Books → Publisher

  -  Many-to-Many: Books ↔ Authors

- Service Layer: Centralized and transactional business logic (@Transactional).

- Data Validation: Use of DTOs to validate input data.

---

## 🛠️ Technologies Used

This project was built using the following technologies:

Java 21: Main programming language.
- **Spring Boot:** Framework for building the application and REST API.
- **Spring Web:** For creating controllers and REST endpoints.
- **Spring Data JPA:** For simplified data persistence.
- **Hibernate:** JPA implementation for object-relational mapping (ORM).
- **PostgreSQL:** Database used.
- **Maven:** Dependency manager and project build tool.

---

## 📂 Project Structure

The project follows the standard layered architecture of Spring Boot to ensure organized and maintainable code.

## 🚀 How to Run the Project

Prerequisites:

- Java 21 (or higher)

- Maven

Clone the repository:

- git clone https://github.com/CauaBarrosGh/Bookstore---Spring-Data-Jpa-Hibernate.git

Navigate to the project directory:

- cd [repository-name]

Run the application:

- mvn spring-boot:run

**The application will be available at http://localhost:8080.**

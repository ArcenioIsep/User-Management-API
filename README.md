# User-Management-API


## 📌 Project Description
The **User Management API** is a backend RESTful application developed using **Java and Spring Boot**, designed to manage users in a clean, scalable, and professional way.

The project implements a **full CRUD system**, follows **layered architecture best practices**, and simulates a real-world backend service commonly found in enterprise environments.

This project was built as part of my professional development as a **Java Backend Developer**, focusing on clean code, REST standards, and maintainability.

## 🎯 Project Goals
- Apply Java and Spring Boot in a real backend scenario  
- Practice REST API design and best practices  
- Work with relational databases using JPA/Hibernate  
- Structure a project following enterprise standards  
- Prepare a portfolio-ready project for Junior Java positions  

## 🧱 Architecture & Structure

The project follows a **layered architecture**, separating responsibilities clearly:

src/main/java/com/arcenio/usermanagement
│

├── controller     → REST controllers (API layer)

├── service        → Business logic

├── repository     → Data access layer (JPA)

├── dto            → Data Transfer Objects

├── entity         → JPA entities

├── exception      → Global exception handling

├── config         → Configuration classes

└── UserManagementApplication.java


✔️ This structure improves readability, testability, and scalability  
✔️ Commonly used in real company projects

## 🛠️ Tech Stack

**Languages & Core**
- Java 17

**Frameworks & Libraries**
- Spring Boot
- Spring Web
- Spring Data JPA
- Hibernate
- Bean Validation
- Lombok

**Database**
- PostgreSQL

**Tools**
- Maven
- Git / GitHub
- Swagger (OpenAPI)

## 🌐 REST API Endpoints

| Method | Endpoint            | Description              |
|------|---------------------|--------------------------|
| POST | `/api/users`         | Create a new user        |
| GET  | `/api/users`         | List users (paginated)   |
| GET  | `/api/users/{id}`    | Get user by ID           |
| PUT  | `/api/users/{id}`    | Update user              |
| DELETE | `/api/users/{id}`  | Delete user              |

## ✅ Features Implemented
- Full CRUD operations
- RESTful API design
- Input validation
- Pagination and sorting
- DTO pattern
- Global exception handling
- Clean and maintainable code structure
- API documentation with Swagger

## 🚀 How to Run the Project

### Prerequisites
- Java 17+
- Maven
- PostgreSQL

### Steps
1. Clone the repository:
   git clone https://github.com/your-username/user-management-api.git
2. Configure the database connection in `application.properties`
3. Run the application:
   mvn spring-boot:run
4. Access Swagger UI:
   http://localhost:8080/swagger-ui.html

## 📖 What This Project Demonstrates
- Practical experience with **Java backend development**
- Ability to design and implement **REST APIs**
- Knowledge of **Spring Boot ecosystem**
- Understanding of **database integration with JPA**
- Use of **professional Git workflow**
- Readiness for **Junior Java Developer roles**

## 🔮 Future Improvements
- Authentication and authorization (Spring Security + JWT)
- Unit and integration tests
- Docker support
- Role-based access control

## 👤 Author
**Arcenio Uate**  
Junior Java Backend Developer  
Student of Computer Engineering (ISEP)


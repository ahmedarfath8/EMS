# EMS (employee management system)
# Simple Spring Boot CRUD Application

This is a basic Spring Boot project that provides RESTful APIs to manage `Employee` records using Spring Data JPA.

## Tech Stack
- Java 8 
- Spring Boot 2.7.18 
- Spring Data JPA
- MySQL
- Lombok 
- Maven

## How to Run
1. Clone the repository.
2. Open in your IDE.
3. Run `DemoApplication.java`.

The server starts at: `http://localhost:8080`

## API Endpoints

| Method | Endpoint         | Description              |
|--------|------------------|--------------------------|
| POST   | `/employee`      | Create new employee      |
| GET    | `/employee`      | Get all employees        |
| GET    | `/employee/{id}` | Get employee by ID       |
| PUT    | `/employee/{id}` | Update employee by ID    |
| DELETE | `/employee/{id}` | Delete employee by ID    |

---

You can test the APIs using tools like **Postman** or **cURL**.



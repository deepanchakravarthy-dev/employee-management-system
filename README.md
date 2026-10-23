# Employee Management System — Spring Boot REST API
Secure, scalable RESTful API built from scratch using **Java 11, Spring Boot, Spring Data JPA, Hibernate, and MySQL** for managing enterprise employee records with complete CRUD operations and Postman verification.

## Tech Stack
- **Language**: Java 11 (OOP, Collections, Exception Handling)
- **Framework**: Spring Boot, Spring Web (REST API), Spring Data JPA, Hibernate
- **Database**: MySQL 8.0
- **Build & Testing**: Maven, Postman, Git

## REST API Endpoints
| HTTP Method | Endpoint | Description |
| :--- | :--- | :--- |
| `GET` | `/api/v1/employees` | Fetch all employee records |
| `GET` | `/api/v1/employees/{id}` | Fetch employee by ID |
| `POST` | `/api/v1/employees` | Create a new employee record |
| `PUT` | `/api/v1/employees/{id}` | Update existing employee details |
| `DELETE` | `/api/v1/employees/{id}` | Delete an employee record |

## Architecture
- **Controller Layer**: Handles REST HTTP requests and responses (`EmployeeController.java`)
- **Service Layer**: Business logic and transaction management (`EmployeeService.java`)
- **Repository Layer**: JPA/Hibernate database persistence (`EmployeeRepository.java`)
- **Entity Layer**: JPA-mapped domain model (`Employee.java`)

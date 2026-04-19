# Student Management System

## Description
A backend REST API built using Spring Boot to manage student records efficiently.

## Features
- Add, update, delete students (CRUD)
- Search students by name and course
- Input validation using annotations
- Global exception handling
- Swagger UI for API testing

## Technologies Used
- Java
- Spring Boot
- Spring Data JPA
- H2 Database
- Swagger UI

## How to Run
1. Clone the repository
2. Open in IntelliJ IDEA
3. Run `StudentManagementApplication`
4. Open browser:
   http://localhost:8080/swagger-ui.html

## API Endpoints
- GET /students
- POST /students
- PUT /students/{id}
- DELETE /students/{id}
- GET /students/search/name?name=
- GET /students/search/course?course=

## Future Improvements
- Add MySQL database
- Add authentication (JWT)
- Build frontend (React)

---

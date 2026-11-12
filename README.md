# Student Management REST API

A robust Spring Boot backend application for managing student records, built as part of backend engineering coursework.

## Tech Stack
* **Language:** Java 25
* **Framework:** Spring Boot (Spring Web, Spring Data JPA)
* **Database:** MySQL
* **Validation & Lombok:** Jakarta Validation, Project Lombok

## REST API Endpoints

| HTTP Method | Endpoint | Description |
| :--- | :--- | :--- |
| **POST** | `/api/students` | Add a new student |
| **GET** | `/api/students` | Retrieve all students |
| **GET** | `/api/students/{id}` | Retrieve student by ID |
| **PUT** | `/api/students/{id}` | Update student details |
| **DELETE** | `/api/students/{id}` | Delete a student |
| **GET** | `/api/students/course/{course}` | Retrieve students by course |

## Getting Started

1. Clone the repository:
   ```bash
   git clone [https://github.com/AgentXZY/student-management-api.git](https://github.com/AgentXZY/student-management-api.git)

# Task Manager Application

A simple Task Manager built using **Spring Boot** with full **CRUD operations**, connected to a **PostgreSQL** database.

## Features

- Create, Read, Update, Delete (CRUD) tasks
- RESTful API endpoints
- Integration with PostgreSQL
- Error handling and validations
- Logging using Spring Boot

## Technologies Used
- Java 21
- Spring Boot
- Spring Data JPA
- PostgreSQL
- Maven


...

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Rahul9672/Task_Management_App.git
cd taskmanager

### 2. Set up PostgreSQL Database
```bash

CREATE DATABASE taskmanager;

spring.datasource.url=jdbc:postgresql://localhost:5432/taskmanager
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update

### 3. Run the Application

./mvnw spring-boot:run

### 4. server will start at:

http://localhost:8080

### 4. API Endpoints

| Method | Endpoint    | Description       |
| ------ | ----------- | ----------------- |
| GET    | /tasks      | Get all tasks     |
| GET    | /tasks/{id} | Get task by ID    |
| POST   | /tasks      | Create a new task |
| PUT    | /tasks/{id} | Update task by ID |
| DELETE | /tasks/{id} | Delete task by ID |



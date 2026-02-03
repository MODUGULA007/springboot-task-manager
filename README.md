# Spring Boot Task Manager Application

A **Task Management System** built using **Spring Boot** that allows users to create, update, delete, and track tasks efficiently.  
This project demonstrates **RESTful API development**, layered architecture, and database integration using modern Java backend practices.

---

## ✨ Features

- 📋 Task CRUD Operations (Create, Read, Update, Delete)
- 🏷️ Task Priority (Low, Medium, High)
- 📅 Due Date & Status Management
- 🔍 Filter tasks by status or priority
- 🧩 RESTful APIs for frontend or mobile integration
- 🧪 API testing using Postman

---

## 🛠️ Tech Stack

- **Language**: Java  
- **Framework**: Spring Boot  
- **Architecture**: Controller – Service – Repository  
- **Database**: MySQL  
- **ORM**: Spring Data JPA / Hibernate  
- **Build Tool**: Maven  
- **API Testing**: Postman  

---

## 📂 Project Structure

```plaintext
springboot-task-manager/
├── controller/        # REST Controllers
├── service/           # Business Logic
├── repository/        # JPA Repositories
├── model/             # Entity Classes
├── dto/               # Data Transfer Objects
├── exception/         # Global Exception Handling
├── application.yml    # Configuration
└── pom.xml            # Maven Dependencies

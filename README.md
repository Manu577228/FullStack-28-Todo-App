# 📝 TodoApp – Spring Boot 4 + Thymeleaf + MySQL

A full-stack Task Management Web Application built using Spring Boot 4, Spring MVC, Spring Data JPA, Thymeleaf, and MySQL.

This project demonstrates clean layered architecture and real-world CRUD operations using modern Java (21).

---

## 🚀 Features

- ✅ Add New Tasks
- 📋 View All Tasks
- ✏️ Edit Tasks
- 🗑 Delete Tasks
- 💾 MySQL Database Integration
- 🎨 Responsive UI using Bootstrap 5
- 🧱 Clean MVC + Service Layer Architecture

---

## 🛠 Tech Stack

- Java 21
- Spring Boot 4.0.3
- Spring MVC
- Spring Data JPA (Hibernate)
- Thymeleaf
- MySQL
- Lombok
- Maven

---

## 📁 Project Structure

src/main/java/com/app/todoapp

├── controller     → Handles HTTP requests  
├── models         → Entity classes  
├── repository     → JPA Repositories  
├── services       → Business logic  
└── TodoappApplication.java  

src/main/resources

├── templates  
│     ├── tasks.html  
│     └── edit-task.html  
└── application.properties  

---

## 🧠 Architecture

Client (Browser)  
↓  
Controller  
↓  
Service  
↓  
Repository  
↓  
MySQL Database  

- Controller manages routes  
- Service contains business logic  
- Repository communicates with database  
- Thymeleaf renders dynamic HTML  

---

## ⚙️ Setup & Run

### 1️⃣ Clone the Repository

git clone https://github.com/your-username/todoapp.git  
cd todoapp  

### 2️⃣ Configure MySQL

Update `src/main/resources/application.properties`:

spring.datasource.url=jdbc:mysql://localhost:3306/todo_db  
spring.datasource.username=root  
spring.datasource.password=your_password  
spring.jpa.hibernate.ddl-auto=update  

Make sure MySQL is running and database `todo_db` exists.

### 3️⃣ Run Application

Using Maven Wrapper:

./mvnw spring-boot:run  

Or:

mvn spring-boot:run  

### 4️⃣ Open in Browser

http://localhost:8080  

---

## 🧪 Testing Dependencies Included

- spring-boot-starter-data-jpa-test
- spring-boot-starter-thymeleaf-test
- spring-boot-starter-webmvc-test

You can add unit and integration tests easily.

---

## 🌟 Future Enhancements

- 🔐 Add Spring Security (Authentication)
- 🔎 Task Filtering (Completed / Pending)
- 📊 Pagination
- 🐳 Docker Support
- ☁️ Cloud Deployment (AWS / Render)
- 🧪 Full Test Coverage

---

## 🎯 What This Project Demonstrates

- Modern Spring Boot 4 architecture
- Clean separation of concerns
- Database integration with JPA
- Server-side rendering using Thymeleaf
- Production-style folder structure
- Real-world CRUD application

Perfect for:
- Portfolio Projects
- Internship Applications
- Backend Development Practice
- Spring Boot Learning

---

## 👨‍💻 Author

Bharadwaj  

If you found this useful, consider giving it a ⭐ on GitHub!

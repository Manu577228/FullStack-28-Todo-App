# 📝 TodoApp – Full Stack Spring Boot 4 Application

Production-ready Task Management Web Application built using Spring Boot 4, Spring MVC, Thymeleaf, and MySQL.

---

## 🚀 Overview

TodoApp is a clean and scalable full-stack web application that allows users to manage daily tasks efficiently.

It demonstrates:

- Layered MVC Architecture  
- Service–Repository Pattern  
- Database Integration using JPA  
- Server-Side Rendering with Thymeleaf  
- Responsive UI with Bootstrap 5  
- Modern Java 21 Development  

---

## 🛠 Tech Stack

Java 21  
Spring Boot 4.0.3  
Spring MVC  
Spring Data JPA (Hibernate)  
Thymeleaf  
MySQL  
Lombok  
Maven  

---

## 📁 Project Structure

```
todoapp
│
├── pom.xml
├── mvnw
├── mvnw.cmd
│
└── src
    ├── main
    │   ├── java
    │   │   └── com.app.todoapp
    │   │       ├── controller
    │   │       ├── models
    │   │       ├── repository
    │   │       ├── services
    │   │       └── TodoappApplication.java
    │   │
    │   └── resources
    │       ├── templates
    │       │   ├── tasks.html
    │       │   └── edit-task.html
    │       └── application.properties
    │
    └── test
        └── java
            └── com.app.todoapp
```

---

## 🧠 Architecture Flow

Client (Browser)  
↓  
Controller Layer  
↓  
Service Layer  
↓  
Repository Layer  
↓  
MySQL Database  

---

## ✨ Features

- Add Tasks  
- View All Tasks  
- Edit Tasks  
- Delete Tasks  
- Persistent MySQL Storage  
- Fully Responsive UI  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

git clone https://github.com/Manu577228/todoapp.git  
cd todoapp  

### 2️⃣ Configure MySQL

Open:

src/main/resources/application.properties

Add:

spring.datasource.url=jdbc:mysql://localhost:3306/todo_db  
spring.datasource.username=root  
spring.datasource.password=your_password  
spring.jpa.hibernate.ddl-auto=update  
spring.jpa.show-sql=true  

Make sure MySQL is running and database `todo_db` exists.

### 3️⃣ Run Application

./mvnw spring-boot:run  

or  

mvn spring-boot:run  

### 4️⃣ Open in Browser

http://localhost:8080  

---

## 🧪 Testing Support

spring-boot-starter-data-jpa-test  
spring-boot-starter-thymeleaf-test  
spring-boot-starter-webmvc-test  

---

## 🌟 Future Enhancements

- Spring Security Authentication  
- Search & Filtering  
- Pagination  
- Docker Support  
- Cloud Deployment  
- Full Test Coverage  
- REST API Version  

---

## 👨‍💻 Author

Bharadwaj  

GitHub: https://github.com/Manu577228  
YouTube: https://youtube.com/@code-with-Bharadwaj  

If you found this helpful, consider giving it a ⭐ on GitHub!

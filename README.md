# 👨‍💼 Employee Management System

A full-stack Employee Management System built using Spring MVC, Hibernate (JPA), MySQL, and Spring Security.  
This application allows Admin and User roles to manage employee records with complete CRUD functionality.

---

## 🚀 Features

- ➕ Add new employees  
- 📋 View employee list  
- ✏ Update employee details  
- ❌ Delete employees (Admin only)  
- 🔐 Role-Based Access Control (ADMIN / USER)  
- 🗄 MySQL database integration  
- 🏗 Layered Architecture (Controller → Service → Repository → Database)  

---

## 🛠 Tech Stack

- Java 17  
- Spring Boot  
- Spring MVC  
- Hibernate (JPA)  
- MySQL  
- Spring Security  
- Thymeleaf  
- Maven  

---

## 📂 Project Structure
employee-management-system
│
├── src
│ └── main
│ ├── java
│ │ └── com.ems
│ │ ├── EmployeeManagementApplication.java
│ │ │
│ │ ├── config
│ │ │ └── SecurityConfig.java
│ │ │
│ │ ├── controller
│ │ │ └── EmployeeController.java
│ │ │
│ │ ├── model
│ │ │ └── Employee.java
│ │ │
│ │ ├── repository
│ │ │ └── EmployeeRepository.java
│ │ │
│ │ ├── service
│ │ │ ├── EmployeeService.java
│ │ │ └── impl
│ │ │ └── EmployeeServiceImpl.java
│ │
│ └── resources
│ ├── application.properties
│ ├── templates
│ │ ├── employees.html
│ │ ├── create_employee.html
│ │ └── edit_employee.html
│
├── pom.xml
└── README.md

📦 E-Commerce Order & Inventory Management System
🚀 Project Overview

A full-stack E-Commerce Order & Inventory Management System built using Spring Boot (Backend) and Frontend Web Technologies.

This system allows administrators to:

-Manage products
-Track inventory
-Process customer orders
-Monitor stock levels
-Maintain order records efficiently
-Designed using RESTful architecture and clean layered structure.

🛠️ Tech Stack
🔹Backend
-Java 17
-Spring Boot
-Spring Data JPA
-Hibernate
-MySQL
-Maven

🔹Frontend
-HTML
-CSS
-JavaScript

🔹Tools
-Eclipse IDE
-Postman (API Testing)
-Git & GitHub


🏗️ Project Architecture

Controller Layer
      ↓
Service Layer
      ↓
Repository Layer (JPA)
      ↓
MySQL Database

The application follows a clean layered architecture to ensure:

-Maintainability
-Scalability
-Separation of concerns

✨ Features

🛒 Product Management
-Add new products
-Update product details
-Delete products
-View product list

📦 Inventory Management
-Track stock quantity
-Auto-update inventory on order placement
-Prevent order if stock unavailable

🧾 Order Management
-Create customer orders
-View order history
-Track order details


📂 Project Structure
ECOM_NEW
│
├── E-CommerceOrder        → Spring Boot Backend
├── ECommerce-Frontend     → Frontend UI
└── README.md


⚙️ How to Run the Project
🔹 Backend Setup
1] Clone the repository:
git clone https://github.com/UtkarshUpadhyay7/E-Commerce-Order-Inventory-System.git

2] Open in Eclipse / IntelliJ
3] Configure MySQL database
4]Update application.properties
5]Run Spring Boot application

🔹 Frontend Setup
1] Navigate to ECommerce-Frontend
2] Open index.html
3] Connect to backend APIs
4] Run in browser

🗄️ Database Configuration (Example)
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update

📌 API Sample Endpoints
| Method | Endpoint       | Description      |
| ------ | -------------- | ---------------- |
| GET    | /products      | Get all products |
| POST   | /products      | Add new product  |
| PUT    | /products/{id} | Update product   |
| DELETE | /products/{id} | Delete product   |
| POST   | /orders        | Create order     |

🎯 Learning Outcomes
-Built REST APIs using Spring Boot
-Implemented layered architecture
-Integrated MySQL database
-Practiced Git version control
-Designed full-stack application structure

👨‍💻 Author

Utkarsh Upadhyay
Backend Developer | Java & Spring Boot Enthusiast

GitHub: https://github.com/UtkarshUpadhyay7


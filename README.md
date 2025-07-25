# ⚡ ElectroMart – E-Commerce Microservices Platform for Electronic Devices

A modular and scalable backend system for an online electronics store, built with **Java + Spring Boot** using **Microservices Architecture**.

---

## 🔧 Tech Stack

- **Language:** Java  
- **Framework:** Spring Boot, Spring Cloud Gateway  
- **Security:** Spring Security, JWT  
- **Database:** MongoDB, PostgreSQL  
- **DevOps:** Docker, Docker Compose, Jenkins  
- **Other:** Redis, WebClient, API Gateway  

---

## 🧩 Microservices Overview

- `auth-service`: User registration, login, JWT generation  
- `product-service`: Manage electronics products and categories  
- `cart-service`: Add/remove/update items in cart  
- `order-service`: Order creation and tracking  
- `payment-service`: Handle payment simulation  
- `report-service`: Sales reports and statistics (JasperReports)  
- `admin-service`: Admin dashboard & control  
- `api-gateway`: Request routing, global authentication  

---

## ✅ Features

- ✅ JWT-based authentication and authorization  
- ✅ Role-based access control  
- ✅ RESTful APIs with consistent response format  
- ✅ Microservice communication via HTTP  
- ✅ Dockerized environment  
- ✅ CI/CD integration with Jenkins  
- ✅ MVC design with layered structure  

---

## 👥 Contributors

This project was developed as a group assignment for the *Software Architecture & Design* course.

🔗 **View full team repository with commit history and contributors:**  
[GitHub – Original Repo (Team)](https://github.com/HoangNam69/Software_Architecture_And_Design.git)

---

## 📦 Project Structure

```bash
.
├── api-gateway/
├── auth-service/
├── product-service/
├── cart-service/
├── order-service/
├── payment-service/
├── admin-service/
├── report-service/
├── docker-compose.yml
└── README.md
```

---

## 📝 Commit Rules

A commit message must follow the format:

```bash
<type>(<scope>): message
```

### 🔹 `type` – Type of commit:
- `feat`: Thêm một chức năng mới  
- `fix`: Sửa một lỗi  
- `docs`: Cập nhật hoặc thêm tài liệu (ví dụ README.md)  
- `style`: Sửa style code frontend  
- `refactor`: Refactor code không ảnh hưởng đến chức năng  
- `perf`: Tối ưu hiệu suất  
- `test`: Thêm/sửa test

### 🔹 `scope` – Phạm vi ảnh hưởng (module/tính năng):
Ví dụ: `login`, `database`, `wiki`, ...

### 🔹 `message` – Mô tả ngắn gọn thay đổi:
Ví dụ: `fix bug login`, `add new feature login`, `update README.md`

---

# 🛒 E-Commerce REST API

A full-stack REST API built with **Java Spring Boot** for an e-commerce platform with JWT authentication, product management, and order processing.

## 🚀 Tech Stack

- **Backend:** Java, Spring Boot
- **Security:** Spring Security, JWT Authentication
- **Database:** MySQL
- **ORM:** Hibernate / JPA
- **Tools:** Postman, Eclipse, Maven

## ✨ Features

- ✅ User Registration & Login
- ✅ JWT Token-based Authentication
- ✅ BCrypt Password Encryption
- ✅ Product Management (Add, Update, Delete, View)
- ✅ Order Placement & Tracking
- ✅ Role-based Access (Admin/User)

## 📁 Project Structure

## 🔗 API Endpoints

### Auth
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/auth/register` | Register new user |
| POST | `/api/auth/login` | Login & get JWT token |

### Products
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/products` | Get all products |
| GET | `/api/products/{id}` | Get product by ID |
| POST | `/api/products` | Add new product |
| PUT | `/api/products/{id}` | Update product |
| DELETE | `/api/products/{id}` | Delete product |

### Orders
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/orders` | Place an order |
| GET | `/api/orders/user/{userId}` | Get user orders |
| PUT | `/api/orders/{id}/status` | Update order status |

## ⚙️ Setup Instructions

### Prerequisites
- Java 17
- MySQL
- Maven

### Steps
1. Clone the repository
```bash
   git clone https://github.com/anupriya715/ecommerce-api.git
```

2. Create MySQL database
```sql
   CREATE DATABASE ecommerce_db;
```

3. Update `application.properties`
```properties
   spring.datasource.username=root
   spring.datasource.password=yourpassword
```

4. Run the application
```bash
   mvn spring-boot:run
```

5. API runs on `http://localhost:8080`

## 📬 Testing

Import endpoints in **Postman** and test:
1. Register a user
2. Login to get JWT token
3. Use token in Authorization header for protected routes

## 👩‍💻 Author

**Anu Priya K**  
Java Full Stack Developer  
[LinkedIn](https://linkedin.com/in/anu-priya-kakulla-480252279) | [GitHub](https://github.com/anupriya715)

# 💰 Personal Budget Tracker – Backend

This is the Java Spring Boot backend for the **Personal Budget Tracker** app.  
It handles user accounts, transactions, categories, and budgeting logic.  
This repo is part of my portfolio as I transition into IT and prepare to work in the Netherlands 🇳🇱

## 🔧 Tech Stack
- Java 21
- Spring Boot 3.4.4
- PostgreSQL
- Spring Data JPA
- REST API

## 📦 Project Structure
- `controller/`: REST API endpoints
- `model/`: Entity classes (User, Transaction, Category, etc.)
- `repository/`: Spring Data JPA interfaces
- `service/`: Business logic

## ⚙️ How to Run

```bash
# Make sure PostgreSQL is running locally
./mvnw spring-boot:run

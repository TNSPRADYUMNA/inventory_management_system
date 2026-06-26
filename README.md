# inventory_management_system
# 📦 Inventory Management System with Facial Recognition

> A secure and intelligent inventory management system that integrates facial recognition technology for user authentication and inventory monitoring.

![Java](https://img.shields.io/badge/Java-17-red?logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-Framework-green?logo=springboot)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue?logo=mysql)
![Python](https://img.shields.io/badge/Python-Facial%20Recognition-yellow?logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv)

---

# 📖 Overview

The **Inventory Management System with Facial Recognition** is a smart inventory solution designed to simplify stock management while enhancing security through AI-powered facial recognition. The application enables users to manage products, suppliers, inventory transactions, and user access within a centralized platform.

The system combines a robust backend built with **Spring Boot** and **MySQL** with a facial recognition module developed using **Python**, **OpenCV**, and **DeepFace**, providing secure authentication and automated user identification.

---

# ✨ Features

- 📦 Product Management
- 🏪 Supplier Management
- 📋 Inventory Tracking
- ➕ Stock In Management
- ➖ Stock Out Management
- 📊 Inventory Reports
- 👤 User Authentication
- 🎭 Facial Recognition Login
- 🔍 Search & Filter Products
- 🗄️ Secure Database Management

---

# 🧠 System Workflow

```
User
   │
   ▼
Facial Recognition Authentication
   │
   ▼
Login Verification
   │
   ▼
Inventory Dashboard
   │
   ├── Add Products
   ├── Update Products
   ├── Delete Products
   ├── Manage Suppliers
   ├── Stock In
   ├── Stock Out
   └── Generate Reports
```

---

# 🛠️ Technology Stack

| Category | Technology |
|----------|------------|
| Backend | Spring Boot |
| Language | Java |
| Database | MySQL |
| ORM | Spring Data JPA |
| API Testing | Postman |
| Facial Recognition | Python |
| Computer Vision | OpenCV |
| Face Verification | DeepFace |
| Version Control | Git & GitHub |

---

# 📁 Project Structure

```
Inventory-Management-System/
│
├── backend/
│   ├── controller/
│   ├── service/
│   ├── repository/
│   ├── entity/
│   ├── config/
│   └── resources/
│
├── facial-recognition/
│   ├── dataset/
│   ├── models/
│   ├── recognize.py
│   └── train.py
│
├── database/
│   └── inventory.sql
│
├── screenshots/
│
├── README.md
└── pom.xml
```

---

# ⚙️ Core Modules

### 📦 Inventory Management
- Add new products
- Update product information
- Delete products
- Monitor stock levels

### 🏪 Supplier Management
- Add suppliers
- Update supplier details
- Track supplier information

### 📈 Stock Management
- Stock In
- Stock Out
- Quantity Tracking
- Inventory History

### 👤 User Management
- User Login
- Role-based Access
- Secure Authentication

### 🎭 Facial Recognition
- Face Detection
- Face Verification
- Authorized User Identification
- Secure Login Process

---

# 🚀 Getting Started

## Clone the Repository

```bash
git clone https://github.com/your-username/Inventory-Management-System.git
```

## Navigate to the Project

```bash
cd Inventory-Management-System
```

## Configure Database

- Create a MySQL database.
- Import the provided SQL file.
- Update database credentials in `application.properties`.

## Run Backend

```bash
mvn spring-boot:run
```

## Run Facial Recognition Module

```bash
python recognize.py
```

---

# 📊 Key Features

- AI-powered facial recognition authentication
- Secure inventory access
- Efficient product and supplier management
- Real-time inventory updates
- Relational database design using MySQL
- RESTful API architecture
- Scalable backend with Spring Boot

---

# 🎯 Future Enhancements

- Barcode & QR Code Integration
- Multi-Warehouse Support
- Email & SMS Notifications
- Sales and Purchase Analytics Dashboard
- Mobile Application
- Cloud Deployment
- RFID Integration
- AI-Based Inventory Demand Forecasting

---

# 💊 Medicine Record System

> A Java + JDBC + MySQL based application to manage medicine inventory, booking system, and secure medical records.

---

## 📌 Overview

The Medicine Record System is a database-driven application designed to efficiently manage medicine records, stock levels, and booking operations. It ensures secure access, real-time updates, and structured data handling using JDBC.

---

## ✨ Features

### 💊 Medicine Management
- Add, update, delete, and search medicines  
- Maintain detailed medicine records  
- Expiry date monitoring  

### 📦 Inventory Management
- Real-time stock tracking  
- Automatic quantity updates  
- Low stock awareness  

### 🎟️ Booking System
- Ticket booking  
- Ticket cancellation  
- Unique PNR generation  
- Seat allocation and management  

### 🗄️ Database Operations
- Full CRUD operations  
- MySQL relational database  
- JDBC connectivity  

---

## 🛠️ Tech Stack

- ☕ Java  
- 🔗 JDBC  
- 🐬 MySQL  

---

## 📂 Project Structure

    Medicine-Record-System/
    │
    ├── src/
    │   ├── database/
    │   ├── models/
    │   ├── services/
    │   └── ui/
    │
    ├── sql/
    │   └── schema.sql
    │
    ├── Main.java
    └── README.md

---

## ⚙️ Setup Instructions

### 1. Clone Repository

```bash
git clone https://github.com/Dipanshu-ux/Medicine-Record-System.git
cd Medicine-Record-System
```

### 2. Create Database

```sql
CREATE DATABASE medicine_db;
```

### 3. Import Schema

```bash
mysql -u root -p medicine_db < sql/schema.sql
```

### 4. Configure JDBC

```java
String url = "jdbc:mysql://localhost:3306/medicine_db";
String user = "root";
String password = "your_password";
```

### 5. Run Application

```bash
javac Main.java
java Main
```

---

## 🔒 Security

- Authentication-based access control  
- Secure handling of sensitive data  

---

## 🚀 Future Enhancements

- Web version using Spring Boot  
- Role-based access control  
- Expiry notifications system  
- Analytics dashboard  

---

## 🤝 Contributing

1. Fork the repository  
2. Create a new branch  
3. Commit your changes  
4. Open a pull request  

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Dipanshu  
https://github.com/Dipanshu-ux

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

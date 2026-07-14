# 🏦 ATM Simulator System

A desktop-based **ATM Simulator System** developed using **Java Swing**, **JDBC**, and **MySQL**. The application simulates the basic functionalities of an Automated Teller Machine (ATM), allowing users to perform banking operations through an interactive graphical user interface.

---

## 📌 Features

- User Login Authentication
- Create New Account
- Deposit Money
- Withdraw Money
- Fast Cash
- Balance Enquiry
- Mini Statement
- Change PIN
- Transaction History
- Secure Database Connectivity using JDBC
- User-friendly Java Swing Interface

---

## 🛠 Technologies Used

- Java (JDK 8 or above)
- Java Swing
- JDBC
- MySQL
- NetBeans IDE (Ant Project)

---

## 📂 Project Structure

```
ATM-Simulator-System/
│
├── src/
│   └── ASimulatorSystem/
│       ├── Login.java
│       ├── Signup.java
│       ├── Signup2.java
│       ├── Signup3.java
│       ├── Transactions.java
│       ├── Deposit.java
│       ├── Withdrawl.java
│       ├── FastCash.java
│       ├── BalanceEnquiry.java
│       ├── MiniStatement.java
│       ├── Pin.java
│       ├── Conn.java
│       └── ...
│
├── icons/
│
├── build/
├── nbproject/
├── README.md
└── ATM-Simulator-System.zip
```

---

## 💾 Database

Create a MySQL database:

```sql
CREATE DATABASE bankmanagementsystem;
```

Import the SQL tables required for the project.

Typical tables include:

- signup
- signup2
- signup3
- login
- bank

---

## ⚙ Database Configuration

Update your database credentials inside:

```
Conn.java
```

Example:

```java
Connection c = DriverManager.getConnection(
    "jdbc:mysql://localhost:3306/bankmanagementsystem",
    "root",
    "your_password"
);
```

---

## ▶ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/ATM-Simulator-System.git
```

### 2. Open in NetBeans

- Open NetBeans IDE.
- Select **File → Open Project**.
- Choose the project folder.

### 3. Configure MySQL

- Create the database.
- Import the SQL file.
- Update the username and password in `Conn.java`.

### 4. Add MySQL JDBC Driver

Download **MySQL Connector/J** and add it to the project's Libraries.

---

## 🚀 Run the Project

Run the main class:

```
Login.java
```

---

## 📸 Application Screens

- Login Page
- Sign Up
- Main Transactions
- Deposit
- Withdraw
- Fast Cash
- Balance Enquiry
- Mini Statement
- Change PIN

*(You can add screenshots here later.)*

---

## 🎯 Learning Objectives

This project demonstrates:

- Java Swing GUI Development
- JDBC Connectivity
- Event Handling
- SQL Database Operations
- Object-Oriented Programming
- Banking Transaction Logic

---

## 🔒 Future Improvements

- Password Encryption
- OTP Authentication
- Admin Dashboard
- QR Code Payments
- UPI Integration
- Account Locking
- Email Notifications
- PDF Statement Generation
- Responsive UI
- Logging System

---

## 👨‍💻 Author

jaibhee

Computer Science Engineer

Java Full Stack Developer

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!

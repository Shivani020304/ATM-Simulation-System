# 🏦 ATM Simulation System

An **ATM Simulation System** built using **Core Java**, **Swing & AWT** for the frontend, and **MySQL** for the backend database.

This project replicates basic ATM functionalities, including account creation, login, cash deposit, withdrawal, balance inquiry, mini statement, and PIN change.

---

## 📜 Table of Contents
- [About the Project](#-about-the-project)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Database Schema](#-database-schema)
- [Installation and Setup](#-installation-and-setup)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [License](#-license)

---

## 📖 About the Project

The **ATM Simulation System** is a desktop application designed to mimic the operations of a real-world ATM.

The system allows users to securely manage their banking operations—such as deposits, withdrawals, and PIN changes—through an easy-to-use graphical interface.

Both existing users and new users can interact with the system.

---

## ✨ Features

### User Authentication
- Login using Card Number and PIN.
- New users can create accounts through the Sign-Up form.

### Account Management
- Collects personal, additional, and account details during registration.

### Banking Operations
- Cash Deposit
- Cash Withdrawal
- Balance Enquiry
- Mini Statement
- PIN Change
- Exit System

### Security
- Secure login mechanism using Card Number and PIN authentication.

### User Interface
- Designed using Java Swing and AWT for an interactive GUI experience.

---

## 🛠 Technologies Used

### Frontend:
- Java Swing
- Java AWT

### Backend:
- Core Java

### Database:
- MySQL

### Tools:
- IntelliJ IDEA (or any Java IDE)
- MySQL Workbench
- Git & GitHub

---

## 🗂 Database Schema

The application uses a **MySQL** database to store user and transaction information.

### Tables:

#### `users`
- `card_number` (Primary Key)
- `pin`
- `name`
- `date_of_birth`
- `gender`
- `email`
- `phone_number`
- `address`
- `account_type`
- `services`
- `balance`

#### `transactions`
- `id` (Primary Key)
- `card_number` (Foreign Key)
- `transaction_type` (Deposit/Withdrawal)
- `amount`
- `transaction_date`

---


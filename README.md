# 📊 LetsUpgrade Database Assignment

## Event Management System (SQL Project)

---

## 📖 Project Overview

This project implements an **Event Management System (EMS)** using SQL, focusing on core database design and practical implementation.

It includes:

* Event management
* Venue handling
* Attendee management
* Event registrations
* Data querying and analysis

The project is built using **clean SQL practices** and demonstrates real-world database concepts like relationships, constraints, and query optimization.

---

## 🧱 Database Schema

### Core Tables

| Table               | Purpose                                          |
| ------------------- | ------------------------------------------------ |
| Events              | Stores event details (name, date, status, venue) |
| Venues              | Stores venue information                         |
| Attendees           | Stores user/participant details                  |
| Event_Registrations | Links attendees with events (many-to-many)       |

---

## ⭐ Features

### ✔️ Core System Features

* Event creation and management
* Venue mapping
* Attendee registration system
* Many-to-many relationship handling
* Event status tracking

---

### ✔️ Database Design Features

* Primary & Foreign Keys
* NOT NULL, UNIQUE, CHECK constraints
* Default values (event status)
* Proper relational schema design

---

### ✔️ Optimization & Improvements

* Indexing for faster queries
* Structured and normalized tables
* Clean SQL organization

---

## ⚡ SQL Queries Included

* Fetch events with venue details (JOIN)
* Count attendees per event
* Get upcoming events
* Sort events by latest date
* Filter events by status

---

## 🧠 Additional Enhancements

* Sample data insertion for testing
* Email validation constraint
* Unique event name enforcement
* Query-based insights for event analysis

---

## 🛠 Tech Stack

| Technology                   | Purpose            |
| ---------------------------- | ------------------ |
| MySQL / SQL                  | Database           |
| GitHub                       | Version control    |
| MySQL Workbench / phpMyAdmin | Database interface |

---

## 🚀 Setup Instructions

### 1️⃣ Clone the repository

```bash
git clone https://github.com/karmaboy1309/LetsUpgrade_Database_Assignment.git
```

### 2️⃣ Open MySQL and create database

```sql
CREATE DATABASE event_management;
USE event_management;
```

### 3️⃣ Run the SQL file

```sql
SOURCE Database_Assignment/event_management_system.sql;
```

---

## 📈 Learning Outcomes

* Database schema design
* Relationships (1:N, M:N)
* SQL constraints & indexing
* Writing efficient queries
* Real-world DB implementation

---

## 📊 Example Use Cases

* Event listing system
* Registration tracking
* Attendance insights
* Basic analytics on events

---

## 👨‍💻 Author

**Darshan Makwana**
📍 India
💻 MERN Stack | SQL Developer

---

## 📌 Conclusion

This project demonstrates how a structured relational database can be used to build a **real-world event management system**, covering essential DBMS concepts and practical SQL implementation.

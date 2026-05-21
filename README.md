# 📊 LetsUpgrade Database Assignment

## Event Management System (SQL Project)

---

## 📖 Project Overview

This project implements a structured **Event Management System (EMS)** using SQL and DBMS concepts.

The system is designed to manage:

* Events
* Venues
* Attendees
* Organizers
* Registrations
* Feedback & Ratings
* Event Analytics

The project demonstrates practical implementation of:

* Relational database design
* SQL constraints
* Joins & analytical queries
* Data normalization
* Query optimization

It follows clean database practices similar to real-world event management platforms. ([GitHub][1])

---

# 🧱 Database Schema

## 📌 Core Tables

| Table               | Purpose                         |
| ------------------- | ------------------------------- |
| Events              | Stores event details            |
| Venues              | Stores venue information        |
| Attendees           | Stores attendee/user data       |
| Event_Registrations | Handles event registrations     |
| Organizers          | Stores organizer details        |
| Feedback            | Stores event ratings & comments |

---

# ⭐ Features

## ✔️ Core Features

* Event creation & management
* Venue mapping
* Attendee registration system
* Organizer-event relationship
* Feedback & rating system
* Attendance tracking

---

## ✔️ Database Design Features

* Primary Keys
* Foreign Keys
* NOT NULL constraints
* UNIQUE constraints
* CHECK constraints
* Default column values

---

## ✔️ Optimization Features

* Indexing for faster queries
* Proper relational mapping
* Normalized database structure
* Organized SQL sections

---

# ⚡ SQL Functionalities Included

## 📌 Analytical Queries

* Fetch events with venue details
* Count attendees per event
* Filter upcoming events
* Sort events by latest date
* Category-based event filtering
* Venue-based event filtering
* Attendance analytics
* Registration insights

---

## 📌 Constraints & Validation

* Email validation constraint
* Unique event name enforcement
* NOT NULL validations
* Default event status

---

## 📌 Additional Functionalities

* Sample data insertion
* Feedback management
* Organizer management
* Event categorization
* Event descriptions

---

# 🛠 Tech Stack

| Technology                   | Purpose            |
| ---------------------------- | ------------------ |
| MySQL / SQL                  | Database           |
| GitHub                       | Version Control    |
| MySQL Workbench / phpMyAdmin | Database Interface |

---

# 🚀 Setup Instructions

## 1️⃣ Clone Repository

```bash
git clone https://github.com/karmaboy1309/LetsUpgrade_Database_Assignment.git
```

## 2️⃣ Open MySQL

Create a database:

```sql
CREATE DATABASE event_management;
USE event_management;
```

## 3️⃣ Run SQL File

```sql
SOURCE Database_Assignment/event_management_system.sql;
```

---

# 📂 Project Structure

```bash
LetsUpgrade_Database_Assignment/
│
├── Database_Assignment/
│   └── event_management_system.sql
│
└── README.md
```

---

# 📈 Learning Outcomes

This project helps in understanding:

* Relational database design
* SQL joins & relationships
* Constraints & indexing
* Query optimization
* Real-world DBMS implementation

---

# 📊 Example Use Cases

* Event booking systems
* Conference management
* College fest management
* Workshop registrations
* Attendance analytics systems

---

# 👨‍💻 Author

**Darshan Makwana**
📍 India
💻 MERN Stack | SQL Developer

---

# 📌 Conclusion

This project demonstrates how SQL and DBMS concepts can be used to build a practical **Event Management System** with proper schema design, relational mapping, validations, and analytical queries.

It serves as a strong beginner-to-intermediate level database project for learning and portfolio building.

[1]: https://github.com/topics/database-systems?utm_source=chatgpt.com "database-systems · GitHub Topics · GitHub"

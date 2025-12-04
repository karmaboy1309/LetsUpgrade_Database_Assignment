# 🚀 **Event Management System – SQL Project**

A complete SQL-based Event Management System featuring database schema design, sample dataset, analytical queries, stored procedures, triggers, views, and performance optimizations.

This project demonstrates **real-world database design**, **advanced SQL features**, and **clean query architecture** suitable for learning, interviews, and portfolio showcases.

---

# 📌 **Table of Contents**

* [Project Overview]
* [Database Schema]
* [Features]
* [Tech Stack]
* [Setup Instructions]
* [Database Objects]

  * [Tables]
  * [Indexes]
  * [Stored Procedures]
  * [Functions]
  * [Triggers]
  * [Views]
* [Analytical Queries]
* [Screenshots / ER Diagram (Optional)]
* [Author]

---

# 📖 **Project Overview**

This SQL project implements a functional **Event Management System (EMS)** capable of handling:

* Users
* Events
* Event Registrations
* Feedback
* Attendance
* Revenue analytics
* Event organizers

It includes advanced SQL additions like **indexes, triggers, views, and stored procedures** to make the system *performance-optimized* and *production-ready*.

---

# 🧱 **Database Schema**

The project contains the following core tables:

* **Users** – Stores user info
* **Events** – Event details
* **Registrations** – Tracks participation, attendance & ratings
* **Organizers** – Who manages each event

Foreign keys ensure proper relational integrity across the system.

---

# ⭐ **Features**

### ✔️ Core Features

* User, Event & Registration management
* Feedback rating validations
* Attendance tracking
* Category-wise event insights
* Revenue calculations

### ✔️ Advanced Features

* **Stored procedure** to generate event summary
* **Function** to compute average ratings
* **Trigger** for auto-cleaning invalid feedback
* **Views** for dashboards
* **Indexes** for performance optimization

### ✔️ Analytical Queries Included

* Event popularity
* Category-wise top performers
* Revenue generation
* User attendance analysis
* Leaderboards

---

# 🛠 **Tech Stack**

| Technology      | Purpose                      |
| --------------- | ---------------------------- |
| **SQL / MySQL** | Database engine              |
| **GitHub**      | Version control              |
| **ERD Tools**   | (optional) For visualization |

---

# 🚀 **Setup Instructions**

### 1️⃣ Clone the repository


git clone https://github.com/karmaboy1309/event-management-sql.git


### 2️⃣ Import the SQL file

Open MySQL Workbench / phpMyAdmin / CLI:


SOURCE event_management.sql;


### 3️⃣ Run analytical queries or test stored procedures:


CALL GetEventSummary(201);
SELECT * FROM EventRevenueView;


---

# 🧩 **Database Objects**

## 📌 **Tables**

* Users
* Events
* Organizers
* Registrations

### Relationships:

* `Events.organizer_id → Organizers.organizer_id`
* `Registrations.user_id → Users.user_id`
* `Registrations.event_id → Events.event_id`

---

## ⚡ **Indexes**

Improves read performance:

* `idx_registrations_user`
* `idx_registrations_event`
* `idx_users_city`
* `idx_events_category`

---

## 🧮 **Stored Procedures**

### **GetEventSummary(event_id)**

Provides:

* Event name
* Category
* Ticket price
* Total registrations
* Average rating

---

## 🔢 **Function**

### **GetEventAverageRating(event_id)**

Returns average feedback for any event.

---

## 🎯 **Trigger**

### **ValidateRatingBeforeInsert**

Automatically fixes invalid ratings by converting them to `NULL`.

---

## 📊 **Views**

### **EventRevenueView**

* tickets sold
* total revenue
* event-wise breakdown

### **UserAttendanceView**

* total attended events
* average rating by user

---

# 📈 **Analytical Queries**

Important queries included:

* Event popularity
* Total registrations & feedback summary
* Events with rating > 8
* Revenue generation
* Category-wise leaders
* Users with multiple attendances
* Users who never attended
* Attendance leaderboard

---

# ✨ **Author**

**Darshan Makwana**
📍 India
💻 Web Developer | MERN & SQL Enthusiast
🔥 Always Learning. Always Building.

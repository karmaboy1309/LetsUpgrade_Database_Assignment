# 🚀 **Event Management System – SQL Project (Fully Upgraded)**

A complete **end-to-end SQL Event Management System** built using MySQL, containing:

✔️ Real-world schema
✔️ Clean data model
✔️ Analytical dashboards
✔️ Stored procedures, functions
✔️ Triggers, indexes, views
✔️ Fraud detection
✔️ Recommendations
✔️ Dynamic pricing
✔️ Badges, waitlist, payout system
✔️ Complete GitHub commit-based enhancements

This project is perfect for **portfolio**, **interview preparation**, **DBMS viva**, and **SQL practice**.

---

# 📌 **Table of Contents**

* [Project Overview](#project-overview)
* [Database Schema](#database-schema)
* [Features](#features)
* [Tech Stack](#tech-stack)
* [Setup Instructions](#setup-instructions)
* [Database Objects](#database-objects)

  * Tables
  * Indexes
  * Stored Procedures
  * Functions
  * Triggers
  * Views
* [Advanced Add-On Systems](#advanced-add-on-systems)
* [Analytical Queries](#analytical-queries)
* [Author](#author)

---

# 📖 **Project Overview**

This SQL project implements a full-scale **Event Management System (EMS)** with:

* User management
* Event handling
* Registrations
* Attendance tracking
* Feedback ratings
* Revenue insight modules
* Organizers & payout logic
* Predictive pricing
* Recommendation engine
* Security & fraud detection

Every feature has been implemented using **clean SQL**, following real production database standards.

---

# 🧱 **Database Schema**

Core tables:

| Table                 | Purpose                                    |
| --------------------- | ------------------------------------------ |
| **Users**             | User profile & demographics                |
| **Events**            | Event details, pricing, category, capacity |
| **Organizers**        | Event management and payouts               |
| **Registrations**     | Every booking, attendance, rating          |
| **Refunds**           | Event refunds                              |
| **Waitlist**          | Auto waitlist for full events              |
| **UserBadges**        | Achievement tracking                       |
| **FraudFlags**        | Fraud detection logs                       |
| **SpamRegistrations** | Duplicate registration protection          |
| **EventHistory**      | Event versioning audit log                 |
| **OrganizerPayouts**  | Commission + revenue sharing               |
| **PriceHistory**      | Dynamic pricing changes                    |

---

# ⭐ **Features**

## ✔️ Core System Features

* User / Event / Registration management
* Attendance tracking
* Feedback management
* Category-based insights
* Revenue analytics

## ✔️ Database Optimization

* Multi-column indexes
* Proper foreign key mapping
* Check constraints
* Normalized relational structure

## ✔️ Advanced SQL Implementations

### 📌 Stored Procedure

* `GetEventSummary()`
* `UpdateEventPrices()` (Dynamic Pricing Engine)

### 📌 SQL Function

* `GetEventAverageRating()`

### 📌 Triggers

* Clean invalid ratings
* Prevent spam registrations
* Block over-capacity entries
* Auto-add users to waitlist
* Event update audit logging
* Fraud detection trigger

### 📌 Views (Dashboards)

* `EventRevenueView`
* `UserAttendanceView`
* `UserBadgeView`
* `OrganizerPayoutView`
* `RefundAnalytics`
* `UserEventRecommendations`

---

# 🧠 **Advanced Add-On Systems**

### 🔥 1. AI-Style Recommendation Engine

Recommends event categories based on user interest & attendance frequency.

### 🔥 2. Spam Registration Detector

Detects duplicate / multiple registrations for same event.

### 🔥 3. Refund & Cancellation Analytics

Tracks refunds and losses.

### 🔥 4. Event Version History

Tracks every event update (name, category, price).

### 🔥 5. Organizer Payout System

Automatically calculates commission & payout amounts.

### 🔥 6. User Badge Achievement System

Awards Bronze / Silver / Gold badges based on attendance.

### 🔥 7. Smart Event Capacity

Blocks new registrations when event limit reaches.

### 🔥 8. Auto Waitlist System

Automatically moves overflow users to waitlist.

### 🔥 9. Predictive Dynamic Pricing

Ticket price increases based on event popularity & attendance.

### 🔥 10. Fraud Detection Engine

Flags underage or suspicious registrations.

---

# 🛠 **Tech Stack**

| Technology                   | Purpose                 |
| ---------------------------- | ----------------------- |
| **MySQL**                    | Database engine         |
| **GitHub**                   | Version control         |
| **Workbench / phpMyAdmin**   | DB interface            |
| **SQL Triggers, Views, SPs** | Advanced database logic |

---

# 🚀 **Setup Instructions**

### 1️⃣ Clone the repository

```
git clone https://github.com/karmaboy1309/event-management-sql.git
```

### 2️⃣ Import the SQL file

```
SOURCE event_management.sql;
```

### 3️⃣ Test features

```
CALL GetEventSummary(201);
SELECT * FROM EventRevenueView;
SELECT * FROM UserBadgeView;
CALL UpdateEventPrices();
```

---

# 🧩 **Database Objects**

## 📌 Tables (Core + Advanced)

* Users
* Events
* Organizers
* Registrations
* SpamRegistrations
* Refunds
* EventHistory
* PriceHistory
* UserBadges
* Waitlist
* OrganizerPayouts
* FraudFlags

---

## ⚡ Indexes

* idx_registrations_user
* idx_registrations_event
* idx_users_city
* idx_events_category

---

## 🧮 Stored Procedures

* `GetEventSummary(event_id)`
* `UpdateEventPrices()`

---

## 🔢 Function

* `GetEventAverageRating(event_id)`

---

## 🎯 Triggers Implemented

| Trigger                    | Purpose                      |
| -------------------------- | ---------------------------- |
| ValidateRatingBeforeInsert | Cleans invalid ratings       |
| DetectSpamRegistration     | Logs spam activity           |
| BlockIfFullCapacity        | Prevents overbooking         |
| AddToWaitlistIfFull        | Auto waitlist assignment     |
| LogEventUpdate             | Stores event version history |
| FraudScanOnRegistration    | Fraud detection              |

---

## 📊 Views (Dashboards)

| View Name                | Purpose               |
| ------------------------ | --------------------- |
| EventRevenueView         | Revenue breakdown     |
| UserAttendanceView       | User analytics        |
| RefundAnalytics          | Refund insights       |
| UserBadgeView            | Achievement system    |
| OrganizerPayoutView      | Organizer earnings    |
| UserEventRecommendations | Smart recommendations |

---

# 📈 **Analytical Queries Included**

* Event popularity ranking
* Average feedback per event
* Events with rating > 8
* Revenue calculation
* Category top performers
* Users with multiple attendances
* Users with zero attendance
* Attendance-based leaderboard
* Predictive pricing analysis

---

# ✨ **Author**

**Darshan Makwana**
📍 India
💻 Full-Stack | MERN | SQL Developer
🔥 Building daily, learning daily, shipping daily.

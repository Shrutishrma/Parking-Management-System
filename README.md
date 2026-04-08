# 🚗 Parking Management System

This repository contains a **Parking Management System** built entirely in Python, utilizing a MySQL database for persistent data storage. It is a command-line interface (CLI) application designed to simulate the day-to-day operations of a paid parking lot, handling everything from vehicle check-ins to generating financial reports.

### What I Built
I built a software tool that a parking lot attendant could use to:
* **Check Vehicles In and Out:** Record exactly when a car, bike, or truck enters the lot and when it leaves.
* **Manage Parking Spaces:** Keep track of which slots are "full" and which are "open" so the lot never overbooks.
* **Calculate Costs:** Automatically determine the parking fee based on the specific type of vehicle (e.g., Cars cost more than Two-Wheelers).
* **Generate Reports:** Search the database to see daily transactions and total revenue collected.
* **Secure Access:** Requires a username and password to log in before making any changes.

---

## 🛠️ Technical Stack

| Component | Technology Used |
| :--- | :--- |
| **Language** | **Python 3** |
| **Database** | **MySQL** (Relational Database Management) |
| **Connector** | **`mysql-connector-python`** (Bridges Python to MySQL) |
| **Interface** | **Command Line / Terminal** |

---

## 📂 Project Structure

```text
Python-Parking-Management-CLI/
├── Parking_management_system.py  # The main Python script containing the application logic and menus
└── parking_system.sql            # The database dump containing the tables (login, parking_space, transaction, etc.)
```

---

## 🚀 Key Technical Highlights
* **CRUD Operations:** This project demonstrates mastery of the core database operations: **C**reate (adding vehicles), **R**ead (generating reports), **U**pdate (modifying parking slots), and **D**elete (removing checked-out vehicles).
* **Relational Database Design:** The SQL database uses separate tables for `parking_type` (prices), `parking_space` (availability), and `transaction` (history), linking them logically rather than throwing all data into one messy sheet.
---

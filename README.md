# 💊 Pharmacy Management System

## 📌 Problem Statement

In the modern era of increasing demand for pharmaceutical and chemical products, every medical store—whether small or medium-sized—faces challenges in managing stock, maintaining accurate records, and computing revenue efficiently.

Traditional paper-based methods are ❌ error-prone, ⏳ time-consuming, and inefficient. This project introduces an electronic solution that enables:

* 📦 Easy stock maintenance
* ⚡ Automatic record updates during billing
* 🗂️ Reliable electronic documentation

By automating these processes, the system reduces manual effort, lowers labor costs, and improves overall management efficiency.

## 🎯 Objective

The primary objective of this project is to design and implement software that ensures effective management of a pharmaceutical store’s database.

Key goals include:

1. ✅ Enhancing accuracy, safety, and efficiency in store operations
2. 📊 Maintaining detailed records of medicines and stock
3. 🔐 Managing user and admin information securely
4. ⏰ Monitoring medicine validity and ensuring timely renewal
5. 🛒 Tracking and processing customer orders effectively

## ✨ Features

* 📦 Medicine inventory management
* 🧾 Automated billing and record updates
* ⏰ Expiry date tracking and notifications
* 👨‍⚕️ Role-based access for Admin and Pharmacist
* 🛒 Customer order management

## 🛠️ Tech Stack

### 💻 Frontend

* **Streamlit**: Python-based web UI framework
* **Pandas**: For displaying and managing tabular data
* **PIL (Pillow)**: For handling and displaying images

### ⚙️ Backend

* **Python 3**: Core programming language
* **SQLite3**: Local relational database (tables for Drugs, Customers, Orders)
* **SQL (MySQL compatible)**: Schema (`drugdatabase.sql`) designed with triggers, procedures, and constraints for advanced database operations

### 🗄️ Database

* **SQLite (`drug_data.db`)**: Used directly by the application (`main.py`) for real-time CRUD operations
* **MySQL (via `drugdatabase.sql`)**: Defines scalable schema with triggers and stored procedures for production-level use

### 🔑 Additional Tools

* **Random module**: For unique order ID generation
* **Streamlit Sidebar & Widgets**: For interactive dashboards and forms

## 📖 Usage

* 👨‍💼 Admin can add, update, or delete medicines and manage users
* 👨‍⚕️ Pharmacist can handle billing and stock updates
* ⏰ System automatically checks for expired medicines
* 🛒 Customers can place and track orders

## 🔮 Future Enhancements

* 🌐 Integration with online ordering portals
* 📊 Analytics dashboard for sales and inventory
* 📷 Barcode/QR code scanning support
* 🏪 Multi-branch store management

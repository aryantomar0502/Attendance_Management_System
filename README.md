
# 📊 Online Attendance Management System (PHP)

## 📌 Overview

The **Online Attendance Management System** is a web-based platform developed using **PHP and MySQL** that helps institutions efficiently manage attendance records for students and teachers.

The system enables **secure login, role-based access control, attendance tracking, PDF report generation, and remote accessibility**, making attendance monitoring transparent, fast, and reliable.

This project was developed as an **academic full-stack web application**.

---

# ✨ Key Highlights

* 🌐 Web-based attendance system
* 🔐 Role-based login (Admin / Teacher / Student)
* 📊 Real-time attendance monitoring
* 📄 PDF report generation
* 📈 Attendance percentage tracking
* 📷 Profile image upload support
* 🔑 Encrypted password security
* 📱 Responsive Bootstrap interface
* 🌍 Accessible from anywhere

---

# 👥 User Roles & Functionalities

## 👨‍💼 Admin Module

Admin controls the entire system:

* Approve teacher accounts
* Approve student accounts
* Manage users
* Monitor attendance activity
* Maintain lecture allocations

---

## 👨‍🏫 Teacher Module

Teachers can:

* Register and get admin approval
* Manage multiple lectures
* Mark attendance after each lecture
* View assigned students
* Track individual attendance
* Generate attendance reports (PDF)
* Calculate attendance percentage
* Update profile details
* Upload profile picture
* Change password securely

---

## 👨‍🎓 Student Module

Students can:

* Register account
* Join multiple lectures
* View attendance anytime
* Track attendance percentage
* Download attendance reports (PDF)
* Update profile information
* Upload profile picture
* Change password securely

---

# 🚀 System Workflow

1️⃣ User registers account
2️⃣ Admin approves account
3️⃣ Teacher manages lectures
4️⃣ Students enroll into lectures
5️⃣ Teacher marks attendance
6️⃣ Attendance stored in database
7️⃣ Reports generated automatically

---

# 🧠 Technologies Used

## Frontend

* HTML
* CSS
* JavaScript
* Bootstrap
* jQuery
* Ajax

## Backend

* PHP

## Database

* MySQL

---

# 🏗 System Architecture

```
Online Attendance Management System
│
├── Admin Module
├── Teacher Module
├── Student Module
│
├── Authentication System
├── Attendance Engine
├── Report Generator (PDF)
└── Database Management (MySQL)
```

---

# ⚙️ Installation Guide

## Step 1 — Clone Repository

```
git clone https://github.com/YOUR_USERNAME/attendance-management-system.git
```

---

## Step 2 — Move Project Folder

Move the project into:

```
xampp/htdocs/
```

Example:

```
C:\xampp\htdocs\attendance-management-system
```

---

## Step 3 — Start Server

Start services from **XAMPP Control Panel**

* Apache ✅
* MySQL ✅

---

## Step 4 — Import Database

Open:

```
http://localhost/phpmyadmin
```

Create database:

```
attendance_system
```

Import:

```
attendance_system.sql
```

(from project folder)

---

## Step 5 — Run Project

Open browser:

```
http://localhost/attendance-management-system
```

---

# 🔐 Security Features

* Password encryption
* Role-based authentication
* Admin approval verification
* Secure database interaction
* Session management

---

# 🎯 Project Objectives

The main objectives of this system:

* Digitize attendance tracking
* Improve transparency
* Reduce manual errors
* Enable remote accessibility
* Automate attendance reporting
* Improve institutional productivity

---

# 📂 Project Structure

```
attendance-management-system/
│
├── admin/
├── teacher/
├── student/
├── database/
├── assets/
├── css/
├── js/
└── index.php
```

---

# 💻 Software Requirements

Run this project using:

* XAMPP (Recommended)
* WAMP
* MAMP
* LAMP

---

# 📊 Future Enhancements

Possible improvements:

* Face recognition attendance
* Email notification alerts
* Mobile application integration
* QR-code attendance system
* Cloud deployment support

---

# 👨‍💻 Author

**Aryan Tomar**
B.Tech Computer Science Engineering

---

# 📄 License

This project is developed for **academic and educational purposes only**.

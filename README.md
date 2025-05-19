# 💊 Hospital Management Lite — Java & MySQL 🏥

A lightweight, terminal-based Hospital Management System built in **Java** with **MySQL** backend using **JDBC**.  
This project is perfect for learners exploring Java OOPs, database integration, and real-world CRUD operations.

---

## 🚀 Features

- 🧑‍⚕️ Add & view **Patients**
- 👨‍⚕️ View **Doctors**
- 📅 **Book Appointments** with availability checks
- 🗓️ View all **Scheduled Appointments**
- 💻 Run **custom SQL queries** directly from terminal

---

## 🏗️ Project Structure

Hospital-Management-Lite_JAVA/
├── HospitalManagementSystem.java # Main controller
├── Doctor.java # Doctor logic
├── Patient.java # Patient logic
├── schema.sql # Database setup script


---

## 🛠️ Tech Stack

- 🧠 Java (JDK 8+)
- 🐬 MySQL (8.0 or 5.7+)
- 🔌 JDBC API
- 📟 Console UI

---

## 🗄️ Database Setup

Run the [`schema.sql`](schema.sql) file to create necessary tables:

```bash
mysql -u root -p < schema.sql

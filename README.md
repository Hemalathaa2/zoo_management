# 🐾 Zoo Management System

A web-based Zoo Management System designed to simplify zoo operations such as animal records, caretaker assignments, food tracking, user profiles, and more. This project is ideal for small zoo administrations to manage internal tasks efficiently.

---

## 🌟 Features

- 🐘 **Animal Information Management** – Add, update, delete records of animals.
- 👩‍🌾 **Caretaker Management** – Assign caretakers to specific animals.
- 🍽️ **Food and Feeding Schedules** – Track food items and feeding times.
- 📝 **Visitor & Booking Information** – Store details of visitors and their schedules.
- 🔐 **Admin Login System** – Secure access for management.
- 📊 **Reports & Dashboard** – Overview of zoo statistics and quick access to key data.

---

## 💻 Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Others:** XAMPP / WAMP for local deployment

---

## 📁 Project Structure

```bash
zoo_management/
├── admin/             # Admin dashboard and backend panels
├── classes/           # PHP classes for DB and logic
├── css/               # Stylesheets
├── db/                # Database SQL files
├── files/cv/          # Uploaded files (e.g. resumes)
├── fonts/             # Web fonts
├── functions/         # PHP functions
├── img/               # Project images
├── js/                # JavaScript files
├── pages/             # Website pages (about, contact, etc.)
├── public_html/       # Public access files
├── report/            # Generated reports
└── README.md          # This file
```
⚙️ How to Run Locally
1. Install XAMPP

2. Clone or download the repo into htdocs folder: git clone https://github.com/Hemalathaa2/zoo_management.git

3.Import the database:
   Open phpMyAdmin → Create DB zoo_db
   Import the .sql file from /db folder

4. Start Apache and MySQL from XAMPP

5. Visit: http://localhost/zoo_management/

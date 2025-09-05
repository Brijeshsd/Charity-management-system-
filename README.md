# Charity Management System

A **web-based application** built with **PHP and MySQL** to manage charity donations, requests, and donor details.  
This project simplifies the process of recording donations, handling donation requests, and managing communication between donors and administrators.

---

## 🚀 Features
- Donor can register and donate funds/items.
- Admin can view and manage donation requests.
- Contact form for users to reach out.
- Secure SQL-based storage of donor and donation records.
- CRUD operations for managing records.
- Simple, user-friendly interface.

---

## 🛠️ Tech Stack
- **Frontend**: HTML, CSS, Bootstrap (basic styling in PHP pages)
- **Backend**: PHP (Core PHP with mysqli)
- **Database**: MySQL
- **Server**: XAMPP / Apache

---

## 📂 Project Structure
Charity-management-system/
│
├── about.php # About page
├── contact.php # Contact page
├── details.php # View donor/donation details
├── donate.php # Donation form
├── donation_request.php # Request form for donations
├── edit.php # Edit records
├── conn.php # Database connection file
├── charitydb.sql # Database schema & sample data
├── bred.jpg, care.jpg,
│ coins.jpg # Images used in project
└── FRONT PAGE REPORT.docx # Documentation

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/Charity-management-system.git
Move project to XAMPP folder
Place inside:
C:\xampp\htdocs\charity-management-system
Setup Database
Start XAMPP → Run Apache & MySQL
Open phpMyAdmin
Create a database:
CREATE DATABASE charity_management;
Import charitydb.sql into the new database.
Configure Database Connection
Edit conn.php if needed:
$servername = "localhost";
$username   = "root";   // default user
$password   = "";       // leave blank if no password
$dbname     = "charity_management";
Run the Project
Open in browser:http://localhost/charity-management-system/about.php

📊 Database Tables
sign → Stores user login/registration details
donations → Stores donor donation records
donation_requests → Stores requests from beneficiaries
contact_messages → Stores messages from contact form
🚀 Future Enhancements
Add login/authentication for donors and admins.
Create an admin dashboard with analytics.
Implement email/SMS notifications.
Use prepared statements to secure against SQL injection.
👨‍💻 Author
Brijesh S D
GitHub: Brijeshsd
LinkedIn: Brijesh S D
📜 License
This project is developed for educational purposes only.

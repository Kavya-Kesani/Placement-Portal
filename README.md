# 🎓 Placement Portal

A comprehensive and user-friendly **Web-Based Placement Management System** designed to streamline campus placement activities for both **students** and **administrators**. This portal simplifies job notifications, application tracking, student eligibility checks, and attendance management.

---

## 📁 Project Structure
```
placement-portal/
│
├── index.php # Landing page
├── home.php # Student dashboard
├── config.php # Database connection
├── functions.php # Reusable backend functions
├── db_setup.php # Database setup script
├── add_job_notification.php # Admin: Add job openings
├── add_notification.php # Admin: Post notifications
├── check_cgpa.php # Eligibility check logic
├── applications.php # Application tracking
├── admin-attendance.php # Admin: Attendance management
├── image.png # Portal logo/banner
└── *.sql # Database scripts
```

---

## 🎯 Features

- 🔐 **Secure Student Login & Profile Management**
- 📢 **Post Job Openings and Notifications**
- ✅ **Eligibility Check Based on CGPA**
- 📝 **Track Applications Submitted by Students**
- 📊 **Record and View Attendance Details**
- 🛠️ **Admin Panel for Managing Jobs, Notifications, and Attendance**

---
## 🛠️ Tech Stack
```
Frontend: HTML, CSS, JavaScript
Backend: PHP
Database: MySQL
```
---

## ⚙️ How to Run Locally

**1. Clone the Repository**
```
git clone https://github.com/your-username/placement-portal.git
cd placement-portal
```
**2. Start XAMPP / WAMP Server**

**3. Move Files to ```htdocs``` Folder**

Copy all files to:
```
C:\xampp\htdocs\placement-portal
```
**4. Import Database**
- Open ```phpMyAdmin```
- Create a database named ```placement```
Import the following files in order:
```
db_setup.php
additional_jobs.sql
```
**5. Access in Browser**
```
http://localhost/placement-portal/index.php
```
---

## 🤝 Contribution

Feel free to **fork** this repository, enhance the UI, or add new features via pull requests.

---

## 🙋‍♀️ Author

**K. Kavya**  
🎓 Student, SRM University AP  
💡  Passionate about developing efficient, user-friendly web portals that simplify and automate campus placement processes using web applications.

---

## 📬 Contact

📧 Gmail: [kavyarambabu232@gmail.com](mailto:kavyarambabu232@gmail.com)  
🔗 LinkedIn: [linkedin.com/in/kavya-kesani-700a51292](https://www.linkedin.com/in/kavya-kesani-700a51292)

---

## 🏷️ License

This project is open-source and free to use for educational or personal projects.

---

⭐ *Feel free to fork, star, or contribute to this repository!*

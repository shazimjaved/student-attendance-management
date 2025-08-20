# 🎓 Student Attendance Management System

A **web-based Student Attendance Management System** built to streamline attendance tracking and class management. It provides **separate login panels for Admin and Teachers**, ensuring a role-based access control with powerful features for managing academic sessions, classes, students, and attendance records.

🔐 Login Credentials

## **Admin Login Details**
- **Email:** `admin@mail.com`  
- **Password:** `Password@123`

## **Teacher Login Details**
| Email                  | Password  |
|------------------------|-----------|
| teacher@mail.com       | pass123   |
| teacher2@mail.com      | pass123   |
| teacher3@mail.com      | pass123   |
| teacher4@mail.com      | pass123   |
| teacher5@mail.com      | pass123   |
| teacher6@mail.com      | pass123   |
| teacher7@mail.com      | pass123   |
| raheela@mail.com       | pass123   |

## 🚀 Features

✅ Multi-Role System: Admin, Class Teacher, and Student panels.

✅ Student Attendance Management: Mark, update, and view attendance records.

✅ Secure Login System: Role-based authentication with session handling.

✅ Forgot Password Functionality: Recover credentials securely.

✅ Database Integration: MySQL for storing all records.

✅ User-Friendly UI: Clean and simple interface.

✅ Fully Responsive Design: Works seamlessly on desktop, tablets, and mobile devices.

### ✅ **Admin Panel**
- **Dashboard** with an overview of classes, students, and attendance.
- **Manage Classes & Sections**: Add, edit, delete class details.
- **Manage Teachers**: Add new teachers, update details, or remove.
- **Manage Students**: Register students and assign them to classes.
- **Manage Session & Term**: Configure academic sessions and terms.
- **User-Friendly UI**: Clean and responsive dashboard for easy navigation.

### ✅ **Teacher Panel**
- **Manage Students**: View students assigned to their class.
- **Mark Attendance**: Daily attendance marking system.
- **View Attendance**: Monthly attendance summary for each student.
- **Generate Reports**: Export attendance data in **Excel (.xlsx)** format.
- **Simple Dashboard**: Focused on attendance-related operations.

## 🛠️ Tech Stack
- **Frontend**: HTML, CSS, JavaScript (Bootstrap for UI)
- **Backend**: PHP 
- **Database**: MySQL
- **Additional Tools**: XAMPP for local server, PhpMyAdmin for DB management

---

## 📂 Project Structure
└── Student-Attendance-System01-main
    ├── Admin/
    ├── ClassTeacher/
    ├── css/
    ├── DATABASE FILE/
    ├── font/
    ├── img/
    ├── Includes/
    ├── js/
    ├── scripts/
    ├── scss/
    ├── vendor/
    ├── .gitattributes
    ├── classTeacherLogin.php
    ├── forgotPassword.php
    └── index.php


## ⚙️ Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/shazimjaved/student-attendance-management.git
Move the project to your XAMPP htdocs folder.

Start Apache and MySQL in XAMPP.

Import the SQL file located in database/ folder into PhpMyAdmin.

Configure database connection in config.php file.

Access the project in your browser:
http://localhost/student-attendance-management

📜 License
This project is licensed under the MIT License - feel free to use and modify.

🙌 Contributing
Contributions are welcome! Fork the repo, make changes, and submit a pull request.

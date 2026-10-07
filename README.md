# Student Management System

A web-based **Student Management System** developed using **Python, Django, HTML, CSS, Bootstrap, and MySQL**. The project implements complete **CRUD (Create, Read, Update, Delete) operations** to manage student records efficiently.

## 📌 Project Overview

The Student Management System is designed to simplify the process of managing student information. It allows users to add new students, view student records, update existing information, and delete records when they are no longer required.

This project demonstrates the implementation of a full-stack web application using Django and a relational database.

## 🚀 Features

* Add new student records
* View all student records
* View individual student details
* Update student information
* Delete student records
* Store student data in MySQL database
* User-friendly interface
* Responsive design using Bootstrap
* Complete CRUD functionality

## 🛠️ Technologies Used

### Backend

* Python
* Django

### Frontend

* HTML
* CSS
* Bootstrap

### Database

* MySQL

### Development Tools

* Visual Studio Code
* Git & GitHub

## 🔄 CRUD Operations

The application performs the following operations:

| Operation  | Description                               |
| ---------- | ----------------------------------------- |
| **Create** | Add a new student to the database         |
| **Read**   | Display existing student records          |
| **Update** | Modify student information                |
| **Delete** | Remove a student record from the database |

## 📂 Project Structure

```text
Student-Management-System/
│
├── manage.py
├── requirements.txt
│
├── project/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── studentapp/
│   ├── migrations/
│   ├── templates/
│   ├── admin.py
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── forms.py
│
└── README.md
```

> The exact folder structure may vary depending on your Django project setup.

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/student-management-system.git
```

### 2. Navigate to the Project Folder

```bash
cd student-management-system
```

### 3. Create a Virtual Environment

```bash
python -m venv myenv
```

### 4. Activate the Virtual Environment

**Windows:**

```bash
myenv\Scripts\activate
```

### 5. Install Required Packages

```bash
pip install django
```

If you have a `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### 6. Configure MySQL

Create a database in MySQL:

```sql
CREATE DATABASE student_management;
```

Update the database configuration in `settings.py` according to your MySQL username, password, and database name.

### 7. Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 8. Start the Development Server

```bash
python manage.py runserver
```

### 9. Open the Application

Open your browser and visit:

```text
http://127.0.0.1:8000/
```

## 🎯 Project Objectives

* To create an easy-to-use student record management system.
* To implement CRUD operations using Django.
* To connect a Django application with a MySQL database.
* To understand the development of a full-stack web application.
* To reduce manual management of student records.

## 🔮 Future Enhancements

* User authentication and authorization
* Student search and filtering
* Pagination for student records
* Student attendance management
* Course management
* Student profile with image upload
* Export student records to Excel/PDF
* Deployment to a cloud platform

## 👨‍💻 Developer

**Chiyadara Jaya Shankar Reddy**

**Technologies:** Python | Django | HTML | CSS | Bootstrap | MySQL

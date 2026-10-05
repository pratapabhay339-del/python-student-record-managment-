# Student Record Management System

A beginner-friendly Python project for managing student records using
CRUD operations and file-based data storage.

## 📌 Project Overview

The **Student Record Management System** is a console-based Python
application developed as part of **Module 2 -- Functions, Files &
Exception Handling**.

The project demonstrates how core Python concepts can be combined to
build a practical application.

## ✨ Features

-   Add new student records
-   View all student records
-   Search for a student
-   Update student information
-   Delete student records
-   Store data using JSON
-   Handle invalid input and runtime errors
-   Use Python functions for modular code
-   Use list comprehensions and lambda functions where appropriate

## 🛠️ Concepts Covered

-   Python Functions
-   Parameters and Arguments
-   Return Values
-   Lambda Functions
-   List Comprehensions
-   File Handling
-   JSON Data Handling
-   CRUD Operations
-   Exception Handling
-   `try-except-finally`
-   Virtual Environments
-   Git and GitHub

## 📂 Project Structure

``` text
python-student-record-management/
│
├── main.py
├── students.json
├── requirements.txt
├── .gitignore
├── README.md
└── screenshots/
```

## ▶️ How to Run

### 1. Clone the repository

``` bash
git clone https://github.com/YOUR_USERNAME/python-student-record-management.git
```

### 2. Open the project directory

``` bash
cd python-student-record-management
```

### 3. Create a virtual environment

``` bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

``` bash
venv\Scripts\activate
```

**Linux/macOS:**

``` bash
source venv/bin/activate
```

### 5. Run the application

``` bash
python main.py
```

## 💾 Data Storage

Student records are stored locally in a JSON file.

Example record:

``` json
{
    "id": 101,
    "name": "Rahul",
    "age": 20,
    "course": "B.Tech CSE"
}
```

## 🔄 CRUD Operations

  Operation   Description
  ----------- --------------------------------
  Create      Add a new student
  Read        Display/search student records
  Update      Modify an existing record
  Delete      Remove a student record

## 🎯 Learning Objective

The main objective of this project is to apply Python fundamentals to a
real-world style application while understanding functions, file
handling, data persistence, and exception handling.

## 👨‍💻 Author

**Your Name**

B.Tech CSE Student

## 📜 License

This project is created for educational and learning purposes.

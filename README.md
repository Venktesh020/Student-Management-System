# Student-Management-System
Here's a complete `README.md` file tailored for your **Student Management System** Java project. You can use this directly on GitHub to document the purpose, features, and usage of your project.

---

```markdown
# 🎓 Student Management System (Java Console Application)

## 📋 Description

The "Student Management System" is a Java-based console application that allows users to manage student information and their examination results. It is designed with a simple and intuitive menu interface, enabling operations like adding students, entering subject marks, and viewing details and performance.

---

## 🚀 Features

- ➕ Add new student information (name, roll number, DOB, email, student ID, course).
- 📝 Enter examination details for a student (subject name and marks for 5 subjects).
- 🧮 Automatic calculation of:
  - Subject-wise percentage and grade.
  - Overall percentage and grade.
- 🔍 View individual student details by roll number.
- 📊 View examination results by roll number.
- 🚫 Handles invalid input (e.g., marks not between 0–100).

---

## 📦 Technologies Used

- Java (JDK 8 or higher)
- Standard Java libraries (`java.util`)

---

## 🏗️ Project Structure

```

StudentManagementSystem/
├── StudentManagementSystem.java   # Main application
└── README.md                      # Project documentation

```

---

## 🧾 Classes Overview

### ✅ `Student`
Stores student information like name, roll number, email, date of birth, course, and student ID.

### ✅ `Subject`
Handles individual subject details including:
- Marks
- Percentage (calculated)
- Grade (calculated)

### ✅ `Examination`
Manages a student's collection of `Subject`s and computes:
- Overall percentage
- Overall grade

### ✅ `StudentManagementSystem`
Main class with the `main()` method that drives the console-based menu system.

---

## 📂 Functionality

### 🧑 Add Student

```

Enter Student Details:
Name: John Doe
Roll Number: 101
Date of Birth: 01/01/2000
Email: [john@example.com](mailto:john@example.com)
Student ID: S101
Course: Computer Science
Student added successfully!

```

### 📋 Add Examination Details

```

Enter student roll number to add examination details: 101
Enter marks for 5 subjects (out of 100):
Subject 1 name: Math
Marks for Math: 95
...

```

### 📄 View Student Details

```

Enter student roll number to view details: 101

Student Details:
Name: John Doe
Roll Number: 101
Date of Birth: 01/01/2000
Email: [john@example.com](mailto:john@example.com)
Student ID: S101
Course: Computer Science

```

### 📈 View Examination Results

```

Examination results for John Doe:

\--- Examination Results ---

Subject: Math
Marks: 95
Grade: A+
Percentage: 95.0%

...

Overall Performance:
Percentage: 84.2%
Grade: A

````

---

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/StudentManagementSystem.git
   cd StudentManagementSystem
````

2. Compile the Java program:

   ```bash
   javac StudentManagementSystem.java
   ```

3. Run the application:

   ```bash
   java StudentManagementSystem
   ```




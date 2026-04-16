# 🎓 Smart Campus Management System (Java)

## 📌 Project Overview

The **Smart Campus Management System** is a Java-based console application designed to manage students, courses, and enrollments efficiently. It demonstrates core Java concepts such as **OOP (Object-Oriented Programming)**, **Exception Handling**, **Collections Framework**, and **Multithreading**.

---

## 🚀 Features

* ➕ Add new students
* 📚 Add courses with fee validation
* 📝 Enroll students in courses
* 👨‍🎓 View student details
* 📊 View enrollment records
* ⚡ Process enrollments using multithreading
* ❌ Handle invalid inputs using custom exceptions

---

## 🛠️ Technologies Used

* Java (JDK 8 or above)
* VS Code / IntelliJ IDEA
* Collections Framework (HashMap, ArrayList)
* Multithreading (Thread class)

---

## 📂 Project Structure

```
SmartCampus/
│── SmartCampus.java      (Main class)
│── Student.java          (Student class)
│── Course.java           (Course class)
│── InvalidFeeException.java
│── EnrollmentThread.java
```

---

## ▶️ How to Run the Project

### Step 1: Compile the program

```
javac SmartCampus.java
```

### Step 2: Run the program

```
java SmartCampus
```

---

## 🧪 Sample Functionality

### Add Student

* Input: ID, Name, Email
* Output: Student added successfully

### Add Course

* Input: Course ID, Name, Fee
* Validation: Fee must not be negative

### Enrollment

* Links student with course

### Multithreading

* Simulates background processing of enrollment

---

## ⚠️ Exception Handling

* Custom Exception: `InvalidFeeException`
* Handles:

  * Negative course fee
  * Invalid input

---

## 🧠 Concepts Used

* Classes and Objects
* Constructor
* Method Overriding (`toString()`)
* Exception Handling
* Collections (`HashMap`, `ArrayList`)
* Multithreading

---

## 💡 Future Enhancements

* GUI version using JavaFX / Swing
* Database integration (MySQL)
* Login authentication system
* File handling for data storage

---

## 👨‍💻 Author

* Name: *Your Name*
* Course: B.Tech (CSE/IT)
* University: AKTU

---

## ⭐ Notes

This project is ideal for:

* College practical exams
* Viva preparation
* Mini project submission

---

✨ *“Code, Learn, and Build Smart Systems!”*

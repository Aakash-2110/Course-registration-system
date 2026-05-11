# Course Registration System

A full-stack web application where students can register for available courses.  
The frontend is built using HTML, CSS, and JavaScript, while the backend uses Spring Boot with MySQL for data storage.

---

## Features

- Student course registration
- View available courses
- Store registration details in MySQL database
- REST API integration using Fetch API
- Simple and responsive frontend

---

## How It Works

1. User fills the course registration form.
2. JavaScript (Fetch API) sends the form data as JSON to the Spring Boot backend.
3. Spring Boot processes the request and stores the data in the MySQL database.
4. Registered course details can be retrieved and displayed.

---

## Tech Stack

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Java
- Spring Boot

### Database
- MySQL

### Data Transfer
- JSON

---

## Project Structure

```text
Course-registration-system/
│
├── Backend/
│   ├── src/
│   ├── pom.xml
│   └── ...
│
├── Frontend/
│   ├── index.html
│   ├── register.html
│   ├── availablecourse.html
│   ├── enrolled.html
│   └── myscript.js
│
└── README.md

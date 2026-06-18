# 🎬 Movie Booking System

A full-stack **Movie Ticket Booking System** built using **Spring Boot, Java, MySQL, REST APIs, HTML, CSS, and JavaScript**.
This project simulates a real-world online movie booking platform where users can browse movies, view theaters and shows, select seats, and book tickets.

---

## 📌 Project Overview

The **Movie Booking System** is designed to replicate the workflow of modern ticket booking platforms such as BookMyShow. It provides a backend API architecture for handling movie listings, theaters, screens, seat management, show scheduling, and ticket booking operations.

The project follows a clean layered architecture using:

* Controller Layer
* Service Layer
* Repository Layer
* DTO Layer
* Entity Layer
* Exception Handling Layer

It also includes a frontend UI built with HTML, CSS, and JavaScript that interacts with backend APIs.

---

## 🚀 Features

### User Management

* User Registration
* User Login Authentication
* User Data Management

### Movie Management

* Add Movies
* View All Movies
* Movie Details
* Language, Genre, Duration, Ratings

### Theater Management

* Create Theaters
* Manage Theater Information
* Theater Listing by City

### Screen Management

* Create Multiple Screens per Theater
* Screen Configuration

### Show Management

* Create Movie Shows
* Assign Shows to Screens
* Manage Show Timings

### Seat Management

* Seat Creation
* Seat Categories
* Seat Availability Checking

### Booking Management

* Ticket Booking System
* Seat Reservation
* Booking Status Management

### API Integration

* RESTful API Architecture
* API Testing with Postman
* Frontend Integration with Backend

---

## 🛠 Tech Stack

### Backend

* Java
* Spring Boot
* Spring Data JPA
* Hibernate
* REST API
* Maven

### Database

* MySQL

### Frontend

* HTML5
* CSS3
* JavaScript

### Tools

* Postman
* Git
* GitHub
* IntelliJ IDEA / VS Code

---

## 📂 Project Structure

```text
Movie-Booking-System
│
├── UI/
│   ├── index.html
│   ├── css/
│   ├── js/
│   └── pages/
│
├── src/main/java/com/cfs/BMS/
│   ├── controller/
│   ├── service/
│   ├── repository/
│   ├── entity/
│   ├── dto/
│   ├── config/
│   ├── exception/
│   └── enums/
│
├── src/main/resources/
│   └── BMS.sql
│
├── pom.xml
└── README.md
```

---

## ⚙️ API Endpoints

### User APIs

```http
POST /users
GET /users
GET /users/{id}
PUT /users/{id}
DELETE /users/{id}
```

### Movie APIs

```http
POST /movies
GET /movies
GET /movies/{id}
PUT /movies/{id}
DELETE /movies/{id}
```

### Theater APIs

```http
POST /theaters
GET /theaters
```

### Booking APIs

```http
POST /bookings
GET /bookings
```

### Show APIs

```http
POST /shows
GET /shows
```

### Seat APIs

```http
POST /seats
GET /seats
```

---

## 🗄 Database

The project uses **MySQL Database**.

Database script included:

```text
src/main/resources/BMS.sql
```

Contains:

* Cities Data
* Users Data
* Movies Data
* Theater Data
* Shows Data
* Seats Data
* Booking Sample Data

---

## 🔧 Installation & Setup

### Clone Repository

```bash
git clone https://github.com/SanjeevMaurya63/Movie-Booking-System.git
```

### Navigate Project Folder

```bash
cd Movie-Booking-System
```

### Configure Database

Create MySQL database and import:

```text
BMS.sql
```

### Run Spring Boot Application

```bash
mvn spring-boot:run
```

Backend runs on:

```text
http://localhost:8080
```

---

## 🧪 API Testing

API endpoints tested using:

* Postman
* Browser Requests
* Frontend Integration

---

## Future Improvements

* JWT Authentication
* Payment Gateway Integration
* Email Notifications
* Movie Search Filters
* Admin Dashboard
* Online Payment Integration
* Booking History
* Seat Locking System
* Deployment on AWS

---

## Learning Outcomes

This project helped in understanding:

* Backend Development using Spring Boot
* REST API Design
* Database Design with MySQL
* Layered Architecture
* CRUD Operations
* Frontend and Backend Integration
* API Testing using Postman
* Git & GitHub Version Control

---

## Author

**Sanjeev Maurya**

GitHub Profile:

https://github.com/SanjeevMaurya63

---

## Project Status

Project Completed ✅
Actively improving and adding new features.

---

### If you found this project helpful, feel free to star the repository ⭐

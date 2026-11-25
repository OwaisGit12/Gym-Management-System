# 🏋️ Gym Management System

A web-based Gym Management System developed to simplify gym administration and manage essential gym operations, including members, coaches, receptionists and billing.

## 📌 Project Overview

Managing a gym involves handling multiple activities, such as maintaining member records, managing coaches, tracking billing information and organizing administrative tasks.

The Gym Management System aims to simplify these operations through a centralized web-based application backed by a MySQL database.

This project was developed as a DBMS mini project to demonstrate the practical implementation of database connectivity and web development concepts.

## 🎯 Problem Statement

Traditional gym management methods often rely on manual records and paperwork, making it difficult to maintain accurate information and efficiently manage daily operations.

This project addresses these challenges by providing a centralized system that helps organize gym-related information, manage records and simplify administrative activities.

## ✨ Key Modules

| Module | Description |
|---|---|
| Admin Login | Provides an administrative login interface. |
| Member Management | Maintains gym member information. |
| Coach Management | Handles coach-related information. |
| Receptionist Management | Maintains receptionist information. |
| Billing Management | Provides a billing interface for gym operations. |

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Webpage structure |
| CSS3 | Styling and presentation |
| PHP | Server-side development |
| MySQL | Database management |
| Bootstrap 4 | Responsive user interface |
| JavaScript | Frontend functionality |
| XAMPP | Local development environment |
| phpMyAdmin | Database administration |

## 📂 Project Structure

```text
Gym-Management-System/
│
├── README.md
│
├── index.html
├── about.html
├── blog.html
├── blog_details.html
├── contact.html
├── courses.html
├── elements.html
├── gallery.html
├── pricing.html
│
├── admin-login.php
├── config.php
├── members.php
├── coach.php
├── receptionist.php
├── billing.php
```

## ⚙️ Installation and Setup

### Prerequisites

Install the following software:

- XAMPP
- PHP 7.4 or higher
- MySQL
- Web browser
- Git (optional)

### Step 1: Clone the Repository

Open your terminal and execute:

```bash
git clone https://github.com/OwaisGit12/Gym-Management-System.git
```

### Step 2: Move the Project

Copy or move the project folder into the XAMPP `htdocs` directory.

For Windows:

```text
C:\xampp\htdocs\Gym-Management-System
```

### Step 3: Start XAMPP

Open the XAMPP Control Panel and start:

- Apache
- MySQL

### Step 4: Create the Database

1. Open phpMyAdmin.
2. Create a database named `GMS`.
3. Import the project's SQL database file if available.
4. Ensure the required database tables are created.

**Note:** A database export (`.sql`) is not currently included in the repository. The database schema must be exported and added to the project for a complete setup.

### Step 5: Configure Database Connection

Open `config.php` and configure your database credentials:

```php
<?php

define('DB_SERVER', 'localhost');
define('DB_USERNAME', 'root');
define('DB_PASSWORD', '');
define('DB_NAME', 'GMS');

$connection = mysqli_connect(
    DB_SERVER,
    DB_USERNAME,
    DB_PASSWORD,
    DB_NAME
);

if (!$connection) {
    die("Database connection failed: " . mysqli_connect_error());
}

?>
```

Update the credentials according to your MySQL configuration.

### Step 6: Run the Application

Open your browser and navigate to:

```text
http://localhost/Gym-Management-System/
```

The application should now be accessible through your local XAMPP server.

## 📸 Screenshots and Outputs

Screenshots demonstrating the application's functionality will be added here.

### 1. Home Page
<img width="1350" height="655" alt="thmbnail" src="https://github.com/user-attachments/assets/12dc7abb-6f42-4e21-8293-4236c76e6c26" />



### 2. Admin Login

<img width="1920" height="1080" alt="Index Page" src="https://github.com/user-attachments/assets/f471436e-b44f-4c30-9d98-5dd4f80f3e80" />


### 3. Member Management

<img width="1920" height="1080" alt="Manage Member" src="https://github.com/user-attachments/assets/7605c1fa-fd12-44e1-a2e2-117d282d0788" />


### 4. Coach Management

<<img width="1920" height="1080" alt="Manage Trainer" src="https://github.com/user-attachments/assets/0e0c9eb6-ea2b-4deb-bb01-9b709578303b" />


### 5. Receptionist Management

<img width="1920" height="1080" alt="Manage Gym" src="https://github.com/user-attachments/assets/e8d45e61-a8ae-4693-a274-d304309dcb7e" />


### 6. Billing Management

<img width="1920" height="1080" alt="Manage Payment" src="https://github.com/user-attachments/assets/70a11893-f85b-44ea-b510-100e4fee4591" />


## 📚 Concepts Implemented

This project demonstrates the practical application of:

- Database Management Systems (DBMS)
- Relational Database Concepts
- MySQL Database Connectivity
- PHP and MySQL Integration
- CRUD Operations
- Web Application Development
- Frontend and Backend Integration

## 🚀 Future Enhancements

Potential improvements include:

- Improved admin authentication and authorization.
- Member search, update and deletion functionality.
- Membership subscription management.
- Payment history and transaction tracking.
- Database backup and reporting.
- Enhanced input validation and security.
- Improved responsive user interface.

## 👨‍💻 Author

**Syed Owais Ahmed Quadri**

Computer Science and Engineering Graduate

GitHub: [@OwaisGit12](https://github.com/OwaisGit12)
LinkedIn: [Connect with me](https://www.linkedin.com/in/syedowaisahmed)

---

⭐ If you find this project interesting, consider giving the repository a star!

**Developed as a DBMS Mini Project.**

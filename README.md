# 🏥 Hospital Management System

<p align="center">
  <strong>A PHP & MySQL-Based Web Application for Hospital Operations</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

## 📌 Overview

The **Hospital Management System** is a web-based application developed using PHP and MySQL to simplify essential hospital activities.

It provides an interface for managing patient registration, doctor information, appointment bookings, and administrative operations through a centralized web application.

### 🎯 Objectives

- Streamline patient registration and appointment booking.
- Organize doctor information and specializations.
- Provide separate login interfaces for doctors and administrators.
- Store and manage hospital records using MySQL.
- Simplify access to essential hospital workflows.

## ✨ Features

- 🧑‍⚕️ **Doctor Management** — Maintain doctor details, specializations, and consultation fees.
- 🧑 **Patient Registration** — Record patient information through web forms.
- 📅 **Appointment Booking** — Book appointments and store appointment records.
- 🔐 **Login Interfaces** — Provide doctor and administrative login workflows.
- 📊 **Dashboard Interfaces** — Access relevant hospital information through dedicated panels.
- 💊 **Prescription Management** — Support prescription-related workflows included in the application.
- 🗄️ **Database Integration** — Store and retrieve information using MySQL.
- 📱 **Web-Based UI** — Use Bootstrap, HTML, CSS, and JavaScript to build the interface.

## 🛠️ Technology Stack

| Technology | Purpose |
|:---|:---|
| **PHP** | Server-side programming and application logic |
| **MySQL** | Database storage and management |
| **HTML5** | Web page structure |
| **CSS3** | Styling and layout |
| **JavaScript** | Client-side interactions |
| **Bootstrap** | Responsive UI components |
| **XAMPP** | Local PHP and MySQL development environment |
| **phpMyAdmin** | Database administration |
| **Git & GitHub** | Version control and project hosting |

## 🏗️ Application Architecture

```text
              User
               |
               v
       Web Interface
  HTML + CSS + Bootstrap
        + JavaScript
               |
               v
        PHP Application
      Request Processing
               |
               v
         MySQL Database
               |
               v
       Data Returned to UI
```

## 📂 Project Structure

```text
Hospital-Management-System-master/
│
├── index.php
├── func1.php
├── func3.php
├── newfunc.php
├── doctor-panel.php
├── admin-panel.php
├── admin-panel1.php
├── myhmsdb.sql
├── TCPDF/
└── README.md
```

> **Note:** This is a simplified overview. Additional files, templates, stylesheets, and resources may be present in the repository.

## 🚀 Getting Started

Follow these instructions to run the application locally.

### Prerequisites

Install the following:

- [XAMPP](https://www.apachefriends.org/)
- A modern web browser
- A code editor such as [Visual Studio Code](https://code.visualstudio.com/)

### ⚙️ Installation

**Step 1: Place the project in XAMPP**

Copy the project folder into:

```text
C:\xampp\htdocs\Hospital-Management-System-master
```

**Step 2: Start the services**

- Open the XAMPP Control Panel.
- Start **Apache**.
- Start **MySQL**.

**Step 3: Set up the database**

1. Open [phpMyAdmin](http://localhost/phpmyadmin).
2. Create a database named `myhmsdb`.
3. Select the database and open the **Import** tab.
4. Choose the `myhmsdb.sql` file.
5. Import the SQL file to create the required tables.

**Step 4: Configure the database connection**

Locate the PHP file that contains the database connection settings and configure it to match your local MySQL setup.

Example configuration for a typical local XAMPP installation:

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "myhmsdb";
```

> Adjust these values if your MySQL username, password, or database name is different.

**Step 5: Launch the application**

Open your browser and visit:

[http://localhost/Hospital-Management-System-master/](http://localhost/Hospital-Management-System-master/)

The application should load if Apache, MySQL, and the database connection are configured correctly.

## 🗄️ Database

The project uses MySQL to store hospital-related information.

| Table | Purpose |
|:---|:---|
| `doctb` | Doctor information and login details |
| `admintb` | Administrative login details |
| `appointmenttb` | Appointment records |

Refer to `myhmsdb.sql` for the complete database schema and any additional tables.

## 📚 Learning Outcomes

Working on this project provides practical experience with:

- Full-stack web application development.
- PHP programming and server-side form processing.
- MySQL database integration and record management.
- Login workflows and dashboard-based interfaces.
- Frontend development using HTML, CSS, JavaScript, and Bootstrap.
- Local deployment using XAMPP.
- Project documentation and version control using GitHub.

## 🔮 Future Enhancements

Potential improvements include:

- 📧 Email and SMS appointment notifications.
- 🗓️ Calendar-based appointment scheduling.
- 🔒 Improved authentication and role-based access control.
- 📈 Dashboard analytics and reporting.
- 🔍 Advanced patient and doctor search.
- 🛡️ Stronger input validation and database security.
- 🧪 Automated testing and deployment.

## 🔐 Security Notice

This project is intended for educational and development purposes. Before deploying it publicly or using real patient information:

- Review authentication and password storage.
- Use prepared statements for database queries.
- Validate input on the server.
- Enforce appropriate access controls.
- Protect database credentials and sensitive information.
- Never upload real patient records to a public repository.

## 👨‍💻 Project Information

**Project:** Hospital Management System  
**Backend:** PHP  
**Database:** MySQL  
**Frontend:** HTML, CSS, JavaScript, Bootstrap  
**Development Environment:** XAMPP

---

<p align="center">
  <strong>Built to explore web development and hospital workflow management.</strong>
</p>

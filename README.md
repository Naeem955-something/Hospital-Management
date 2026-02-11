

# MediScript - Digital Medical Prescription Management System

**MediScript** is a comprehensive digital platform designed to streamline the medical prescription process by replacing outdated, paper-based workflows with a modern, web-based solution. Built as a full-stack system, it allows doctors to create prescriptions, patients to access them, and administrators to manage the overall system — securely and efficiently.

---

## 📌 Table of Contents

* [🎯 Features](#-features)
* [🚀 Technologies Used](#-technologies-used)
* [🛠 Installation](#-installation)
* [🖥 System Architecture](#-system-architecture)
* [🧪 Testing & Security](#-testing--security)
* [📚 Future Enhancements](#-future-enhancements)
* [👨‍💻 Authors](#-authors)
* [📄 License](#-license)

---

## 🎯 Features

### 👨‍⚕️ For Doctors

* Create, edit, and manage digital prescriptions.
* View patient history and drug records.
* Integrated drug inventory.
* Apply and get verified for system access.
* Access "My Patients" list and manage consultations.

### 🧑‍⚕️ For Patients

* Secure portal to view and download prescriptions.
* Request medication refills.
* View doctor list with reviews and ratings.
* Submit doctor reviews and feedback.

### 🧑‍💼 For Administrators

* Approve or reject doctor applications.
* Manage medicine inventory with batch numbers and expiry dates.
* Approve refill requests.
* Receive and manage issue reports from users.

### 🌐 Core Functionalities

* Role-based access: Admin, Doctor, Patient.
* PDF generation of prescriptions using Puppeteer.
* Responsive and mobile-friendly UI with Tailwind CSS.
* Secure file uploads (licenses, profile images, etc.).
* Real-time email notifications via Nodemailer.
* Medicine expiry tracking and automated alerts.

---

## 🚀 Technologies Used

### Frontend

* HTML5, CSS3, JavaScript
* Tailwind CSS, DaisyUI
* Font Awesome Icons

### Backend

* Node.js, Express.js
* MySQL Database
* Multer (File uploads)
* Puppeteer (PDF generation)
* Nodemailer (Email service)

### Tools

* Git & GitHub for version control
* VS Code as IDE
* MySQL Workbench for database management
* Postman for API testing

---

## 🛠 Installation

1️⃣ **Clone the repository and install dependencies**

```bash
cd mediscript
npm install
```

2️⃣ **Set up the MySQL database**

* Import the provided SQL schema into MySQL.
* Configure DB credentials in `.env` file.

3️⃣ **Run the server**

```bash
npm start
```

---

## 🖥 System Architecture

* **Frontend:** HTML + Tailwind CSS for clean UI
* **Backend:** Node.js with Express.js handling APIs
* **Database:** MySQL with relational schema
* **Architecture:** Three-tier (UI, Business Logic, Database)

---

## 🧪 Testing & Security

* Manual testing across all user roles and use cases
* File upload validations and sanitization
* Role-based access control (RBAC)
* SQL Injection protection with parameterized queries
* Input validation and session management

---

## 📚 Future Enhancements

* Implement real-time notifications for prescriptions and refills
* Support for multi-language prescriptions
* AI-based drug substitution suggestions
* Mobile app version for easier accessibility

---

## 👨‍💻 Authors

* **Uzzal Das** – 011 231 0198
* **Sadman Biazid Arnob** – 011 231 0405
* **Mohammad Naeem Mollah** – 011 231 0202


---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


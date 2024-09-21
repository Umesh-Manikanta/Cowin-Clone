# 🩺 CoWIN Clone Website



## 📚 Project Overview
This project is a **clone of the CoWIN website**, designed to simulate the functionality of India's official COVID-19 vaccination portal. It allows users to **register**, **book vaccination slots**, **search for centers**, and check their **vaccination status**. 

The backend is powered by **PHP** with **MySQL** as the database, handling user data, vaccination centers, and appointment scheduling.

---

## 🎯 Objectives
✨ **Key Features**:
1. **User Registration & Login**: Users can create accounts and log in securely.
2. **Vaccination Slot Booking**: Book available vaccination slots at nearby centers.
3. **Search for Centers**: Filter vaccination centers by **location** and **vaccine type**.
4. **Vaccination Status Check**: Check vaccination status via registered ID.
5. **Admin Dashboard**: Manage centers, view statistics, and update slot availability.

---

## 🛠️ Technologies Used

### 💻 Frontend
- **HTML5**: Page structure.
- **CSS3**: Styling and responsive design.
- **JavaScript**: Dynamic interactions and validations.
- **Bootstrap**: For responsive UI.

### 🖥️ Backend
- **PHP**: Server-side scripting.
- **MySQL**: Database to store user data, vaccination slots, and appointments.
- **PHPMailer**: For sending email notifications and OTPs.

### 🔒 Security
- **Password Hashing**: Using `password_hash()` and `password_verify()` in PHP for user authentication.
- **Session Management**: Secure user sessions with PHP sessions.

---

## 🔧 Features

### 👨‍💻 **User Features**
- **User Registration/Login**: Secure registration with hashed passwords.
- **Dashboard**: View vaccination status, booked appointments, and vaccination history.
- **Slot Booking**: Users can search for available slots and book appointments.
- **Email Notifications**: Receive appointment confirmations via email.

### 🏥 **Admin Features**
- **Manage Centers**: Add, update, or remove vaccination centers.
- **Slot Management**: Real-time updates on slot availability.
- **Statistics Dashboard**: View daily appointments and overall vaccination progress.

### 🔎 **Search & Filter**
- **Search Centers**: Find vaccination centers by state, district, or pincode.
- **Slot Availability**: Filter centers by slot availability and vaccine type.

### 📊 **Vaccination Reports**
- **Daily Reports**: Track daily vaccinations across different centers.
- **Center Reports**: View detailed statistics for individual centers.

---

## 📂 Folder Structure

```plaintext
📦 Cowin-Clone-Website
├── 📁 public
│   ├── 📁 css
│   ├── 📁 js
│   └── 📁 assets
├── 📁 views
│   ├── index.php
│   ├── login.php
│   └── dashboard.php
├── 📁 controllers
│   ├── userController.php
│   └── adminController.php
├── 📁 models
│   ├── User.php
│   └── Slot.php
├── 📁 config
│   └── db.php
├── 📁 utils
│   └── PHPMailer.php
└── README.md

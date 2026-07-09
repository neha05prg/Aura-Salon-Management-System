# 💇 Aura Salon Management System

A full-stack **Salon Management System** developed using **PHP, MySQL, HTML, CSS, and JavaScript**. This web application simplifies salon operations by providing online appointment booking, product management, shopping cart functionality, payment processing, invoice generation, and an administrator dashboard.

---

## 📌 Project Overview

Aura Salon Management System is designed to automate the day-to-day operations of a beauty salon. Customers can browse salon services, purchase beauty products, book appointments, and manage orders online. Administrators can efficiently manage users, products, appointments, and customer orders through a dedicated admin dashboard.

---

## ✨ Features

### 👤 Customer Module

- User Registration
- User Login & Logout
- Browse Salon Services
- Book Appointments
- View Available Products
- Shopping Cart
- Checkout Process
- Payment Processing
- Order Confirmation
- Invoice Generation
- Responsive User Interface

---

### 👨‍💼 Administrator Module

- Secure Admin Login
- Admin Dashboard
- View Customer Appointments
- Approve Appointments
- Reject Appointments
- Manage Products
- Manage Users
- Manage Orders
- Admin Logout

---

## 🛠️ Technologies Used

### Frontend

- HTML5
- CSS3
- JavaScript

### Backend

- PHP

### Database

- MySQL

### Development Environment

- XAMPP / WAMP
- Apache Server
- phpMyAdmin

---

# 📂 Project Structure

```
Aura-Salon-Management-System/
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── images/
│
├── includes/
│   ├── dbconnection.php
│   ├── header.php
│   ├── footer.php
│   ├── navbar.php
│   └── sidebar.php
│
├── index.php
├── aboutus.php
├── service.php
├── product.php
├── login.php
├── signup.php
├── signin.php
├── logout.php
├── book_service.php
├── book_service_redirect.php
├── cart.php
├── checkout.php
├── payment.php
├── payment_process.php
├── order.php
├── order_confirmation.php
├── invoice.php
├── invoice1.php
├── admin_login.php
├── admin_dashboard.php
├── admin_panel.php
├── admin_appointments.php
├── manage_appointments.php
├── approve_appointment.php
├── reject_appointment.php
├── manage_products.php
├── manage_users.php
├── adlogout.php
├── aura.sql
└── README.md
```

---

# 📄 File Description

| File | Description |
|------|-------------|
| index.php | Homepage |
| aboutus.php | About the salon |
| service.php | Displays salon services |
| product.php | Displays beauty products |
| login.php | User login |
| signup.php | User registration |
| signin.php | User authentication |
| logout.php | User logout |
| book_service.php | Appointment booking page |
| book_service_redirect.php | Booking processing |
| cart.php | Shopping cart |
| checkout.php | Checkout page |
| payment.php | Payment page |
| payment_process.php | Payment processing |
| order.php | Customer orders |
| order_confirmation.php | Order confirmation |
| invoice.php | Invoice generation |
| invoice1.php | Alternate invoice |
| admin_login.php | Administrator login |
| admin_dashboard.php | Admin dashboard |
| admin_panel.php | Admin control panel |
| admin_appointments.php | Appointment management |
| manage_appointments.php | Manage appointments |
| approve_appointment.php | Approve bookings |
| reject_appointment.php | Reject bookings |
| manage_products.php | Product management |
| manage_users.php | User management |
| adlogout.php | Admin logout |
| aura.sql | Database file |

---

# 💾 Database

Database Name

```
aura
```

Import the database using:

```
aura.sql
```

---

# ⚙️ Installation Guide

## Step 1

Clone the repository

```bash
git clone https://github.com/yourusername/Aura-Salon-Management-System.git
```

---

## Step 2

Move the project folder into

```
xampp/htdocs/
```

---

## Step 3

Start

- Apache
- MySQL

using XAMPP Control Panel.

---

## Step 4

Open phpMyAdmin

```
http://localhost/phpmyadmin
```

Create a new database

```
aura
```

Import

```
aura.sql
```

---

## Step 5

Configure database connection

Open

```
includes/dbconnection.php
```

Update

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "aura";
```

---

## Step 6

Run the project

```
http://localhost/Aura-Salon-Management-System/
```

---

# 📷 Screenshots

You can add screenshots of:

- Home Page
- Login Page
- Registration Page
- Services Page
- Products Page
- Appointment Booking
- Shopping Cart
- Checkout
- Invoice
- Admin Dashboard
- Appointment Management
- Product Management

Create a folder

```
screenshots/
```

Example

```
screenshots/
    home.png
    login.png
    services.png
    products.png
    booking.png
    dashboard.png
```

Then add

```markdown
## Screenshots

### Home Page

![Home](screenshots/home.png)

### Login

![Login](screenshots/login.png)

### Admin Dashboard

![Dashboard](screenshots/dashboard.png)
```

---

# 🔐 Default Credentials

## Admin

```
Username : 
Password : 
```

Replace with your actual admin credentials if different.

---

# 🚀 Future Enhancements

- Email Notifications
- SMS Notifications
- Online Payment Gateway Integration
- Customer Reviews
- Loyalty Rewards
- Service Ratings
- Appointment Reminder
- QR Code Invoice
- Mobile Application
- Dark Mode
- Analytics Dashboard
- Multi-Branch Salon Support

---

# 📚 Learning Outcomes

This project demonstrates knowledge of:

- PHP Programming
- MySQL Database Design
- CRUD Operations
- Session Management
- Authentication
- Form Validation
- Responsive Web Design
- Database Connectivity
- E-commerce Workflow
- Appointment Scheduling

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

# 📄 License

This project is developed for educational and academic purposes.

You are free to use and modify it for learning.

---

# 👩‍💻 Author

**Neha**

GitHub: https://github.com/yourusername

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

---

## 📧 Contact

For suggestions or improvements, feel free to create an issue or submit a pull request.

---

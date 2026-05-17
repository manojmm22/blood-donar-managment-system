

<div align="center">
  <img src="images/banner1.jpg" alt="BBDMSS Banner" width="80%"/>
  <h1>Blood Bank & Donor Management System (BBDMSS)</h1>
  <p>A web-based platform for managing blood bank operations, donor registrations, blood requests, and more.</p>
</div>

---

## 🚀 Overview
BBDMSS is a comprehensive web application designed to streamline blood bank operations, donor management, and blood request workflows. It provides both user and admin interfaces for efficient management and transparency.

<div align="center">
  <img src="images/blood-donor.jpg" alt="Blood Donor Screenshot" width="60%"/>
</div>

---

## ✨ Features

- Donor registration, authentication, and profile management
- Blood group and inventory management
- Blood request submission, tracking, and approval
- Admin dashboard for managing donors, requests, and blood groups
- Contact and support system
- Secure password management and authentication

<div align="center">
  <img src="images/b2.png" alt="Dashboard Screenshot" width="60%"/>
</div>

---

## 🛠️ Technologies Used

- **PHP** (Core backend logic)
- **MySQL** (Database, not included in this repo)
- **HTML5, CSS3, JavaScript** (Frontend)
- **Bootstrap** (Responsive UI)

---

## ⚡ Getting Started

### Prerequisites
- PHP 7.x or higher
- MySQL
- Web server (XAMPP, WAMP, Apache, etc.)

### Installation
1. **Clone the repository:**
	```bash
	git clone https://github.com/manojmm22/blood-donar-managment-system.git
	```
2. **Import the database:**
	- Import the provided SQL file (if available) into your MySQL server.
	- Create necessary tables as per your requirements.
3. **Configure the database connection:**
	- Update `includes/config.php` with your MySQL credentials.
4. **Run the application:**
	- Place the project folder in your web server's root directory (e.g., `htdocs` for XAMPP).
	- Access via `http://localhost/bbdms` (or your configured path).

---

## 👤 Usage

- **User:** Register, log in, and request blood or become a donor.
- **Admin:** Log in to the admin dashboard to manage donors, requests, and blood groups.

---

## 📁 Folder Structure

```
bbdms/
├── admin/           # Admin dashboard and management tools
├── includes/        # Shared PHP includes (header, footer, config)
├── css/             # Stylesheets
├── js/              # JavaScript files
├── images/          # Image assets
├── webfonts/        # Font files
├── *.php            # Main PHP files for user-facing features
```

---

## 🤝 Contribution
Contributions are welcome! Please fork the repository and submit a pull request for review.

---

## 📄 License
This project is for educational purposes. Add your license if needed.

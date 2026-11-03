# Community Helper

##  Project Overview

**Community Helper** is a web-based community support platform designed to connect people with useful local services, assistance, and community resources through a simple and user-friendly interface.

The main goal of this project is to make it easier for users to find and access community-related services and information from a single platform.

##  Objectives

- Provide a centralized platform for community assistance.
- Help users find relevant local services and resources.
- Make community support information easily accessible.
- Provide a simple and responsive user interface.
- Store and manage application data using a database.

##  Features

- User-friendly community support interface
- User registration and login
- Service/resource information
- Community assistance features
- PHP-based dynamic web pages
- MySQL database integration
- Form submission and data management
- Responsive web design
- Easy-to-use navigation

## Technologies Used

- **HTML5** – Website structure
- **CSS3** – Styling and responsive design
- **JavaScript** – Client-side functionality
- **PHP** – Server-side development
- **MySQL** – Database management
- **phpMyAdmin** – Database administration
- **Apache** – Web server

## ⚙️ Requirements

To run this project locally, you need:

- XAMPP / WAMP / MAMP
- Apache Server
- PHP
- MySQL
- phpMyAdmin
- Web Browser

##  How to Run Locally

### 1. Clone the Repository

git clone https://github.com/romioraz1107-spec/community_helepr2.git


### 2. Move the Project

If you are using XAMPP, place the project inside:

C:\xampp\htdocs\


For example:
C:\xampp\htdocs\community_helepr2\

### 3. Start XAMPP

Start:
Apache
MySQL

### 4. Create the Database

Open:
http://localhost/phpmyadmin

Create the required database and import the project's .sql file if one is provided.

### 5. Configure Database Connection

Update the database configuration file with your local MySQL details:

$host = "localhost";
$username = "root";
$password = "";
$database = "your_database_name";

### 6. Open the Website

Open:
http://localhost/community_helepr2/
## 🌐 Hosting

This project requires **PHP + MySQL hosting** because it contains PHP files and database functionality.

### Recommended Free Hosting

**InfinityFree** can be used for student/demo projects because it currently supports PHP, MySQL, SSL, and file uploading.

After creating a hosting account:

1. Create your website/subdomain.
2. Open the hosting File Manager.
3. Upload the project files.
4. Upload the files into the hosting website's required web directory.
5. Create a MySQL database.
6. Import your `.sql` database using phpMyAdmin.
7. Update your PHP database connection settings.
8. Open the hosting URL in your browser.

For a PHP + MySQL project, do **not** use GitHub Pages as the actual PHP server. GitHub Pages is intended for static site content, whereas your PHP files need a PHP-enabled web server.

## 🔗 Repository

GitHub Repository:

[https://github.com/romioraz1107-spec/community_helepr2](https://github.com/romioraz1107-spec/community_helepr2)

##  Security Notes

- Do not upload database passwords or API keys.
- Do not upload `.env` files containing private credentials.
- Use secure passwords for production databases.
- Validate and sanitize user input.
- Use prepared SQL statements to reduce SQL injection risks.

## 👨‍💻 Developer

**Rizwan Ansari**

## 📄 License

This project is developed for educational and academic purposes.

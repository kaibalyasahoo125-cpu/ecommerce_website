🛒 Kman Shop – E-Commerce Website
📌 Project Overview

This is an E-Commerce Website built using JSP (Java Server Pages) and JDBC (Java Database Connectivity) for backend operations.
The frontend is developed with HTML, CSS, and JavaScript, providing a responsive and user-friendly shopping experience.

The system allows users to browse products, manage their cart, register/login, and place orders.

⚙️ Tech Stack

Frontend:

HTML5

CSS3

JavaScript

Backend:

JSP (Java Server Pages)

JDBC (Java Database Connectivity)

Java

Database:

MySQL (or any JDBC supported RDBMS)

✨ Features

🔑 User Authentication – Register and Login functionality

🛍 Product Catalog – View all products dynamically from the database

🛒 Shopping Cart – Add, update, and remove items from the cart

💳 Checkout System – Calculate total price and proceed with order

👨‍💻 Admin Features – (if included) Add/Edit/Delete products

📱 Responsive Design – Works on desktop and mobile

🚀 Installation & Setup
1️⃣ Prerequisites

Install JDK 8+

Install Apache Tomcat Server

Install MySQL Database

An IDE like Eclipse/IntelliJ/NetBeans

2️⃣ Database Setup

Create a MySQL database (e.g., ecommerce_db).

Run the provided SQL script (ecommerce.sql) to create tables.

Update db.jsp (or database config file) with your database credentials:

<%
  String url = "jdbc:mysql://localhost:3306/ecommerce_db";
  String user = "root";
  String password = "yourpassword";
  Class.forName("com.mysql.cj.jdbc.Driver");
  Connection conn = DriverManager.getConnection(url, user, password);
%>

3️⃣ Project Setup

Place the project folder in your Tomcat webapps directory.

Start Tomcat Server.

Access the project in browser:

http://localhost:8080/KmanShop

📂 Project Structure
KmanShop/
│── index.html           # Homepage
│── login.jsp            # User login
│── register.jsp         # User registration
│── products.jsp         # Product catalog
│── cart.jsp             # Shopping cart
│── checkout.jsp         # Checkout page
│── contact.html         # Contact us page
│── db.jsp               # Database connection
│── css/                 # Stylesheets
│── js/                  # JavaScript files
│── images/              # Project images
│── WEB-INF/             # Deployment descriptor (web.xml)

🎯 Future Enhancements

Online Payment Gateway Integration

Order History & Invoice Download

User Profile Management

Product Reviews & Ratings

👨‍💻 Author

Kman Shop – Developed by Kaibalya
📧 Email: kaibalyasahoo125@gmail.com

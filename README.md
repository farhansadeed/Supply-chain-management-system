# Supply-chain-management-system
This is a web-based application for managing inventory, orders, and logistics in a supply chain. It was built using PHP and MySQL, and can be used by businesses of any size to streamline their operations and improve efficiency.

# Features
- Inventory management: Add, edit, and delete products, and track their stock levels, unit prices, and suppliers.
- Order management: Create and manage orders, with features like product search, quantity selection, and total cost calculation.
- Logistics management: Enter shipping information, delivery address, and special instructions for each order, and track their status until they are delivered.
- User authentication: Secure login and registration for users, with password encryption and email verification.
- Responsive design: Mobile-friendly layout that adapts to different screen sizes and devices.

# Requirements
- A web server running PHP
- MySQL database

# File structure
- index.php - The landing page of the application that allows users to add product information and order entries
- view-products.php - A page that displays all product information
- view-orders.php - A page that displays all order entries
- login.php - A page for users to log in and access the application
- register.php - A page for new users to create an account

# Installation
To install this system on a server, follow these steps:

- Import the SQL database from the database.sql file in the sql folder, using a tool like phpMyAdmin or the MySQL command line.
bash

mysql -u username -p database_name < sql/database.sql

- Update the database connection settings in the config.php file with your own database credentials:
php

// Database connection
$conn = new mysqli('localhost','username','password','database_name');

- Upload the files to your web server, or run a local web server like XAMPP or WAMP to test the system.
Usage

Once the system is installed and running, you can access it from your web browser by visiting the URL of your server. You will be prompted to login or register as a new user.

Once logged in, you can navigate the different pages of the system using the sidebar menu. The main pages are:

- Dashboard: Overview of the current stock levels, pending orders, and recent activity.
- Products: View, add, edit, or delete products in the inventory.
- Orders: View, create, edit, or delete orders, and track their status.
- Logistics: Enter shipping information, delivery address, and special instructions for each order.
- Profile: Update your personal information and change your password.


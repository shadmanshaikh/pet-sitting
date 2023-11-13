# Pet Sitting and Products Website

Welcome to the Pet Sitting and Products Website! This web application is designed to connect pet owners with reliable pet sitters and provide a platform for purchasing pet-related products. It is built using the LAMP (Linux, Apache, MySQL, PHP) stack.

## Features

- Find and contact pet sitters for your beloved pets.
- Browse and purchase a variety of pet-related products.
- User authentication and authorization for secure access.
- Dashboard for users to manage their pet sitting requests and product orders.

## Technologies Used

- **Linux**: Operating system for the server.
- **Apache**: Web server for serving the PHP application.
- **MySQL**: Relational database for storing user data, pet sitting information, and product details.
- **PHP**: Server-side scripting language for building dynamic web pages.
- **HTML/CSS**: Front-end markup and styling.
- **[Bootstrap](https://getbootstrap.com/)**: CSS framework for creating a responsive and visually appealing design.

## Getting Started

### Prerequisites

- A server with Linux installed.
- Apache web server.
- MySQL database server.
- PHP installed.

### Installation

1. Clone the repository: `git clone https://github.com/yourusername/pet-sitting-and-products.git`
2. Set up the Apache server to serve the PHP application.
3. Import the MySQL database schema from the `database.sql` file.

### Configuration

1. Update the database connection details in the `config.php` file:

   ```php
   <?php
   define('DB_HOST', 'your_mysql_host');
   define('DB_USER', 'your_mysql_user');
   define('DB_PASSWORD', 'your_mysql_password');
   define('DB_NAME', 'your_mysql_database');
   ?>

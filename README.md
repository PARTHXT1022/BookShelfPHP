# BookStoreManager

Welcome to **BookStoreManager**, a comprehensive bookstore management system built with PHP and MySQL. This application is designed to help bookstore owners manage inventory, sales, customers, and more in an efficient and user-friendly manner.

## Table of Contents

1. [Features](#features)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Configuration](#configuration)
5. [Usage](#usage)
6. [Screenshots](#screenshots)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

## Features

- **Inventory Management**: Add, update, delete, and view books in the inventory.
- **Sales Management**: Record sales transactions and generate sales reports.
- **Customer Management**: Maintain customer information and purchase history.
- **User Authentication**: Secure login and registration system for users.
- **Search Functionality**: Easily search for books, customers, and transactions.
- **Responsive Design**: Mobile-friendly interface for use on various devices.

## Requirements

- **PHP** version 7.2 or higher
- **MySQL** version 5.6 or higher
- Web server (e.g., Apache, Nginx)
- Web browser (e.g., Chrome, Firefox)

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/BookStoreManager.git
    ```

2. **Navigate to the project directory:**

    ```sh
    cd BookStoreManager
    ```

3. **Create a database:**

    ```sql
    CREATE DATABASE bookstore;
    ```

4. **Import the database schema:**

    ```sh
    mysql -u username -p bookstore < database/schema.sql
    ```

5. **Configure the database connection:**

    Open `config.php` and update the database connection settings:

    ```php
    <?php
    define('DB_SERVER', 'localhost');
    define('DB_USERNAME', 'yourusername');
    define('DB_PASSWORD', 'yourpassword');
    define('DB_NAME', 'bookstore');
    ?>
    ```

6. **Start the web server:**

    Ensure your web server is running and serving the project directory.

## Configuration

- **Database Configuration:** Update the `config.php` file with your database credentials.
- **Web Server Configuration:** Ensure your web server is configured to serve PHP files and the project directory is correctly set up.

## Usage

1. **Access the application:**

    Open your web browser and navigate to `http://localhost/BookStoreManager`.

2. **Login or Register:**

    Use the login page to access the system or register a new account if you don't have one.

3. **Manage Inventory:**

    Add, update, or delete books from the inventory section.

4. **Manage Sales:**

    Record new sales and generate reports from the sales section.

5. **Manage Customers:**

    Add new customers and view their purchase history.

## Screenshots

![Screenshot (560)](https://github.com/PARTHXT1022/BookShelfPHP/assets/63895030/cd664b6c-5dc1-498c-acff-055850606960)

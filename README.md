# Library System

## Description

Simple Library Information System built using Laravel and MySQL.

This project was created as part of the Laravel Environment Setup assignment. Its purpose is to prepare a Laravel development environment and connect the application to a MySQL database.

## Requirements

Before running this project, make sure the following software is installed:

- PHP
- Composer
- MySQL
- Laravel
- Git

## Installation

1. Clone the repository.

   ```bash
   git clone https://github.com/USERNAME/library-system.git
   ```

2. Enter the project directory.

   ```bash
   cd library-system
   ```

3. Install Composer dependencies.

   ```bash
   composer install
   ```

4. Copy the environment configuration file.

   ```bash
   cp .env.example .env
   ```

5. Generate the Laravel application key.

   ```bash
   php artisan key:generate
   ```

6. Create a MySQL database named `library_system`.

7. Configure the database connection in the `.env` file.

   ```env
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=library_system
   DB_USERNAME=root
   DB_PASSWORD=
   ```

8. Run the database migrations.

   ```bash
   php artisan migrate
   ```

9. Start the Laravel development server.

   ```bash
   php artisan serve
   ```

10. Open the application in a web browser.

    ```text
    http://127.0.0.1:8000
    ```

## Database

This project uses MySQL as the database management system.

Database name: `library_system`

## Author

Salman Al Farisi

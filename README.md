# Laravel Support Ticket System Admin Panel

This project is a **PHP Laravel**-based support ticket system with an admin panel. Users (customers) can submit support tickets to website owners, track the status of their tickets, and update their profile settings such as password and profile image. The admin (website owner) can view, manage, and respond to support tickets from a centralized dashboard.

## Demo Link

There is no live demo available. However, you can run the project locally by following the installation instructions below.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Routes](#routes)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- **Support Ticket Submission**: Users can submit support tickets to the website admin.
- **Admin Panel**: Admins can view and manage submitted tickets from the admin dashboard.
- **Ticket Status Tracking**: Users can track the status of their submitted tickets (open, closed, pending).
- **Profile Management**: Users can update their profile settings, including password and profile picture.
- **Role-Based Access**: Role-specific features for users (customers) and admins (website owners).

---

## Technologies Used

- **PHP Laravel 9**: Backend framework.
- **MySQL**: Database for storing tickets and user information.
- **Blade**: Laravel’s templating engine.
- **Bootstrap 5**: For responsive front-end design.
- **JavaScript & Ajax**: For interactive UI elements and real-time ticket updates.

---

## Installation

To run the Laravel Support Ticket System on your local machine, follow these steps:

1. **Clone the Repository**

   First, clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/laravel-support-ticket-system.git

2. Navigate to the Project Directory

Change to the project directory:

```bash
cd laravel-support-ticket-system
```

3. Install Dependencies

Run the following command to install all the necessary dependencies:


```bash
composer install
composer update
cp .env.example .env


DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_database_username
DB_PASSWORD=your_database_password
```

4. Generate Application Key

Generate the Laravel application key:

```bash
php artisan key:generate
php artisan migrate
php artisan db:seed
php artisan serve

```

# Support Ticketing System

A comprehensive ticketing system built with Laravel that allows users to create support tickets and administrators to manage them efficiently. Perfect for customer service departments, IT help desks, or any team that needs to track and resolve user-submitted issues.

## Features

- User authentication with role-based access control
- Create and manage support tickets with attachments
- Categorization with priorities and statuses
- Admin dashboard with detailed statistics
- Email notifications for ticket updates
- Comment system for communication between users and support staff
- User roles (Admin and Agent) with different permissions

## Requirements

- PHP 7.4 or higher
- MySQL 5.7 or higher
- Composer
- Node.js and npm
- PHP Extensions:
  - PDO MySQL
  - Fileinfo
  - Exif
  - OpenSSL
  - Tokenizer
  - Mbstring
  - XML
  - JSON

## Setup Instructions

1. Copy `.env.example` file to `.env` and edit database credentials
2. Run `composer install`
3. Run `php artisan key:generate`
4. Run `php artisan migrate --seed`
5. Run `npm install && npm run dev`
6. Start the server with `php artisan serve`
7. Access the application at http://localhost:8000

## Login Credentials

- **Admin:** admin@admin.com / password
- **Agent:** agent1@agent1.com / password

## License

This project is open-sourced software.
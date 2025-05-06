College Media is a Social media wesite or web app and feature includes -

• Student Role: Allowed students to send friend requests, chat with friends, and share photos with public or
friends-only visibility options.
• Chat Functionality: Integrated a messaging feature, displaying a single tick when a friend is online and a
double tick when the message is read.
• Authentication: Implemented secure user authentication with role-based access, allowing users to register as
teachers or students.
• Teacher Role: Enabled teachers to edit or remove student details, providing them with management
capabilities.

Tech use - LARAVEL 
Server use - WAPM

# 🚀 Laravel Project Setup Guide

This guide will help you clone and set up the Laravel project on your local machine.

---

## 🛠️ Prerequisites

Make sure the following are installed:

- PHP >= 8.x
- Composer
- MySQL or compatible database
- Node.js and npm (for frontend assets)
- Laravel CLI (optional)

---

## 📥 Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name



📦 Install Dependencies
Install PHP dependencies:

composer install



⚙️ Environment Setup -
Copy .env.example to .env:
cp .env.example .env


Generate the application key:
php artisan key:generate


🗄️ Configure Database-
Edit the .env file with your local database details:

env
DB_DATABASE=your_db_name
DB_USERNAME=your_username
DB_PASSWORD=your_password
Run migrations (if applicable):
php artisan migrate



▶️ Run the Application-
Serve the Laravel application locally:

php artisan serve

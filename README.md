# TaskHive - Laravel Task Manager

TaskHive is a simple task management app built with Laravel, Laravel Breeze, Livewire, and Bootstrap. It allows users to register, log in, and manage their personal tasks with CRUD functionality.

## Features

- User authentication (Laravel Breeze)
- Create, Read, Update, Delete tasks
- Task status: To Do, In Progress, Completed
- Deadline support
- Livewire components for real-time updates
- Bootstrap for basic styling

## Tech Stack

- Laravel 10
- Laravel Breeze
- Livewire
- Bootstrap 5
- MySQL

## Installation

```bash
git clone https://github.com/yourusername/taskhive.git
cd taskhive

composer install
npm install && npm run dev

cp .env.example .env
php artisan key:generate
# Set up your database in .env

php artisan migrate
php artisan serve

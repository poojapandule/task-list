# Task Management Application

This is a simple task management application built with Laravel.

## Prerequisites

- PHP 8.2 or higher
- Composer
- SQLite (default database)
- Node.js and npm (for frontend assets)

## Setup

1. Install PHP dependencies:
   ```
   composer install
   ```

2. Copy the `.env.example` file to `.env`:
   ```
   cp .env.example .env
   ```
   The default configuration uses SQLite, so no additional database setup is required.

3. Generate application key:
   ```
   php artisan key:generate
   ```

4. Run database migrations and seed the database:
   ```
   php artisan migrate --seed
   ```

5. Install and compile frontend assets:
   ```
   npm install
   npm run dev
   ```

6. Start the development server:
   ```
   php artisan serve
   ```

The application should now be running at `http://localhost:8000`.

## Features

- Create, read, update, and delete tasks
- Mark tasks as complete/incomplete
- Paginated task list
- Form validation

This project is intended for educational purposes to demonstrate basic Laravel functionality and CRUD operations.

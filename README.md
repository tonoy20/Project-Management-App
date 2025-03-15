Laravel 11 + React SPA Project
A simple project management application using Laravel 11 and React.

The project was developed for the following YouTube tutorial.

Features

Registration & Login

Projects CRUD with sorting, filtering and pagination

Tasks CRUD with sorting, filtering and pagination

Create Tasks inside project

Show all tasks or show tasks for a specific project

Assign users to tasks
View Tasks assigned to me
Show dashboard with overview information
Installation
Clone the project
Navigate to the project's root directory using terminal
Create .env file - cp .env.example .env
Execute composer install
Execute npm install
Set application key - php artisan key:generate --ansi
Execute migrations and seed data - php artisan migrate --seed
Start vite server - npm run dev
Start Artisan server - php artisan serve

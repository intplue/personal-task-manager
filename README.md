# Personal Task Manager

A simple Laravel-based web application for creating, organizing, and tracking personal tasks.

## Project Information

* **Project Code:** WST21-PM-2026-SF
* **Student Name:** [Your Name]
* **Course & Year:** [Your Course & Year]
* **Database Used:** SQLite

## Project Description

The Personal Task Manager is a web-based task management system developed using Laravel. It allows users to create tasks, view their task list, edit existing tasks, delete tasks, and update the status of each task.

The system uses Laravel's MVC architecture, connecting routes, controllers, models, database operations, and Blade views to manage task information.

## Features

* **Add Task** – Create a new task with a task name, description, status, and due date.
* **View Tasks** – Display all saved tasks and their current information.
* **Edit Task** – Modify the details of an existing task.
* **Delete Task** – Remove a task from the task list.
* **Update Status** – Change a task's status between Pending and Completed.

## Task Fields

Each task contains the following information:

* Task ID
* Task Name
* Description
* Status
* Due Date

## Technologies Used

* Laravel
* PHP
* SQLite
* Blade
* HTML
* CSS

## Project Structure

The application follows the Laravel MVC structure:

**Routes → Controller → Model → Database → Blade**

* **Routes** handle incoming requests and direct them to the appropriate controller methods.
* **Controller** contains the application's task management logic.
* **Model** communicates with the database through Laravel's Eloquent ORM.
* **Database** stores the task information.
* **Blade Views** provide the user interface for managing tasks.

## Status Options

Tasks can have one of two statuses:

* Pending
* Completed

## How to Run the Project

1. Clone or open the project.
2. Install the required dependencies.
3. Configure the `.env` file.
4. Run the database migrations.
5. Start the Laravel development server.

Example:

```bash
php artisan migrate
php artisan serve --host=0.0.0.0 --port=8000
```

## Project Purpose

This project demonstrates the development of a basic CRUD-based Laravel application using routes, controllers, models, database operations, and Blade views.

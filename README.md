A simple task management application built with Node.js, Express, and MongoDB.

## Features

- Create, read, update, and delete tasks
- Task filtering by status
- Basic CRUD operations
- Lightweight and efficient backend

## Prerequisites

- Node.js and npm installed
- MongoDB installed and running

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
Navigate to the project directory:


cd task-manager
Install dependencies:


npm install
Start MongoDB server:


mongod --dbpath /path/to/data/db
Start the application:


npm start
Usage
Visit http://localhost:3000 to access the Task Manager web application.
Create, edit, or delete tasks through the provided UI or API endpoints.
API Endpoints
POST /tasks - Create a new task
GET /tasks - Get all tasks
GET /tasks/:id - Get a specific task by ID
PUT /tasks/:id - Update a specific task
DELETE /tasks/:id - Delete a specific task

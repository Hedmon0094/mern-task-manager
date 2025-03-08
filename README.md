# MERN Task Manager

A full-stack web application to manage tasks, built with the MERN stack (MongoDB, Express.js, React, Node.js). This project demonstrates backend and frontend integration, CRUD operations, RESTful API development, and deployment to cloud platforms.

## Project Overview

The Task Manager app allows users to create, read, update, and delete tasks. Each task includes a title, description, status, and due date. The app is designed with a responsive UI using Tailwind CSS and follows proper project structuring practices.

## Features

- Add, update, delete, and view tasks
- API routes for CRUD operations
- Task status management (pending, in progress, completed)
- Date management for task deadlines
- Fully responsive UI with Tailwind CSS
- React state management with hooks (useState, useEffect)

## Installation Steps

1. **Clone the Repository:**
```bash
git clone <repository-url>
cd mern-task-manager
```

2. **Backend Setup:**
```bash
cd backend
npm install
```
Create a `.env` file and add your MongoDB URI:
```
MONGO_URI=your_mongodb_connection_string
PORT=5000
```
Run the server:
```bash
npm start
```

3. **Frontend Setup:**
```bash
cd ../frontend
npm install
```
Run the React app:
```bash
npm run dev
```

## API Endpoint Documentation

| Method | Endpoint            | Description             |
|--------|---------------------|-------------------------|
| POST   | `/api/tasks`        | Create a new task       |
| GET    | `/api/tasks`        | Retrieve all tasks      |
| PUT    | `/api/tasks/:id`    | Update a task by ID     |
| DELETE | `/api/tasks/:id`    | Delete a task by ID     |

### Task Model Structure

```json
{
  "title": "Task Title",
  "description": "Task Description",
  "status": "pending",
  "dueDate": "2025-03-15"
}
```

## Usage Guide

1. **Add a Task:** Fill out the form and click 'Add Task.'
2. **Update a Task:** Click the edit icon next to a task, modify the details, and save.
3. **Delete a Task:** Click the delete icon to remove a task.
4. **View Tasks:** The homepage lists all tasks, showing their status and due date.

## Deployment

- **Backend:** Deployed on Render
- **Frontend:** Deployed on Vercel


```




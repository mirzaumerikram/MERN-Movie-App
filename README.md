# RESTful API Project

## Project Overview
This project implements a RESTful API using Node.js and Express that reads and writes data from multiple JSON files. The API supports basic CRUD operations to fetch, add, update, partially update, and delete records.

# Home Page
<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/b088fc0b-100c-453d-863a-425b86b4f6e2" />
# Movies Page
<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/fd1756fb-299f-493d-bf4a-9a415d7c54ba" />


## Available JSON Files
- users.json - Contains user data
- students.json - Contains student data
- tasks.json - Contains task/assignment data

## API Endpoints

### Users
- `GET /api/users` - Get all users
- `GET /api/users/:id` - Get user by ID
- `POST /api/users` - Add a new user
- `PUT /api/users/:id` - Update entire user record
- `PATCH /api/users/:id` - Partially update a user record
- `DELETE /api/users/:id` - Delete a user record

### Students
- `GET /api/students` - Get all students
- `GET /api/students/:id` - Get student by ID
- `POST /api/students` - Add a new student
- `PUT /api/students/:id` - Update entire student record
- `PATCH /api/students/:id` - Partially update a student record
- `DELETE /api/students/:id` - Delete a student record

### Tasks
- `GET /api/tasks` - Get all tasks
- `GET /api/tasks/:id` - Get task by ID
- `POST /api/tasks` - Add a new task
- `PUT /api/tasks/:id` - Update entire task record
- `PATCH /api/tasks/:id` - Partially update a task record
- `DELETE /api/tasks/:id` - Delete a task record





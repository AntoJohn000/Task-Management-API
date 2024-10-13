# Task-Management-API

A simple RESTful API built with Django and Django REST Framework for managing tasks. This API allows users to create, update, delete, and retrieve tasks with features such as user assignment, pagination, and search functionality.

## Table of Contents

- [Features](#Features)
- [Technologies Used](#Technologies-used)
- [Installation](#Installation)
- [Usage](#Usage)
- [API Endpoints](#Api-Endpoints)
- [Contributing](#Contributing)
- [License](#license)

## Features

- Create, read, update, and delete tasks
- Assign tasks to users
- Search tasks by title or description
- Pagination for task retrieval
- User authentication support

## Technologies Used

- Python 3.x
- Django
- Django REST Framework
- SQLite (or any other database of your choice)

## Installation

1. **Clone the repository**:
    ```bash
   git clone https://github.com/yourusername/task-management-api.git
   cd task-management-api
   
2. **Create a virtual environment**:
   
    ```bash
    python -m venv venv
    source venv/bin/activate  # For macOS/Linux
    venv\Scripts\activate    # For Windows


3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt


4. **Run migrations:**
    ```bash
    python manage.py migrate

5. ** Run the development server**:
    ```bash
     python manage.py runserver


**Usage**

You can interact with the API using tools like Postman or cURL. 
The API provides a browsable interface that you can access at:
   ```text
    http://127.0.0.1:8000/api/
```
****API Endpoints****

| Method | Endpoint              | Description                               |
|--------|-----------------------|-------------------------------------------|
| GET    | `/api/tasks/`        | Retrieve all tasks                        |
| POST   | `/api/tasks/`        | Create a new task                         |
| GET    | `/api/tasks/{id}/`    | Retrieve a specific task                  |
| PUT    | `/api/tasks/{id}/`    | Update a specific task                    |
| PATCH  | `/api/tasks/{id}/`    | Partially update a specific task          |
| DELETE | `/api/tasks/{id}/`    | Delete a specific task                    |
 

**Contributions are welcome!**

Please follow these steps:
Fork the repository.
Create a new branch (git checkout -b feature/YourFeature).
Make your changes.
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature/YourFeature).
Open a pull request.

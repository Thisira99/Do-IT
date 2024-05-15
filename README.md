# To-Do List App

## Overview
This is a simple To-Do List application that allows users to manage their tasks. Users can add, delete, and edit tasks. The application uses a database to store tasks persistently.

## Features
- **Add Task**: Allows users to add new tasks to their to-do list.
- **Delete Task**: Users can delete tasks from their list.
- **Edit Task**: Users can edit existing tasks.
- **Database Integration**: Tasks are stored in a database for persistence.

## Screenshots
### Start Screen
  ![Start](https://github.com/Thisira99/Do-IT/assets/90537716/67c9aacb-f59d-4853-9b22-419b33b4d5d0)


### Home Screen
  ![Home](https://github.com/Thisira99/Do-IT/assets/90537716/8d01cd96-f594-455e-90a3-47aafedbe167)
                

### Edit Task
  ![edit](https://github.com/Thisira99/Do-IT/assets/90537716/28f4c203-7294-4af0-8ac6-8035595197f6)


### Delete Task
   ![delete](https://github.com/Thisira99/Do-IT/assets/90537716/42db27e3-b0ac-4210-b0f5-e8dc1ca2d4ed)


## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/todo-list-app.git
    ```
2. Navigate to the project directory:
    ```bash
    cd todo-list-app
    ```
3. Install the dependencies:
    ```bash
    npm install
    ```
    or for Python:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Start the application:
    ```bash
    npm start
    ```
    or for Python:
    ```bash
    python app.py
    ```
2. Open your browser and navigate to `http://localhost:3000` to use the app.

## API Endpoints
- **GET /tasks**: Retrieve all tasks.
- **POST /tasks**: Add a new task.
- **PUT /tasks/:id**: Edit an existing task.
- **DELETE /tasks/:id**: Delete a task.

## Database
The app uses [Your Database Choice] to store tasks. Configure your database connection in the `.env` file.

Example configuration for a MongoDB database:

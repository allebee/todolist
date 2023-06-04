# FastAPI Todo App

This is a simple FastAPI Todo application that allows you to manage your todo list. 
The project was created to learn about CRUD operations and other concepts in FastAPI.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/allebee/todolist.git
2. Install the dependencies 
   ```shell
   pip install -r requirements.txt
3. Run the application:
   ```shell
   uvicorn app:app --reload

Endpoints
GET /: Retrieves the todo list from the database and displays it on the homepage.
POST /add: Adds a new todo item to the database.
GET /update/{todo_id}: Toggles the completion status of a todo item.
GET /delete/{todo_id}: Deletes a todo item from the database.
POST /edit/{todo_id}: Edits the title of a todo item.


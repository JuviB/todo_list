# todo_list

## Table of Contents:

  - Description of the project 
  - Importance of the project and what it does
  - Installation
  - Usage
  - Credits

### Description of the project

Built a Website using Django. This website is a ToDo List that allows the user to create an account and enables them to track their everyday tasks.
  - Create an account with an appropriate username and password
  - Log in to their account with repective login details
  - Add tasks that need to be done
    - A title of the task is required
    - A description of the task is optional
    - Specifiy whether the tasks are completed or still yet to be completed
  - Tasks can also be searched up and displayed from the database
  - Tasks that have already been added can be edited Eg. stating whether a specific task is now completed

This project includes a database-driven component that differentiates and keeps track of all tasks created for a logged in user, this is done through user login and authentication in django.
  
### Importance of the project and what it does

This program is useful for a user to track their everyday tasks that needs to be done and whether the tasks are completed or not.

### Installation
- git clone https://github.com/JuviB/todo_list.git

- cd todo_list

#### Step-by-step guide on how to install and set up the project:

##### Example for Django migrations
- python manage.py migrate

##### Example for running the development server
- python manage.py runserver

##### Example for creating a virtual environment
- python -m venv venv

##### Example for creating database tables
- python manage.py makemigrations

- python manage.py migrate

##### Example for running the application
- python manage.py runserver

##### Example for building and running the Docker container
- docker build -t todo_list

- docker run -p 8000:8000 todo_list

### Usage

As soon as the server is running, the login page will be displayed for users that already have an account to login.

![login](https://github.com/JuviB/todo_list/assets/149655754/6837f1ed-b38c-4fa4-ba69-4c75ceab4803)

For users that don't have an account can click the "Register" link to create an account in the user creation portal.

![signUp](https://github.com/JuviB/todo_list/assets/149655754/7c5b3be7-4ada-4303-88db-083223ef7156)

Once an account has been created, the user will be redirected back to the login page where the user will need to enter their details for login.

Once logged in, the users dashboard will be displayed, either empty (for new users), or displayed the various tasks that have already created (for existing users).

![dashboard](https://github.com/JuviB/todo_list/assets/149655754/18355e63-d71d-40d0-bc21-2199ed7b8db1)

New tasks can be added by clicking on the '+' icon, this will redirect the user to the new task creation page where the user can specify details for a task to add to their ToDo List.

![addTask](https://github.com/JuviB/todo_list/assets/149655754/799f59a3-f11c-48e1-b70a-98131bff8333)

Tasks can be modified by clicking on the task title, if a task is marked completed a line will be crossed through it.

Tasks can also be deleted by clicking on the 'x' icon on the extreme right of the task title.

### Credits

- Guided by Hyperiondev
- Created by Juvaan Bechoo 

### URL

[Github Repository URL](https://github.com/JuviB/todo_list.git)

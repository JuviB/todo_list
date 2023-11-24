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

The database is created by means of a table that contains the following column headings for each book entry:
  - id
  - title
  - author
  - qty
  
### Importance of the projetc and what it does
This program is useful when searching for and retrieving data based on a book in a bookstore.

### Installation
git clone https://github.com/JuviB/todo_list.git

cd todo_list

####Step-by-step guide on how to install and set up the project:

# Example for Django migrations
python manage.py migrate

# Example for running the development server
python manage.py runserver

# Example for creating a virtual environment
python -m venv venv

# Example for creating database tables
python manage.py makemigrations
python manage.py migrate

# Example for running the application
python manage.py runserver

# Example for building and running the Docker container
docker build -t todo_list
docker run -p 8000:8000 todo_list

### Usage
As soon as the program is run, all book data that are currently inserted into the database is uploaded and available to be displayed and manipulated.
The menu will then be displayed to the user with the various menu options: 

1. Display all books
2. Enter book
3. Update book
4. Delete book
5. Search book
0. Exit

You will be required to select an option depending on the needs of the user, followed by system commands to guide you through each process.

### Credits
- Guided by Hyperiondev
- Created by Juvaan Bechoo 

### URL
[Github Repository URL](https://github.com/JuviB/eBookstore.git)

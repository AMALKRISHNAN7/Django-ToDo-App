# Django To-Do App

A simple To-Do application built with Django that allows users to create, update, and delete tasks.

## Features
- Add new tasks
- Mark tasks as completed
- Edit existing tasks
- Delete tasks
- Responsive UI

## Installation

### Prerequisites
Make sure you have Python and pip installed.

### Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/AMALKRISHNAN7/Django-ToDo-App.git
   cd Django-ToDo-App
   ```
2. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt     -- REQUIREMENTS FILE NOT CREATED
   ```
4. Apply migrations:
   ```sh
   python manage.py migrate
   ```
5. Create a superuser (optional, for admin access):
   ```sh
   python manage.py createsuperuser
   ```
6. Run the development server:
   ```sh
   python manage.py runserver
   ```
7. Open the app in your browser:
   ```
   http://127.0.0.1:8000/
   ```

## Usage
- Add, edit, or delete tasks as needed.
- Mark completed tasks.

## Technologies Used
- Django
- SQLite (default database, can be changed)
- Bootstrap (for styling)



## Contact
For any questions or suggestions, contact me directly through issue.


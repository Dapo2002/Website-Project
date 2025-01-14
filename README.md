# Website Project

A Flask-based web application that allows users to sign up, log in, create notes, and manage them. This application uses SQLAlchemy for database management and Flask-Login for user authentication.

## Features
- User Authentication: Sign up, login, and logout functionality with password hashing.
- Notes Management: Create, view, and delete notes.
- Flask & SQLAlchemy: Backend is built with Flask, and SQLAlchemy is used for database management.

## Requirements
- Python 3.7+
- Flask
- Flask-SQLAlchemy
- Flask-Login
- Werkzeug

You can install the required dependencies by running:

```bash
pip install -r requirements.txt
```

## Project Structure

- `main.py`: Entry point for the application, where the app is created and run.
- `__init__.py`: Contains the `create_app()` function that initializes the Flask app and configurations.
- `auth.py`: Handles user authentication (login, logout, sign-up).
- `models.py`: Defines the database models for `User` and `Note`.
- `views.py`: Defines the main functionality, such as home page and note deletion.

## Database

The app uses SQLite for data storage. The database file will be created automatically when the app is run for the first time.

# Django Tutorial Project

This is a simple poll application built using Django, based on the official Django tutorial.

## Requirements

- Python 3.x
- Django 4.x

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/shirozuo/django_tutorial.git
    cd django_tutorial
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Apply migrations:
    ```sh
    python manage.py migrate
    ```

5. Create a superuser:
    ```sh
    python manage.py createsuperuser
    ```

6. Run the development server:
    ```sh
    python manage.py runserver
    ```

## Usage

1. Open your browser and navigate to `http://127.0.0.1:8000/polls/` to access the polls application.
2. To access the admin interface, navigate to `http://127.0.0.1:8000/admin/` and log in with the superuser credentials.

## Project Structure

- `polls/`: Contains the polls application code.
- `polls/migrations/`: Database migration files.
- `polls/templates/`: HTML templates for the polls application.
- `polls/static/`: Static files (CSS, JavaScript) for the polls application.
- `polls/views.py`: View functions for the polls application.
- `polls/models.py`: Database models for the polls application.
- `polls/urls.py`: URL configuration for the polls application.

## Features

- Create and manage polls.
- Vote on polls.
- View poll results.
- Admin interface for managing polls and votes.

## Acknowledgments

- Django Documentation - [Writing your first Django app](https://docs.djangoproject.com/en/stable/intro/tutorial01/)

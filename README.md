# Recruitment Management System

This is a Recruitment Management System to help manage job applications efficiently.

## Requirements

To run this project, you will need the following software installed on your system:

- *Python 3.8 or higher*
- *Django 3.2 or higher*
- *SQLite (for the default database)*
- *Git*

You will also need the following Python packages, which can be installed via pip:

- Django
- djangorestframework
- django-cors-headers

## Installation

1. *Clone the repository:*

    bash
    git clone (https://github.com/AayushiiSharma/Recruitment_system.git)
    cd Recruitment-management-system
    

2. *Create a virtual environment:*

    bash
    python -m venv venv
    

3. *Activate the virtual environment:*

    - On Windows:

        bash
        venv\Scripts\activate
        

    - On macOS/Linux:

        bash
        source venv/bin/activate
        

4. *Install the required packages:*

    bash
    pip install -r requirements.txt
    

## Running the Project

1. *Apply migrations:*

    bash
    python manage.py migrate
    

2. *Create a superuser (optional, but recommended for accessing the admin interface):*

    bash
    python manage.py createsuperuser
    

3. *Run the development server:*

    bash
    python manage.py runserver
    

4. *Open your browser and go to:*

    
    http://127.0.0.1:8000/
    

## Project Structure

- manage.py: Command-line utility for administrative tasks.
- recruitment/: Main Django app directory.
- recruitment/settings.py: Settings and configuration for the Django project.
- recruitment/urls.py: URL declarations for the project.
- recruitment/views.py: Views for handling requests and responses.
- templates/: HTML templates for the project.
- static/: Static files (CSS, JavaScript, images) for the project.

## Features

- User authentication and authorization
- Job posting and application management
- Admin interface for managing job postings and applications
- REST API for integrating with other systems

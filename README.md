                                                            
  
  
  

# Team Collaboration API

This is a project management tool API built with Django and Django REST Framework. It allows users to manage projects, tasks, and comments with role-based access control.

## Table of Contents

  - [Features](#features)
  - [Requirements](#requirements)
  - [Installation](#installation)
  - [API Documentation](#api-documentation)
  - [License](#license)

## Features

- User authentication with JWT
- Project management
- Task management
- Commenting system
- Role-based access control
- API documentation with Swagger and ReDoc

## Requirements

- Python 3.8+
- Django 3.2+
- Django REST Framework
- djangorestframework-simplejwt
- drf-yasg

## Installation

### Clone the Repository

First, clone the repository to your local machine:

1. Open your VS Code terminal.
2. Run the following commands:

    ```bash
    git clone https://github.com/Aniruddha335577/projectManagement-using-django.git
    cd projectManagement-using-django
    ```

### Create and Activate a Virtual Environment

Create a virtual environment to isolate your project dependencies:

1. In your VS Code terminal, run:

    ```bash
    python -m venv env
    env\Scripts\activate
    ```

### Install Dependencies

Install the required dependencies:

```bash
pip install -r requirements.txt
```




### Apply Migrations

Apply the database migrations to set up the database schema:

```bash
python manage.py makemigrations
python manage.py migrate
```

                                                                                
  
  

### Run the Development Server

Start the Django development server:

```bash
python manage.py runserver
```

You can now access the application at `http://127.0.0.1:8000/`.

## API Documentation

The API documentation is available via Swagger UI. To access it, navigate to:

[http://127.0.0.1:8000/swagger/](http://127.0.0.1:8000/swagger/)

Alternatively, you can view the ReDoc documentation at:

[http://127.0.0.1:8000/redoc/](http://127.0.0.1:8000/redoc/)

                                                                                                                                                                                                                                                                                                                      
## License

This project is licensed under the MIT License. See the LICENSE file for details.                                                            
  
  

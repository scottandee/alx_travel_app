# ALX Travel App – ProDev Backend (Milestone 1)
### Project Overview
This repository contains the initial setup for the **ALX Travel App**, a real-world Django application that serves as the foundation for a travel listing platform. Milestone 1 focuses setting up the initial project structure, configuring a robust database, and integrating tools to ensure API documentation and maintainable configurations+.

## Quickstart
1. Create a virtual environment
    ```bash
    python -m venv venv
    source venv/bin/activate
    ```
2. Clone the repository
    ```bash
    git clone https://github.com/scottandee/alx_travel_app.git
    cd alx_travel_app/alx_travel_app/
    ```
3. Install dependencies
    ```bash
    pip install -r requirements.txt
    ```
4. Configure environment variables
    ```bash
    cp .env.example .env
    ```
5. Apply migrations
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```
6. Run the development server
    ```bash
    python manage.py runserver
    ```
7. Access Swagger documentation
- Navigate to: http://127.0.0.1:8000/swagger/

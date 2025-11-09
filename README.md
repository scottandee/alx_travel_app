# ALX Travel App – ProDev Backend (Milestone 1)
### Project Overview
This repository contains the initial setup for the **ALX Travel App**, a real-world Django application that serves as the foundation for a travel listing platform. Milestone 1 focuses setting up the initial project structure, configuring a robust database, and integrating tools to ensure API documentation and maintainable configurations+.

## Quickstart
1. Clone the repository
  ```bash
    git clone https://github.com/scottandee/alx_travel_app.git
    cd alx_travel_app/alx_travel_app/
  ```
2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Configure environment variables
```bash
cp .env.example .env
```
4. Apply migrations
```bash
python manage.py makemigrations
python manage.py migrate
```
5. Run the development server
```bash
python manage.py runserver
```
6. Access Swagger documentation
- Navigate to: http://127.0.0.1:8000/swagger/

# Customer360 Django Application

This is a Django-based web application to manage and display customer information. The application includes a simple CRUD interface for customer records.

## Features

- List customers with details such as ID, Name, Email, Phone, Address.
- Simple UI to view customers.
- SQLite database for storage.

## Prerequisites

- Python 3.11
- Django 5.0.6

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/phanikum4r/Customer360.git
cd Customer360

### 2. Create a Virtual Environment
Create and activate a virtual environment to manage dependencies.
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

### 3. Install Dependencies
Install the required Python packages using pip.
python -m pip install Django

### 4. Apply Migrations
Generate and apply database migrations.
python manage.py makemigrations customer360
python manage.py migrate

### 6. Run the Development Server
Start the Django development server.
python manage.py runserver

Access the application at http://localhost:8000/.

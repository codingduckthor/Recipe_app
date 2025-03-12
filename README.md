# Recipe Manager

### A simple Django-based Recipe Manager to add, view, edit, and delete recipes. This project is designed to help manage your favorite recipes efficiently.

# Features

### Add new recipes with title, ingredients, and instructions

### Categorize recipes by type (e.g., Breakfast, Dinner, Dessert)

### Edit and delete existing recipes

### User-friendly interface with intuitive navigation

# Installation

## Prerequisites

### Python 3.10+

### Django 4+

### Git

# Setup Instructions

### Clone the repository

```
git clone https://github.com/codingduckthor/Recipe_app.git

cd Recipe_app
```

### Create and activate a virtual environment

```
python -m venv venv
source venv/Scripts/activate  # On Windows
source venv/bin/activate      # On Mac/Linux
```

### Install dependencies

```
pip install -r requirements.txt
```

### Apply migrations

```
python manage.py migrate
```

### Create a superuser (optional for admin access)

```
python manage.py createsuperuser
```

### Run the development server

```
python manage.py runserver
```

### Access the app in your browser:

Home page: http://localhost:8000

Admin panel: http://localhost:8000/admin

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

# Usage

Navigate to the homepage to view all recipes.

Click 'Add Recipe' to submit a new recipe.

Click on a recipe title to view details.

Use the 'Edit' and 'Delete' buttons to manage entries.

Project Structure

recipe_manager/
├── recipes/
│ ├── migrations/
│ ├── static/recipes/
│ ├── templates/recipes/
│ ├── admin.py
│ ├── models.py
│ ├── urls.py
│ ├── views.py
│ └── forms.py
├── recipe_manager/
│ ├── settings.py
│ ├── urls.py
│ ├── wsgi.py
│ └── asgi.py
├── db.sqlite3
├── manage.py
├── requirements.txt
└── README.md

Technologies Used

Django — Web framework for rapid development

HTML/CSS — For frontend design

SQLite — Lightweight database for development

Known Issues & Improvements

Improved styling for better UX

Enhanced search functionality

User authentication for personal recipe management

Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

License

This project is licensed under the MIT License.

Contact

For any questions or suggestions, please reach out via [your email or social media link].

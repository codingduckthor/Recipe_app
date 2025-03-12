# Recipe Manager

### Простое приложение на основе Django для добавления, просмотра, коррекции и удаления рецептов.

# Функции

### Добавление рецептов с названием, ингридиентами, инструкциями к приготовлению

### Возможность выбора категорий "Завтрак", "Обед", "Перекус", "Ужин"

### Корректировка и удаление рецептов

# Установка

## Пререквезиты

### Python 3.10+

### Django 4+

### Git

# Инструкции к установке

### Клонирование репозитория

```
git clone https://github.com/codingduckthor/Recipe_app.git

cd Recipe_app
```

### Создание и запуск вируальной среды

```
python -m venv venv
source venv/Scripts/activate  # On Windows
source venv/bin/activate      # On Mac/Linux
```

### Установка необходимых элементов

```
pip install -r requirements.txt
```

### Миграции

```
python manage.py migrate
```

### Создание админки, если есть необходимость

```
python manage.py createsuperuser
```

### Запуск сервера

```
python manage.py runserver
```

### Сервер теперь доступен по адресам:

Home page: http://localhost:8000

Admin panel: http://localhost:8000/admin

<<<<<<< HEAD
# EasyEats-Backend
=======
# Easy Eats Backend

This is the Django backend for the Easy Eats mobile application.

## Setup Instructions

1. Create a virtual environment:
```bash
python -m venv venv
```

2. Activate the virtual environment:
- Windows:
```bash
venv\Scripts\activate
```
- Unix/MacOS:
```bash
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Create a .env file in the root directory with the following variables:
```
DEBUG=True
SECRET_KEY=your-secret-key-here
ALLOWED_HOSTS=localhost,127.0.0.1
```

5. Run migrations:
```bash
python manage.py makemigrations
python manage.py migrate
```

6. Create a superuser:
```bash
python manage.py createsuperuser
```

7. Run the development server:
```bash
python manage.py runserver
```

## API Endpoints

The API will be available at `http://localhost:8000/api/`

## Project Structure

```
EasyEats-Backend/
├── easy_eats/          # Main project directory
├── api/               # API app
├── users/             # User management app
├── restaurants/       # Restaurant management app
├── orders/           # Order management app
└── manage.py
```

## Features

- User authentication and authorization
- Restaurant management
- Menu management
- Order processing
- Payment integration
- Image upload and storage 
>>>>>>> 393f0aa (Initial commit)

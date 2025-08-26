# Web Application Personalisation

This project is a **Django web application** designed to **dynamically deliver personalised data views** to mobile app users.

-----

## 🚀 Features

  - Personalised content delivery based on user preferences.
  - Modular **Django app (`landing`)** for data models, views, and APIs.
  - Configurable routing and scalable architecture.
  - Ready for integration with mobile applications.

-----

## 🛠️ Tech Stack

  - **Python 3.x**
  - **Django 3.x+**
  - **SQLite / PostgreSQL** (configurable in `settings.py`)

-----

## 📂 Project Structure

```
app/
├── manage.py # Django entry point
├── project/ # Main Django project settings
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
└── landing/ # Personalisation app
    ├── models.py
    ├── views.py
    ├── urls.py
    ├── admin.py
    └── migrations/
```

-----

## ⚙️ Setup Instructions

### 1\. Clone Repository

```bash
git clone <repo-url>
cd app
```

### 2\. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3\. Apply Migrations

```bash
python manage.py migrate
```

### 4\. Create Superuser (for Django Admin)

```bash
python manage.py createsuperuser
```

### 5\. Run Development Server

```bash
python manage.py runserver
```

Visit: `http://127.0.0.1:8000`

-----

## ✅ Use Cases

  - Delivering personalised dashboards to mobile app users.
  - Backend system for tailored notifications and user data views.
  - Extensible platform for content-driven applications.

## 👏 Credits
Built by Arav Baboolal & Forage — 2025 🔥

For practice and educational use.

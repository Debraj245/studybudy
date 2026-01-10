# 📚 Studybudy

**Studybudy** is a **Django-based web application** that helps learners find and join study rooms, organize topics, and interact with other learners. It aims to make collaborative study easy, structured, and social.

---

## 🚀 Features

- ✨ Browse and join study rooms by topic  
- 📌 Create and host your own study rooms  
- 🗣️ View recent activity and discussions  
- 👤 User profile pages with avatars and bio  
- 🔐 User authentication (Login/Register)  
- 📍 Filter discussions by topics

---

## 🧠 Project Purpose

Studybudy is built as a practical project to learn and demonstrate:

- Django fundamentals (Models, Views, Templates)  
- URL routing  
- User authentication  
- Template rendering  
- Static & media file handling  
- Database interaction  
- Git & GitHub workflow

This project mirrors real-world application logic and is great for beginner to intermediate Django learners.

---

## 📦 Tech Stack

| Layer       | Technology                |
|-------------|---------------------------|
| Backend     | Python, Django            |
| Frontend    | HTML, CSS, JavaScript     |
| Database    | SQLite (default)          |
| Tools       | VS Code, Git, GitHub      |

---

## 📁 Project Structure

studybudy/
│
├── manage.py                 # Django management script
│
├── studybud/                 # Main Django project (settings)
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── base/                     # Core Django app
│   ├── __init__.py
│   ├── admin.py              # Admin configurations
│   ├── apps.py               # App configuration
│   ├── forms.py              # Django forms
│   ├── models.py             # Database models
│   ├── tests.py              # App tests
│   ├── urls.py               # App URL routes
│   ├── views.py              # App views / business logic
│   │
│   ├── migrations/           # Database migrations
│   │   └── __init__.py
│   │
│   ├── templates/            # HTML templates
│   │   └── base/
│   │       ├── main.html
│   │       ├── navbar.html
│   │       ├── home.html
│   │       ├── room.html
│   │       ├── profile.html
│   │       ├── login_register.html
│   │       ├── room_form.html
│   │       └── delete.html
│   │
│   └── static/               # Static files (CSS, JS, Images)
│       ├── css/
│       │   └── style.css
│       ├── js/
│       │   └── main.js
│       └── images/
│           └── avatar.svg
│
├── media/                    # User-uploaded files (avatars)
│   └── avatars/
│
├── venv/                     # Virtual environment (not pushed to GitHub)
│
├── .gitignore                # Git ignored files
├── README.md                 # Project documentation
└── requirements.txt          # Project dependencies



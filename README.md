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
├── base/                         # Main Django application
│   ├── migrations/              # Database migrations
│   ├── static/                  # Static files (CSS, JS, images)
│   │   ├── css/
│   │   ├── js/
│   │   └── images/
│   ├── templates/               # HTML templates
│   │   └── base/
│   │       ├── home.html
│   │       ├── profile.html
│   │       ├── room.html
│   │       ├── login_register.html
│   │       ├── navbar.html
│   │       └── main.html
│   ├── admin.py                 # Admin site configuration
│   ├── apps.py                  # App configuration
│   ├── forms.py                 # Django forms
│   ├── models.py                # Database models
│   ├── urls.py                  # App URL routes
│   ├── views.py                 # View logic
│   └── __init__.py
│
├── studybud/                     # Django project settings
│   ├── __init__.py
│   ├── settings.py              # Project settings
│   ├── urls.py                  # Main URL configuration
│   ├── asgi.py
│   └── wsgi.py
│
├── media/                        # Uploaded media files (avatars)
├── env/                          # Virtual environment (ignored in Git)
├── .gitignore                    # Git ignore rules
├── requirements.txt              # Project dependencies
├── manage.py                     # Django management script
└── README.md                     # Project documentation




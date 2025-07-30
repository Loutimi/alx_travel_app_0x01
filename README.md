# 🌍 ALX Travel App

A Django-based travel booking platform that allows users to browse listings, book trips, and leave reviews. This project was built as part of the ALX Backend Specialization program to demonstrate proficiency in Django, REST APIs, Celery, and background task management.

---

## 🚀 Features

- User registration & authentication
- Create, browse, and manage travel listings
- Book listings and leave 1–5 star reviews
- Background tasks using Celery (e.g. sending confirmation emails)
- Environment variable management with `django-environ`

---

## 🏗 Tech Stack

- **Backend:** Django, Django REST Framework
- **Task Queue:** Celery with RabbitMQ or Redis (via `pika`)
- **Environment Management:** `django-environ`, `.env`
- **Fake Data Generation:** `Faker`
- **Database:** SQLite (default) or PostgreSQL

---

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/Loutimi/alx_travel_app_0x00.git
cd alx_travel_app_0x00

# Set up virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

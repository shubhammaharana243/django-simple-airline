# ✈️ Django Simple Airline

A flight management web application built with **Python and Django**. The application allows users to explore available flights, view flight details, and manage passengers associated with each flight.

## 🚀 Features

- View a list of available flights
- View individual flight details
- Display origin and destination airports
- View flight duration
- Display passengers associated with each flight
- Add passengers to flights using a selection form
- Navigate between the flight list and detail pages
- Store flight and passenger data using Django models

## 🛠️ Tech Stack

- **Backend:** Python, Django
- **Frontend:** HTML
- **Database:** SQLite
- **Version Control:** Git and GitHub

## 📁 Project Structure

```text
django-simple-airline/
├── airline/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
├── flights/
│   ├── migrations/
│   ├── templates/
│   │   └── flights/
│   │       ├── flight.html
│   │       ├── index.html
│   │       └── layout.html
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
├── .gitignore
├── manage.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/shubhammaharana243/django-simple-airline.git
cd django-simple-airline
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure environment variables

Create a `.env` file in the project root and configure the variables required by `settings.py`.

```env
DJANGO_SECRET_KEY=your-secret-key
DEBUG=True
ALLOWED_HOSTS=127.0.0.1,localhost
```

Generate your own secret key. Never publish your actual `.env` file.

### 5. Apply database migrations

```bash
python manage.py migrate
```

### 6. Run the development server

```bash
python manage.py runserver
```

Open your browser at:

http://127.0.0.1:8000/

## 🎯 Learning Objectives

This project helped me practice:

- Django models and database relationships
- URL routing and views
- Rendering dynamic data in HTML templates
- Django ORM and database migrations
- Handling form submissions
- Organizing a Django application into reusable components

## 🔮 Future Improvements

- Add user authentication
- Implement flight search and filtering
- Add flight booking functionality
- Improve the interface with responsive CSS
- Add automated tests
- Deploy the application online

## 👨‍💻 Author

**Shubham Maharana**

GitHub: [@shubhammaharana243](https://github.com/shubhammaharana243)

---

Thanks for checking out this project! Feedback and suggestions are welcome.

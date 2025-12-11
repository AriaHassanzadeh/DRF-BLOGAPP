# DRF-BLOGAPP

A simple and extensible Blog API built with Django and Django REST Framework, designed as a clean starter template for learning, experimenting, and building real-world REST APIs.


# 🚀 Features

Full CRUD API for blog posts

Django REST Framework serializers & viewsets

Token-based authentication with Simple JWT

Create / Delete / Edit / Read   for  Blogs and Users 

Clean project structure


# 📦 Tech Stack

# Python 3.x

# Django

# Django REST Framework (DRF)

# SQLite (default local DB)



DRF-BLOGAPP/
│── blog/                # Blog app (models, serializers, views, urls)
│── DRF/                 # Project settings, URLs, WSGI
│── venv/                # Virtual environment (not included in repo)
│── manage.py            # Django management file
└── requirements.txt     # Dependencies (create using pip freeze)



# 🔧 Installation & Setup


1. Clone the repository

git clone https://github.com/AriaHassanzadeh/DRF-BLOGAPP.git
cd DRF-BLOGAPP


2. Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate        # Linux / macOS
venv\Scripts\activate           # Windows


3. Install dependencies
pip install -r requirements.txt



# 📌 Apply Migrations

python manage.py migrate



# ▶️ Run the Development Server


python manage.py runserver

👉 http://127.0.0.1:8000/



# 📚 API Endpoints (Example)
Method	Endpoint	Description
GET	/api/posts/	List all posts
POST	/api/posts/	Create a new post
GET	/api/posts/<id>	Retrieve a post
PUT	/api/posts/<id>	Update a post
DELETE	/api/posts/<id>	Delete a post
(Adjust based on your URLs.)



# 🌐 Live Deployment:
Deployed on Render → https://drf-blogapp.onrender.com
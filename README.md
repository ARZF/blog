Blog Project
A simple blog application built with Django, showcasing the backend development process. This project is part of my learning journey as a backend developer, where I integrate databases, handle user authentication, and work with dynamic content rendering.


Features
User authentication (Login/Logout/Register)
Create, read, update, and delete (CRUD) blog posts
Dynamic content rendering using Django templates
Admin panel for blog management
Comment system for blog posts
Responsive design


Technologies Used
Django: Python-based web framework for backend development
SQLite: Database for data persistence
HTML/CSS: Frontend styling
Bootstrap: For responsive design


Setup
To run this project locally, follow these steps:
git clone https://github.com/ARZF/blog.git
cd blog
python -m venv env
source env/bin/activate   # On Windows, use `env\Scripts\activate`
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

Open your browser and go to http://127.0.0.1:8000 to view the blog.

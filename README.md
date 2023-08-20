# Django-blog

Welcome to **Django-blog** documentation. This document aims to provide an overview of the project, its features, setup instructions, and other essential information.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)

## Introduction

**Django-blog** is a social media/blog website built using Django, a popular Python web framework. It allows users to register, create posts/blogs, and interact with each other through the platform.

The project uses Django for the backend, Django Templates for rendering the frontend, and PostgreSQL as the database management system to store user and blog data.

[Checkout the application here](https://hidden-violet-6754.fly.dev/)

## Features

- User Registration: Users can create accounts on the platform, providing basic details.
- User Authentication: Secure user authentication and authorization mechanisms.
- Create Posts/Blogs: Registered users can create, edit, and delete their posts/blogs.
- User Profiles: Each user has a profile page displaying their information and posts.

## Installation

Follow these steps to set up the project locally:

1. **Clone the repository:**
- git clone https://github.com/v-pramod/django-blog.git
- cd django-blog

2. **Install Dependencies:**
- pip install -r requirements.txt

3. **Database Setup:**
- Create a PostgreSQL database for the project.
- Update the `DATABASES` settings in `settings.py` with your database information.

4. **Migrations:**
- python manage.py makemigrations
- python manage.py migrate

5. **Create Superuser:**
- python manage.py createsuperuser

6. **Run the Development Server:**
- python manage.py runserver

Access the application at `http://localhost:8000/` in your web browser.

## Usage

1. Register an account or log in with your existing credentials.
2. Explore the platform, view posts, and interact with other users.
3. Create your own posts/blogs from your profile dashboard.

## Technologies Used

- Django: Backend framework for building web applications using Python.
- PostgreSQL: Open-source relational database management system.
- Django Templates: Rendering frontend views in Django.
- HTML, CSS, JavaScript: Frontend technologies for creating user interfaces.

## Contributing

Contributions to the project are welcome! If you find a bug or want to add a new feature, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m "Add some feature"`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request describing your changes.

---

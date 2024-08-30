# Django Rest Framework Demo Blog
=====================================

A demo blog project built using Django Rest Framework, featuring JWT authentication and API endpoints for blog posts.

## Table of Contents

* [Getting Started](#getting-started)
* [Features](#features)
* [API Endpoints](#api-endpoints)
* [Authentication](#authentication)
* [Admin Interface](#admin-interface)
* [Requirements](#requirements)

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository: `git clone https://github.com/salmanh/drf_blog.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the migrations: `python manage.py migrate`
4. Start the development server: `python manage.py runserver`

## Features

* JWT authentication for secure login
* API endpoints for creating, reading, updating, and deleting blog posts
* Admin interface for managing blog posts and users

## API Endpoints

### Blog Posts

* `GET /api/blog/`: Retrieve a list of all blog posts
* `POST /api/blog/`: Create a new blog post
* `GET /api/blog/{id}/`: Retrieve a single blog post by ID
* `PUT /api/blog/{id}/`: Update a single blog post by ID
* `DELETE /api/blog/{id}/`: Delete a single blog post by ID

### Authentication

* `POST /auth/token/`: Obtain a JWT token for authentication
* `POST /auth/token/refresh/`: Refresh a JWT token
* `POST /auth/token/verify/`: Verify a JWT token

## Admin Interface

The admin interface is available at `http://localhost:8000/admin/`.
You can log in using the credentials you created during the setup process.
or if you can use the db.sqlite3 then the default admin is 
`salman.humdullah@gmail.com` or `salmanh` with password `Abc123()`

## Requirements

* Python 3.8+
* Django 3.2+
* Django Rest Framework 3.12+
* PyJWT 2.3+

Note: This is just a basic `README.md` file, and you may want to add more details or sections depending on your project's specific needs.
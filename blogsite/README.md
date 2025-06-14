# Django Blogsite

A simple Django-powered blog application where users can create, edit, and delete posts with optional images. Includes user authentication (signup, login, logout).

## Features
- User registration and authentication
- Create, edit, and delete blog posts
- Upload and display images with posts
- List and detail views for posts

## Setup Instructions

1. **Clone the repository** (if applicable):
   ```sh
   git clone <repo-url>
   cd blogsite
   ```

2. **Install dependencies:**
   ```sh
   pip install django
   ```

3. **Apply migrations:**
   ```sh
   python manage.py makemigrations
   python manage.py migrate
   ```

4. **Create a superuser (optional):**
   ```sh
   python manage.py createsuperuser
   ```

5. **Run the development server:**
   ```sh
   python manage.py runserver
   ```

6. **Access the site:**
   Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser.

## Media Files
Uploaded images are stored in the `media/` directory. In development, Django serves these files automatically when `DEBUG=True`.

## Directory Structure
- `blog/` - Main app with models, views, templates
- `blogsite/` - Project settings and URLs
- `media/` - Uploaded images

## License
MIT

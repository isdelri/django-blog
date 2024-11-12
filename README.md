# Django Blog Project

## Introduction
This project was created as part of the lesson "Using APIs & Getting Started with Django." The purpose of this lesson was to introduce Django, a powerful Python web framework, and teach the basics of setting up a Django project, creating apps, and working with Git for version control.

## Project Structure
The project is structured as follows:
- `mysite/`: The main Django project directory containing configuration files.
  - `settings.py`: Configures project settings, including installed apps, middleware, database, and templates.
  - `urls.py`: Defines the URL patterns for the project, linking paths to different views.
  - `wsgi.py`: Used to serve the application in a production environment.
- `polling/`: A Django app created within the project to manage polling functionality.
  - `models.py`: Defines the data models for the app.
  - `views.py`: Contains the views for displaying polls.
  - `urls.py`: Maps URLs specific to the polling app.
  - `templates/`: Directory containing HTML templates for polling views.
- `blogging/`: Another Django app created to manage blog posts.
  - `models.py`: Defines data models for blog posts.
  - `views.py`: Contains the views for displaying blog posts.
  - `urls.py`: Maps URLs specific to the blogging app.
  - `templates/`: Directory containing HTML templates for blog views.

## Setup Instructions
To run this project, you’ll need to follow these steps:

1. **Clone the Repository**
   ```bash
   git clone [your repository link]
   cd django-blog
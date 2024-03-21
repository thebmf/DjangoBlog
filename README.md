# Anime Blog

## Overview
This project is a blog which was created for practicing Django, designed and implemented using HTML, CSS. It showcases my skills in front-end development and my proficiency in utilizing Django for backend operations.

## Features
- **Home Page**: Features a vibrant collection of anime characters, providing an immersive experience for anime enthusiasts.
- **Blog Posts**: The blog supports multiple posts, each with a unique identifier and a 'Read More' link for detailed viewing.
- **Responsive Design**: Crafted to provide a seamless experience across various devices and screen sizes.

## Technical Aspects
- **Frontend**: The frontend is built with HTML and CSS, ensuring a visually appealing layout and design.
- **Backend**: Django is used for the backend, managing the blog's content and interactions with ease.
- **Database Integration**: Posts are stored and managed via Django's ORM, interfacing with a SQLite database.

## Local Development
To set up this project locally:
```bash
   git clone https://github.com/<your-github-username>/anime-blog.git
   cd anime-blog
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py collectstatic
python manage.py runserver
```


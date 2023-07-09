# Django Landmarks Blog

This is a Django-based web application for a personal landmark blog. The blog allows an admin to post landmarks, which can be viewed by users. Users can explore the places, add them to a "Read Later" list, delete places from the list, view detailed information about each place, leave comments, and manage their own Read Later list.<br>


<img src="https://github.com/maryamalsadat-tabatabaei/Django-Landmarks-Blog/assets/87692864/bac5ed7e-22f7-429f-9c41-00755dde9885" alt="Stored Posts Page" width="30%" height="auto">
<img src="https://github.com/maryamalsadat-tabatabaei/Django-Landmarks-Blog/assets/87692864/92972c82-d48b-462c-a1e7-341ae1890543" alt="Single Post Page-with commends" width="30%" height="auto">
<img src="https://github.com/maryamalsadat-tabatabaei/Django-Landmarks-Blog/assets/87692864/a6c53d58-459e-48a9-a0fa-91180022066d" alt="Single Post Page" width="30%" height="auto">
<img src="https://github.com/maryamalsadat-tabatabaei/Django-Landmarks-Blog/assets/87692864/1c1d482b-4423-41b0-aaf8-a7aff22338be" alt="Stored Posts Page" width="30%" height="auto">
<img src="https://github.com/maryamalsadat-tabatabaei/Django-Landmarks-Blog/assets/87692864/0b93c807-2b8d-40fa-8375-2fd10ff9f923" alt="Posts List Page" width="30%" height="auto">
<img src="https://github.com/maryamalsadat-tabatabaei/Django-Landmarks-Blog/assets/87692864/e3e4187d-3f25-48c2-ae1e-7df550c93005" alt="Home Page" width="30%" height="auto">


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Background](#project-background)
- [Features](#features)
- [Dependencies](#dependencies)

## Installation

1. Clone the repository: `git clone https://github.com/maryamalsadat-tabatabaei/django-project.git`
2. Navigate to the project directory: `cd django-project`
3. Install dependencies: `pip install django`

## Usage

To run the project, use the following command:

<pre><code>python manage.py runserver</code></pre> Then Open a web browser and visit http://localhost:8000 to access the blog.

## Features

- Starting Page: The starting page of the blog.
  - URL: "" (empty string)
  - View: views.StartingPageView
  - Name: "starting-page"
- All Posts: Displays all the landmarks/posts.
  - URL: "posts"
  - View: views.AllPostView
  - Name: "posts"
- Post Detail Page: Shows detailed information about a specific landmark/post.

  - URL: "posts/<slug:slug>"
  - View: views.SinglePostView
  - Name: "post-detail-page"
- Read Later: Allows users to add landmarks/posts to their Read Later list.

  - URL: "read-later"
  - View: views.ReadLaterView
  - Name: "read-later"
## Dependencies
The application is built using Python and utilizes SQLite for data management and templates for rendering views. The following dependencies are required to run the Django Landmarks Blog:

- Django
- SQLite

## Project Background

This project is based on Maximilian Schwarzmüller's tutorial on Udemy Python Django - The Practical Guide. I have made some modifications to the original project and I built upon that foundation to extend the project's functionality and address specific requirements. However, the course inspired the core concept and initial implementation and the work of the original author.

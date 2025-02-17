# flask-appFlask Web Application - Hello Flask Documentation

Overview

This is a simple Flask web application I've created with pages for Home, About, Contact, and Careers. The project demonstrates Flask routing, template rendering using Jinja2, and styling with Bootstrap.

Setup Instructions

Install Python 3.x: I made sure to install Python from python.org.

Install Flask: In my terminal, I ran the following command:

pip install flask

Create Project Folder: I created a directory called flask-app (or whatever I chose) and navigated to it:


mkdir flask-app
cd flask-app

Create Flask Application: Inside the project folder, I created the app.py file to define my routes for Home, About, Contact, and Careers.

Templates Folder: I made a templates/ folder and placed my HTML files inside (such as index.html, about.html, etc.).

Static Folder: I created a static/ folder for my Bootstrap (or custom) CSS files. I included the Bootstrap CDN in my HTML files for styling.

Run the Application: I ran the Flask development server with:
python app.py

I could now access the app at http://127.0.0.1:5000.

Project Structure

flask-app/
│
├── app.py                  # Main Flask application
├── templates/              # HTML files (index.html, about.html, etc.)
└── static/                 # Static files (CSS, JS)
    └── css/
        └── styles.css      # CSS styles (using Bootstrap)

Libraries Used

Flask: The micro web framework I used to build the app.
Bootstrap: The CSS framework I used to style the pages, integrated via a CDN in my HTML files.

Conclusion

This project is a basic Flask web app styled with Bootstrap. It shows how to set up routes, templates, and static files, with responsive design provided by Bootstrap. I can easily extend this app by adding more features, pages, or customizing the CSS further.
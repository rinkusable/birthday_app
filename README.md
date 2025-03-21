A Django web application designed to manage employee birthday details, display upcoming birthdays, and track gift delivery status with enhanced user interactivity.

📋 Features
Displays a list of employees with details like Name, Work Location, Department, and Birthdate.
Provides a 'Present Delivered' button to track gift delivery for the current year.
Implements AJAX-based updates for seamless gift status changes without page refresh.
Supports search, filter, and sort functionalities for improved user experience.
Optimized for mobile browsers to ensure accessibility on various devices.

Project structure :

.
├── birthdays
│   ├── migrations
│   ├── static
│   ├── templates
│   ├── urls.py
│   ├── views.py
│   ├── models.py
│   └── forms.py
├── birthday_app
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
├── templates
│   └── staff_list.html
├── manage.py
└── requirements.txt

💻 Technologies Used
Django 5.1.7
SQL Server
HTML/CSS/JavaScript
AJAX for real-time updates



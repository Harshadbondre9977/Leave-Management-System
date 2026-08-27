# Leave Management System

A web-based Leave Management System built with Django to simplify the process of applying for, reviewing, and managing employee leave requests.

The system provides different access levels for **Admin, HR, Manager, and Employee**, with features designed according to each role.

## Features

* User authentication and login
* Role-based access for Admin, HR, Manager, and Employee
* Employees can apply for leave
* Managers can review leave requests
* Leave requests can be approved or rejected
* Employees can view their leave history
* Dashboard for managing leave information
* Responsive and simple user interface

## User Roles

### Employee

* Login to the system
* Apply for leave
* Check leave status
* View previous leave requests

### Manager

* View employee leave requests
* Approve or reject leave applications
* Manage leave requests for their team

### HR / Admin

* Manage users and employee information
* Monitor leave requests
* View overall leave information
* Manage the system

## Technology Stack

**Backend**

* Python
* Django

**Frontend**

* HTML
* CSS
* JavaScript

**Database**

* SQLite / Django-supported database

## Project Structure

```text
Leave-Management-System/
│
├── src/
│   ├── ...
│   └── ...
│
├── static_cdn/
│   └── media_root/
│       └── profiles/
│
├── .gitignore
├── README.md
└── manage.py
```

> The exact structure may vary depending on the Django apps and configuration in the project.

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/Harshadbondre9977/Leave-Management-System.git
```

### 2. Open the project folder

```bash
cd Leave-Management-System
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

**macOS / Linux:**

```bash
source venv/bin/activate
```

### 5. Install dependencies

If the project contains a `requirements.txt` file:

```bash
pip install -r requirements.txt
```

If it doesn't contain one, install Django:

```bash
pip install django
```

### 6. Run database migrations

```bash
python manage.py migrate
```

### 7. Start the development server

```bash
python manage.py runserver
```

Open the application in your browser at:

```text
http://127.0.0.1:8000/
```

## Screenshots

Add screenshots of the main pages here.

For example:

* Login page
* Employee dashboard
* Leave application page
* Manager dashboard
* Leave approval page
* Admin/HR dashboard

```markdown
![Login Page](screenshots/login.png)

![Dashboard](screenshots/dashboard.png)

![Leave Management](screenshots/leave-management.png)
```

## What I Worked On

This repository is based on an existing Leave Management System project.

I worked with the project codebase and focused on understanding, improving, and working with the Django application, including its user interface and leave-management functionality.

The repository demonstrates my practical experience with:

* Django project structure
* Python
* HTML and CSS
* JavaScript
* User authentication
* Role-based access
* CRUD operations
* Database integration
* Web application development

## Learning Outcomes

Through this project, I gained practical experience in developing a web application using Django.

I learned how different user roles can be handled in a single application and how leave requests can be created, reviewed, updated, and managed through a web interface.

## Future Improvements

Some features that could be added in the future:

* Email notifications for leave requests
* Leave balance management
* Advanced HR reports
* Search and filtering
* Attendance integration
* Password reset through email
* Deployment to a cloud platform

## Project Status

**Status:** Completed / Learning Project

The project can be further improved with additional features and UI enhancements.

## Credits

This project is based on the original **Leave Management System** repository by **Haresh-Dhasade**.

Original repository:

https://github.com/Haresh-Dhasade/Leave-Management-System

Changes and improvements made in this fork are maintained in this repository.

## Author

**Harshad Bondre**

GitHub: `@Harshadbondre9977`

## License

This project is intended for learning and portfolio purposes.

Please refer to the original repository and its license before redistributing or presenting modified versions of the project as your own.

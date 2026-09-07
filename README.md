# MedConnect – Healthcare Appointment Booking System

MedConnect is a full-stack healthcare appointment booking web application developed using Django, HTML, CSS, JavaScript, and SQLite.

The application provides a simple and responsive platform where users can register, log in, explore doctors, view doctor profiles, book appointments, and submit contact messages.

---

## 📌 Features

- User Registration
- User Login and Logout
- User Authentication using Django
- Doctor Directory
- Doctor Profile
- Online Appointment Booking
- Department Selection
- Doctor Selection
- Appointment Date and Time Selection
- Appointment Reason
- Contact Form
- Responsive User Interface
- SQLite Database
- Authentication-protected pages

---

## 🛠️ Technologies Used

- **Python**
- **Django**
- **HTML5**
- **CSS3**
- **JavaScript**
- **SQLite**

---

## 📂 Project Structure

```text
HEALTHCARE-APPOINTMENT-BOOKING-SYSTEM/
│
├── accounts/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── medconnect/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── all_doctors.html
│   ├── doctor_profile.html
│   ├── book_appointment.html
│   ├── contact.html
│   └── ...
│
├── .gitignore
├── db.sqlite3
├── manage.py
└── README.md
```
## 🔄 Application Workflow
## 1. User Registration

New users can create an account by providing their username, email, and password.

## 2. User Login

Registered users can log in using their username and password.

Django's built-in authentication system is used to authenticate users.

## 3. Home Page

After successful authentication, users can access the main MedConnect application.

## 4. Doctors

Users can browse the available doctors and view their profiles.

## 5. Appointment Booking

Users can book an appointment by providing:

- Full Name
- Email
- Phone Number
- Department
- Doctor
- Appointment Date
- Appointment Time
- Reason for Appointment

The appointment details are stored in the database.

## 6. Contact

Users can submit a message through the contact form by providing:

- Name
- Email
- Phone Number
- Subject
- Message
🗄️ Database

The application uses SQLite as its database.

## Appointment

The appointment information includes:

- Full Name
- Email
- Phone Number
- Department
- Doctor
- Appointment Date
- Appointment Time
- Reason
- Contact

The contact information includes:

Name
Email
Phone Number
Subject
Message
Created Date and Time
🔐 Authentication

## MedConnect uses Django's built-in authentication system.

The application provides:

User Registration
User Login
User Logout
Login-protected pages

Users must be authenticated to access the main application features.

## ⚙️ Installation
Step 1: Clone the Repository
git clone https://github.com/SimranNadaf2608/HEALTHCARE-APPOINTMENT-BOOKING-SYSTEM.git
Step 2: Navigate to the Project
cd HEALTHCARE-APPOINTMENT-BOOKING-SYSTEM
Step 3: Create a Virtual Environment

## For Windows:
```
python -m venv .venv

Activate the virtual environment:

.venv\Scripts\activate
```
## For macOS/Linux:
```
python3 -m venv .venv
source .venv/bin/activate
```
Step 4: Install Django
```
pip install django
```
Step 5: Apply Migrations
```
python manage.py migrate
```
Step 6: Run the Application
```
python manage.py runserver
```

The application will be available at:

http://127.0.0.1:8000/

## 👨‍💻 Django Management Commands
Create Migrations
```
python manage.py makemigrations
```
Apply Migrations
```
python manage.py migrate
```
Create Admin User
```
python manage.py createsuperuser
```
Start Development Server
```
python manage.py runserver
```
🔑 Admin Panel

The Django admin panel can be accessed at:

http://127.0.0.1:8000/admin/

Create an administrator account using:

python manage.py createsuperuser
🚀 Future Enhancements
Doctor availability management
Appointment availability checking
Appointment cancellation
Appointment rescheduling
Patient appointment history
Doctor dashboard
Admin dashboard
Email appointment confirmation
SMS notifications
Online consultation
Automated testing
Production deployment
👩‍💻 Author

Simran Nadaf

GitHub:

https://github.com/SimranNadaf2608

📄 License

This project is developed for educational and portfolio purposes.

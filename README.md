# Booktique
A simple project based on Library Management System that uses Python with Django Web Framework. <br/>
Booktique focuses mainly on dealing with issuing books and records. Also, the system displays all the available students with their issued books. In addition, the system allows managing books by entering a title, author, ISBN, and category. This project has two login access: Student and Admin. <br/> 
In an overview of this web application, a student can simply register and start using it. Here, the system displays all the issued books for the student. The system limits other access to the student account as they can only view issued book records which displays expiry dates, total fine charge, and others.

# Features
- Student Panel
- Admin Panel
- Add Books
- List Books
- Issue Books
- Auto Fine Charge
- View Issued Books
- View Available Students

# Instructions on How to Run
- Create a virtual environment: python -m venv .venv
- Activate the virtual environment: . .venv/bin/activate
- Install Django: pip install django
- Install the Requirements: pip install -r requirements.txt
- Make database migrations: python manage.py makemigrations
- Apply migrations to the database: python manage.py migrate
- And finally, run the application: python manage.py runserver

For Admin Account, please create one with superuser!

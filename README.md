# RentIt
RentIt is a car rental platform built mainly with Django framework and MySQL

**Pre-requirements :**

Python installed in the desktop<br />
XAMPP installed in the desktop

**Steps :**

1. Start 'Apache' and 'MySQL' in XAMPP
2. Create a database called 'ocrsdjango' using MySQL through cmd.
3. Go to the project folder. Hold shift and right click on an empty space.
4. Choose 'Open command prompt/Powershell here'
5. Install virtualenv by typing the code : py -m pip install --user virtualenv
6. Create a virtual environment 'env' by typing the code : py -m venv env
7. Activate the environment by typing the code : .\env\Scripts\activate
8. Install the requirements for the project : pip install -r requirements.txt
9. Check for migrations in the project : python manage.py makemigrations
10. Migrate all the migrations : python manage.py migrate
11. Initiate a server to run the project : python manage.py runserver
12. Copy the url provided in the command/powershell window and paste it in a browser(Use incognito to prevent caches being stored)

To create admin login for 'Django admin panel', type : python manage.py createsuperuser <br/>
The admin panel can be accessed through URL/admin (Eg.: http://127.0.0.1:8000/admin )

**Recommended versions :**

Python 3.10.2 <br />
Django 3.2.9 <br />
mysqlclient 2.1.0


# Setting Up the Environment

## step 1:Navigate to the Project folder.
For my case the project was in: cd "C:\Users\thuku\Documents\2ND YEAR\2.2\Application programming for the internet\cat2\ecommerce"

## step 2: Set Up a Virtual Environment
### creating:
python -m venv .venv
### Activating:
.\.venv\Scripts\activate

## step 3:Install Project Dependencies

## step 4: Set up the database
python manage.py migrate

## step 5: Create a Superuser/administrator
python manage.py createsuperuser

## step 6: Run the development Server
python manage.py runserver

**Once one has finished all  this steps, they can now access the application from a browser of their choice using:
_http://127.0.0.1:8000/_
and the admin interface using: 
_http://127.0.0.1:8000/admin/_**



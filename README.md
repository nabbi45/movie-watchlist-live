# movie-watchlist-live
A movie watchlist website with CRUD operations and Authentication in django

Steps to run the app:

install django (you need python 3 installed on your system to install django) using pip install django

Now clone the project

Create a dummy project and copy the secret key from settings.py and replace '#########..' in the settings.py of the project.

Now migrate to prepare database using command - python manage.py makemigrations python manage.py migrate

Now create a superuser using python manage.py createsuperuser

Now run the app using python manage.py runserver

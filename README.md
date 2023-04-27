# exspan-and-income-managemen-system-django
<!-- create env -->
python3 -m venv env

<!-- activate env -->
source env/bin/activate

<!-- install django -->
pip install django || pip3 install django

<!-- use command to install project -->
django-admin startproject blog_project .

<!-- use command to check other command that you can use on django -->
python manage.py

<!-- create main folder -->
python manage.py startapp main

<!-- when you update something you need to migrate -->
python manage.py makemigrations

<!-- use this command to create admin user -->

python manage.py createsuperuser

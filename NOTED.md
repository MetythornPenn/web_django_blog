python -m venv env
pip install django
django-admin startproject blogapp .
python manage.py runserver
python manage.py startapp blogapp

python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser: (username: xyber | email: xyberpunk@gmail.com | pw: Xyberpunk.321)
web: gunicorn -b "0.0.0.0:$port" -w 3 myproject.wsgi
release: python manage.py migrate
web: gunicorn config.wsgi --log-file -
web: python manage.py runserver 0.0.0.0:$PORT
release: python manage.py migrate

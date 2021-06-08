release: python manage.py migrate
web: gunicorn  puppy_store.wsgi --workers=2 --timeout 120
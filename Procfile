release: python manage.py migrate && python manage.py loaddata initial_data.yaml

web: gunicorn --threads 8 app.wsgi --log-file -

web: gunicorn django_website.wsgi


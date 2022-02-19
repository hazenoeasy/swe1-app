release: python manage.py migrate
loaddata: python manage.py loaddata data.json
web: gunicorn swe1App.wsgi
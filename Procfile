release: python manage.py migrate --noinput
web: gunicorn config.wsgi:application --timeout 300

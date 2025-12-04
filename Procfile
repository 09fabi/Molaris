web: cd gestion_clinica && python manage.py migrate --noinput && python manage.py collectstatic --noinput && gunicorn gestion_clinica.wsgi:application --bind 0.0.0.0:$PORT --workers 2 --timeout 120


release: sh -c 'python manage.py migrate && python manage.py loaddata initial_wishlist_data.json'
release: python manage.py migrate
web: gunicorn project_django.wsgi --log-file -
Enable environment:
`workon rangoenv`

Disable environment:
`deactivate`

Run server:
`python manage.py runserver`

Register the changes to models:
`python manage.py makemigrations rango`

Check SQL for migration:
`python manage.py sqlmigrate rango 0001`

Apply migrations:
`python manage.py migrate`

Access shell:
`python manage.py shell`

Reset DB:
delete db.sqlite3
`python manage.py makemigrations rango`
`python manage.py migrate`
`python manage.py createsuperuser`
`python populate_rango.py`

Run tests:
`python manage.py test rango.tests_chapter1`

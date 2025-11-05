# python_practice

# start app
server:
`python manage.py runserver`

# database

This command takes migration names and returns SQL:
`python manage.py sqlmigrate polls 0001`

This command is for is you made some changes to your models and that you’d like the changes to be stored as a migration:
`python manage.py makemigrations polls`

This command for creating models in your database:
`python manage.py migrate`

Python shell:
`python manage.py shell`

# create admin user

 `python manage.py createsuperuser`


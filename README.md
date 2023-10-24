It is a basic working django-cms template. Followed the quick start guide of django-cms documentation. Pull the repo and use. Struggled many days to fix the plugin conflicts. Finally consolidated working plugin versions. Its very useful to quick start the django-cms sites

# Steps to use the repo

1. Clone the repo
2. Remove project.db file from the root directory. Because its default sqlite3 db, also migrated the objects
3. Configure your database in settings.py
4. Run the migrations (python manage.py migrate)
5. Run the server (python manage.py runserver)
6. Test the localhost URL http://localhost:8000/

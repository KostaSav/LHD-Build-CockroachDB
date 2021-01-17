# lhd-build-cockroachdb

This simple application follows the "hello, world" [tutorial](https://www.cockroachlabs.com/docs/cockroachcloud/build-a-python-app-with-cockroachdb-django.html).

## Quick Start

0. Set up virtual environment

   ```
   python -m venv env
   env\Scripts\activate (Windows)
   source env/bin/activate (Mac)
   ```

1. Install dependencies (django etc)

   ```
   python -m pip install django
   pip install psycopg2-binary
   ```

   > Note: Might need to upgrade pip if getting error installing psycopg2-binary

   ```
   python -m pip install --upgrade pip
   ```

   Then, continue installing depencencies:

   ```
   python -m pip install django-cockroachdb
   pip install python-dotenv
   ```

2. Start application

   ```
   python manage.py runserver 0.0.0.0:8000
   ```

   or another port if 8000 is used by another application.

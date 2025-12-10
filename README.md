# rick-and-morty

### How to run:

- Create venv: `Python -m venv venv`
- Activate it: `source venv/bin/activate`
- Install requirements: `pip install -r requirements.txt`
- Create new Postgres DB & User
- Copy .env.sample -> .env and populate with all required data
- Run migrations: `python manage.py migrate`
- Run celery for tasks handling:
- Run celery beat for task scheduling
- Create Schedule for running sync in DB
- Run app: `python manage.py runserver`

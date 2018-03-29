# django-template

### How to quick start new project:
    1. virtualenv -p /usr/bin/python3 venv3
    2. git clone git@github.com:mmasterenko/django-template.git
    3. cd django-template
    4. mv .env.example .env
    5. vim .env  <--- set environ variables
    6. mv requirements.txt.example requirements.txt

    7. add the snippet to the end of venv3/bin/activate

    ENV_FILE='/path/to/.env'
    export $(cat $ENV_FILE | xargs)

    8. source venv3/bin/activate
    9. pip install -r requirements.txt
    10. ./manage.py migrate
    11. ./manage.py runserver


### DATABASE_URL example

    DATABASE_URL='postgres://user:password@localhost/dbname'

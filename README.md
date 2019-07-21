# How to run

## Creating new programming environment
```
virtualenv -p python3 venv
source venv/bin/activate
pip install -r requirements.txt
```

## Start with hot loader
```
FLASK_APP=run.py FLASK_DEBUG=1 flask run
```

# Migrate

## Create migrations
```
python manage.py db init
```

## Migrate
```
python manage.py db migrate
```

## Update database
```
python manage.py db upgrade
```
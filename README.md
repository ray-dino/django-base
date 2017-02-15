# Django Project Boilerplate

* Current Django version: 1.10
* Requires Python 3
* Requires PostgreSQL
* Update this README when used on other projects

## Setup

- Install requirements 
```
pip install -r requirements.txt
```
- Update configuration file
```
1. Open config-sample.py.
2. Fill in the values.
3. Save as config.py
```
- Sync database
```
python manage.py syncdb
```
- Run migrations (if any)
```
python manage.py migrate
```
- Create superuser 
```
python manage.py createsuperuser
```

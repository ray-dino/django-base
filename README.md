# Django Project Boilerplate

* Requires PostgreSQL
* Update this README when used on other projects

## Setup

- Install requirements 
```
pip install -r requirements.txt
```
- Set environment variables:
```
DB_NAME=XXXXXXXXXXXXXXX
DB_USER=XXXXXXXXXXXXXXX
DB_PASSWORD=XXXXXXXXXXX
DB_HOST=XXXXXXXXXXXXXXX [default:127.0.0.1]
DB_PORT=XXXXXXXXXXXXXXX [default:5432]
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
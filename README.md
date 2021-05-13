```sh
 django-admin startproject admin
 cd admin
 python3 manage.py runserver
```

## Get the shell inside the docker-compose
```sh
docker-compose exec backend sh
```

> python manage.py startapp products

## Migrations
```sh
python manage.py makemigrations
python manage.py migrate
```

### Way to Go
1. models.py
2. serializers.py
3. views.py
4. urls.py
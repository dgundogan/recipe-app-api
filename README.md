# recipe-app-api
Recepi app api source code.

## Docker build
docker build .

## Docker compose build
docker-compose build

## Create a django project.
docker-compose run app sh -c "django-admin.py startproject app ."

## Run Test
docker-compose run app sh -c "python manage.py test

docker-compose run app sh -c "python manage.py  startapp core"

docker-compose run app sh -c "python manage.py makemigrations core"

### Test & Lint
docker-compose run app sh -c "python manage.py test && flake8"
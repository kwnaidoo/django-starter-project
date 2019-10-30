## README

Simply run `docker-compose up -d`

Then visit: http://127.0.0.1:8000/

You can then run any "manage.py" command by doing the following:

`docker-compose exec web python manage.py`

Example commands you can run: 

`docker-compose exec web python manage.py migrate`

`docker-compose exec web python manage.py createsuperuser`


#### To take down
docker-compose down --remove-orphans

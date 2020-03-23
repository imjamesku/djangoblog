# Setup
1. Run the containers
`docker-compose up -d`

2. Log into the django container `docker exec -it djangoblog_web_1 bash`

3. Run the migrations `python manage.py migrate`

4. Create a superuser `python manage.py createsuperuser --username=<username> --email=<your email>`

5. Open in browser at localhost:8000 and login
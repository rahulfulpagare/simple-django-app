git clone https://github.com/rahulfulpagare/simple-django-app.git

cd simple-django-app

docker build -t simple-django-app .

docker run -d -p 8000:8000 --name django-app simple-django-app:latest

http://localhost:8000

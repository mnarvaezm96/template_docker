FROM python:3.10
 
WORKDIR /usr/src/app

RUN pip install django

RUN django-admin startproject prueba_django

EXPOSE 8000

CMD ["python", "/usr/src/app/manage.py", "runserver", "0.0.0.0:8000"]

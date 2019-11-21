FROM python:3-onbuild
COPY . /usr/src/myapp
WORKDIR /usr/src/myapp
RUN pip install -r requirements.txt
WORKDIR /usr/src/myapp/proyectoso
RUN ls
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]

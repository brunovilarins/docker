FROM python

VOLUME /root

WORKDIR /root

COPY ./application/ /

RUN pip install -r /requirements.txt

#EXPOSE 8000

#CMD django-admin startproject myapp . || \
#CMD  gunicorn --bind 0.0.0.0:8000 --reload --workers 2 --timeout 900 prj1.wsgi:application




#FROM alpine

# Initialize
#RUN mkdir -p /data/web
#WORKDIR /data/web
#COPY requirements.txt /data/web/

# Setup
#RUN apk update
#RUN apk upgrade
#RUN apk add --update libxml2 libxml2-dev python3 python3-dev postgresql-client postgresql-dev build-base gettext
#RUN pip3 install --upgrade pip
#RUN pip3 install -r requirements.txt
#RUN python3 manage.py makemigrations
#RUN python3 manage.py migrate
#RUN python3 manage.py collectstatic --noinput

# Clean
#RUN apk del -r python3-dev postgresql

# Prepare
#COPY . /data/web/
#RUN mkdir -p static/admin




FROM python:3.7.3-alpine3.8
RUN apk add --no-cache mariadb-dev build-base
ADD requirements.txt /
RUN pip install -r /requirements.txt
WORKDIR /code

FROM python:3.9.10-alpine

WORKDIR /nginx_test

COPY requirements.txt /nginx_test/

RUN pip install --upgrade pip
RUN pip install -r requirements.txt

COPY . /nginx_test
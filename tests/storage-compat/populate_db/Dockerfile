FROM python:3.14.0rc1-alpine

WORKDIR /

COPY requirements-freeze.txt /

COPY populate_db.py /

RUN pip install -r requirements-freeze.txt

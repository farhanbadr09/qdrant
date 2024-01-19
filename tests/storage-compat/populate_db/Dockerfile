FROM python:3.13.0a3-alpine

WORKDIR /

COPY requirements-freeze.txt /

COPY populate_db.py /

RUN pip install -r requirements-freeze.txt

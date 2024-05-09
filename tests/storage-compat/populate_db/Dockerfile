FROM python:3.13.0b1-alpine

WORKDIR /

COPY requirements-freeze.txt /

COPY populate_db.py /

RUN pip install -r requirements-freeze.txt

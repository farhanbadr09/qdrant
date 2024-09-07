FROM python:3.12.0a1-alpine

WORKDIR /

COPY requirements-freeze.txt /

COPY populate_db.py /

RUN pip install -r requirements-freeze.txt

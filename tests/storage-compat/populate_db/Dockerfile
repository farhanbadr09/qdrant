FROM python:3.12.3-alpine

WORKDIR /

COPY requirements-freeze.txt /

COPY populate_db.py /

RUN pip install -r requirements-freeze.txt

FROM python:3.9-slim

WORKDIR /usr/src/app
ENV FLASK_APP=app

COPY requirements.txt ${PWD}

RUN pip install --upgrade pip
RUN pip install -r requirements.txt
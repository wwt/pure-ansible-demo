FROM python:3.9.2-slim-buster
LABEL maintainer="Bob Longmore" email="bob.longmore@wwt.com"

RUN apt update && apt -y install git
RUN pip install --upgrade pip

#install requirments through pip
ADD requirements.txt .
RUN pip install -r requirements.txt

#install galaxy requirements
ADD requirements.yml .
RUN ansible-galaxy install -r requirements.yml

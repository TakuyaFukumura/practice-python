FROM python:3.12.1-bullseye

RUN adduser takuya-fukumura
USER takuya-fukumura
WORKDIR /home/takuya-fukumura

RUN git clone https://github.com/TakuyaFukumura/practice-python.git

RUN python -m pip install Django
RUN django-admin startproject mysite

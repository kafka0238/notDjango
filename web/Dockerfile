FROM python:3.6
ENV PYTHONUNBUFFERED 1
RUN mkdir /notDjango
WORKDIR /notDjango
ADD requirements.txt /notDjango/
RUN pip install --upgrade pip && pip install -r requirements.txt
ADD . /notDjango/
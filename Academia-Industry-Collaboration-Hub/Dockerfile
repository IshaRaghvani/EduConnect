FROM python:3.8
WORKDIR /usr/src/app

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

RUN python3 -m pip install --upgrade pip
COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .
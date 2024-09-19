FROM python:3.7.7

WORKDIR /app

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONBUFFERED 1

ENV PYTHONPATH="/app:/app/users"

COPY users/requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

FROM python:3.7.7

WORKDIR /app

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONBUFFERED 1

ENV PYTHONPATH="/app:/app/orders"

COPY orders/requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

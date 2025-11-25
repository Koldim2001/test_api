FROM python:3.11-slim

WORKDIR /app

RUN apt-get update

# Сначала копируем только requirements.txt и устанавливаем зависимости
COPY ./titanic-api/requirements.txt /app
RUN pip3 install -r requirements.txt

# Затем копируем остальной код
COPY ./titanic-api /app

CMD ["python3", "app_api.py"]

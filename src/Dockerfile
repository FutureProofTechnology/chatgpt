FROM python:3.9

WORKDIR /app

COPY requirements/* requirements/
RUN pip install --upgrade pip
RUN pip install --no-cache-dir -r requirements/dev.txt

COPY . .

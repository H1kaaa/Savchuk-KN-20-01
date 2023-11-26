# Інструкція по Запуску

## Білд Docker Image
docker build -t web-server .

## Запуск Docker Container
docker run -d -p 5000:5000 web-server

## Перевірка
Перейдіть за адресою http://localhost:5000 для перевірки додатку.

## Задание №1 Docker  
### 1. Собрать образ из Dockerfile:  
*docker build -t content-nginx*  
  
### 2. Сщздать и запустить контейнер:
*docker run --name some-nginx -d -t 8080:80 content-nginx*
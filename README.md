# test_api
API взаимодействие с моделью



Запустим сервис titanic-service:
```
docker build -t titanic-service:latest .   

docker run -d --name titanic-service -p 500:5000 titanic-service:latest
```
---
Итоговый вид проекта можно увидеть в данной ветке репозитория - [ссылка](https://github.com/Koldim2001/test_api/tree/microservices-example). <br/>
Там же можете найти в README ссылку на дополнительное видео, в котором я показал как реализовать микросервисное приложение и работать с docker compose.

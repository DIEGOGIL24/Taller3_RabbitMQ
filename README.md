# Docker Traefik

# Autor
**Diego Alejandro Gil Otálora**  
Código: 202222152  
Universidad Pedagógica y Tecnológica de Colombia  
Ingeniería de Sistemas y Computación - Sistemas Distribuidos  
Tunja, 2025  


## Ejecuciòn de RabbitMQ

Para esto ejecutamos el siguiente comando usando la imagen oficial de RabbitMQ

`docker run -d --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:4-management`

Verificamos 

![alt text](image.png)

## Ejecuciòn del consumidor

Para esto, ejecutamos el archivo que ya tenemos `receive.py` en una terminal aparte

![alt text](image-1.png)

## Ejecuciòn del productor

Para esto, ejecutamos el archivo `send.py` en una terminal aparte

![alt text](image-2.png)

y verificamos que el mensaje efectivamente llegò al consumidor

![alt text](image-3.png)
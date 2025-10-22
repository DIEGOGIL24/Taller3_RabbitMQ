# RabbitMQ Publish/Subscribe

# Autores
**Diego Alejandro Gil Otálora**<br>
**Julian David Bocanegra Segura** <br>
Universidad Pedagógica y Tecnológica de Colombia  
Ingeniería de Sistemas y Computación - Sistemas Distribuidos  
Tunja, 2025  


## Ejecuciòn de RabbitMQ

Para esto ejecutamos el siguiente comando usando la imagen oficial de RabbitMQ

`docker run -d --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:4-management`

## Prueba con publish
Ejecutamos el codigo `receive_logs.py` en una terminal y `emit_log.py` en la otra terminal para confirmar que se envian los mensajes y reciben de forma correcta. 

<img width="810" height="225" alt="image" src="https://github.com/user-attachments/assets/aacd5976-0f4d-44ed-8650-72684c382065" />

<img width="810" height="225" alt="image" src="https://github.com/user-attachments/assets/f8b294a8-71bc-4a52-b369-f6c1369eda83" />

## Prueba con Routing

Ejecutamos el codigo `receive_logs_direct.py` en una terminal y `emit_log_direct.py` en la otra terminal para confirmar que se envian los mensajes y reciben de forma correcta. 
<img width="1457" height="855" alt="image" src="https://github.com/user-attachments/assets/df129664-2669-4f48-89d6-5f925a8adee7" />

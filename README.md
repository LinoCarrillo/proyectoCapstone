# proyectoCapstone

Gracias por visitar el GitHub del proyecto Capstone "Sistema de vigilancia casera para adultos mayores" derealizado por: **José Lino Carrillo Villalobos** en colaboración con **Aturo JavierLópez Fausto**. 
Este sitio encontraras  los diagramas de Hardaware y una parte del Software del proyecto.

Objetivo: Tener un sistema de Monitoreo para adultos mayores que están solo en casa, mediante envío de mensajes por Telegram, además de trabajar con Mqtt, Node-Red y Mysql para el procesamiento de los datos generados por los sensores:
1. Sensor de Movimiento PIR detecta personas en la puerta principal y manda mensajes e imagenes por Telegram a los contactos agregados en un grupo.
2. Sensor MQ-6 colocado cerca de la estufa  detecta fugas de gas y manda una señal al mismo grupo de telegram y a Node-Red por Mqtt
3. Sensor MQ-135 detecta CO2 en el ambiente y se colocará cerca de los calentones para medir la calidad del aire en caso de superar la frontera establecida igual manda mensajes por Telegram y por mqtt a Node-Red
4. Sensor DHT-22 mide temperatura y humedad de la recamara principal, en caso de sobrepasar los umbrales establecidos manda mensajes por Telegram y mqtt a Node-Red

![Circuito Principal](/home/lino/Documents/GitHub/proyectoCapstone/imagenes/circuitoV3.png)



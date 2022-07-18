# proyectoCapstone

Gracias por visitar el GitHub del proyecto Capstone "Sistema de vigilancia casera para adultos mayores" realizado por: **José Lino Carrillo Villalobos** en colaboración con **Arturo Javier López Fausto**. 
Este sitio encontraras  los diagramas de Hardaware y una parte del Software del proyecto.

Objetivo: Tener un sistema de Monitoreo para adultos mayores que están solo en casa, mediante envío de mensajes por Telegram, además de trabajar con Mqtt, Node-Red y Mysql para el procesamiento de los datos generados por los sensores:
1. Sensor de Movimiento PIR detecta personas en la puerta principal y manda mensajes e imagenes por Telegram a los contactos agregados en un grupo.
2. Sensor MQ-6 colocado cerca de la estufa  detecta fugas de gas y manda una señal al mismo grupo de telegram y a Node-Red por Mqtt
3. Sensor MQ-135 detecta CO<sub>2</sub> en el ambiente y se colocará cerca de los calentones para medir la calidad del aire en caso de superar la frontera establecida igual manda mensajes por Telegram y por mqtt a Node-Red
4. Sensor DHT-22 mide temperatura y humedad de la recamara principal, en caso de sobrepasar los umbrales establecidos manda mensajes por Telegram y mqtt a Node-Red

![Circuito Principal](https://github.com/LinoCarrillo/proyectoCapstone/blob/main/imagenes/circuitoV3.png)

**Hojas de datos de los sensores utilizados:**

a) Sensor MQ-6   [Informacion importante para su uso...] (https://github.com/LinoCarrillo/proyectoCapstone/blob/main/documentos/MQ-6.pdf)

b) Sensor MQ-135 [Informacion importante para su uso...] (https://github.com/LinoCarrillo/proyectoCapstone/blob/main/documentos/MQ135.pdf)

c) Sensor DHT22  [Informacion importante para su uso...] (https://github.com/LinoCarrillo/proyectoCapstone/blob/main/documentos/DHT-22.pdf)

d) Sensor PIR    [Informacion importante para su uso...] (https://github.com/LinoCarrillo/proyectoCapstone/blob/main/documentos/pir.pdf)

e) ESP32-CAM     [Informacion importante para su uso...] (https://github.com/LinoCarrillo/proyectoCapstone/blob/main/documentos/ESP32-CAM.pdf)



# proyectoCapstone

Gracias por visitar el GitHub del proyecto Capstone **"Sistema de Vigilancia Casera para Adultos Mayores"** realizado por: **José Lino Carrillo Villalobos** en colaboración con **Arturo Javier López Fausto** y **Julio Cesar Ortiz Cornejo**. 
Este sitio encontraras  los diagramas de Hardaware y una parte del Software del proyecto.

Objetivo: Tener un sistema de Monitoreo para adultos mayores que están solos en casa, mediante envío de mensajes por Telegram, además de trabajar con Mqtt, Node-Red y Mysql para el procesamiento de los datos generados por los sensores:

- **Sensor de Movimiento PIR** detecta personas en la puerta principal y manda mensajes e imagenes por Telegram a los contactos agregados en un grupo.
- **Sensor MQ-6** colocado cerca de la estufa  detecta fugas de gas y manda una señal al mismo grupo de telegram y a Node-Red por Mqtt
- **Sensor MQ-135** detecta CO<sub>2</sub> en el ambiente y se colocará cerca de los calentones para medir la calidad del aire en caso de superar la frontera establecida igual manda mensajes por Telegram y por mqtt a Node-Red
- **Sensor DHT-22** mide temperatura y humedad de la recamara principal, en caso de sobrepasar los umbrales establecidos manda mensajes por Telegram y mqtt a Node-Red
- **ESP-32 CAM** administra el flujo de datos entre los sensores y el Software creado en el IDE de Arduino

![Circuito Principal](https://github.com/LinoCarrillo/proyectoCapstone/blob/main/imagenes/circuitoV3.png)

**Hojas de datos de los sensores utilizados:**

- **Sensor MQ-6**     (https://github.com/LinoCarrillo/proyectoCapstone/blob/main/documentos/MQ-6.pdf)

- **Sensor MQ-135**   (https://github.com/LinoCarrillo/proyectoCapstone/blob/main/documentos/MQ135.pdf)

- **Sensor DHT22**    (https://github.com/LinoCarrillo/proyectoCapstone/blob/main/documentos/DHT-22.pdf)

- **Sensor PIR**      (https://github.com/LinoCarrillo/proyectoCapstone/blob/main/documentos/pir.pdf)

- **ESP32-CAM**       (https://github.com/LinoCarrillo/proyectoCapstone/blob/main/documentos/ESP32-CAM.pdf)



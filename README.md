# Hello World IoT Watson Bluemix
Proyecto scratching para el testeo de la plataforma Node-Red con soporte a un IoT Watson local

### Esquema Node-RED

![](https://github.com/vicboma1/HelloWorldBluemix/blob/master/assets/_helloWorldIoT.gif)

La solución se basa en un esquema simple donde se injecta un paquete con las siguientes propiedades :

* Topic : Nombre descriptivo del paquete
* Payload : Contenido del paquete
* msgid : Atributo oculto que crea el empaquetado.

Dentro del Payload tenemos que definir el mensaje el protocolo de comunicación MQTT

* d : Define un paquete para un dispositivo


Este mensaje es recibido por un nodo IoT Watson output que envía a la entrada de un IoT Watson input el paquete que recibe a través de un protocolo MQTT.

Una vez recibido el paquete, el nodo ToLowerCase manipula la información del paquete (payload) y saca el resultado por la consola.


## Pasos a seguir
1.   Copiar la ![Plantilla txt](https://raw.githubusercontent.com/vicboma1/HelloWorldBluemix/master/assets/_helloWorldIoT.txt) con "Control A" + "Control C"

2.   Ir al menú contextual de nuestra aplicación Node-RED

3.   Importar

4.   Clipboard

5.   Import Nodes -> "Control V" para pegar la template

6.   Aceptar pulsando el botón de "Import"


@Author: [Victor Bolinches Marin](https://github.com/vicboma1)  

@Documento Principal  [CoEValencia - Hackathon 2017](https://github.com/CoEValencia/Hackathon_2017)

# ESP8266-EXTENDER
Este es un proyecto que hice en mi tiempo de ocio 
para el modulo ESP01s, puede ser usado para probarlo o para proyectos de IoT, me he basado en otros proyectos
para hacer mejoras e implementarlas en el mio. dichas mejoras son:

• incremento en la velocidad de transmisión y recepción, 
pasando de 100kbps a tener 2 o 3 mbps, suficientes para ver tiktok o youtube

• mejoras en la interfaz web

• añadí una lista de redes, para saber si el modulo esta dentro del alcance 
de la red anfitriona, también incluye intensidad de señal y tipo de encriptacion 

• mejoras menores en el codigo

Este proyecto lo probé en el modulo ESP01S, no se si funcionará en otros módulos 
ya que no dispongo de ellos, pero va de maravillas, su consumo energético promedio ronda entre 
70 a 90 mAh, aunque tiene picos de hasta 120mA, con una pila 18650 puede llegar a durar hasta 2
días continuo, por mi parte, la probé con una batería reciclada de un teléfono huawei de 1850mAh 
y me ha llegado a durar casi 38 horas, algo que ami me dejo sorprendido la primera vez.

en cuanto a la compilación, hay un detalle, este codigo funciona con la versión 3.0.0 de las librerias de esp8266,
no he podido adaptarlo a las nuevas versiones, también pueden grabarlo en su modulo con el archivo binario que deje 
en el archivo. espero que les sea de utilidad ;)

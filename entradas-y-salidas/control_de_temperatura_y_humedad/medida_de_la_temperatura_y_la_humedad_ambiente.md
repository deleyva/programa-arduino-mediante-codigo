# 3.5.1 Conexión

![](../../.gitbook/assets/dht11.jpg)

**Realizar un montaje que mida temperatura y humedad mediante el sensor DHT11.**

Para ello tendrás que realizar las conexiones necesarias para poder obtener los datos desde Arduino. Se trata de un sensor digital que utiliza 3 pines: Alimentación +5V, tierra/GND \(-\) y pin de datos \(out\) por donde se envían los datos de humedad y temperatura. A veces el sensor viene sobre 4 pines, en este caso uno de ellos no se conecta. Como las medidas de humedad y temperatura van por un solo pin, la información se transmite como un tren de pulsos en serie, por lo tanto, necesitamos un programa que "extraiga" eso dos datos de forma diferenciada. Para ello vamos a usar una librería referenciada por **DHT11.h** que se explica en[ la siguiente página.](https://github.com/deleyva/programa-arduino-mediante-codigo/tree/a407da71017a2f6edc4a9de5f70319276906de88/libreria_dht11h.html) A través del monitor serie del IDE de Arduino podremos ver las medidas obtenidas.

### ESQUEMA DHT11 :

Es un modelo "conectar y listo" que ya vienen con los cables preparados, pero si te fijas son en este orden : GND - 5V -NC - D2 donde NC significa NO CONECTADO y D2 son los datos

![](../../.gitbook/assets/img1.png)

Lo conectamos en el Arduino sin necesidad de placa Protoboard:

![](../../.gitbook/assets/m1_img2.png)

utilizando cables macho-macho

![](../../.gitbook/assets/img3.png)

Esquema de conexión:

![](../../.gitbook/assets/seleccion_005.png)

## Esquema DHT12

Es un sensor que necesita 3.3V pero si trabajas con 5V necesitas hacer este puente con una resistencia de más o menos 10K

![](../../.gitbook/assets/img0.2.png)

O con la placa Protoboard

![](../../.gitbook/assets/img1.2.png)

[Fuente Cactus.io](http://cactus.io/hookups/sensors/temperature-humidity/dht22/hookup-arduino-to-dht22-temp-humidity-sensor) CC BY-NC-SA 3.0


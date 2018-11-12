# 3.5.8 dweet.io

Disponemos del portal web **dweet.io** que nos ofrece un servicio para enviar y representar datos en la nube sin necesidad, ni si quiera, de registrarnos en la plataforma.

Vamos a ver los pasos a seguir:

1. Probamos la plataforma introduciendo un dato, para ello en el navegador tecleamos por ejemplo \(cambia **catedu** por tu nombre\): [https://dweet.io/dweet/for/catedu?temperatura=20](http://dweet.io/dweet/for/jorgeroden?temperatura=20)
2. Abre otra pestaña del navegador o utiliza un móvil para seguir el dato: [https://dweet.io/follow/catedu](http://dweet.io/follow/jorgeroden)
3. Prueba añadiendo otra variable, en este caso la humedad: [https://dweet.io/dweet/for/catedu?temperatura=20&humedad=8](http://dweet.io/dweet/for/jorgeroden?temperatura=20&amp;humedad=8)

![](../../.gitbook/assets/2017-10-10_19_44_57-dweet.io_-_share_your_thing-_like_it_aint_no_thang..png)

Automatizamos el proceso de recogida de datos desde Arduino con un programa en Processing, que enviará datos a través del navegador a dweet.io.

**IMPORTANTE**: No hay que tener abierto el monitor serie del IDE de Arduino porque ocupa el puerto y, por lo tanto, no deja leer los datos a Processing.

## REPRESENTACIÓN DE DATOS EN EL NAVEGADOR:

**Dweet.io** nos ofrecerá los datos de la siguiente manera:

![](../../.gitbook/assets/dweetio-jorgeroden-2.png)

Si queremos algo más vistoso podemos utilizar el servicio [freeboard.io](https://github.com/deleyva/programa-arduino-mediante-codigo/tree/a407da71017a2f6edc4a9de5f70319276906de88/freeboard.io) aunque en este caso nos tendremos que registrar en la web.

Una vez registrados podemos crear paneles indicadores configurados a nuestro gusto para visualizar la información. Primero habrá que añadir como fuente de datos Dweet.io y nuestro nombre utilizado allí \(jorgeroden en el ejemplo\).

Después creamos un panel indicando que la fuente de datos que queremos utilizar y la variable en cuestión a visualizar.

![](../../.gitbook/assets/freeb-1.png)

¡Y resultado puede ser de este tipo!

![](../../.gitbook/assets/freeb-2.png)


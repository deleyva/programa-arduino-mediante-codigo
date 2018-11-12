# EA.5.1 Conexiones

## CONEXIONES

Vamos a definir las conexiones para los siguientes montajes del transistor, utilizaremos tenemos un[ TIP121 o TP120 es un transistor NPN tipo "Darlington" ](https://alltransistors.com/pdfview.php?doc=tip121.pdf&amp;dire=_fairchild_semi)es decir, está integrado por dos transistores interiormente.

### SIN EDUBASICA

Realizaremos el siguiente esquema,conectando la base al D6 y dejando el colector abierto para los experimentos:

![](../../../.gitbook/assets/esquematransistor.png)

por lo tanto:

![](../../../.gitbook/assets/sinedubasica-transistor.png)

## CON EDUBASICA

En la shield ya tenemos el siguiente esquema:

![Esquema del transistor en EDUBASICA, en nuestro caso real R6 es 10k](../../../.gitbook/assets/m3img0.2.png)

Los conectores X2-2 y X2-1 son los de abajo a la izquierda. **X2-2 es el colecto**r del transistor y **X2-1 es V1** \(aunque en la foto pone Vin\):

![](../../../.gitbook/assets/m3img1.2.png)

V1 y Vin está conectado por el interruptor según este esquema:

![Vin y V1 en EDUBASICA](../../../.gitbook/assets/m3img2.2.png)

Luego es mejor **que el interruptor esté conectado en ON** para unir V1 con Vin y cortar el diodo D1, en caso contrario se nos va la corriente de la resistencia de colector por D1 a R5 y al led engañando la medida.

Vin son aproximadamente 5V de potencia de entrada al arduino que se utilizan si no lo alimentamos por el USB.


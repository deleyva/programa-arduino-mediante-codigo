# 5.2.3 M5 Motor-transistor

Monta el motor con el Arduino utilizando Edubásica o utilizando un transistor tal y como se ha explicado en las páginas anteriores. NO CONECTES UN MOTOR DIRÉCTAMENTE A LOS PINES DEL ARDUINO puedes dañarlo.

Este es el programa que te proponemos:

```cpp
// Activa y desactiva un 
// motorDC conectado al pin6 
// durante 2 segundos

#define motorDC 6

void setup() {

  pinMode(motorDC, OUTPUT);

}

void loop() {

  digitalWrite(motorDC, HIGH);
  delay(2000);
  digitalWrite(motorDC, LOW);
  delay(2000);
}
```

{% embed url="https://www.youtube.com/watch?v=enfIaqwsDhg&feature=youtu.be" %}

## ¿Te atreves?

Diseñar un montaje que active el motor DC mediante un relé conectado al colector del transistor.


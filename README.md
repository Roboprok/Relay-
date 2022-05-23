# Relay-
Instalar y programar un relay

![download](https://user-images.githubusercontent.com/80070044/169896680-bd649efb-6ad9-4a4f-9bfb-d48f6c28f0a9.jpg)
![AR0037-KY019-V1](https://user-images.githubusercontent.com/80070044/169896893-d62421e2-5618-45b8-ad50-3c9e54cf19ff.jpg)


Para usarlo con Arduino

![D_NQ_NP_724095-MLB31173211586_062019-O](https://user-images.githubusercontent.com/80070044/169897053-548e6a1b-ca33-463f-8061-abdca29413ce.jpg)


```C++
void setup() {
  // inicializar pin 13 como salida.
  pinMode(13, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(13, HIGH);   // activa el relay poniendo el pin en alto
  delay(1000);              // espera un segundo
  digitalWrite(13, LOW);    // deactiva el relay poniendo el pin en bajo
  delay(1000);              // espera un segundo
}

```

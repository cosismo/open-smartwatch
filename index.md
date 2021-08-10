### Open-Smartwatch

Bienvenido al Internet de las Cosas.

Protip: para cargar el sketch / bin a tu ESP32, presiona y deja presionado el botón "boot" (que tiene el rótulo 1 en el PCB) y después presiona y libera el botón Reset (R en el PCB) mientras lo transfieres.  
Si no lo haces probablemente no puedas cargar el sketch y se te presentarán errores como los que se describen en este post:  
[https://github.com/espressif/arduino-esp32/issues/1253](https://github.com/espressif/arduino-esp32/issues/1253)  
 
![Open-Smartwatch Pinout](https://raw.githubusercontent.com/cosismo/open-smartwatch/master/Open-SmartwatchPinout.jpg)


Para comenzar a utilizar tu Open-Smartwatch y encontrar toda la información técnica, te recomendamos las siguientes ligas:

* Facebook.
[Grupo de Facebook en español sobre Internet de las Cosas](https://www.facebook.com/groups/724628401049648/)

**ARDUINO**
Para programar con Arduino IDE sólo selecciona la placa ESP32 PICO-D4 y podrás subir cualquier sketch de manera normal. Para utilizar la pantalla requerirás de la librería Arduino_GFX_Library (instálala de la manera normal, la encontrarás como "GFX Library for Arduino by Moon on Our Nation" en el gestor de librerías del IDE) con los siguientes parámetros: [parámetros Arduino_GFX_Library  para Open-Smartwatch](https://github.com/moononournation/Arduino_GFX/issues/71)
* Ejemplo básico helloWorld (escribe texto al display después de subir el sketch y dar reset) [Ejemplo Arduino Open-Smartwatch Hello World texto al display](https://gist.github.com/cosismo/10b544eb6accbe3d7879d46bc1386545)
* Ejemplo de reproductor de GIFs [Ejemplo Arduino Open-Smartwatch GIF Player](https://github.com/cosismo/opensmarwatchGifPlayer) (requiere que subas el GIF al ESP32 con el plugin [Arduino ESP32 filesystem uploader](https://github.com/me-no-dev/arduino-esp32fs-plugin/), instales las librerías correspondientes y después subas el sketch.

**PLATFORMIO + VSCode (Sistema operativo oficial del reloj)**
* Actualizar firmware.
[Instrucciones para clonar, compilar y subir el firmware  (OS) del Open-Smartwatch](https://open-smartwatch.github.io/4_flashing/)

OTRA INFORMACIÓN ÚTIL

* Canal de Discord oficial.
[Ayuda de la comunidad por el canal de Discord oficial](https://discord.gg/9DK5JY6)

* Driver USB
[Driver USB para el Open-Smartwatch](http://www.wch-ic.com/downloads/CH341SER_ZIP.html)

* Información general sobre el ESP32 _(info sobre el ESP32 dev kit, pero aplica en un 95% para esta placa)._
[Información sobre el ESP32 dev kit](https://cosismo.github.io/esp32-devkit/)


¡Suerte!

  Equipo Cosismo

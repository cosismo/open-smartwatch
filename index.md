### Open-Smartwatch

Bienvenido al Internet de las Cosas.

Protip: para cargar el sketch / bin a tu ESP32, presiona y deja presionado el botón "boot" (que tiene el rótulo 1 en el PCB) y después presiona y libera el botón Reset (R en el PCB) mientras lo transfieres.  
Si no lo haces probablemente no puedas cargar el sketch y se te presentarán errores como los que se describen en este post:  
[https://github.com/espressif/arduino-esp32/issues/1253](https://github.com/espressif/arduino-esp32/issues/1253)  
 
![Open-Smartwatch Pinout](https://raw.githubusercontent.com/cosismo/open-smartwatch/master/1.jpg)


Para comenzar a utilizar tu Open-Smartwatch y encontrar toda la información técnica, te recomendamos las siguientes ligas:

* Facebook.
[Grupo de Facebook en español sobre Internet de las Cosas](https://www.facebook.com/groups/724628401049648/)

**Conceptos básicos**  
* El modelo 2021 del opensmartwatch no incluye convertidor USB a TTL. Por lo que necesitarás usar uno (se incluye en el kit, es el modelo T-U2T)
* El reloj viene con el firmware oficial precargado.
* Puedes programar con Platformio. En el repositorio del fabricante se encuentra el código del firmware completo en la carpeta de software con el nombre de SmartWatch.zip. Las credenciales WiFi se configuran en un archivo de configuración. Puedes leer esta liga para ubicarlo: [CONFIG_WIFI_SSID](https://github.com/Xinyuan-LilyGO/T-Watch-2021/issues/2)
* También puedes usar el reloj como cualquier Arduino y programarlo a través de la librería incluída en el repositorio oficial. Hay un par de ejemplos en la carpeta software/Arduino de dicho repositorio.


**Repositorio oficial del fabricante:**  
[Repositorio LilyGOT-Watch-2021](https://github.com/Xinyuan-LilyGO/T-Watch-2021)

OTRA INFORMACIÓN ÚTIL

* Canal de Discord oficial.
[Ayuda de la comunidad por el canal de Discord oficial](https://discord.gg/9DK5JY6)


* Información general sobre el ESP32 _(info sobre el ESP32 dev kit, pero aplica en un 95% para esta placa)._
[Información sobre el ESP32 dev kit](https://cosismo.github.io/esp32-devkit/)


¡Suerte!

  Equipo Cosismo

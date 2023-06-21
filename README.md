# EasyESP

## Kompatibilitet

* ESP8266  - Most likely option  (use also for ESP8285 chips)
* ESP32    - Showing up in commercial products, but mainly seen on NodeMCU like boards.
* ESP32-S2 - Newer version of ESP32, with more GPIO pins, but lacking some features of ESP32.
* ESP32-S3 - Not yet supported in ESPEasy. (hardly available to buy)
* ESP32-C3 - Support in ESPEasy will be added soon.

## Arbetsgång

For Linux or Mac users, the recommended tool for ESP82xx/ESP32 is esptool.py

1. Download [firmware as binary including flash tool](https://github.com/letscontrolit/ESPEasy/tree/mega/dist)
2. [Connect the ESP to Windows PC Using](https://espeasy.readthedocs.io/en/latest/Reference/Flashing.html#flashing-software) either USB/UART of board or separate USB/TTL adapter
3. Write firmware using flash tool (Note necessity for GPIO to be LOW to enter flashmode)
4. Restart ESP. WiFi AP "ESP_Easy_0" will appear, password: configesp (prior to 2.0 the AP was named ESP_0). If you're not automatically taken to the log-in page, browse to 192.168.4.1
5. Search for you routers WiFi and connect (if you have multiple AP they will all show up with the same SSID name multiple times)
6. Reconnect to your WiFi and enter IP adress shown on previous screen

## ESPEasy GUI

* (GUI)[https://www.letscontrolit.com/wiki/index.php/ESP_Easy_web_interface]

## Rules

* https://www.letscontrolit.com/wiki/index.php/Tutorial_Rules

## Inspiration

* https://www.letscontrolit.com/wiki/index.php/EasyNotifications
* https://www.letscontrolit.com/wiki/index.php?title=SleepMode

## Noteringar om ESP-Easy

### Anslut och Flash'a

* Ladda ned firmware från https://github.com/letscontrolit/ESPEasy/releases 
* Anslut USB-till-TTL-konverterare satt till 3V3

https://td-er.nl/ESPEasy/

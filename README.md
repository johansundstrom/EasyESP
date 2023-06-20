# EasyESP

## Kompatibilitet

* ESP8266      => Most likely option  (use also for ESP8285 chips)
* ESP32        => Showing up in commercial products, but mainly seen on NodeMCU like boards.
* ESP32-S2     => Newer version of ESP32, with more GPIO pins, but lacking some features of ESP32.
* ESP32-S3     => Not yet supported in ESPEasy. (hardly available to buy)
* ESP32-C3     => Support in ESPEasy will be added soon.

## Arbetsgång

1. Download [firmware as binary including flash tool](https://github.com/letscontrolit/ESPEasy/tree/mega/dist)
2. Connect the ESP to Windows PC Using either USB/UART of board or separate USB/TTL adapter
3. Write firmware using flash tool (Note necessity for GPIO to be LOW to enter flashmode)
4. Restart ESP. WiFi AP "ESP_Easy_0" will appear, password: configesp (prior to 2.0 the AP was named ESP_0). If you're not automatically taken to the log-in page, browse to 192.168.4.1
5. Search for you routers WiFi and connect (if you have multiple AP they will all show up with the same SSID name multiple times)
6. Reconnect to your WiFi and enter IP adress shown on previous screen

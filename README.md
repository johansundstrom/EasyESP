# EasyESP



1. Download [firmware as binary including flash tool](https://github.com/letscontrolit/ESPEasy/tree/mega/dist)
2. Connect the ESP to Windows PC Using either USB/UART of board or separate USB/TTL adapter
3. Write firmware using flash tool (Note necessity for GPIO to be LOW to enter flashmode)
4. Restart ESP. WiFi AP "ESP_Easy_0" will appear, password: configesp (prior to 2.0 the AP was named ESP_0). If you're not automatically taken to the log-in page, browse to 192.168.4.1
5. Search for you routers WiFi and connect (if you have multiple AP they will all show up with the same SSID name multiple times)
6. Reconnect to your WiFi and enter IP adress shown on previous screen

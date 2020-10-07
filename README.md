# esp8266-gps


esp based gps perfomance meter with 10Hz [NEO-m8n](https://www.u-blox.com/sites/default/files/NEO-M8-FW3_DataSheet_%28UBX-15031086%29.pdf)

ESP reads nmea data from [NEO-m8n](https://www.u-blox.com/sites/default/files/NEO-M8-FW3_DataSheet_%28UBX-15031086%29.pdf) and calculate time from x to x, avg slope and
peak G-force.

Libraries:
- `TinyGPS++`
- `SoftwareSerial`
- `Adafruit_ssd1306syp`

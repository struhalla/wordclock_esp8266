##Wordclock based on an ESP8266 / WS2812
![front_an](img/front_an.jpg)

###Hardware:
- LDR with voltagedevider on A0 
- WS2866 via levelshifter on RXD0 

![wiring1](img/schematics.jpg)
![wiring2](img/drahtverhau.jpg)

###Features:
- defineable hardware layout (leds.h)
- word fading
- display hour and minutes
- display seconds
- display temperature
- 8 different color modes with HUE rotate
- wifimanger
- Webserver http://deviceip:80
- OTA
- mdns
- NTP time client
- MQTT Sub: ON/OFF && BRIGHTNESS && COLORMODE && DISPLAYMODE (Non persistent)
- MQTT Pub: current config as JSON to broker
- LDR driven brightness


##Todos befor V1.0:
###Addons
- tempsensor implementation
###Bugfixing

##Images
![front_blank](img/front_blank.jpg)
![front](img/front.jpg)
![menu1](img/menu1.jpg)
![menu21](img/menu2_2.jpg)
![menu22](img/menu2_2.jpg)
![menu3](img/menu3.jpg)
![menu4](img/menu4.jpg)
![menu5](img/menu5.jpg)








# esp8266-http-switch
A simple esp8266 with three links for: ON / OFF and STATE

Diese Zeilen müssen vor dem Upload bearbeitet werden:

```c++

const char* ssid = "WLAN_SSID";
const char* password = "WLAN_PASSWORD";

```

Der ESP ist erreichbar unter folgenden links
http://esp8266.local/relay_on
http://esp8266.local/relay_off
http://esp8266.local/state


Die Signalleitung des Relaismoduls kommt an D1.

```c++
int relay_pin = 5; //D1
```

Hier nochmal alle Pins mit den dazugehörigen Nummern.
https://github.com/makesmartnet/esp8266-pin-definitions

# velux-cube-for-homee
## Installation

Aktuelle Version des Chips ESP32 Wroom32 

  - mit dem Esp Wlan Verbinden "velux_cube" ohne PW oder homee-community-cube
  - anmelden an der WEBUI unter der IP 192.168.4.1 , Name admin und Passwort admin
  - Wlan Zugangsdaten eintippen
  - AP Passwort vergeben 
  - WEBUI Anmeldenamen und Passwort neu vergeben, danach neu anmelden
  - Velux Anmeldedaten eingben und neustarten
  - Esp unter velux-cube.fritz.box aufrufen ( wenn er an der Fritzbox angemeldet ist, ansonsten die Ip im Router raussuchen )
  - in homee nun Geräte hinzufügen und homee in homee auswählen
    -> mit homee verbinden drücken -> IP Adresse xxx.xxx.xxx.xxx eingeben oder Velux -> User XYZ -> PW ABC -> verbinden drücken
    nun sollten alle angelegten Geräte angezeigt werden
  - Aktuelles Update über die Seite IP/update einspielen
  - Aktuell getestet Zahl an angelernten Geräten liegt bei 40 Aktoren ( Stand 16.7.22 )
  
 # Update
 
 07.09.2022
 - Beim betätigen der Button UP/Down wird jetzt öffnet oder schließt angezeigt und bei erreichen der Position bzw. bei 
   Werten über 50% wird geschlossen und bei unter 50% geöffnet angezeigt. 

ssid-changer
============

Skript zum Ändern der SSID, wenn keine ausreichende Verbindung zum ausgewählten Gateway besteht.

Es ist ganz einfach, es überprüft nur die Qualität der Verbindung und entscheidet, ob eine Änderung der SSID erforderlich ist.

Die SSID wird in original-ssid + "(inaktiv)" geändert, wenn die Verbindung unter der Untergrenze liegt. 
Wenn die Verbindung über der Obergrenze liegt, wird die SSID wieder in die ursprüngliche SSID (wireless.client_radio0.ssid) geändert.

-------------------
Update: 
Es werden keine Verbindungsqualitätsbeschränkungen mehr verwendet, um zu entscheiden, ob offline. 
Die SSID hängt von mindestens einem Gateway in Reichweite ab.

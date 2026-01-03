# Wetterstation Projekt - WeatherCam

Dies ist mein langjähriges Wetterstationsprojekt, das 2014 als Hobby begann. Es entwickelte sich von einer Lösung für einen Hausmeisterbetrieb zu einem persönlichen Projekt, das regelmäßig erweitert wird, um verschiedene Wetterdaten zu erfassen und zu analysieren. Ab 2024 hat sich der Name des Projekts geändert, und es wird jetzt unter **WeatherCam** geführt.

## Versionsübersicht

### **Version 0.0** (Ideenphase, 2014)
- Konzeptualisierung und erste Ideen.

### **Version 1.0 - 1.1** (2015)
- **System**: Siemens Logo 8
- **Messwerte**: Bodentemperatur, Lufttemperatur, Niederschlag
- **Ausgabe**: Alarm Sirene

### **Version 2.0 - 2.1** (2016)
- **System**: Siemens Logo 8 + Insys IMON G100
- **Messwerte**: Bodentemperatur, Lufttemperatur, Niederschlag
- **Ausgabe**: SMS, E-Mail

### **Version 3.0 - 3.2** (2017)
- **System**: Siemens Logo 8 + Insys IMON G100
- **Messwerte**: Bodentemperatur, Lufttemperatur, Niederschlag, Schneefall, Sonne, Wind
- **Ausgabe**: SMS, E-Mail

### **Version 4.0 - 4.2** (2018)
- **System**: Siemens Logo 8 + Raspberry Pi (FHEM)
- **Messwerte**: Bodentemperatur, Lufttemperatur, Niederschlag, Schneefall, Sonne, Wind
- **Ausgabe**: SMS, E-Mail, WhatsApp, Telegram

### **Version 4.3.1** (2019)
- **System**: Arduino UNO + Raspberry Pi (FHEM)
- **Messwerte**: Bodentemperatur, Lufttemperatur, Niederschlag, Schneefall, Sonne, Wind, Luftfeuchte
- **Ausgabe**: SMS, E-Mail, WhatsApp, Telegram
- **Projektname**: **WetterDachau**

### **Ab 2024** – **Namensänderung zu "WeatherCam"**
- Der Name des Projekts wird zu **WeatherCam** geändert, um den Fokus auf Wetterdaten und Kamerabilder zu legen und eine breitere Zielgruppe anzusprechen.

### **Version 5.0.0** (2024)
- **System**: Arduino MEGA 2560
- **Messwerte**: Umfassende Wetterdaten (Temperatur, Luftfeuchte, UV-Index, Wind, Niederschlag, etc.)
- **Speicherung**: SD-Karte, EEPROM
- **Hintergrundsystem**: MQTT, Webserver, Ethernet
- **Benachrichtigungen**: E-Mail, Telegram
- **Anzeige**: Display (optional)

### **2025** – **Erweiterung durch einen Bekannten**
- Ein Bekannter bringt sich aktiv in das Projekt ein und stellt seinen Mast auf einem Geschäftsgebäude zur Verfügung über den Dächern von München. 
  Zusätzlich stellt er Rechenleistung und Netzwerk-Ressourcen zur Verfügung, um das Projekt weiter auszubauen und die Datenverarbeitung zu optimieren.

### **Ab 8.2025** – **Nochmalige Namensänderung**

### **Version 6.0.0** (2026)
- **System**: Arduino MEGA 2560
- **Neue Funktionen**: Erweiterung mit zusätzlichen Sensoren und eigenen Bibliotheken zur Speicheroptimierung.
- **Ziel**: Effizientere Verarbeitung und Speicherung von Wetterdaten, um den wachsenden Anforderungen gerecht zu werden.

## Funktionen:
- Messung einer Vielzahl von Wetter- und Umweltdaten (z.B. Temperatur, Luftfeuchte, UV-Index, Wind, Niederschlag).
- Speicherung und Verarbeitung der Daten auf SD-Karte und/oder EEPROM.
- Online-Datenübertragung via MQTT und Webserver.
- Benachrichtigungen bei bestimmten Wetterereignissen (E-Mail, Telegram).
- Erweiterte Datenvisualisierung auf einem Display und über einen Webserver.

## Benötigte Hardware:
- **Arduino MEGA 2560** (oder Arduino UNO, je nach Version)
- Wetter- und Umweltsensoren (z.B. Temperatur, Luftfeuchte, Luftdruck, Wind)
- **Raspberry Pi** (für Version 4.0 und höher)
- SD-Kartenleser, Display (optional)

## Installation:
1. Baue die Hardware auf (Sensoren und Arduino).
2. Lade den entsprechenden Code über die Arduino IDE hoch.
3. (Optional) Verbinde das System mit einem Raspberry Pi für erweiterte Funktionen (Version 4.0+).
4. (Optional) Konfiguriere den Webserver und/oder MQTT für die Datenübertragung.

## Lizenz:
Dieses Projekt ist unter der MIT-Lizenz lizenziert – siehe die [LICENSE](LICENSE)-Datei für Details.

## Kontakt:
Für Fragen oder Verbesserungsvorschläge kannst du mich über GitHub oder per E-Mail kontaktieren: [deine-email@beispiel.de].

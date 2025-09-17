# DaysOld - Foto-Altersrechner

Eine einfache Web-Anwendung zur Berechnung des Alters von Personen basierend auf EXIF-Zeitstempeln von Fotos.\
Es werden keine Fotos übertragen, nur im Browser geladen !

## 🎯 Funktionen

- **Personenverwaltung**: Fügen Sie mehrere Personen mit Namen und Geburtsdatum hinzu
- **EXIF-Datenanalyse**: Automatische auslesen des Aufnahmedatums aus Foto-Metadaten (EXIF)
- **Altersberechnung**: Präzise Berechnung des Alters zum Zeitpunkt der Fotoaufnahme / Fotoerstellung
- **Schwangerschaftsmodus** (BABY-Version): Spezielle Anzeige für noch ungeborene Babys
- **Foto-Sharing**: Erstellen und teilen Sie Bilder mit Altersangaben im Polaroid-Stil
- **Responsive Design**: Optimiert für Desktop und mobile Geräte


## 🚀 Verwendung

1. **Personen hinzufügen**
   - Geben Sie Name und Geburtsdatum ein
   - Klicken Sie auf "Person hinzufügen"
   - Für ungeborene Babys: Verwenden Sie ein zukünftiges Datum für den Schwangerschaftsmodus

2. **Foto wählen**
   - Wählen Sie ein Foto mit EXIF-Daten aus
   - Das Alter wird automatisch berechnet und angezeigt

3. **Ergebnisse teilen**
   - Klicken Sie auf "Share Photo" um eine teilbare Version zu erstellen
   - Das generierte Bild kann heruntergeladen oder geteilt werden

## 📋 Technische Details

- **Single-Page Application**: Gesamte Anwendung in einer HTML-Datei
- **Keine Installation erforderlich**: Funktioniert direkt im Browser
- **EXIF.js Integration**: Liest Metadaten direkt aus Bilddateien
- **Datenschutz**: Alle Berechnungen erfolgen lokal im Browser

## FAQ
- **Warum wird das Alter falsch angezeigt?**\
    Wenn ein Foto keine EXIF (Kamera)-Informationen hat, wird das erstellt Datum der Datei als Aufnahmedatum verwendet.\
    Der Text ist dann ein wenig anders: "Photo created" statt "Photo taken"


## 📝 Lizenz

Dieses Projekt ist Open Source und steht unter der MIT-Lizenz.

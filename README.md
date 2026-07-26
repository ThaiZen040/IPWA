# CO₂-Transparenzatlas

Der CO₂-Transparenzatlas ist eine responsive Webanwendung zur Darstellung
fiktiver CO₂-Emissionsdaten von Ländern und Unternehmen. Die Daten lassen sich
nach Land, Unternehmen und Sektor filtern sowie auf- oder absteigend sortieren.

## Voraussetzungen

- ein aktueller Webbrowser, zum Beispiel Firefox, Chrome, Edge oder Safari
- eine Internetverbindung, da Pico CSS, Alpine.js und Google Fonts über CDNs
  geladen werden
- optional: Python 3, um einen lokalen Webserver zu starten

Eine Paketinstallation und ein Build-Schritt sind nicht erforderlich.

## Projekt herunterladen

```bash
git clone https://github.com/ThaiZen040/IPWA.git
cd IPWA
```

Alternativ kann das Repository als ZIP-Datei heruntergeladen und entpackt
werden.

## Projekt starten

### Empfohlen: mit lokalem Webserver

Im Projektordner folgenden Befehl ausführen:

```bash
python3 -m http.server 8000
```

Unter Windows kann stattdessen dieser Befehl verwendet werden:

```powershell
py -m http.server 8000
```

Anschließend im Browser
[http://localhost:8000](http://localhost:8000) aufrufen.

Der Server kann im Terminal mit `Strg` + `C` beendet werden.

### Ohne lokalen Webserver

Da es sich um eine statische Webseite handelt, kann alternativ die Datei
`index.html` direkt im Browser geöffnet werden.

## Bedienung

- Über die Eingabefelder können Land und Unternehmen gesucht werden.
- Die Auswahlfelder filtern nach Sektor und bestimmen die Sortierung.
- Mit „Richtung“ wird zwischen auf- und absteigender Sortierung gewechselt.
- „Filter zurücksetzen“ stellt die ursprüngliche Ansicht wieder her.
- „Schriftkultur“ wechselt zwischen Links-nach-rechts- und
  Rechts-nach-links-Darstellung.

## Projektstruktur

```text
IPWA/
├── index.html   # Aufbau und Inhalte der Webseite
├── style.css    # Gestaltung und responsives Layout
├── script.js    # Daten, Filterung, Sortierung und Schreibrichtung
└── README.md    # Anleitung zum Projekt
```

## Verwendete Technologien

- HTML5
- CSS3
- JavaScript
- [Pico CSS](https://picocss.com/)
- [Alpine.js](https://alpinejs.dev/)

## Hinweis zu den Daten

Alle auf der Webseite angezeigten Emissionswerte sowie Namen von Unternehmen
sind fiktiv und dienen ausschließlich der Demonstration.

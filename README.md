# ASZ Asten - Material Management UI

Touch-optimized on-site terminal and live monitor for container management at the ASZ Asten recycling center. A minimalist, real-time web interface
for the Asten recycling center. Based on HTML5 and local data synchronization. It allows on-site staff to quickly record container fill levels via tablet and instantly reflects the status on the dashboard on their office PC.

## 🚀 Quick Start

Since the project is currently designed as a standalone, lightweight web app, no complex installation is necessary:

1. Download the file `index.html`.

2. Save the file to your office PC (e.g., in a shared network folder).

3. **Office View:** Open the file in your browser on your office PC and click on **"Switch View (Office PC)"** in the upper right corner.

4. **Container Terminal (Tablet):** Open the same file on the tablet (via the network path). Changes are synchronized thanks to local storage.

## 🛠️ Features

- **Container Terminal:** Large, touch-friendly tiles for the most important waste categories (scrap wood, construction waste, bulky waste, etc.).

- **Three-Stage Status:** Empty/Ready (Green), 75% Full (Yellow), Critical/Full (Red with flashing light).

- **Office Dashboard:** Live monitoring of all container statuses, including a continuous activity log.

- **Data Export:** Ability to export the daily log as a `.csv` file for Excel with one click.


## 📈 Future Enhancements

- Switching from `localStorage` to a local Node.js/Python server if synchronization needs to scale across multiple separate devices/networks.

<hr>

# ASZ Asten - Material Management UI

Touch-optimiertes Platz-Terminal und Live-Monitor für die Containerverwaltung des ASZ Asten. Ein minimalistisches, echtzeitfähiges Web-Interface 
für das Altstoffsammelzentrum Asten. Basiert auf HTML5 und lokalem Datensync. Es ermöglicht dem Personal auf dem Platz die schnelle Erfassung von 
Container-Füllständen via Tablet und spiegelt den Status sofort auf das Dashboard im Büro-PC.

## 🚀 Schnellstart

Da das Projekt aktuell als eigenständige, leichtgewichtige Web-App konzipiert ist, ist keine komplexe Installation notwendig:

1. Laden Sie die Datei `index.html` herunter.
2. Speichern Sie die Datei auf dem Büro-PC (z.B. in einem freigegebenen Netzwerkordner).
3. **Büro-Ansicht:** Öffnen Sie die Datei im Browser auf dem Büro-PC und klicken Sie oben rechts auf **"Ansicht wechseln (Büro PC)"**.
4. **Platz-Terminal (Tablet):** Öffnen Sie dieselbe Datei auf dem Tablet (über den Netzwerkpfad). Änderungen werden dank lokalem Speicher synchronisiert.

## 🛠️ Funktionen

- **Platz-Terminal:** Große, berührungsfreundliche Kacheln für die wichtigsten Abfallkategorien (Altholz, Bauschutt, Sperrmüll, etc.).
- **Drei-Stufen-Status:** Leer/Bereit (Grün), 75% Voll (Gelb), Kritisch/Voll (Rot mit Blinksignal).
- **Büro-Dashboard:** Live-Überwachung aller Container-Zustände inklusive fortlaufendem Aktivitätsprotokoll.
- **Datenexport:** Möglichkeit, das Tagesprotokoll mit einem Klick als `.csv`-Datei für Excel zu exportieren.

## 📈 Zukünftige Erweiterungen
- Umstellung von `localStorage` auf einen lokalen Node.js/Python-Server, falls die Synchronisation über mehrere separate Geräte/Netzwerke hinweg skaliert werden muss.

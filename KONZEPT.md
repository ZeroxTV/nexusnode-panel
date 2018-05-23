Das Nexusnode Admin Panel ist ein erweiterbares Administrationspanel für alle Arten für Game- Voiceservern.

Das Konzept:
Wichtige Begriffe:
  - Node:
    - Ein realer Server der über einen installierten Daemon mit dem Panel kommuniziert
  - Location:
    - Eine Gruppierung von Nodes
  - Image:
    - Eine Konfiguration und genaue Beschreibung, wie ein Daemon eine Serverinstanz einer bestimmten Art aufsetzt, einrichtet, und verwaltet

(Konzept des Webpanels)
- Das Webpanel ist ein benutzerfreundliches UI mit zwei Perspektiven:
  - Das User-Panel:
    - Im User-Panel können Endbenutzer alle Server verwalten, die ihnen zugeschrieben wurden:
      - Live-Konsole
      - Start/Stop/Restart/Reinstall
      - Datei-Browser/Editor
      - Dateien hoch- bzw. runterladen
      - CPU- und RAM-Auslastung
      - Speicherplatzverwendung
      - SFTP-Informationen
      - IP und Port
      - Gameswitching
    - Alle Aktionen im Userpanel hängen davon ab, welche Rechte ein User hat
    - 2-Faktor-Authentifizierung einrichten
  - Das Admin-Panel:
    - Im Admin-Panel können Administratoren des Adminpanels alles mögliche verwalten:
      - Webpanel verwalten:
        - Sprache
        - Logos
        - Farbschema
        - Allgemeine Konfiguration
        - Updates
        (- Plugins) 
      - Nodes verwalten:
        - Nodes starten/stoppen
        - Nodes updaten
      - Images verwalten:
        - Images bearbeiten
        - Images hinzufügen/entfernen
        - Images importieren/exportieren
      - Server verwalten:
        - Alle Server von Endbenutzern verwalten (siehe User-Panel)
        - Server sperren/freigeben
      - Locations verwalten:
        - Locations hinzufügen/entfernen
        - Einer Location Nodes hinzufügen/entfernen

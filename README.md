# DevVault Launcher 1.4.1

DevVault Launcher zum Herunterladen der offiziellen DevVault-Erweiterung und von Community-Erweiterungen. Keine Anmeldung nötig.

## Starten

1. Python installieren (Windows: bei der Installation **Add Python to PATH** anhaken)
2. Einmalig im Terminal: `pip install customtkinter pillow`
3. Doppelklick auf `devvault_launcher.pyw` (startet ohne Terminal-Fenster)

## Funktionen

- **Ladebildschirm** beim Start und rundes, modernes Design
- **Offizielle Plugins:** DevVault (Chrome-Erweiterung) herunterladen und auf Wunsch gleich entpacken
- **Community:** eigene Erweiterungen mit Name, Bild und Beschreibung hochladen
  - Warnhinweis, dass Community-Erweiterungen nicht vom DevVault-Team sind
  - Vor dem Hochladen kommt eine Sicherheitsabfrage
  - Eigene Uploads lassen sich jederzeit löschen (🗑). Danach kann sie niemand mehr aus dem Launcher herunterladen. Wer sie schon heruntergeladen hat, behält sie.
- **Feedback:** Titel, Sterne und Beschreibung abgeben und alle Feedbacks ansehen
- **Dauerhaft gespeichert:** Uploads und Feedbacks bleiben nach dem Schließen erhalten

## Wo werden die Daten gespeichert?

- Windows: `%APPDATA%\DevVaultLauncher`
- Sonst: `~/.devvault-launcher`

Die Daten liegen lokal auf deinem PC.

## DevVault in Chrome installieren

1. Im Launcher unter **Offizielle Plugins** auf **Download** klicken und entpacken
2. In Chrome `chrome://extensions` öffnen
3. Oben rechts **Entwicklermodus** einschalten
4. **Entpackte Erweiterung laden** klicken und den Ordner `DevVault` wählen
5. Einen neuen Tab öffnen

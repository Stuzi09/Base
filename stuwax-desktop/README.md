# Stuwax Desktop

Die Stuwax-Seite als eigenständige Desktop-App (Electron).

## Starten ohne Installation

    npm install
    npm start

## Installierbare Datei bauen

    npm install
    npm run dist

Die fertige Datei liegt danach im Ordner `dist/`:

- Windows: `Stuwax Setup 1.0.0.exe` (auf Windows bauen)
- macOS: `Stuwax-1.0.0.dmg` (auf einem Mac bauen)
- Linux: `Stuwax-1.0.0.AppImage` (auf Linux bauen)

Electron baut nur für das System, auf dem es läuft. Für Windows also auf einem Windows-Rechner, für macOS auf einem Mac.

## Daten

Auswahl, Fotos und eigene Wachse liegen lokal in der App. Sichern über „Daten“ → „Sicherung kopieren“.

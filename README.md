# MUSEUM OF ABSOLUTE NONSENSE

Ein absichtlich chaotisches, surrealistisches Kunstmuseum mit lokalem Spielgeld-Auktionssystem.

## Lokal testen
Öffne `index.html` im Browser. Für zuverlässigere lokale Tests kannst du im Projektordner `python -m http.server 8000` starten und `http://localhost:8000` öffnen.

## Auf GitHub Pages veröffentlichen
1. Erstelle ein neues GitHub-Repository.
2. Lade `index.html`, `style.css`, `app.js`, `README.md` und den gesamten Ordner `assets` hoch.
3. Öffne **Settings → Pages**.
4. Wähle **Deploy from a branch**, Branch `main`, Ordner `/ (root)` und speichere.
5. Warte auf den Pages-Link.

## Spielstand und Grenzen
- Spielstand wird mit `localStorage` im jeweiligen Browser gespeichert. Er ist nicht automatisch zwischen Geräten synchronisiert.
- Auktionen und Gebote sind lokale Spielmechaniken, keine echten oder gemeinsamen Auktionen.
- Es gibt keine Echtgeldzahlungen. Alle Beträge sind Spielgeld.
- Preise verändern sich lokal. Browserdaten löschen setzt den Spielstand zurück.
- Google Fonts werden optional online geladen; bei fehlender Verbindung greifen lokale Ersatzschriften. Alle Kunstwerkbilder liegen im `assets`-Ordner.

## Geheimnisse
Die Lost Pages sind über `???` erreichbar. Einige Rätsel führen zurück ins Museum und belohnen mit Spielgeld. Der Überraschungsmoment bei `THE SILENT SCREAM` ist kurz, visuell und ohne Ton.

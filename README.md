# AngelPlaner

Fischer-App im Browser: Spot- und Fischwahl, Angelplan mit Ködern, abhakbare Packliste, Aktivitätsdiagramme, Fischkarte mit Hitzekarte, Fangbuch mit Fotos, Fischlexikon und Knotenanleitungen.

## Dateien
- `index.html` – Hauptapp (eine einzige Datei, keine Installation nötig)
- `satellit-version.html` – ältere Version mit echter Satellitenkarte (Leaflet + Esri, braucht Internet)

## Auf GitHub veröffentlichen (GitHub Pages)
1. Neues Repository erstellen und alle Dateien hochladen.
2. Im Repository: Settings → Pages → Branch `main` und Ordner `/ (root)` wählen → Save.
3. Nach ca. 1 Minute ist die App unter `https://DEIN-NAME.github.io/REPO-NAME/` erreichbar.

Auf GitHub Pages funktioniert auch die Satellitenkarte unter `/satellit-version.html`.

## Hinweise
- Fischdichten, Aktivität und Wetter sind Beispiel- und Schätzwerte, keine Live-Daten.
- Fangbuch und Fotos werden nur lokal im Browser gespeichert (localStorage).
- Beachte Patent, Schonzeiten und Schonmasse deines Kantons.

# Kostenlose WeightWatchers-Rezeptbibliothek

Diese kleine statische Website ist ein Prototyp für eine persönliche Rezeptbibliothek. Sie enthält ein Beispielrezept mit Schema.org-`Recipe`-Daten (JSON-LD), damit Rezeptimporteure Zutaten und Zubereitung maschinenlesbar erkennen können.

## Dateien
- `index.html` – Rezeptübersicht
- `recipes/kung-pao-chicken.html` – Beispielrezept inklusive JSON-LD

## Kostenlos mit GitHub Pages veröffentlichen
1. Bei https://github.com anmelden oder ein Konto erstellen.
2. Ein neues **Public** Repository anlegen, z. B. `ww-rezeptbibliothek`.
3. Die Dateien und Ordner aus diesem ZIP in das Repository hochladen. Wichtig: `index.html` muss im Stammverzeichnis liegen.
4. Im Repository **Settings → Pages** öffnen.
5. Unter **Build and deployment** als Source **Deploy from a branch** wählen.
6. Branch `main`, Ordner `/(root)` wählen und speichern.
7. Nach der Veröffentlichung ist die Website typischerweise unter `https://DEIN-USERNAME.github.io/ww-rezeptbibliothek/` erreichbar.

## WeightWatchers-Import testen
1. Die veröffentlichte Rezeptseite öffnen, nicht nur die Startseite.
2. Die vollständige URL der Rezeptseite kopieren.
3. In WeightWatchers die Funktion zum Import eines Rezepts aus dem Internet öffnen und die URL einfügen.
4. Prüfen, ob alle Zutaten, Mengen und Portionen korrekt erkannt wurden.
5. Bei Fehlern Zutaten in WW korrigieren oder manuell ergänzen.

**Wichtig:** JSON-LD ist ein verbreitetes strukturiertes Rezeptformat, aber WeightWatchers garantiert nicht, dass jede externe Website importiert werden kann. Dieser Prototyp muss daher in deinem konkreten WW-App-Konto getestet werden. Die Points werden von WeightWatchers berechnet und sind nicht Teil der Rezeptseite.

## Weitere Rezepte ergänzen
Eine Kopie von `recipes/kung-pao-chicken.html` erstellen, Dateinamen und sichtbare Rezeptinhalte ändern und im JSON-LD-Block mindestens diese Felder anpassen:
- `name`
- `description`
- `recipeYield`
- `recipeIngredient`
- `recipeInstructions`

Anschließend in `index.html` eine weitere Rezeptkarte mit einem Link auf die neue HTML-Datei ergänzen.

## Datenschutz
GitHub Pages ist öffentlich. Veröffentliche dort keine privaten Informationen, persönlichen Notizen oder Daten, die nicht öffentlich sein sollen. Ein öffentliches Repository und seine Seiten können von anderen aufgerufen werden.

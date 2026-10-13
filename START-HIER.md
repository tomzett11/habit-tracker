# Gewohnheiten – dein iPhone-Tracker

## Was enthalten ist

- Beliebig viele Gewohnheiten mit Name, Farbe und Icon
- Tägliches Abhaken auf der Übersicht
- Monatskalender: vergangene Tage antippen, um Erledigungen einzutragen oder zu ändern
- Heatmap mit 26 Wochen; Wochentage laufen von oben nach unten und ältere Wochen liegen rechts
- Sicherung als JSON-Datei und Wiederherstellung aus einer Sicherungsdatei
- Offline-Grundfunktion nach dem ersten Laden

## Daten und Sicherungen

Die Daten werden lokal im Browser auf genau diesem iPhone gespeichert. Sie werden nicht automatisch synchronisiert und könnten verloren gehen, wenn du die Browserdaten löschst oder das Gerät wechselst. Tippe in der Übersicht auf ⇧, um eine Sicherungsdatei zu laden. Bewahre sie an einem Ort auf, den du später wiederfindest. Mit ⇩ kannst du eine Sicherung wiederherstellen; dabei wird die aktuelle Liste ersetzt.

## Online stellen und zum Startbildschirm hinzufügen

Damit iPhone Safari die Seite als Web-App hinzufügen kann, muss sie über eine sichere HTTPS-Adresse erreichbar sein. Ein einfacher kostenloser Weg ist GitHub Pages:

1. Erstelle ein GitHub-Konto und ein neues öffentliches Repository.
2. Lade alle vier Dateien aus diesem Ordner in das oberste Verzeichnis des Repositories hoch.
3. Öffne im Repository **Settings → Pages** und wähle **Deploy from a branch**, Branch **main**, Ordner **/(root)**. Speichere die Einstellung.
4. Warte, bis GitHub Pages die angezeigte Webadresse bereitstellt. Öffne diese Adresse auf dem iPhone in **Safari**.
5. Tippe auf **Teilen** (Quadrat mit Pfeil nach oben), dann **Zum Home-Bildschirm** und anschließend **Hinzufügen**.

GitHub Pages veröffentlicht die App-Dateien öffentlich. Die Gewohnheitsdaten selbst liegen weiterhin lokal auf deinem iPhone und werden nicht an GitHub übertragen. Falls du kein öffentliches Repository möchtest, können wir als nächsten Schritt einen privaten bzw. anderen Hosting-Weg auswählen.

## Erste Schritte

1. Tippe auf **Gewohnheit hinzufügen**.
2. Gib einen Namen ein, wähle ein Icon und eine Farbe und tippe auf **Speichern**.
3. Tippe täglich auf das Kästchen rechts neben dem Namen.
4. Tippe auf die Gewohnheit, um den Monatskalender und die Wochen-Heatmap zu öffnen.

## Grenzen der ersten Version

Die Daten synchronisieren sich nicht zwischen mehreren Geräten. Die Heatmap zeigt die letzten 26 Wochen. Die App kann offline öffnen, sobald sie einmal online geladen wurde. Für automatische Synchronisierung wäre später ein Konto mit einer Datenbank nötig.

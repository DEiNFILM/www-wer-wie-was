# Qualitätszentrale v1 – PR-Beschreibung

## Ziel
Die WWW-Beta erhält eine lokale Qualitätsansicht für ausschließlich lokale Testdaten. Es werden keine externen Plattformen abgefragt, keine APIs benötigt und keine Live-Daten behauptet.

## Geänderte Dateien
- `quality-center.html` – neue, mobile-first Qualitätsansicht mit Filtern, Quellenstatus, Qualitätsampel, Linkstatus, Aktualität, Dublettenhinweisen und lokalem Feedback.

## Nutzerwirkung
- Qualitätsinformationen werden verständlich und ohne Tabellenflut dargestellt.
- Quellen können nach Status und Qualitätsampel gefiltert werden.
- Problematische oder veraltete Testquellen sind sichtbar gekennzeichnet.
- Feedback bleibt lokal im Browser und wird nicht übertragen.
- Die öffentliche Suche und die Top-3-Ergebnisse bleiben unverändert.

## Einschränkungen
- Alle Einträge sind lokale Testdaten.
- Linkstatus und Aktualität sind Beispiele, keine Live-Prüfungen.
- Es gibt keine Serverpersistenz, Anmeldung, API-Anbindung oder externe Abhängigkeit.
- Die Qualitätsseite muss nach dem Merge noch über einen sichtbaren Beta-/Qualitätslink in der öffentlichen Oberfläche erreichbar gemacht werden.

## Manuelle Tests
- [ ] `quality-center.html` direkt öffnen und auf Mobil- und Desktopbreite prüfen.
- [ ] Quellenstatus-Filter auf `verified`, `pilot`, `paused` und `blocked` testen.
- [ ] Qualitätsfilter auf Grün, Gelb, Rot und eine Kombination mit dem Statusfilter testen.
- [ ] Feedback für einen Eintrag anklicken, Seite neu laden und lokale Speicherung prüfen.
- [ ] Einen Filter ohne Treffer auswählen und den hilfreichen Leerzustand prüfen.
- [ ] Prüfen, dass keine externen Skripte, Stylesheets, APIs oder Schlüssel eingebunden sind.

## Review-Hinweis
Bitte nach dem Review einen manuellen Browser-Test durchführen. Die Seite ist für die statische GitHub-Pages-Beta gedacht und soll gegen `main` gemergt werden.

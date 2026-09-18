# WWW Qualitätszentrale v1

## Geänderte Dateien
- `quality-center.html`: klar getrennter Beta-/Qualitätsbereich mit lokalen Testquellen, Quellenstatus, Qualitätsampel, Aktualität, Linkstatus, Dubletten-Hinweisen, Filtern und lokalem Feedback.

## Nutzerwirkung
- Qualitätsrisiken sind nachvollziehbar sichtbar, ohne die öffentliche Suche mit einer Tabellenansicht zu überladen.
- Quellen können nach Status und Qualitätsampel gefiltert werden.
- Feedback bleibt im Browser und wird nicht an einen Server übertragen.

## Einschränkungen
- Ausschließlich lokale Testdaten.
- Linkstatus und Aktualität sind statische Beispiele, keine Live-Prüfungen.
- Kein Backend, keine Anmeldung, keine APIs, kein Scraping und keine externen Abhängigkeiten.
- Die bestehende öffentliche Suche bleibt unverändert; der Qualitätsbereich ist separat erreichbar.

## Manuelle Tests
1. `quality-center.html` auf Mobil- und Desktopbreite öffnen und den Link zurück zur Suche prüfen.
2. Quellenstatus und Qualitätsampel einzeln sowie kombiniert filtern; einen leeren Filterzustand prüfen.
3. Alle Feedbackoptionen für eine Quelle testen, Seite neu laden und die lokale Speicherung im selben Browser prüfen.

## Review
Bitte gegen `main` prüfen. Besonders auf lokale-only Daten, sichtbare Statuswerte, Kontrast, Tastaturbedienbarkeit und fehlende externe Abhängigkeiten achten.

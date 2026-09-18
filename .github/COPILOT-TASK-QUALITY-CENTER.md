# Copilot-Auftrag: WWW Qualitätszentrale v1

Lies zuerst `.github/copilot-instructions.md` vollständig. Halte jede dort definierte Regel ein.

## Ziel
Baue die nächste sichere WWW-Erweiterung: eine lokale Qualitätszentrale für die Beta. Sie darf keine externe Plattform scrapen, keine API-Schlüssel verlangen und keine Live-Daten behaupten.

## Aufgabe
Erweitere die vorhandene statische WWW-Beta so, dass sie zusätzlich eine kleine, klare interne Qualitätsansicht vorbereitet. Nutze ausschließlich lokale Testdaten.

## Erforderliche Funktionen
- Quellenstatus: verified, pilot, restricted, paused, blocked.
- Qualitätsampel pro Treffer: grün, gelb oder rot.
- Beispiele für Linkstatus: erreichbar, prüfen, defekt.
- Beispiele für Aktualität: aktuell, älter, abgelaufen.
- Dubletten-Hinweis für ähnliche Treffer.
- Lokales Feedback: passt, unpassend, Link kaputt, Problem melden.
- Erklärung, dass Feedback in der Beta nur lokal gespeichert wird.
- Öffentliche Suchoberfläche darf minimalistisch bleiben; Admin-Informationen nur hinter einem klaren Beta-/Qualitätsbereich zeigen.

## UX
Mobile-first. Keine Tabellenflut auf der öffentlichen Startseite. Keine Werbung. Keine dunklen Muster. Nutzer sollen weiter in wenigen Sekunden einen direkten Link erreichen.

## Codequalität
Keine externe Abhängigkeit. Kein Framework-Zwang. Zugängliche Buttons und ausreichender Kontrast. Bestehende Funktionen nicht zerstören. Baue Fehler- und Leerzustände ein. Kommentiere kurz, warum Testdaten keine Live-Daten sind.

## Fertigstellung
Erstelle einen Pull Request gegen `main`. Beschreibe im Pull Request: geänderte Dateien, Nutzerwirkung, Einschränkungen und mindestens drei manuelle Tests. Fordere anschließend einen Copilot-Code-Review an.

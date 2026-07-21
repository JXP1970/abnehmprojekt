# Projekt −10 kg

Eine eigenständige Single-File-Web-App zum Abnehmen im Bauplan-/Baustellen-Design.
Alles steckt in einer einzigen HTML-Datei — kein Build, kein Server, kein Konto.

## Funktionen

- **Planung** – Grunddaten erfassen, Grund-/Gesamtumsatz (BMR/TDEE), Tagesziel, Defizit und Zieltermin berechnen
- **Gewicht** – tägliche Messungen eintragen, Soll-Ist-Vergleich mit Verlaufsdiagramm und 7-Tage-Schnitt
- **Ernährung** – Tagesziele für Kalorien/Makros, Tagebuch mit Lebensmittel-Datenbank, Beispieltag und Einkaufsliste
- **Sport** – Wochenprogramm, zwei Kraft-Einheiten (Ganzkörper), Ausdauer, Trainings-Log
- **Woche** – wöchentlicher Gewohnheits-Check, Troubleshooting, Daten-Export (JSON) und Reset

## Nutzung

Die Datei [`abnehmprojekt.html`](abnehmprojekt.html) einfach im Browser öffnen.

> **Hinweis zur Speicherung:** Die App nutzt aktuell die `window.storage`-API (Claude-Artifact-Umgebung).
> Als lokale Datei im Browser geöffnet werden Daten dadurch nicht dauerhaft gespeichert.
> Für eigenständigen Betrieb müsste die Speicherung auf `localStorage` umgestellt werden.

## Hinweis

Kein Ersatz für ärztlichen Rat. Bei Vorerkrankungen, Medikamenten oder Beschwerden
vorher den Hausarzt konsultieren.

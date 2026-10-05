<!-- ELUCENIA technical documentation · fracao-de-excrecao-de-ureia · de · no clinical/professional/rights approval -->

# Fraktionelle Harnstoffausscheidung (FEHarnstoff)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/fracao-de-excrecao-de-ureia)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Urinharnstoff

`uur`

mg/dL · Bereich: 10–5000

### Serumharnstoff

`pur`

mg/dL · Bereich: 10–600

### Urinkreatinin

`ucr`

mg/dL · Bereich: 1–500

### Serumkreatinin

`pcr`

mg/dL · Bereich: 0,2–20

## Fassung der Methode

FEUrea/Carvounis 2002: 100×Uurea×PCr/(Purea×UCr); einheitliche Harnstoff/BUN-Messgrößen

## Dokumentierte Formel

FEUrea (%) = (Urinharnstoff × Serumkreatinin) ÷ (Serumharnstoff × Urinkreatinin) × 100.

Harnstoff oder BUN liefern dasselbe Ergebnis, wenn Blut und Urin dieselbe Messgröße verwenden.

## Grenzen und Population

Die Studie von 2002 bewertete Episoden akuten Nierenversagens, einschließlich prärenaler Ursachen mit und ohne Diuretika sowie Tubulusnekrose. Die Harnstoffausscheidungsfraktion war in diesem Vergleich weniger durch Diuretika beeinflusst; das macht sie weder von allen Störfaktoren unabhängig noch bestätigt die Schwelle allein die Ursache.

## Referenzen

- [Carvounis CP, Nisar S, Guro-Razuman S. Significance of the fractional excretion of urea in the differential diagnosis of acute renal failure. Kidney Int, 2002.](https://doi.org/10.1046/j.1523-1755.2002.00683.x)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026

# UC-06b: Aktiv-Invest (AI) GmbH — ROI-Berechnung & Business Case
> KI-Manager
> ⚠️ Nicht vertraulich — Teilnehmer-Version

---

## Szenario

Du bist Portfoliomanager:in der **Aktiv-Invest (AI) GmbH**. Das Go/No-Go-Screening (Phase 1) habt ihr konzeptionell abgeschlossen. Jetzt geht es um die Investitionsentscheidung selbst: Dr. Vogt will wissen, ob die Entwicklung eines KI-gestützten Bewertungssystems wirtschaftlich sinnvoll ist — **bevor** das Team Zeit und Geld in die Umsetzung steckt.

**Das Setting:** Die Aktiv-Invest (AI) GmbH erhält monatlich Ø 17 Investitionsvorschläge (15–20 Range). Rund 50 % bestehen die Go/No-Go-Prüfung und gehen in die Detailbewertung (Phase 2) über. Phase 2 umfasst Umsatz- und Einsparungsanalyse, Kostenstruktur und — bei konkretem Interesse — eine DCF-Modellierung mit drei Szenarien.

**Die Entscheidungsfrage:** Lohnt sich der Aufbau eines KI-Systems, das die Bewertungsarbeit der Analysten messbar beschleunigt?

---

## Deine Aufgabe

Berechne den **Return on Investment (ROI)** für die Einführung eines KI-gestützten Investment-Bewertungssystems bei der Aktiv-Invest (AI) GmbH.

Nutze dafür das **ROI-Template (Excel)** oder den **interaktiven ROI-Rechner (HTML)** als Werkzeug.

---

### Schritt 1 — IST-Prozesskosten ermitteln

Berechne die jährlichen Personalkosten des heutigen manuellen Screening- und Bewertungsprozesses:

| Parameter | Wert |
|---|---|
| Vorgänge / Monat | Ø 17 (15–20) |
| Grobprüfung (Phase 1) je Vorgang | 3,0 h |
| Anteil mit Detailprüfung (Phase 2) | 50 % |
| Detailprüfung je Vorgang | 12,0 h |
| Vollkosten Analyst:in | 120 €/h |

Berechne: Gesamt-Analyststunden IST pro Jahr → Jährl. Prozesskosten IST.

---

### Schritt 2 — SOLL-Prozesskosten mit KI-Unterstützung

Schätze die Zeitersparnis durch ein KI-Bewertungssystem — basierend auf Benchmarks für NLP-Screening-Systeme:

| Effizienzgewinn | Annahme |
|---|---|
| Zeitersparnis Grobprüfung (Phase 1) | 70 % |
| Zeitersparnis Detailprüfung (Phase 2) | 50 % |

Berechne: Gesamt-Analyststunden SOLL → Jährl. Prozesskosten SOLL → **Jährl. Einsparung**.

---

### Schritt 3 — Investitionskosten schätzen

Schätze die Kosten für Aufbau und Betrieb des Systems:

| Kostenart | Betrag |
|---|---|
| Entwicklung & Implementierung | 55.000 € |
| Datenvorbereitung & Integration (Crunchbase-API, interne DB) | 15.000 € |
| Schulung & Change Management | 5.000 € |
| **Einmalige Investition gesamt** | **75.000 €** |
| Infrastruktur & Cloud / Jahr | 12.000 € |
| Wartung, Modell-Pflege, Updates / Jahr | 8.000 € |
| **Jährl. Betriebskosten** | **20.000 €** |

---

### Schritt 4 — ROI-Kennzahlen berechnen

Berechne die drei Kernindikatoren für eine Management-Entscheidung:

1. **Payback Period** (Amortisationsdauer in Monaten)
2. **Break-even-Punkt** (erster Monat mit positivem kumulierten Cashflow)
3. **ROI über 3 Jahre** (Return on Investment in %)

Erstelle eine **5-Jahres-Timeline** mit kumuliertem Cashflow.

---

### Schritt 5 — Sensitivitätsanalyse (Erweiterungsaufgabe)

Teste die Robustheit Deiner Empfehlung mit mindestens zwei Alternativszenarien:

- **Weniger Volumen:** Was passiert, wenn die AI GmbH nur 10 statt 17 Proposals/Monat erhält?
- **Schlechtere Effizienz:** Was passiert, wenn die KI nur 50 %/35 % statt 70 %/50 % Effizienzgewinn bringt?

Ab welchem Minimalvolumen oder welcher Mindeffizienz ist das Projekt noch wirtschaftlich?

---

### Schritt 6 — Business Case formulieren

Formuliere eine Management-Empfehlung für Dr. Vogt mit den **7 Business-Case-Bausteinen**:

1. Problem / Ausgangslage (Was kostet die heutige Situation?)
2. Lösungsansatz (Was soll das KI-System tun?)
3. Kosten (TCO über 3 Jahre)
4. Harter Nutzen (messbar, belegbar)
5. Weicher Nutzen (real, aber nicht eingerechnet)
6. Opportunitätskosten (Was passiert, wenn wir es nicht tun?)
7. Empfehlung (Go / No-Go mit Bedingungen)

---

## Ergebnisdokumentation

Trage Deine Ergebnisse in das **ROI-Template** ein (Dateiname: `ROI_UC06_AktivInvest_v1.xlsx`) und halte die Eckdaten im **Steckbrief §4** fest.

Ziel: Du kannst Dr. Vogt in einem 10-Minuten-Gespräch sagen, ob das Projekt wirtschaftlich ist — und warum.

---

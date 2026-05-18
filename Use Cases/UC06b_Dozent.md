# UC-06b: ROI-Berechnung & Business Case — Dozenten-Hinweise
> alfatraining · KI-Manager
> ⚠️ Nicht für Teilnehmende

---

## Einordnung

**Kurs:** KI-Manager — Woche 1, Tag 5 (ROI-Bewertung & KI-Business-Case)  
**KI-System-Typ:** Quantitative Rentabilitätsanalyse — kein spezifisches KI-System, sondern Methodik  
**Schwierigkeitsgrad:** Mittel (Formeln einfach; Herausforderung liegt in konservativer Schätzung und Argumentation)  
**Didaktische Funktion:** Kern-Kompetenz des Tages — von der Idee zur Zahl, von der Zahl zur Entscheidung

---

## Vollständige Musterlösung

### IST-Prozesskosten

| Position | Rechnung | Ergebnis |
|---|---|---|
| Vorgänge / Jahr | 17 × 12 | 204 |
| Grobprüfung gesamt | 204 × 3,0 h | 612 h/Jahr |
| Vorgänge mit Detailprüfung | 204 × 50 % | 102 |
| Detailprüfung gesamt | 102 × 12,0 h | 1.224 h/Jahr |
| Gesamt IST | 612 + 1.224 | **1.836 h/Jahr** |
| Jährl. Kosten IST | 1.836 × 120 € | **220.320 €/Jahr** |

### SOLL-Prozesskosten mit KI

| Position | Rechnung | Ergebnis |
|---|---|---|
| Grobprüfung mit KI | 204 × 3,0 × (1 − 70 %) | 183,6 h/Jahr |
| Detailprüfung mit KI | 102 × 12,0 × (1 − 50 %) | 612,0 h/Jahr |
| Gesamt SOLL | 183,6 + 612 | **795,6 h/Jahr** |
| Jährl. Kosten SOLL | 795,6 × 120 € | **95.472 €/Jahr** |
| **Jährl. Einsparung** | 220.320 − 95.472 | **124.848 €/Jahr** |

Gesparte Stunden: 1.040,4 h/Jahr = **0,59 FTE** (220 Arbeitstage × 8 h = 1.760 h)

### Investitionskosten

Einmalig: **75.000 €** · Jährl. Betrieb: **15.000 €** (Cloud-Infrastruktur 8.000 € + Updates, Re-Training & Fine-Tuning 7.000 €)

### ROI-Kennzahlen

| Kennzahl | Rechnung | Ergebnis |
|---|---|---|
| Netto-Monatsvorteil | (124.848 − 15.000) ÷ 12 | **9.154 €/Monat** |
| Payback Period | 75.000 ÷ 9.154 | **8,2 Monate** |
| Break-even | kumulierter Cashflow ≥ 0 | **Monat 9** |
| ROI (3 Jahre) | (374.544 − 120.000) ÷ 120.000 | **212 %** |

### 5-Jahres-Timeline

| | Jahr 0 | Jahr 1 | Jahr 2 | Jahr 3 | Jahr 4 | Jahr 5 |
|---|---|---|---|---|---|---|
| Einmalige Investition | −75.000 € | — | — | — | — | — |
| Jährl. Betriebskosten | — | −15.000 € | −15.000 € | −15.000 € | −15.000 € | −15.000 € |
| Netto-Cashflow | −75.000 € | +109.848 € | +109.848 € | +109.848 € | +109.848 € | +109.848 € |
| **Kumuliert** | **−75.000 €** | **+34.848 €** | **+144.696 €** | **+254.544 €** | **+364.392 €** | **+474.240 €** |

---

## Sensitivitätsanalyse — Musterlösung

| Szenario | Anpassung | Einsparung/J | ROI (3J) | Payback | Empfehlung |
|---|---|---|---|---|---|
| Base Case | 70 %/50 %, 17/Mo. | 124.848 € | **212 %** | 8,2 Mo. | ✅ Go |
| Worst Case | 50 %/35 % Effizienz | 88.128 € | **120 %** | 12,3 Mo. | ✅ Go |
| Weniger Volumen | 10 statt 17/Mo. | 73.440 € | **84 %** | 15,4 Mo. | ✅ Go |
| Höhere Kosten | 100.000 € Erstinvestition | 124.848 € | **158 %** | 10,9 Mo. | ✅ Go |
| Best Case | 80 %/60 % Effizienz | 146.880 € | **267 %** | 6,8 Mo. | ✅ Go mit Priorität |

**Kernbotschaft für Teilnehmende:** Selbst im Worst Case (50 %/35 % Effizienz) liegt der ROI bei 120 % über 3 Jahre — und selbst bei halbiertem Volumen (10/Monat) noch bei 84 %. Alle Szenarien sind Go. Das ist eine außergewöhnlich robuste Empfehlung — verglichen mit typischen IT-Projekten im Mittelstand.

---

## Mindestvolumen-Berechnung (für erfahrene Teilnehmende)

Ab welchem Monatsvolumen amortisiert sich das Projekt innerhalb von 24 Monaten?

Bedingung: Netto-Monatsvorteil ≥ 75.000 ÷ 24 = 3.125 €/Monat  
→ (Jährl. Einsparung − 15.000) ÷ 12 ≥ 3.125  
→ Jährl. Einsparung ≥ 52.500 €  
→ Bei 70 %/50 % Effizienz: Mindest-Vorgänge/Monat ≈ **7,2** (also ab 8/Monat)

Das bedeutet: Selbst wenn die AI GmbH nur 8 Proposals/Monat hätte, wäre das Projekt innerhalb von 24 Monaten amortisiert. Das schärft das Verständnis für die Skalierungshebel.

---

## Business Case — Musterlösung (Kurzform)

| Baustein | UC-06 Antwort |
|---|---|
| **Problem** | 220.320 €/Jahr Screening-Kosten · Kapazitätsdeckel bei 20 Proposals/Monat · Inkonsistente Bewertungsqualität |
| **Lösung** | KI-gestütztes NLP-Screening + Detailbewertungs-Support · Human-in-the-Loop · Integration Crunchbase/PitchBook |
| **Kosten** | 75.000 € einmalig + 15.000 €/Jahr = 120.000 € über 3 Jahre |
| **Harter Nutzen** | 124.848 €/Jahr · ROI 212 % · Payback 8,2 Monate · Break-even Monat 9 |
| **Weicher Nutzen** | Kapazitätsskalierung auf 25–30 Proposals/Monat · konsistenteres Scoring · schnellere Time-to-Decision · LP-Reporting-Qualität |
| **Opportunitätskosten** | 220.320 €/Jahr bleiben · Fondswachstum auf 100 Mio. € ohne Kapazitätsaufbau nicht erreichbar |
| **Empfehlung** | ✅ Go — vorbehaltlich: ML-Engineering-Ressource (Ben Fischer, ~40 % FTE), DSGVO-Prüfung Gründer-Scoring, KAGB-konformes Dokumentationskonzept |

---

## Didaktische Hinweise

**DCF-Frage:** Teilnehmende mit Finance-Background werden DCF vermissen. Antwort: *"DCF ist Standard bei langen Zeithorizonten und bekanntem WACC. Bei internen Effizienzprojekten mit kurzer Amortisation und hoher Unsicherheit in den Eingangsdaten schafft DCF Scheingenauigkeit. Der ROI reicht für Go/No-Go auf dieser Entscheidungsebene."* — Das Excel-Template hat eine optionale NPV-Zeile; erfahrene Teilnehmende können das selbst erkunden.

**Warum ist der ROI so hoch?** Das Investment-Umfeld hat extrem hohe Stundensätze (120 €/h Analyst) kombiniert mit hohem Volumen und starker Automatisierbarkeit der Recherche-Arbeit. Das ist kein ungewöhnliches Ergebnis für wissensintensive Prozesse mit hoher Wiederholungsrate — und genau der Grund, warum KI im Finance-Bereich so schnell ROI erzeugt.

**Weiche Nutzen als strategische Argumente:** Die Skalierung auf 25–30 Proposals/Monat ist das eigentliche strategische Argument. Das unterstützt das Fondswachstumsziel direkt — und das kann Sophie Krane gegenüber Dr. Vogt quantifizieren: 30 Proposals × 3x Return-Multiple × Ø 1 Mio. EUR Ticket → potenziell deutlich mehr Deal-Flow-Kapazität pro Jahr.

---

## Verbindung zu anderen Kursinhalten

| Tag / UC | Thema | Verbindung |
|---|---|---|
| Tag 5 allgemein | ROI-Methodik | UC-06b ist die Musterlösung für die Tageskompetenz |
| UC-06a | Phase 1 Screening | Phase 2 setzt voraus, dass Phase 1 konzeptionell verstanden wurde |
| UC-06c (KI-Transformation) | Portfolio-Monitoring | Dieselbe Dateninfrastruktur, andere Anwendung |
| Steckbrief §4 | Geschäftlicher Mehrwert | ROI-Ergebnis fließt direkt in den Steckbrief ein |

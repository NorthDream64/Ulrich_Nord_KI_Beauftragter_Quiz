# UC-06c: Aktiv-Invest (AI) GmbH — KI-gestütztes Portfoliomonitoring
> KI-Manager angewandte Transformation
> ⚠️ Nicht vertraulich — Teilnehmer-Version

---

## Szenario

Du bist Portfoliomanager:in der **Aktiv-Invest (AI) GmbH**. Das KI-Screening-System für neue Proposals läuft seit sechs Monaten erfolgreich. Jetzt steht das nächste Problem: das **laufende Monitoring** der sechs Portfoliounternehmen.

Julia Romberg (CFO) hat ein klares Bild davon, was sie braucht: *„Ich will bei jedem Quartalsbericht sofort sehen, welche Beteiligungen Alarm schlagen — ohne drei Tage händische Pivot-Tabellen."*

Aktuell liefern alle sechs Portfoliounternehmen monatliche KPI-Reports — in unterschiedlichen Formaten (PDF, Excel, Google Sheets). Die Konsolidierung dauert 2–3 Tage vor jedem Quartalsmeeting. Abweichungen vom Plan fallen oft erst im Nachhinein auf.

---

## Die Portfoliounternehmen (vereinfacht)

| Unternehmen | Segment | ARR (aktuell) | Wachstum YoY | EBITDA-Marge | Rule of 40 |
|---|---|---|---|---|---|
| **FlowML** | KI-Prozessautomatisierung | 1,2 Mio. € | +55 % | −12 % | **43 %** ✅ |
| **DataBridge** | Datenmigrations-KI | 800 T € | +22 % | +8 % | **30 %** ⚠️ |
| **ClearScan** | Dokumenten-KI (Health) | 2,1 Mio. € | +18 % | +14 % | **32 %** ⚠️ |
| **NexusChat** | Enterprise-LLM | 400 T € | +95 % | −45 % | **50 %** ✅ |
| **TrustLayer** | KI-Compliance | 600 T € | +10 % | +5 % | **15 %** 🔴 |
| **VizLogic** | KI-Visualisierung | 1,8 Mio. € | +35 % | +18 % | **53 %** ✅ |

*ARR = Annual Recurring Revenue · Rule of 40 = Wachstum % + EBITDA-Marge %*

---

## Deine Aufgabe

### Aufgabe 1 — Rule of 40 verstehen und anwenden

Berechne die **Rule of 40** für jedes Portfoliounternehmen und interpretiere die Ergebnisse:
- Was bedeutet ein Wert unter 40 % in einem Frühphasen-Unternehmen?
- Welche zwei Portfoliounternehmen erfordern sofortige Aufmerksamkeit — und warum?
- Ist die Rule of 40 immer die richtige Metrik? Für welche Unternehmenstypen oder -phasen hat sie Schwächen?

---

### Aufgabe 2 — KPI-Monitoring-System konzipieren

Julia Romberg will ein KI-gestütztes Dashboard, das:
1. Monatliche KPI-Reports der Portfoliounternehmen **automatisch konsolidiert** (unabhängig vom Eingabeformat)
2. Plan-Ist-Abweichungen **visuell hervorhebt** (Ampel-Logik)
3. **Frühwarnsignale** ausgibt, wenn ein Unternehmen 2+ aufeinanderfolgende Monate negativ abweicht
4. Das **Quartalssreporting für LPs** (private Anleger) vorbereitet

Konzipiere dieses System:
- Welche KPIs sollen überwacht werden? (Mindestens 6, begründet)
- Wie funktioniert die Datenerfassung? (Format, Frequenz, Qualitätssicherung)
- Wie sieht das Dashboard aus? (Skizze oder Beschreibung der wichtigsten Ansichten)
- Welche KI-Funktionen sind sinnvoll — und welche sind Overkill?

---

### Aufgabe 3 — Interpretationsaufgabe

TrustLayer (Rule of 40: 15 %) und DataBridge (Rule of 40: 30 %) liegen unter der 40-%-Schwelle. 

Entwickle für **einen dieser beiden Fälle** eine Analyse-Storyline:
- Warum liegt der Wert unter 40 %?
- Ist das ein strukturelles Problem oder eine Wachstumsphase?
- Welche drei Fragen würdest Du im nächsten Board-Meeting stellen?
- Welche KI-Tools könnten Dir bei der Vorbereitung dieses Gesprächs helfen?

---

### Aufgabe 4 — Grenzen der Metrik (Diskussionsaufgabe)

Die Rule of 40 ist eine verbreitete Heuristik in der SaaS- und VC-Welt. Aber sie hat blinde Flecken.

Diskutiert in der Gruppe: 
- In welchen Situationen wäre ein Unternehmen mit Rule-of-40-Wert von 15 % trotzdem ein gutes Investment?
- Welche zusätzlichen Metriken würdet ihr in ein robustes KI-Monitoring einbauen?

---

## Hintergrundwissen: Rule of 40

Die **Rule of 40** wurde popularisiert durch Brad Feld (Foundry Group) und ist heute ein Standard-KPI in der SaaS-Investmentwelt.

**Formel:** Rule of 40 = Wachstumsrate (% YoY) + EBITDA-Marge (%)

**Interpretation:**
- **≥ 40 %:** Gesundes Wachstums-Profitabilitäts-Gleichgewicht
- **30–40 %:** Grenzbereich — beobachten
- **< 30 %:** Alarm — entweder zu langsam wachsend oder zu unprofitabel (oder beides)

**Wichtig:** Die Metrik ist für **SaaS/Subscription-Modelle** konzipiert. Sie funktioniert weniger gut für Hardware-Unternehmen, Marktplätze mit netto-negativer Unit Economics oder sehr frühphasige Pre-Revenue-Startups.

Quelle: [Techcrunch — The Rule of 40 for SaaS Companies](https://techcrunch.com/2015/02/01/the-rule-of-40-for-saas-companies/) · [Brad Feld — Rule of 40](https://feld.com/archives/2015/02/rule-40-healthy-saas-company.html)

---

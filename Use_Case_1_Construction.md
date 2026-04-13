# KI Use Cases — KI-Beauftragter (Modul 764)
> TÜV Rheinland · Stand: April 2026  
> Autor: Ulrich Nord  
> Format: Jeder Use Case beschreibt eine reale Einsatzsituation und wird hinsichtlich EU AI Act, DSGVO, Ethik und IT-Sicherheit eingeordnet.

---

## UC-01a: Nachtragsprüfung im Bauplanungsbüro (Betreiber-Stufe)

**Branche/Kontext:** Bauwesen, KMU, Architektur- und Ingenieurbüro  
**Kursbezug:** Woche 1–2, Tag 3–4  
**Rollenrelevanz:** KI-Beauftragter (Governance), IT-Sicherheit (Systemarchitektur)  
**Schwierigkeitsgrad:** Anfänger/Einsteiger

### Szenario
Ein Bauplanungsbüro mit 15 Mitarbeitenden setzt ein KI-System ein, das Nachträge (Änderungsanforderungen während der Bauphase) automatisch gegen den Originalvertrag und die gültigen Baugesetze (VOB/B, BGB Werkvertragsrecht) prüft. Das System liefert eine Einschätzung, ob der Nachtrag durch den bestehenden Vertrag abgedeckt ist oder eine Zusatzbeauftragung des Auftraggebers erfordert. Das Büro hat das System eingekauft und betreibt es — es wurde nichts am Modell verändert.

### KI-System-Typ
Dokumentenanalyse / Legal AI / RAG-System (Retrieval Augmented Generation)

### Prüfdimensionen

| Dimension | Bewertung | Details |
|---|---|---|
| **EU AI Act — Risikoklasse** | Begrenztes Risiko | Keine direkte Entscheidung über Personen; Einfluss auf Vertragsverhältnisse zwischen Unternehmen. Anhang III nicht einschlägig. |
| **EU AI Act — Rolle** | Betreiber (Art. 3 Nr. 4) | Büro kauft und betreibt das System, verändert es nicht. Betreiberpflichten gelten, aber keine Anbieterpflichten. |
| **DSGVO** | Weitgehend unkritisch | Sofern Verträge keine personenbezogenen Daten enthalten. Prüfpflicht: Enthält der Vertrag Namen natürlicher Personen (z.B. Subunternehmer)? |
| **Halluzinationsrisiko** | ⚠️ Hoch und kritisch | Falsche Rechtsauslegung kann zu Vertragsstreitigkeiten führen. RAG-Architektur mit aktuellen Gesetzestexten zwingend empfohlen. |
| **Human-in-the-Loop** | Zwingend empfohlen | KI liefert Einschätzung, Projektleiter/Jurist entscheidet final. |
| **Turing Institute — Ethik** | Transparency & Accountability | Entscheidungsweg muss dokumentiert und nachvollziehbar sein. |
| **CIS / IT-Sicherheit** | Mittel | Vertragsdaten sind sensibel; Zugriffsrechte und Logging erforderlich. |

### Lernziele für den Kurs
- Unterschied Betreiber vs. Anbieter praktisch verstehen
- Risikoklassen des EU AI Act anwenden
- Halluzinationsrisiko bei Legal AI einschätzen
- Human-in-the-Loop als Gestaltungsprinzip

### Quellen
- EU AI Act, Art. 3 Nr. 3/4: https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=OJ:L_202401689
- EU AI Act Explorer (interaktiv): https://artificialintelligenceact.eu/
- Rohrlich, *KI und Recht*, Hanser 2024

---

## UC-01b: Lieferanten- und Personalplanung (Hochrisiko-Grenzfall)

**Branche/Kontext:** Bauwesen, KMU — Erweiterung von UC-01a  
**Kursbezug:** Woche 2–3, Tag 8–9  
**Rollenrelevanz:** KI-Beauftragter (DSGVO/Hochrisiko), IT-Sicherheit (API-Sicherheit, Datenschutz)  
**Schwierigkeitsgrad:** Fortgeschrittene

### Szenario
Das Büro erweitert das KI-System: Es soll nun auch Lieferantenanfragen (Materialverfügbarkeit, Liefertermine) und Personalplanung (Skill-Abgleich, Verfügbarkeit von Mitarbeitenden für Projekte) unterstützen. Bei der Personalplanung werden personenbezogene Daten (Qualifikationen, Verfügbarkeiten, ggf. Weiterbildungshistorie) verarbeitet. Das Büro bleibt Betreiber.

### KI-System-Typ
Planungs- und Entscheidungsunterstützungssystem / Workflow-KI

### Prüfdimensionen

| Dimension | Bewertung | Details |
|---|---|---|
| **EU AI Act — Risikoklasse (Lieferanten)** | Begrenztes Risiko | B2B-Kontext, keine Verbraucherdaten, keine Entscheidung über Personen. |
| **EU AI Act — Risikoklasse (Personal)** | ⚠️ Mögliches Hochrisiko | Anhang III Nr. 4: KI zur Personalentscheidungsunterstützung. Prüfpflicht: Beeinflusst die KI Einstellungs-, Einsatz- oder Beförderungsentscheidungen? |
| **DSGVO — Personalbereich** | ⚠️ Kritisch | Art. 6 (Rechtsgrundlage), Art. 9 (besondere Kategorien möglich), Art. 22 (automatisierte Entscheidung). DSFA wahrscheinlich Pflicht. |
| **Betriebsrat** | ⚠️ Mitbestimmungspflichtig | § 87 Abs. 1 Nr. 6 BetrVG: KI-gestützte Leistungs- und Verhaltensüberwachung ist mitbestimmungspflichtig. |
| **Transparenz gegenüber Mitarbeitenden** | Pflicht | Art. 13/14 DSGVO: Informationspflicht. Art. 15 DSGVO: Auskunftsrecht über KI-gestützte Einschätzungen. |
| **CIS / IT-Sicherheit** | ⚠️ Erhöht | API-Anbindung an Lieferantensysteme: Schnittstellensicherheit, Authentifizierung, Datenminimierung. |
| **Turing Institute — Fairness** | Relevant | Skill-Bewertungen dürfen keine diskriminierenden Muster aus historischen Daten reproduzieren. |

### Lernziele für den Kurs
- DSGVO und EU AI Act als parallele Rechtsrahmen erkennen
- Hochrisiko-Grenzfälle sicher identifizieren
- DSFA-Pflicht einschätzen
- Betriebsrat und Mitbestimmung im KI-Kontext

### Quellen
- EU AI Act, Anhang III: https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=OJ:L_202401689
- EDPB Guidelines AI & DSGVO: https://edpb.europa.eu/our-work-tools/our-documents/guidelines/guidelines-032024-processing-personal-data-through-ai_en
- GDPR Art. 22 (automatisierte Entscheidungen): https://gdpr-info.eu/art-22-gdpr/
- BetrVG § 87: https://www.gesetze-im-internet.de/betrvg/__87.html

---

## UC-01c: Preiskalkulation mit proprietären Daten (Rollenwechsel Betreiber → Anbieter)

**Branche/Kontext:** Bauwesen, KMU — Ausbaustufe von UC-01a/b  
**Kursbezug:** Woche 3–4, Tag 14–15  
**Rollenrelevanz:** KI-Beauftragter (Compliance, Risikomanagement), IT-Sicherheit (Datenschutz, Systemarchitektur)  
**Schwierigkeitsgrad:** Fortgeschrittene

### Szenario
Das Büro möchte das eingekaufte KI-System mit eigenen Projektdaten (abgeschlossene Projekte, Kalkulationen) und internen Expertenschätzungen anreichern, um automatisierte Preisvorschläge für neue Nachträge zu generieren. Geplant ist ein Fine-Tuning oder die Integration einer proprietären Wissensdatenbank (RAG mit internen Daten). Das System erhält damit eine **neue Zweckbestimmung** (Preiskalkulation statt reiner Rechtsprüfung).

### KI-System-Typ
Fine-tuned Legal/Commercial AI / RAG mit proprietären Unternehmensdaten

### ⚠️ Kernproblem: Rollenwechsel

Nach Art. 25 Abs. 1 EU AI Act und der Kommentierung bei Rohrlich (*KI und Recht*, S. 165f.):

> **Wer ein KI-System wesentlich verändert oder dessen Zweckbestimmung ändert, wird rechtlich zum Anbieter und übernimmt die volle Anbieterhaftung.**

Das Büro ist ab diesem Moment **nicht mehr Betreiber**, sondern **Anbieter** im Sinne des EU AI Act.

### Neue Pflichten als Anbieter

| Pflicht | Rechtsgrundlage | Aufwand für KMU |
|---|---|---|
| Risikomanagementsystem | Art. 9 EU AI Act | ⚠️ Erheblich |
| Technische Dokumentation (vor Inverkehrbringen) | Anhang IV EU AI Act | ⚠️ Erheblich |
| CE-Kennzeichnung + EU-Registrierung | Art. 48, 49 EU AI Act | ⚠️ Erheblich |
| Konformitätsbewertung | Art. 43 EU AI Act | ⚠️ Erheblich |
| Post-Market-Monitoring | Art. 72 EU AI Act | Laufend |
| Human Oversight (zwingend) | Art. 14 EU AI Act | Organisatorisch |
| Qualitätsmanagementsystem | Art. 17 EU AI Act | Strukturell |

### Zusätzliche Risiken durch proprietäre Daten

| Risiko | Dimension | Konkret |
|---|---|---|
| **Geschäftsgeheimnisse** | GeschGehG / Vertragsrecht | Werden Kalkulationsdaten in ein externes Cloud-Modell eingespeist? AGB und Datenweitergabe des Anbieters prüfen. |
| **Datenqualität / Bias** | Art. 10 EU AI Act | Historische Schätzungen können systematische Verzerrungen enthalten → fehlerhafte Preisvorschläge. |
| **Halluzination bei Zahlen** | Zuverlässigkeit | LLMs bei numerischen Ausgaben besonders fehleranfällig — Validierungsschicht und menschliche Prüfung zwingend. |
| **Wettbewerbsrecht** | GWB / Art. 101 AEUV | Wenn Kalkulationsdaten mit Branchenpartnern geteilt werden: Preisabsprache-Risiko. |

### Entscheidungsbaum: Bin ich noch Betreiber?

```
Habe ich das KI-System verändert?
├── Nein → Betreiber (Betreiberpflichten)
└── Ja → Wesentliche Veränderung?
    ├── Nein (nur UI, Prompts) → Betreiber bleibt
    └── Ja (Fine-Tuning, neue Zweckbestimmung, RAG mit eigenen Daten)
        └── → Anbieter (volle Anbieterpflichten, Art. 25 Abs. 1 EU AI Act)
```

### Lernziele für den Kurs
- Rollenwechsel Betreiber → Anbieter sicher erkennen
- Anbieterpflichten im EU AI Act kennen und einordnen
- KMU-spezifische Compliance-Last realistisch einschätzen
- Geschäftsgeheimnis- und Wettbewerbsrisiken bei proprietären KI-Daten benennen
- Empfehlung: Wann sollte ein KI-Beauftragter eskalieren?

### Quellen
- EU AI Act, Art. 25 Abs. 1 (Rollenwechsel): https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=OJ:L_202401689
- EU AI Act, Anhang IV (Technische Dokumentation): https://artificialintelligenceact.eu/
- Rohrlich, *KI und Recht*, Hanser 2024, S. 164–167
- GeschGehG (Geschäftsgeheimnisgesetz): https://www.gesetze-im-internet.de/geschgehg/

---

## Statusübersicht

| Use Case | Titel | Kurswoche | Status |
|---|---|---|---|
| UC-01a | Nachtragsprüfung (Betreiber) | Woche 1–2 | ✅ Ausgearbeitet |
| UC-01b | Lieferanten + Personal (Hochrisiko-Grenzfall) | Woche 2–3 | ✅ Ausgearbeitet |
| UC-01c | Preiskalkulation (Rollenwechsel) | Woche 3–4 | ✅ Ausgearbeitet |

---
*Letzte Aktualisierung: April 2026 — Ulrich Nord / Claude (Anthropic)*

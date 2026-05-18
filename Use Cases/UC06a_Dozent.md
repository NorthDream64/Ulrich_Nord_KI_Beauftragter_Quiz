# UC-06a: Go/No-Go-Screening — Dozenten-Hinweise
> alfatraining · KI-Manager
> ⚠️ Nicht für Teilnehmende

---

## Einordnung

**Kurs:** KI-Manager — Woche 1, Tag 3 (Use-Case-Identifikation & Priorisierung)  
**KI-System-Typ:** NLP-gestütztes Screening-System (Dokumentenanalyse + strukturierte Recherche)  
**Schwierigkeitsgrad:** Mittel  
**Didaktische Funktion:** Use-Case-Canvas und Impact/Effort-Einordnung im Kontext eines realen Investment-Workflows — zeigt, warum Strukturierung vor Automatisierung kommt

---

## Was ein gutes Konzept enthält

**Bewertungsrahmen (5–8 Kriterien):**  
Teilnehmende sollten erkennen, dass nicht alle Kriterien gleich maschinell prüfbar sind:

| Kriterium | Automatisierbar? | Begründung |
|---|---|---|
| Marktgröße (TAM/SAM) | ✅ Gut | Crunchbase, Gartner-Reports, Statista — strukturierte Daten |
| Wettbewerbssituation | ✅ Gut | Crunchbase-Wettbewerber, G2/Capterra-Kategorien |
| Team-Background | ⚠️ Teilweise | LinkedIn-Profil analysierbar, aber Qualitätsurteil bleibt beim Menschen |
| Strategischer Fit | ⚠️ Schwer | Erfordert Interpretationsleistung — eher Checklisten-Support |
| Red Flags (regulatorisch) | ✅ Regelbasiert | Stichwort-basierte Prüfung in Presseartikeln, Sanktionslisten |
| IP / Technologie-Differenzierung | ⚠️ Schwer | Patentdatenbanken ja, aber Qualitätsurteil komplex |

**Schwacher Kandidat für Automatisierung:** Bewertung des Gründer-Chemie-Faktors, kultureller Fit. Das gehört explizit nicht ins Screening-System — das gehört ins persönliche Gespräch (IC-Meeting).

---

## Didaktische Hinweise

**Das Hauptlernziel:** Teilnehmende erkennen, dass ein KI-gestütztes Screening-System in erster Linie ein **Strukturierungsinstrument** ist — nicht ein Entscheidungsautomaten. Der Wert liegt in der konsistenten Anwendung eines Frameworks, nicht in der KI-Magie.

**Typischer Fehler:** Teilnehmende wollen "die KI entscheiden lassen". Korrektur: *"Was entscheidet die KI? Sie aggregiert öffentliche Informationen nach einem definierten Kriterienset — das ist kein qualitativer Erkenntnisgewinn, sondern Zeitersparnis und Konsistenz."*

**Ben Fischer als Hebel:** Senior Analyst Ben Fischer hat Python-Kompetenz. Das ist relevant für die Umsetzungsdiskussion. Ein realistisches Minimal-System könnte ein Python-Skript sein, das per Crunchbase-API Basisdaten zieht und ein standardisiertes Profil erzeugt — kein LLM-Training erforderlich.

**DSGVO-Falle:** Gründer-Scoring berührt möglicherweise Art. 22 DSGVO (automatisierte Einzelentscheidungen, die Personen erheblich beeinflussen). Teilnehmende sollten das erkennen und als Risiko benennen — nicht als Stopper, sondern als Design-Anforderung: **Das System liefert Informationen, nicht Entscheidungen.**

**Regulatorische Argumentation (EU AI Act):** Investment-Scoring-Systeme werden möglicherweise als Hochrisikosystem nach Anhang III Nr. 5b klassifiziert (Bewertung der Kreditwürdigkeit). Bei einem VC-Screening, das Proposals — nicht Personen — bewertet, ist die Einordnung weniger eindeutig. Für die Schulung ausreichend: Das Bewusstsein schärfen, dass die Frage gestellt werden muss.

---

## Musterlösung — Screening-Konzept (Kurzform)

**Systemarchitektur:**
```
Proposal (PDF/E-Mail) → Parsing → Daten-Extraktion
        │
        ├── Crunchbase API (Marktdaten, Funding-Historie, Wettbewerber)
        ├── LinkedIn (Gründer-Background — manuell oder über API)
        ├── News-Aggregator (Red-Flag-Prüfung: Stichwortsuche)
        └── Interne DB (ähnliche Proposals aus der Vergangenheit)
        │
        ▼
Strukturiertes Screening-Profil (1 Seite)
 • Kriterien-Scorecard (grün/gelb/rot)
 • Key Facts (Markt, Team, Finanzierung)
 • Red-Flag-Hinweise (automatisch)
 • Empfehlung: Go / Prüfen / No-Go (nicht bindend)
        │
        ▼
Analyst entscheidet in 15–20 Min → Go/No-Go
```

**Zeitersparnis (Musterlösung):**
- IST: 2,5 h Grobprüfung/Vorgang × 204/Jahr = 510 h/Jahr
- SOLL: 0,75 h (Durchsicht Profil + Entscheidung) × 204/Jahr = 153 h/Jahr
- Einsparung: **357 h/Jahr** — entspricht ~0,2 FTE

**Wichtig für Teilnehmende:** Diese Zahlen sind ein grober Richtwert. In der Detailbewertung (UC-06b, Phase 2) wird das Modell präzisiert.

---

## Moderations-Szenarien

**Wenn Teilnehmende fragen, warum nicht einfach ChatGPT nutzen:**  
*„Können Sie mir zeigen, wie Sie das systematisch über 200 Proposals hinweg qualitätssichern — und wie das DSGVO-konform funktioniert, wenn Gründer-Namen in den Prompt eingehen?"* → Das öffnet die Diskussion zu strukturierter Systemarchitektur vs. Ad-hoc-Nutzung.

**Wenn Teilnehmende zu technisch werden (Modell-Architektur, RAG, etc.):**  
*„Gut — aber was ist die Anforderung an das System aus Nutzersicht? Was muss auf dem Output-Dokument stehen?"* → Zurück zur Funktionsanforderung.

**Wenn Teilnehmende Skepsis gegenüber KI äußern (Bias, Fehler):**  
*"Welchen Fehler machen Sie lieber: Ein gutes Startup irrtümlich aussortieren, oder ein schlechtes Startup irrtümlich weiterleiten? Welcher Fehler ist teurer?"* → Das schärft das Verständnis von Precision vs. Recall im Kontext des Anwendungsfalls.

---

## Verbindung zu anderen UCs

| UC | Thema | Verbindung |
|---|---|---|
| UC-06b | ROI + DCF Phase 2 | Proposals, die Phase 1 bestehen, kommen in Phase 2 — das ist die Grundlage für die ROI-Rechnung in Tag 5 |
| UC-04a (SolidFinanz) | Schatten-KI-Inventur | Ähnliche Architektur-Frage: Was macht das System, welche Daten fließen wohin? |
| UC-06c | Portfoliomonitoring | Phase 3 nutzt ähnliche Dateninfrastruktur (strukturierte KPIs), aber für bestehende Investments |

# UC-03b: Patienten-Onboarding-App — Dozenten-Hinweise
> KI-Beauftragter · Modul 764 · TÜV Rheinland · Woche 1–2
> ⚠️ Nicht für Teilnehmende

---

## Einordnung

**KI-System-Typ:** Konversations-KI (Chatbot) mit Reinforcement Learning from Human Feedback (RLHF-ähnlich)  
**Schwierigkeitsgrad:** Anfänger bis Fortgeschrittene  
**Risikoklasse:** Begrenztes Risiko (Basis) → mögliches Hochrisiko wenn medizinische Ratschläge gegeben werden

---

## Prüfdimensionen

| Dimension | Bewertung | Details |
|---|---|---|
| **EU AI Act — Risikoklasse** | ⚠️ Grenzfall | Rein informativ = begrenzt. Sobald der Bot medizinische Empfehlungen gibt → Hochrisiko-Prüfung erforderlich (Anhang III Nr. 5) |
| **EU AI Act — Transparenz** | Art. 50 Pflicht | Patienten müssen wissen, dass sie mit einem KI-System interagieren |
| **EU AI Act — Anbieter** | ⚠️ Kritische Frage | App unter Krankenhaus-Namen veröffentlicht → Krankenhaus ist Anbieter nach Art. 3 Nr. 3, auch wenn Dienstleister entwickelt hat |
| **Lernmechanismus** | ⚠️ Regulatorisch relevant | Bewertungsbasiertes Lernen = wesentliche Veränderung des Systems im Betrieb → Post-Market-Monitoring-Pflichten |
| **DSGVO** | ⚠️ Sensibel | Patienten = Betroffene mit Art. 9-Daten. Minderjährige als Nutzer möglich. Einwilligung oder Art. 9 Abs. 2 lit. h erforderlich |
| **Vertrauen** | Turing Institute | Patienten in vulnerabler Situation — Fehlinformationen können zu medizinischen Schäden führen |
| **Caregiving-Dimension** | Nature Health 2026 | 1 von 7 Anfragen betrifft jemand anderen (Kind, Elternteil, Partner) — App muss diese Nutzungssituation designtechnisch berücksichtigen |
| **Zeitliche Nutzung** | Nature Health 2026 | Persönliche Anfragen steigen abends/nachts — genau wenn das Krankenhaus am schlechtesten erreichbar ist. Hohe Nutzungserwartung in der Nacht |

---

## Didaktische Hinweise

**Der Aha-Moment:** Der Lernmechanismus ist die entscheidende Weichenstellung. Ein statischer FAQ-Bot hat minimales Risiko. Sobald das System aus Nutzerbewertungen lernt und Antworten anpasst, entsteht eine neue Qualität — das System verändert sich im Betrieb. Das löst Post-Market-Monitoring-Pflichten aus und wirft die Frage auf: Wer kontrolliert, ob die "gelernten" Antworten medizinisch korrekt sind?

**Anbieter-Frage als Prüfungsthema:** "Unter eigenem Namen in Verkehr bringen" ist der Schlüsselbegriff in Art. 3 Nr. 3. Das Krankenhaus ist Anbieter — egal wer die technische Arbeit geleistet hat. Das überrascht viele Teilnehmende.

**Grenze zwischen Information und Beratung:** Hier liegt die praktische Herausforderung. "Wann muss ich nüchtern sein?" ist Information. "Soll ich meine Medikamente vor der OP nehmen?" ist medizinische Beratung. Diese Grenze im Prompt-Design durchzusetzen ist eine Governance-Aufgabe.

**Nature Health-Studie als Evidenzbasis:** Die Studie (Costa-Gomes et al., April 2026) liefert drei didaktisch wertvolle Punkte: Erstens bestätigt sie empirisch, dass Patienten KI-Tools für Gesundheitsfragen nutzen — das ist keine Spekulation, sondern Realität mit 500.000+ Datenpunkten. Zweitens zeigt die Caregiving-Dimension (1 von 7 Anfragen für andere): Das App-Design muss nicht nur den Patienten selbst, sondern auch Angehörige als Nutzungskontext berücksichtigen. Drittens: Die abendliche/nächtliche Nutzungsspitze bedeutet, dass das System genau dann stabil, sicher und akkurat sein muss, wenn keine menschliche Aufsicht aktiv ist. Das ist das stärkste Argument für robust konfigurierte Human-Oversight-Prozesse — auch außerhalb der Betriebszeiten.

**Verbindung zu UC-02a (WellSeal Onboarding-Bot):** Gleicher Systemtyp, völlig anderes Risikoprofil. Warum? Weil die Nutzer hier Patienten in vulnerabler Situation sind, nicht Mitarbeitende. Dieser Kontrast ist lehrreich.


## Quelle zum Szenario
- Costa-Gomes et al. — Public use of a generalist LLM chatbot for health queries. *Nature Health* (2026): https://www.nature.com/articles/s44360-026-00117-x

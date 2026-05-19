# UC-03b: Management Systeme & Risikomanagement
> KI-Beauftragter · KI-Manager

---

## Szenario

Das Krankenhaus entwickelt eine App für Patienten und Angehörige, die häufig wiederkehrende Fragen beantwortet: Besuchszeiten, Abläufe vor Operationen, Medikamenteneinnahme, Entlassungsprozesse, Nachsorge. Der Chatbot basiert auf einem Sprachmodell und wird mit internen Dokumenten trainiert. Die App heisst "Ihre Fragen - Unsere Antworten" und kann im Patienten W-LAN des Krankenhauses hochgeladen werden.

**Der Lernmechanismus:** Patienten und Angehörige können Antworten mit 👍 oder 👎 bewerten. Das System lernt aus diesen Bewertungen und verbessert künftige Antworten. Damit verwandelt sich der Bot von einem statischen Informationssystem in ein **lernendes KI-System**. Das Krankenhaus überlegt noch, ob Bewertungen anonym oder mit Klinik-Account erfolgen sollen, und wer die Modell-Updates freigibt.

Das Krankenhaus entwickelt die App mit einem externen Dienstleister. Der Dienstleister liefert die technische Plattform und das Basismodell, das Krankenhaus liefert die internen Dokumente und gibt das System unter eigenem Namen heraus. Allerdings hat ein vergleichbares früheres Onboarding-System in einem ähnlichen Krankenhaus eine falsche Information zur Medikamenten-Vorbereitung gegeben. Die Klinikleitung ist hier besonders sensibilisiert.

**Empirischer Hintergrund:** Eine Studie von Microsoft AI (*Nature Health*, April 2026) analysierte über 500.000 Gesundheitsanfragen an Microsoft Copilot. Zentrale Befunde: Fast jedes fünfte Gespräch betrifft persönliche Symptombewertung oder Erkrankungen. Jede siebte persönliche Gesundheitsanfrage wird nicht für den Nutzer selbst gestellt, sondern für eine andere Person — Kinder, ältere Eltern, Partner. Persönliche Anfragen häufen sich abends und nachts, wenn klassische Gesundheitsversorgung am wenigsten erreichbar ist. Die App würde also eine Nachfrage bedienen, die real existiert — und zu Tageszeiten, die für ein Krankenhaus schwer abzudecken sind.

---

## Lernziele

- Den Unterschied zwischen einem statischen Informationssystem und einem lernenden KI-System erklären
- Die regulatorischen Konsequenzen des Lernmechanismus für die EU AI Act-Einordnung einschätzen
- Transparenzpflichten nach Art. 50 EU AI Act (Chatbot-Kennzeichnung) anwenden
- Klären, wer bei externer Entwicklung unter eigenem Namen Anbieter oder Betreiber ist
- DSGVO-Anforderungen bei einer Patienten-App einschätzen (Einwilligung, Zweckbindung, Minderjährige)

---

## Die entscheidende Frage

Das Krankenhaus veröffentlicht die App unter eigenem Namen — aber der externe Dienstleister hat sie entwickelt. Wer ist nach EU AI Act der **Anbieter**?

---

## Weiterführende Quellen

- EU AI Act Art. 50 (Chatbot-Transparenz): https://artificialintelligenceact.eu/article/50/
- EU AI Act Art. 3 Nr. 3 (Anbieter-Definition): https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=OJ:L_202401689
- DSGVO Art. 6/9 (Rechtsgrundlage, Gesundheitsdaten): https://gdpr-info.eu/art-9-gdpr/
- Turing Institute — AI Ethics: https://doi.org/10.5281/zenodo.3240529
- Costa-Gomes et al. — Public use of a generalist LLM chatbot for health queries (*Nature Health*, 2026): https://www.nature.com/articles/s44360-026-00117-x

---

## Analyse & Hinweise

### Einordnung

**KI-System-Typ:** Konversations-KI (Chatbot) mit Reinforcement Learning from Human Feedback (RLHF-ähnlich)
**Schwierigkeitsgrad:** Anfänger bis Fortgeschrittene
**Risikoklasse:** Begrenztes Risiko (Basis) → mögliches Hochrisiko wenn medizinische Ratschläge gegeben werden

### Prüfdimensionen

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

### Didaktische Hinweise

**Der Aha-Moment:** Der Lernmechanismus ist die entscheidende Weichenstellung. Ein statischer FAQ-Bot hat minimales Risiko. Sobald das System aus Nutzerbewertungen lernt und Antworten anpasst, entsteht eine neue Qualität — das System verändert sich im Betrieb. Das löst Post-Market-Monitoring-Pflichten aus und wirft die Frage auf: Wer kontrolliert, ob die "gelernten" Antworten medizinisch korrekt sind?

**Anbieter-Frage als Prüfungsthema:** "Unter eigenem Namen in Verkehr bringen" ist der Schlüsselbegriff in Art. 3 Nr. 3. Das Krankenhaus ist Anbieter — egal wer die technische Arbeit geleistet hat. Das überrascht viele Teilnehmende.

**Grenze zwischen Information und Beratung:** "Wann muss ich nüchtern sein?" ist Information. "Soll ich meine Medikamente vor der OP nehmen?" ist medizinische Beratung. Diese Grenze im Prompt-Design durchzusetzen ist eine Governance-Aufgabe.

**Nature Health-Studie als Evidenzbasis:** Die Studie (Costa-Gomes et al., April 2026) liefert drei didaktisch wertvolle Punkte: Erstens bestätigt sie empirisch, dass Patienten KI-Tools für Gesundheitsfragen nutzen. Zweitens zeigt die Caregiving-Dimension (1 von 7 Anfragen für andere): Das App-Design muss nicht nur den Patienten selbst, sondern auch Angehörige als Nutzungskontext berücksichtigen. Drittens: Die abendliche/nächtliche Nutzungsspitze bedeutet, dass das System genau dann stabil, sicher und akkurat sein muss, wenn keine menschliche Aufsicht aktiv ist.

**Verbindung zu UC-02 (WellSeal Onboarding-Bot):** Gleicher Systemtyp, völlig anderes Risikoprofil. Warum? Weil die Nutzer hier Patienten in vulnerabler Situation sind, nicht Mitarbeitende. Dieser Kontrast ist lehrreich.

## Quelle zum Szenario
- Costa-Gomes et al. — Public use of a generalist LLM chatbot for health queries. *Nature Health* (2026): https://www.nature.com/articles/s44360-026-00117-x

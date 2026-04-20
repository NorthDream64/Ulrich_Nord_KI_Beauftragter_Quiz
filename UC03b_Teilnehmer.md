# UC-03b: Patienten-Onboarding-App mit Lerneffekt
> KI-Beauftragter · Modul 764 · TÜV Rheinland · Woche 1–2

---

## Szenario

Das Krankenhaus entwickelt eine App für Patienten und Angehörige, die häufig wiederkehrende Fragen beantwortet: Besuchszeiten, Abläufe vor Operationen, Medikamenteneinnahme, Entlassungsprozesse, Nachsorge. Der Chatbot basiert auf einem Sprachmodell und wird mit internen Dokumenten trainiert.

**Der Lernmechanismus:** Patienten und Angehörige können Antworten mit 👍 oder 👎 bewerten. Das System lernt aus diesen Bewertungen und verbessert künftige Antworten. Damit verwandelt sich der Bot von einem statischen Informationssystem in ein **lernendes KI-System**.

Das Krankenhaus entwickelt die App mit einem externen Dienstleister. Die App wird unter dem Namen des Krankenhauses veröffentlicht.

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

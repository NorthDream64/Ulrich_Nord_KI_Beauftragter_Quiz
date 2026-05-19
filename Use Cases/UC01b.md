# UC-01b: Rechtliche Grundlagen & EU AI Act

---

## Szenario

Das Bauplanungsbüro Dr. Seika erweitert sein KI-System: Es soll nun Lieferantenanfragen (Materialverfügbarkeit, Liefertermine) und Personalplanung (Skill-Abgleich, Verfügbarkeit von Mitarbeitenden) unterstützen. Bei der Personalplanung werden Qualifikationen, Verfügbarkeiten und Weiterbildungshistorien verarbeitet.

Das Büro bleibt Betreiber — das System wurde nicht verändert.

---

## Lernziele

- DSGVO und EU AI Act als parallele, gleichzeitig geltende Rechtsrahmen erkennen
- Hochrisiko-Grenzfälle bei Personalentscheidungen sicher identifizieren (Anhang III Nr. 4)
- DSFA-Pflicht nach DSGVO Art. 35 einschätzen
- Mitbestimmungsrechte des Betriebsrats bei KI-gestützter Personalplanung benennen
- API-Sicherheitsanforderungen bei Lieferantenanbindungen einordnen

---

## Weiterführende Quellen

- EU AI Act, Anhang III: https://artificialintelligenceact.eu/
- DSGVO Art. 22 (Automatisierte Entscheidungen): https://gdpr-info.eu/art-22-gdpr/
- DSGVO Art. 35 (DSFA): https://gdpr-info.eu/art-35-gdpr/
- BetrVG § 87: https://www.gesetze-im-internet.de/betrvg/__87.html
- EDPB Guidelines AI & DSGVO: https://edpb.europa.eu/our-work-tools/our-documents/guidelines/guidelines-032024-processing-personal-data-through-ai_en

---

## Analyse & Hinweise

### Einordnung

**KI-System-Typ:** Planungs- und Entscheidungsunterstützungssystem
**Schwierigkeitsgrad:** Fortgeschrittene
**Quiz:** UC01_Quiz_Tag3_4.html (Fragen 3–5 besonders relevant)

### Prüfdimensionen

| Dimension | Bewertung | Details |
|---|---|---|
| **EU AI Act — Lieferanten** | Begrenztes Risiko | B2B, keine Entscheidung über Personen |
| **EU AI Act — Personal** | ⚠️ Mögliches Hochrisiko | Anhang III Nr. 4: Personalentscheidungsunterstützung — Prüfpflicht |
| **DSGVO Personal** | ⚠️ Kritisch | Art. 6, 9, 22 · DSFA wahrscheinlich Pflicht |
| **Betriebsrat** | ⚠️ Mitbestimmungspflichtig | § 87 Abs. 1 Nr. 6 BetrVG |
| **Transparenz** | Pflicht | Art. 13/14/15 DSGVO gegenüber Mitarbeitenden |
| **IT-Sicherheit** | ⚠️ Erhöht | API-Sicherheit, Authentifizierung bei Lieferantenanbindung |
| **Fairness** | Relevant | Skill-Bewertungen dürfen keine Diskriminierungsmuster reproduzieren |

### Didaktische Hinweise

**Kernlernmoment:** Die Grenze zwischen begrenztem und hohem Risiko liegt nicht am System, sondern an der Frage: "Beeinflusst die KI-Ausgabe Einstellungs-, Einsatz- oder Beförderungsentscheidungen?" Diese Frage müssen Teilnehmende lernen zu stellen — nicht zu beantworten.

**Häufige Verwechslung:** Teilnehmende verwechseln Mitbestimmungspflicht (Betriebsrat) mit DSGVO-Pflichten. Beide gelten parallel, sind aber unabhängig voneinander.

**Guter Diskussionsimpuls:** "Was passiert, wenn das Büro keinen Betriebsrat hat?" → Individualarbeitsrechtliche Pflichten bleiben, § 87 BetrVG entfällt formell.

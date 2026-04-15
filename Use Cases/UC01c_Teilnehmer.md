# UC-01c: Preiskalkulation mit proprietären Daten
> KI-Beauftragter · Modul 764 · TÜV Rheinland · Woche 3–4

---

## Szenario

Das Bauplanungsbüro möchte das zugekaufte KI-System erweitern: Mit eigenen Projektdaten und Expertenschätzungen soll das Modell automatisierte Preisvorschläge für Nachträge liefern. Geplant ist ein Fine-Tuning des Modells mit internen Kalkulationsdaten aus abgeschlossenen Projekten.

Das System erhält damit eine neue Funktion — es prüft nicht mehr nur Verträge, sondern kalkuliert Preise.

---

## Lernziele

- Den Rollenwechsel von Betreiber zu Anbieter nach Art. 25 Abs. 1 EU AI Act erkennen und begründen
- Anbieterpflichten (CE-Kennzeichnung, technische Dokumentation, Konformitätsbewertung) benennen
- Geschäftsgeheimnis- und Bias-Risiken bei proprietären Trainingsdaten einschätzen
- Den Entscheidungsbaum "Bin ich noch Betreiber?" selbständig anwenden
- Eskalationspunkte für den KI-Beauftragten identifizieren

---

## Entscheidungsbaum

```
Habe ich das KI-System verändert?
├── Nein → Betreiber (Betreiberpflichten)
└── Ja → Wesentliche Veränderung?
    ├── Nein (nur UI, Prompts) → Betreiber bleibt
    └── Ja (Fine-Tuning, neue Zweckbestimmung, RAG mit eigenen Daten)
        └── → Anbieter → volle Anbieterpflichten (Art. 25 Abs. 1 EU AI Act)
```

---

## Weiterführende Quellen

- EU AI Act Art. 25 (Rollenwechsel): https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=OJ:L_202401689
- EU AI Act Anhang IV (Technische Dokumentation): https://artificialintelligenceact.eu/
- GeschGehG: https://www.gesetze-im-internet.de/geschgehg/
- Rohrlich, *KI und Recht*, Hanser 2024, S. 164–167

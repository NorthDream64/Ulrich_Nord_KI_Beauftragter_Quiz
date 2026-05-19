# UC-01a: Rechtliche Grundlagen & EU AI Act

---

## Szenario

Das Bauplanungsbüro Dr. Seika mit 15 Mitarbeitenden setzt ein KI-System ein, das Nachträge automatisch gegen den Originalvertrag und die gültigen Baugesetze (VOB/B, BGB) prüft. Das System liefert eine Einschätzung, ob ein Nachtrag durch den bestehenden Vertrag abgedeckt ist oder eine Zusatzbeauftragung des Auftraggebers erfordert.

Das Büro hat das System von einem externen Anbieter zugekauft und betreibt es unverändert. Ein Projektleiter prüft jede KI-Empfehlung vor der Entscheidung.

---

## Lernziele

Nach dieser Einheit kannst du:

- Den Unterschied zwischen Betreiber und Anbieter nach EU AI Act erklären und auf ein konkretes Beispiel anwenden
- Die Risikoklasse eines KI-Systems einschätzen und begründen
- Das Halluzinationsrisiko bei Legal AI benennen und Gegenmaßnahmen vorschlagen
- Human-in-the-Loop als Governance-Prinzip erläutern
- Datenschutzrelevanz bei der Verarbeitung von Vertragsdokumenten beurteilen

---

## Weiterführende Quellen

- EU AI Act (Volltext): https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=OJ:L_202401689
- EU AI Act Explorer (interaktiv): https://artificialintelligenceact.eu/
- DSGVO Art. 4 (Personenbezogene Daten): https://gdpr-info.eu/art-4-gdpr/
- Rohrlich, *KI und Recht*, Hanser 2024

---

## Analyse & Hinweise

### Einordnung

**Branche:** Bauwesen, KMU
**KI-System-Typ:** Dokumentenanalyse / Legal AI / RAG-System
**Schwierigkeitsgrad:** Anfänger
**Quiz:** UC01_Quiz_Tag3_4.html · Rolle: KI-Beauftragter + IT-Sicherheit

### Prüfdimensionen

| Dimension | Bewertung | Details |
|---|---|---|
| **EU AI Act — Risikoklasse** | Begrenztes Risiko | B2B-Vertragsverhältnis, kein Anhang-III-Tatbestand, Mensch entscheidet final |
| **EU AI Act — Rolle** | Betreiber (Art. 3 Nr. 4) | System zugekauft, nicht verändert → Betreiberpflichten, keine Anbieterpflichten |
| **DSGVO** | Bedingt relevant | Prüfpflicht: Enthält der Vertrag Namen natürlicher Personen? → Art. 6 Rechtsgrundlage |
| **Halluzinationsrisiko** | ⚠️ Hoch | Falsche Rechtsauslegung → Vertragsstreitigkeiten. RAG mit aktuellen Gesetzestexten empfohlen |
| **Human-in-the-Loop** | Zwingend empfohlen | KI liefert Einschätzung, Projektleiter entscheidet |
| **Turing Institute — Ethik** | Transparency & Accountability | Entscheidungsweg dokumentierbar und nachvollziehbar? |
| **CIS / IT-Sicherheit** | Mittel | Vertragsdaten sensibel → Zugriffsrechte, Logging |

### Didaktische Hinweise

**Typischer Fehler der Teilnehmenden:** Das System als Hochrisiko einordnen, weil es "juristische Entscheidungen trifft". Korrekt ist: Es trifft keine Entscheidungen, es gibt Einschätzungen. Der Mensch entscheidet. Kein Anhang-III-Tatbestand.

**Guter Diskussionsimpuls:** "Ab wann wird dieses System zur Hochrisiko-KI?" — Antwort: Wenn der Projektleiter die KI-Ausgabe ohne eigene Prüfung weitergibt. Das zeigt den Human-Oversight-Mechanismus.

**Verbindung zu UC-01c:** Dieser Use Case ist bewusst einfach gehalten. UC-01c (Preiskalkulation mit eigenen Daten) baut darauf auf und zeigt den Rollenwechsel — das Kontrastpaar ist didaktisch wertvoller als UC-01a allein.

**Zeitplanung:** Use Case als Einstieg ~15 Min., dann Theorieblock. Quiz am Ende des Tages.

### Verbindungen im Curriculum

- **Folge-Use-Case:** UC-01b (Personalplanung), UC-01c (Rollenwechsel)
- **Theorieblock:** EU AI Act Risikoklassen (Tag 3–4), DSGVO Grundlagen (Tag 5–6)
- **Praktische Übung:** Betreiber-Checkliste für das Büro erstellen

# UC-03a: Management Systeme & Risikomanagement
> KI-Beauftragter · KI-Manager

---

## Szenario

Das Krankenhaus St. Ulrich möchte den Verbrauch von medizinischen Verbrauchsmaterialien (Handschuhe, Spritzen, Verbandsmaterial, Gefäße) mit KI optimieren. Ein ML-Modell analysiert historische Verbrauchsdaten, Belegungszahlen und saisonale Muster und schlägt automatisch Bestellmengen vor. Ziel: Engpässe vermeiden, Überbestände reduzieren, Kosten senken.
Das Krankenhaus kauft ein fertiges System eines Logistik-Softwareanbieters zu. Das Modell wird nicht verändert. Der Anbieter wirbt damit, dass sein System bald nach ISO 42001 zertifiziert sein wird.

St. Ulrich hat gegenwärtig ein QM-System nach ISO 9001, sein Informationssicherheitsmanagement-System (ISMS) ist nach ISO 27001 zertifiziert. Die Klinikleitung fragt sich, ob ein AIMS für eine minimal-riskante KI nicht überzogen wäre und neigt zur Antwort: „Wir haben schon 9001 und 27001, das reicht." Sie bittet die KIB um eine begründete Empfehlung.

---

## Lernziele

- Ein KI-System mit minimalem regulatorischen Risiko korrekt einordnen
- Den Unterschied zwischen einer risikoarmen "Quick Win"-Initiative und einer komplexen KI-Einführung erklären
- Begründen, warum Priorisierung eine Governance-Aufgabe des KI-Beauftragten ist
- Den strategischen Wert von Quick Wins für die interne Akzeptanz von KI beschreiben

---

## Weiterführende Quellen

- EU AI Act Risikoklassen: https://artificialintelligenceact.eu/
- EU AI Act Art. 3 Nr. 4 (Betreiber): https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=OJ:L_202401689
- NIST AI RMF: https://airc.nist.gov/RMF

---

## Analyse & Hinweise

### Einordnung

**KI-System-Typ:** Predictive Analytics / Bestandsoptimierung
**Schwierigkeitsgrad:** Anfänger
**Risikoklasse:** Minimal bis begrenzt — kein Anhang-III-Tatbestand, keine personenbezogenen Daten
**Unternehmenskontext:** UC03_Krankenhaus_St_Ulrich.md

### Prüfdimensionen

| Dimension | Bewertung | Details |
|---|---|---|
| **EU AI Act** | Minimales Risiko | Keine Entscheidung über Personen, keine sensiblen Daten, kein Anhang-III-Tatbestand |
| **DSGVO** | Nicht relevant | Verbrauchsmaterialien enthalten keine personenbezogenen Daten |
| **Betreiberpflichten** | Minimal | Zugekauftes System, nicht verändert → nur grundlegende Betreiberpflichten |
| **IT-Sicherheit** | Mittel | Anbindung an Krankenhaus-ERP: Schnittstellensicherheit, Zugriffsrechte |

### Didaktische Hinweise

**Kernbotschaft:** Nicht jede KI-Initiative ist hochriskant. Der KI-Beauftragte muss das Spektrum kennen — von minimal bis Hochrisiko — und entsprechend priorisieren.

**Strategischer Wert im Kurs:** Dieser Use Case zeigt, dass ein kluger erster Schritt bewusst risikoarm gewählt wird. Quick Wins schaffen Vertrauen bei skeptischen Stakeholdern (CISO, Betriebsrat, Ärzteschaft). Wer mit Handschuhen beginnt, kann später Diagnoseunterstützung argumentieren.

**Verbindung zum Artikel:** Der Doom Loop kann auch durch bessere Logistik teilweise unterbrochen werden — Engpässe bei Material erhöhen den Stress beim Personal und verlängern Behandlungszeiten.

**Verbindung zum Longitudinal Assessment:** In Version 1 des 100-Tage-Plans nennen viele Teilnehmende sofort "KI für Diagnose". Nach diesem Use Case sollten sie erkennen: Der erste reale Schritt könnte Verbrauchsmaterialien sein — weil er machbar ist, während die Governance-Grundlagen aufgebaut werden.

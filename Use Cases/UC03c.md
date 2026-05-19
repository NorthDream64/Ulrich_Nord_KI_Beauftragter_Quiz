# UC-03c: Management Systeme & Risikomanagement
> KI-Beauftragter · KI-Manager

---

## Szenario

Das Krankenhaus möchte administrative Prozesse rund um Patientendaten automatisieren: Aufnahme, Terminplanung, Entlassbriefe, Bettenbelegungssteuerung und Abrechnungsdokumente. Zentrale Datenquelle ist die **Elektronische Patientenakte (EPA)**, die seit 2025 in Deutschland für alle gesetzlich Versicherten verpflichtend ist.

KI-Agenten sollen teilweise autonom handeln: Termine vergeben, Entlassbriefe vorstrukturieren, Bettenbelegung optimieren. Ein Arzt oder Pflegeperson bestätigt kritische Aktionen — aber nicht jede. Welche Aktionen als „kritisch" gelten, hat der Software-Anbieter beim Setup vorkonfiguriert: Aktionen mit medizinischer Relevanz (Medikationshinweise, vorstrukturierte Entlassbriefe) werden vorgelegt; rein organisatorische Aktionen (Terminverschiebungen, Bettenbelegung, Standardabrechnungen) führt das System eigenständig aus. Die Konfiguration kann von der IT-Leitung angepasst werden. In der Pilotphase wurden ca. 30 % der Systemvorschläge zur Bestätigung vorgelegt; die übrigen 70 % führte das System eigenständig aus.

---

## Lernziele

- Die Elektronische Patientenakte (EPA) als neuen Rechtsrahmen einordnen (SGB V §§ 341 ff.)
- Den Unterschied zwischen assistierender KI und autonom handelnden KI-Agenten erklären
- Haftungsfragen bei KI-Agenten im Krankenhaus einschätzen: Wer haftet wenn ein Agent einen Fehler macht?
- Zweckbindung nach DSGVO Art. 5 bei der EPA-Nutzung für KI-Training verstehen
- Die Frage klären: Dürfen EPA-Daten für das KI-Modelltraining verwendet werden?

---

## Die Kernfrage

KI-Agenten können autonom Termine vergeben oder Entlassbriefe erstellen. Das entlastet das Personal. Aber: Ab welchem Autonomiegrad ist eine menschliche Prüfung zwingend erforderlich — und wer legt diese Grenze fest?

---

## Weiterführende Quellen

- SGB V §§ 341 ff. (Elektronische Patientenakte): https://www.gesetze-im-internet.de/sgb_5/__341.html
- EU AI Act Art. 14 (Human Oversight): https://artificialintelligenceact.eu/article/14/
- DSGVO Art. 5 (Zweckbindung): https://gdpr-info.eu/art-5-gdpr/
- DSGVO Art. 9 (Gesundheitsdaten): https://gdpr-info.eu/art-9-gdpr/

---

## Analyse & Hinweise

### Einordnung

**KI-System-Typ:** KI-Agenten / Workflow-Automatisierung
**Schwierigkeitsgrad:** Fortgeschrittene
**Risikoklasse:** Mittel bis hoch — EPA = Art. 9-Daten, KI-Agenten = Autonomie-Frage

### Prüfdimensionen

| Dimension | Bewertung | Details |
|---|---|---|
| **EU AI Act — Agenten** | ⚠️ Kritisch | Autonome Handlungsketten ohne vollständigen Human-in-the-Loop → Art. 14 Pflichten. Wann ist die Autonomiegrenze überschritten? |
| **EPA-Zweckbindung** | ⚠️ DSGVO Art. 5 | EPA-Daten wurden für Behandlungszwecke erhoben. Nutzung für KI-Training = Zweckänderung → neue Rechtsgrundlage erforderlich |
| **Haftung bei Agenten** | Ungeklärt | Wenn ein Agent einen falschen Termin vergibt und daraus ein Schaden entsteht: Krankenhaus, Softwareanbieter oder Arzt? Aktuelle Rechtslage ist hier noch offen |
| **SGB V + DSGVO** | Doppeltes Rechtsregime | EPA-Recht (SGB V) und DSGVO gelten parallel — ähnliche Struktur wie EU AI Act + DSGVO bei UC-01 |
| **IT-Sicherheit** | ⚠️ Hoch | EPA-Schnittstelle ist kritische Infrastruktur. Cyberangriffe auf Krankenhäuser sind real und häufig |

### Didaktische Hinweise

**Der Agenten-Autonomie-Slider:** Nicht alle Aktionen eines Agenten sind gleich riskant. Terminvergabe für Routineuntersuchungen ist anders als das Vorstrukturieren eines Entlassbriefs. Teilnehmende sollen lernen, Aktionen nach Autonomiegrad und Schadensrisiko zu kategorisieren und entsprechende Oversight-Regeln zu formulieren.

**EPA als Lernmoment:** Die meisten Teilnehmenden wissen nicht, dass die EPA seit 2025 verpflichtend ist und ein eigenes Rechtsregime hat. Dieser Use Case bietet die Gelegenheit, SGB V und DSGVO als parallele Rechtsrahmen zu zeigen — analog zur DSGVO/EU-AI-Act-Doppelstruktur aus Woche 1.

**Zweckbindungs-Paradox:** Die EPA enthält die reichhaltigsten Patientendaten, die je strukturiert erfasst wurden. Sie sind ideal für KI-Training. Aber: Sie wurden für Behandlungszwecke erhoben. Dieses Spannungsfeld ist real und ungelöst — und genau deshalb lehrreich.

**Verbindung zum Abschluss-Steckbrief:** Dieser Use Case kombiniert sich ideal mit UC-03d (Diagnoseunterstützung) für die Abschlussarbeit — administrative KI und diagnostische KI greifen auf dieselbe EPA-Datenquelle zu, haben aber völlig unterschiedliche Risikoklassen.

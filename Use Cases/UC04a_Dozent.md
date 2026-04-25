# UC-04a: Schatten-KI-Inventur — Dozenten-Hinweise
> alfatraining · Projektaufgabe: KI-Beauftragter
> ⚠️ Nicht für Teilnehmende

---

## Einordnung

**KI-System-Typ:** Verschiedene externe LLM-Tools (ChatGPT, Grammarly, DeepL, Notion AI)  
**Schwierigkeitsgrad:** Anfänger  
**Didaktische Funktion:** Einstieg in die technischen Blöcke — zeigt, warum Prompting, Datenschutz und M365-Governance praxisrelevant sind

---

## Prüfdimensionen

| Dimension | Bewertung | Details |
|---|---|---|
| **DSGVO — ChatGPT kostenlos** | ⚠️ Kritischer Verstoß | Kein AVV, Daten werden für Modelltraining genutzt (OpenAI AGB kostenlose Version), Drittlandtransfer USA ohne Standardvertragsklauseln |
| **DSGVO — Kreditantragsdaten** | ⚠️ Art. 9 möglich | Einkommensnachweise, Kontoauszüge, Schufa = hochsensible Finanzdaten. Weitergabe an Dritte ohne Einwilligung rechtswidrig |
| **MaRisk** | ⚠️ Auslagerung | Cloud-KI-Tools sind Auslagerungen. Ungeplante Auslagerungen verstoßen gegen MaRisk AT 9 |
| **BAIT** | ⚠️ IT-Governance | Nicht genehmigte Software auf Firmengeräten verstößt gegen BAIT-Anforderungen an Informationssicherheitsmanagement |
| **EU AI Act** | Begrenzt bis mittel | Die genutzten Tools (ChatGPT, Grammarly) sind GPAI-Systeme. Microsoft/OpenAI tragen Anbieterpflichten. SolidFinanz AG ist Betreiber |

---

## Didaktische Hinweise

**Der Vorfall als Türöffner:** Der ChatGPT-Vorfall ist nicht primär ein Technologie-Problem — er ist ein Governance-Problem. Mitarbeitende handeln pragmatisch, nicht böswillig. Frank Neumann (Kreditabteilung) hat Recht: Die Entscheidung liegt beim Menschen. Aber er übersieht: Die Daten haben das Unternehmen verlassen, bevor die Entscheidung getroffen wurde.

**Inventur-Methodik als Lernaufgabe:** Teilnehmende sollen eine konkrete Inventur-Checkliste entwickeln. Zwei Kanäle: technisch (Traffic-Analyse, Purview nach Aktivierung, App-Inventar auf Firmengeräten) und organisatorisch (Mitarbeiterbefragung, Abteilungsleiter-Interviews, IT-Helpdesk-Tickets). Beide Kanäle sind nötig — keiner allein reicht.

**Kostenlos vs. Enterprise ist der Schlüsselunterschied:** OpenAI kostenlos = Daten werden für Training genutzt, kein AVV möglich, US-Server ohne Standardvertragsklauseln. OpenAI Enterprise = AVV verfügbar, Daten werden nicht für Training genutzt, EU-Serveroptionen. Das ist kein juristisches Detail — das ist der Unterschied zwischen rechtswidrig und rechtmäßig.

**BaFin-Risiko als Motivator:** Der Hinweis auf BaFin-Prüfungen wirkt bei Finanzdienstleistern wie kein anderer. Eine BaFin-Mängelanzeige wegen ungenehmigter KI-Tools ist realistisch — und das ist die Begründung, warum der Vorstand handelt.

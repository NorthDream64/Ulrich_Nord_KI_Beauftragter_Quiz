# UC-04b: M365 Governance & Purview — Dozenten-Hinweise
> alfatraining · Projektaufgabe: KI-Beauftragter
> ⚠️ Nicht für Teilnehmende

---

## Einordnung

**KI-System-Typ:** M365 Copilot (GPAI) / Purview (Governance-Tool)  
**Schwierigkeitsgrad:** Anfänger bis Fortgeschrittene  
**Verbindung Lehrplan:** Tag 8 (M365-Block, Applied Case Microsoft 365)  
**Verbindung:** UC-02a (WellSeal Oversharing) — gleicher technischer Kontext, andere Branche

---

## Prüfdimensionen

| Dimension | Bewertung | Details |
|---|---|---|
| **Oversharing** | ⚠️ Strukturelles Risiko | Copilot findet alles, worauf der Nutzer Rechte hat. Kreditdaten in ungesicherten SharePoint-Ordnern → Copilot macht sie für alle auffindbar |
| **Privacy by Design** | DSGVO Art. 25 | Sensitivity Labels sind eine Privacy-by-Design-Maßnahme — Datenschutz durch Technikgestaltung |
| **BAIT** | Positive Maßnahme | Purview-Aktivierung erfüllt BAIT-Anforderungen an Informationsklassifizierung |
| **RACI** | Kernaufgabe | KI-Beauftragter koordiniert — entscheidet nicht alleine. CISO: Technik. DSB: Rechtliche Kategorien. IT: Konfiguration. Fachbereich: Inhaltliche Klassifizierung |

---

## Didaktische Hinweise

**Purview ist die Antwort auf Schatten-KI:** Nach UC-04a (Inventur) kommt UC-04b (Sichtbarkeit herstellen). Der logische Zusammenhang: Erst wissen was läuft, dann steuern. Purview gibt dem CISO die Werkzeuge, die er braucht.

**RACI als Übungsformat:** Die leere RACI-Matrix ist eine starke Gruppenübung. Häufige Diskussion: Wer entscheidet, welche Daten "vertraulich" sind — IT oder Fachbereich? Antwort: Fachbereich entscheidet inhaltlich, IT setzt technisch um, DSB prüft rechtlich, KI-Beauftragter koordiniert.

**Oversharing-Demo (wenn technisch möglich):** Zeigen, wie Copilot einen Prompt wie "Zeig mir alle Kreditanträge von letzter Woche" beantwortet, wenn SharePoint-Berechtigungen nicht konfiguriert sind. Das ist der eindrucksvollste Beweis für die Notwendigkeit von Sensitivity Labels — kein juristisches Argument nötig.

**Verbindung zu UC-02a:** WellSeal und SolidFinanz AG haben dasselbe M365-Problem. Der Unterschied: Beim Schiffszulieferer geht es um Ingenieurswissen, beim Finanzdienstleister um Kreditdaten. Gleiche Technologie, anderes Risikoprofil — guter Vergleich für die Gruppe.

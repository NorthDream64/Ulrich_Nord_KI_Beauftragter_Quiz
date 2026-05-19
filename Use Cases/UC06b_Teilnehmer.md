# UC-06b: Aktiv-Invest (AI) GmbH — KI-Modelle verstehen und bewerten
> KI-Manager · Woche 2, Tag 6
> ⚠️ Nicht vertraulich — Teilnehmer-Version

---

## Lernziel

Du kannst den KI-Typ hinter einer Geschäftsidee identifizieren, die typischen Datenanforderungen und Risiken benennen und als Investor:in die richtigen Folgefragen stellen.

---

## Szenario

Du bist Portfoliomanager:in der **Aktiv-Invest (AI) GmbH**. Die folgenden Unternehmen bewerben sich um eine Beteiligung. Jedes behauptet, KI als Kernbestandteil seines Geschäftsmodells einzusetzen.

Deine Aufgabe ist nicht, das Unternehmen technisch zu validieren — das ist Aufgabe der Due Diligence. Deine Aufgabe ist es, *die richtigen Fragen zu stellen*: Welche KI-Technologie steckt wirklich dahinter? Was muss das Unternehmen liefern können, damit die Technologie funktioniert? Und was könnte schief gehen?

---

## Deine Aufgabe

Analysiere jedes Unternehmen anhand des folgenden Rahmens:

| Frage | Was Du beurteilen sollst |
|---|---|
| **① KI-Typ** | Um welche Art von KI handelt es sich? (Supervised / Unsupervised / Reinforcement Learning / Deep Learning / Computer Vision / NLP — oder eine Kombination?) |
| **② Datenbasis** | Welche Daten braucht das System — und woher kommen sie? Wer hat diese Daten bereits, wer nicht? |
| **③ Performance-Frage** | Welche Kennzahl ist für dieses System entscheidend — Accuracy, Precision, Recall? Und welcher Fehler ist für das Geschäftsmodell teurer? |
| **④ Risiken** | Was könnte technisch oder regulatorisch schief gehen? |
| **⑤ Invest-Frage** | Welche eine Frage würdest Du dem Gründerteam im ersten Gespräch stellen? |

---

## Die Unternehmen

*"Mein Hauslehrer": Die KI bietet auf der Basis des Schulstoffs für Schülerinnen und Schüler individualisierte Lernprogramme an, die auf die jeweiligen Stärken und Schwächen abstellen - Reinforcement Learing
*"Zeitreise": Die KI nimmt gescannte Fotos, von denen der Nutzer nicht weiss, wenn oder was sie wann zeigen und trifft eine Aussage: Zeitpunkt des Fotos, Ort, Personen (aus der Familie) auf dem Foto: Supervised Learning + CV + NLP
*"Klangwelt": Ein Musikstreaming-Startup analysiert das Hörverhalten von einer Million Nutzern — ohne vorgegebene Genres. Das System entdeckt selbst, dass es Hörergruppen gibt, die niemand so definiert hatte: z.B. "Spät-Abend-Melancholiker" oder "Montagmorgen-Motivationstypen" -> Unsupervised Learning / Clustering
*"Vertragsampel": App für juristische Laien, die z.B. Miet- oder Arbeitsverträge einliest und automatisch Klauseln markiert, die ungewöhnlich oder nachteilig sind — ohne dass der Nutzer Rechtskenntnisse braucht -> NLP, Text-Klassifikation. Performance-Frage: Recall ist entscheidend (kein nachteiliger Satz darf übersehen werden).
*"Fälschungsradar": Ein Startup für Marktplätze (z.B. "Sammel Deinen Traum", Use Case 05) analysiert Produktfotos automatisch auf Fälschungsmerkmale — Nähte, Logos, Materialstruktur — die für Menschen schwer zu erkennen sind. Die Musterkomplexität erzwingt tiefe Architekturen. → Computer Vision + Deep Learning (hier ist Deep Learning tatsächlich die richtige Antwort, weil die Komplexität der visuellen Muster flachere Modelle überfordert).*

---

## Hinweise zur Bearbeitung

- Es gibt keine "falsche" Antwort beim KI-Typ — wichtig ist die Begründung.
- Manche Systeme kombinieren mehrere KI-Typen. Benennt den Primärtyp und erklärt die Kombination.
- Die Performance-Frage ist oft die schwierigste — denkt vom Geschäftsmodell her, nicht von der Technologie.

---

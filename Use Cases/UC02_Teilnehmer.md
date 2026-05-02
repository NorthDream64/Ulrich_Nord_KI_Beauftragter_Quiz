# Projektakte WellSeal · Wissensmanagement-RAG
## Use Case 02 für die Tage 12–17

> **alfatraining · KI-Beauftragte:r**
>
> ⚠️ Fiktives Unternehmen — alle Namen und Details sind für Schulungszwecke erstellt.

---

## 1. Das Projekt im Überblick

### Projektname
**„Maritimes Wissen 2030"** — Aufbau eines KI-gestützten Wissensmanagement-Systems bei WellSeal.

### Auftrag (Originalwortlaut Geschäftsführung)
„Das implizite Wissen unserer erfahrenen Ingenieure und Werkmeister soll strukturiert erfasst und über ein KI-gestütztes RAG-System für die folgenden Zielgruppen verfügbar gemacht werden:

1. Eigene Service-Ingenieure im Außendienst (Diagnose-Unterstützung)
2. Internationale Vertriebsagenten in Houston, Yokohama, Shanghai, Busan
3. Neue Mitarbeitende über einen integrierten mehrsprachigen Onboarding-Bot

Das System muss bis Ende des Geschäftsjahres produktiv sein. Sicherheit, Datenschutz und Akzeptanz haben höchste Priorität."

### Projektrahmen

| Kennzahl | Wert |
|---|---|
| Projektdauer | 6 Monate (Mai bis Oktober 2026) |
| Budget | 280.000 € (davon 110.000 € externe Beratung, 80.000 € Lizenzen, 90.000 € interne Ressourcen) |
| Projektleitung | KI-Beauftragte (du) — neu eingestellt, im Amt seit Mai 2026 |
| Auftraggeber | Heinrich Mäurer jun., Geschäftsführer |
| Steuerungskreis | Junior Mäurer · CISO Schreiber · DSB Hoffmann · IT-Leiter Brandes · Betriebsrat |
| Externer Implementierungspartner | tba — Auswahl im Projektmonat 1 |
| Pilotbereich | Service-Außendienst Bremen + Niederlassung Yokohama |

### Was vorausgegangen ist

**Vor drei Monaten** wurde Microsoft 365 Copilot eingeführt — knapp, aber erfolgreich. Hoffmann (DSB) und der Senior waren skeptisch, haben sich aber überzeugen lassen. Diese erste Erfahrung ist Rückenwind und Hypothek zugleich: Rückenwind, weil M365 läuft. Hypothek, weil das Wissensmanagement-Projekt ungleich tiefer in die Organisation eingreift — und alle wissen das.

### Das Senior-Motto

Heinrich Mäurer sen. hat dem Projekt ein Motto mitgegeben, das in der Projektakte ausdrücklich vermerkt ist:

> *„Qualität kann man nicht nachträglich hineinkontrollieren, man muss es immer in den Prozess hineinbauen."*

Der Junior hat das Zitat akzeptiert und im Auftrag verankert. Das bedeutet operativ: **Qualitätssicherung ist nicht ein Schritt am Ende — sie ist Teil der Projektarchitektur.**

---

## 2. Die Beteiligten — Stakeholder-Bögen

### Heinrich Mäurer jun. — Geschäftsführer, dein Auftraggeber

**Profil:** 38, Betriebswirt mit MBA, in den USA studiert und gearbeitet. Übernahme vor sechs Monaten vom Vater. Modern aufgestellt, KI-affin, ungeduldig.

**Was er will:** Ein sichtbarer Erfolg im ersten Jahr — als Beweis, dass seine Übernahme eine neue Ära einleitet.

**Was er fürchtet:**
- Im Schatten des Vaters zu stehen
- Dass das Projekt scheitert und er als „der Neue, der zu viel wollte" dasteht
- Dass die alte Garde ihn auflaufen lässt

**Wie er kommuniziert:** Direkt, leicht ungeduldig, aber lernfähig. Schickt SMS um 22:30. Erwartet schnelle Reaktion.

**Sein Verhältnis zu dir:** Du bist seine Hoffnung. Er erwartet, dass du das Projekt zum Erfolg führst. Wenn er merkt, dass du auch nur die Bremserolle übernimmst, wird er enttäuscht sein.

**Roter Satz:** *„Ich brauche jemanden, der das durchzieht. Nicht jemanden, der mir erklärt, warum es nicht geht."*

---

### Heinrich Mäurer sen. — Seniorchef, der Schatten im Hintergrund

**Profil:** 71, Maschinenbau-Ingenieur, hat das Unternehmen 1978 gegründet und 47 Jahre lang geführt. Nicht mehr operativ — aber präsent. Geht zwei Mal pro Woche durchs Haus, frühstückt mit Brockmann, telefoniert mit Schreiber.

**Was er will:** Dass das, was er aufgebaut hat, weiter funktioniert. Dass die alte Garde nicht überrollt wird. Dass das Maritime-Geschäft seinen Charakter behält.

**Was er fürchtet:** Dass das Unternehmen seine Seele verliert. Dass das Wissen, das er und seine Generation aufgebaut haben, in einem Computer landet — und dann gehört es niemandem mehr.

**Wie er kommuniziert:** Knapp. Trocken. „Hmm." als vollständiger Satz. Oder: „Das werden wir sehen."

**Sein Verhältnis zu dir:** Höflich, distanziert, beobachtend. Wird dich nie konfrontieren — aber er hört zu, wenn die alte Garde über dich redet.

**Roter Satz:** *„Qualität kann man nicht nachträglich hineinkontrollieren. Das gilt auch für so ein Projekt."*

---

### Dr. Petra Schreiber — Chief Information Security Officer

**Profil:** 52, promovierte Informatikerin, seit 15 Jahren bei WellSeal. Tiefes Vertrauen des Seniors. Geprägt durch den Ransomware-Angriff 2019, der die Produktionssteuerung lahmgelegt hat — sie hat das damals durchgestanden, ohne dass Daten endgültig verloren gingen. Sie wird das nie vergessen, und das Unternehmen vergisst es ihr nicht.

**Was sie will:** Dass dieses Unternehmen nie wieder einen Sicherheitsvorfall hat, der die Produktion bedroht.

**Was sie fürchtet:**
- Datenabfluss über Cloud-KI-Dienste
- Schlechte SharePoint-Berechtigungen, die durch Copilot sichtbar werden („Oversharing")
- Internationale Datentransfers ohne klare rechtliche Absicherung
- Dass „die Neuen" Sicherheitsstandards aufweichen, weil sie schnell sein wollen

**Wie sie kommuniziert:** Präzise, vorbereitet, stellt Detailfragen, die in 80 Prozent der Fälle die richtigen sind. Mag keine Powerpoint-Slogans. Will Datenflussdiagramme.

**Ihr Verhältnis zu dir:** Misstrauisch, aber fair. Wenn du ihre Fragen ernst nimmst und Antworten lieferst, kann sie zur Verbündeten werden. Wenn du sie als Bremserin abtust, wird sie das Projekt blockieren — mit fachlich korrekten Argumenten, gegen die du wenig sagen kannst.

**Roter Satz:** *„Ich werde nichts absegnen, was ich nicht verstanden habe. Das ist meine Aufgabe."*

**Rote Linie:** SAP-Daten verlassen das Unternehmen unter keinen Umständen — diese Forderung hat sie schon im Rahmen anderer Projekte durchgesetzt.

---

### Marcus Hoffmann — Datenschutzbeauftragter (extern)

**Profil:** 49, Rechtsanwalt, externer DSB, betreut WellSeal seit 2018. Kanzlei in Hamburg. Sehr DSGVO-konservativ. Hat 2022 ein digitales Personalprojekt gestoppt, weil die Auftragsverarbeitungsvereinbarung mit dem US-Cloud-Anbieter unzureichend war.

**Was er will:** Dass die WellSeal datenschutzrechtlich sauber bleibt — auch international.

**Was er fürchtet:**
- DSGVO-Verstöße, für die er als DSB einstehen muss
- Internationale Datentransfers, die er nicht überblicken kann (PIPL, APPI sind Neuland für ihn)
- KI-Systeme, die personenbezogene Daten in Kontexten verarbeiten, die er nicht modellieren kann

**Wie er kommuniziert:** Schriftlich, mit Aktenzeichen. Mündliche Aussagen sind für ihn nicht verbindlich. Will jedes Detail in einer Mail bestätigt sehen.

**Sein Verhältnis zu dir:** Höflich, aber zurückhaltend. Wird im Zweifel ablehnen statt zustimmen — bis du ihm einen tragfähigen Rahmen anbietest.

**Roter Satz:** *„Im Zweifel für den Datenschutz. So ist meine Berufsethik."*

**Wo du ihm helfen kannst:** Hoffmann kennt PIPL und APPI nur oberflächlich. Wenn du ihm ein internationales Datenschutz-Briefing besorgst (extern oder selbst), wird er dir das hoch anrechnen.

---

### Kai Brandes — IT-Leiter

**Profil:** 47, Wirtschaftsinformatiker, seit 12 Jahren bei WellSeal. Hat SAP eingeführt und betreibt es. Leitet ein Team von 8 Personen — 2 für SAP, 3 für Netzwerk/Server, 2 für Helpdesk, 1 für M365. Versteht M365 als Infrastruktur, nicht als Werkzeug.

**Was er will:** Dass sein Team nicht überlastet wird. Dass keine neuen Systeme dazukommen, ohne dass er Personal bekommt.

**Was er fürchtet:**
- Dass ihm das KI-Projekt aufgehalst wird, ohne dass jemand sein Team verstärkt
- Dass im Pilot Fehler entstehen, für die sein Helpdesk haftet
- Dass die internationale Anbindung neue Sicherheitslücken aufreißt, die Schreiber ihm anlastet

**Wie er kommuniziert:** Sachlich, zurückhaltend. Sagt nicht direkt nein, sondern nennt Bedingungen. „Ja, wenn ich zwei zusätzliche Vollzeit-Stellen bekomme."

**Sein Verhältnis zu dir:** Pragmatisch. Du bist für ihn weder Bedrohung noch Hoffnung — du bist eine neue Schnittstelle, mit der er klarkommen muss. Wenn du ihm zeigst, dass du seine Belastung verstehst und das Projekt seine Last nicht erhöht, hast du einen verlässlichen Partner.

**Roter Satz:** *„Wenn das Ding produktiv geht, will ich wissen, wer den 24/7-Support macht."*

---

### Klaus Brockmann — Werkmeister, informeller Wortführer der „alten Garde"

**Profil:** 58, gelernter Industriemechaniker mit Meisterbrief, seit 32 Jahren bei WellSeal. Hat das interne Diagnose-Handbuch geschrieben, das in der Werkstatt liegt — 380 Seiten, drei Auflagen. Niemand sonst kennt das Material so. Sein Spitzname intern: „der Brock".

**Was er will:** Dass seine Erfahrung gewürdigt wird. Dass die Service-Ingenieure von ihm lernen — nicht von einer Maschine.

**Was er fürchtet:**
- Dass die jüngeren Kollegen das Handbuch in eine KI laden und dann meinen, sie hätten verstanden, was er weiß
- Dass sein Wert für das Unternehmen schwindet, sobald sein Wissen „im System" ist
- Dass er in fünf Jahren nicht mehr gebraucht wird

**Wie er kommuniziert:** Direkt, manchmal ruppig. Nutzt Bilder aus der Werkstatt: *„Eine Dichtung, die du am Schreibtisch konstruiert hast, ist keine Dichtung — sie ist ein Vorschlag."*

**Sein Verhältnis zu dir:** Erstkontakt im Projektmonat 1. Wird höflich sein. Beobachtet. Bildet sich ein Urteil über mehrere Wochen.

**Was du wissen musst:** Brockmann ist der Schlüssel. Wenn er das Projekt unterstützt, kommen die anderen sieben Senioren mit. Wenn er es ablehnt — auch dann kommen die anderen mit, aber in die andere Richtung.

**Roter Satz:** *„30 Jahre. Du bekommst 30 Jahre nicht in einen Computer."*

---

### Drei weitere namentliche Stimmen aus der alten Garde

| Name | Funktion | Charakteristikum |
|---|---|---|
| **Anke Drewes** | Senior-Konstrukteurin, 56 | Aufgeschlossen für Digitalisierung — ihre Tochter arbeitet bei einem Tech-Startup. Skeptisch gegenüber Brockmann, aber loyal. Wenn jemand „kippt", dann sie zuerst. |
| **Hans-Joachim Wittenberg** | Senior-Diagnostiker, 61 | Technisch interessiert, aber zutiefst misstrauisch gegenüber Cloud-Diensten. Hat 1985 ein elektronisches Lager-System eingeführt, das nach drei Jahren vom Hersteller eingestellt wurde — *„Damit fing das Misstrauen an"*. |
| **Bernd Kruse** | Werkmeister Yokohama (entsandt), 54 | Sitzt seit 2008 in Yokohama. Spricht Japanisch. Sieht das Pilotprojekt mit gemischten Gefühlen — er weiß, dass die japanischen Kollegen ein RAG-System gut nutzen würden, fürchtet aber Bremsens-Druck aus Bremen. |

**Plus fünf weitere abstrakte Stimmen** der alten Garde — sieben Werkmeister und Konstrukteure am Standort Bremen, die nicht namentlich auftreten, aber als Gruppe spürbar sind.

---

## 3. Die Datenrealität

Hier wird's unaufgeräumt — wie es in Wirklichkeit ist.

### SharePoint-Inventur (Bestand vor Projektstart)

**Insgesamt 12.400 Dokumente** in 47 Bibliotheken — Stand 1. Mai 2026.

| Bibliothek | Dokumente | Berechtigungen | Zustand |
|---|---|---|---|
| Diagnose-Handbuch (Brockmann, scans + Word) | 380 Seiten + 14 Word-Anhänge | Lesezugriff: alle Service-Ingenieure | Sauber, gut gepflegt |
| Wartungsberichte 2010–2025 | ca. 7.800 PDFs (gescannt) | „Jeder authentifizierte Nutzer" | Inkonsistent benannt, ohne Metadaten |
| Reparaturhistorien Houston | ca. 1.200 Excel-Dateien | „Nur USA-Niederlassung" — aber 14 Bremer Mitarbeiter haben Zugriff (vergessene Rechte aus 2018) | Englisch, anderes Klassifizierungsschema |
| Reparaturhistorien Yokohama | ca. 950 PDFs | Berechtigungen unklar | Japanisch, OCR teilweise fehlerhaft |
| Ältere Materialien (Mäurer sen. persönlich) | ca. 280 Dateien | „Nur Geschäftsführung" | Nicht digitalisiert — Papierordner, die der Senior in seinem Büro hat |
| Sammelordner „Hochladen-vorläufig" | ca. 1.800 Dateien | „Jeder im Unternehmen" | Mischmasch — Privatfotos, Schulungsvideos, alte Verträge |

**Schreibers Bewertung dieser Inventur** (E-Mail vom 28. April 2026):
*„Bevor ich auch nur eine KI-Anbindung freigebe, müssen wir hier aufräumen. Der Sammelordner ist ein Datenschutz-Albtraum. Das ist Voraussetzung, nicht Verhandlungsmasse."*

### Wartungshistorien — der heikle Teil

Die wertvollste Datenquelle für das RAG-System sind die Reparaturhistorien. Das Problem:

- **Etwa 60 Prozent** liegen in SharePoint, gescannt, ohne strukturierte Felder
- **Etwa 30 Prozent** existieren nur als handschriftliche Notizen in Brockmanns Dienstbüchern (12 Bände, von 1993 bis heute) — physisch in seinem Büro
- **Etwa 10 Prozent** sind als E-Mail-Korrespondenz mit Kunden archiviert — bei den Service-Ingenieuren in den persönlichen Postfächern

Brockmann hat in einer informellen Bemerkung gesagt: *„Was in den Büchern steht, das gebe ich nicht raus, bevor ich nicht weiß, was damit gemacht wird."*

### Die internationale Datenfrage

Die Yokohama-Daten unterliegen dem japanischen APPI (Act on the Protection of Personal Information). Houston-Daten sind US-Recht. Shanghai unterliegt dem PIPL — und PIPL hat Vorschriften für **Datenexport aus China**, die sehr streng sind.

Hoffmann hat dazu im Stakeholder-Termin gesagt: *„Ich bin nicht der Experte für PIPL und APPI. Wir brauchen für jedes Land eine separate Bewertung. Das ist mit meinem Kanzlei-Volumen für WellSeal nicht abgedeckt."*

### Aktualität der Daten

Etwa 15 Prozent der Reparaturhistorien sind älter als 10 Jahre — und betreffen Produkttypen, die WellSeal heute nicht mehr herstellt. Das RAG-System würde diese Inhalte gleichberechtigt mit aktuellen Daten heranziehen.

---

## 4. Der Projektkalender — sechs Monate

Pro Kurstag ein Projektmonat. Was in jeder Phase passiert:

### Projektmonat 1 (entspricht Tag 12) — Initiation

**Geplante Hauptaktivitäten:**
- Kick-off mit Steuerungskreis
- Anforderungsanalyse: Was soll das RAG-System genau leisten?
- Auswahl externer Implementierungspartner (drei Anbieter im Vergleich)
- Erste Stakeholder-Gespräche mit der alten Garde

**Stimmungsbild zum Monatsende:** Junior euphorisch, Schreiber misstrauisch, Brockmann höflich-distanziert, Brandes überfordert mit der zusätzlichen Last.

### Projektmonat 2 (entspricht Tag 13) — Anforderungs-Vertiefung

**Geplante Hauptaktivitäten:**
- Detail-Anforderungen pro Zielgruppe (Service-Ingenieure intern, Agenten international, Onboarding)
- Test- und Abnahmekriterien definieren
- Risiko-Klassifikation nach EU AI Act (Hochrisiko ja/nein?)
- Datenschutz-Folgenabschätzung (DSFA) initiieren

**Stimmungsbild zum Monatsende:** Erste Reibung — die Zielgruppen wollen unterschiedliche Dinge, die alte Garde wird zum ersten Mal konkret nach Inhalten gefragt. Brockmann reagiert ausweichend.

### Projektmonat 3 (entspricht Tag 14) — Datenmanagement & Pilotvorbereitung

**Geplante Hauptaktivitäten:**
- SharePoint-Aufräumen (Schreibers Vorbedingung) startet
- Daten-Audit der Wartungshistorien
- Internationale Daten-Compliance pro Land klären
- Onboarding-Bot-Inhalte definieren (Reisekosten, Krankmeldung, Kantine, Quittungs-Scan)

**Stimmungsbild zum Monatsende:** Die Datenrealität wird sichtbar — die Lücken, die Inkonsistenzen, die handschriftlichen Bücher. Junior fragt: *„Warum dauert das so lange?"*

### Projektmonat 4 (entspricht Tag 15) — Pilot beginnt — und Widerstand wird sichtbar

**Geplante Hauptaktivitäten:**
- Pilot-Start: Bremen Service + Yokohama
- 8 Service-Ingenieure und 4 japanische Agenten als Pilot-Nutzer
- Erste Daten in das RAG-System eingespeist
- Wöchentliches Pilot-Monitoring beginnt

**Was tatsächlich passiert:** Brockmann hat zugesagt, drei seiner Dienstbücher zur Verfügung zu stellen. Im Projektmonat 4 stellt sich heraus, dass er bisher zwei Bücher übergeben hat — beide aus den Jahren 2003–2005. Die aktuelleren Bücher (2018–2026, die wertvollsten) liegen weiterhin in seinem Büro. Auf Nachfrage sagt er: *„Ich komme nicht dazu, die Stellen rauszusuchen, die freigegeben werden können."*

Drei der acht Pilot-Service-Ingenieure liefern keine Test-Diagnose-Anfragen ans System. Auf Nachfrage: *„Brockmann hat gesagt, wir sollen erst abwarten."*

In der wöchentlichen Pilot-Auswertung zeigt sich: Das System antwortet auf die wenigen vorhandenen Anfragen — aber die Antworten sind oft zu generisch. Der Grund: die Datenbasis ist dünn.

### Projektmonat 5 (entspricht Tag 16) — die Eskalation und die Strategie

**Was zum Stand des Monatsbeginns passiert:** Junior fordert ein Gespräch mit dir. *„Wir verlieren Zeit. Brockmann blockiert. Was tun?"* Schreiber sagt im selben Steuerungskreis-Termin: *„Hab' ich es nicht gesagt? Ich habe von Anfang an darauf hingewiesen, dass die Akzeptanz das Risiko ist."*

Du musst entscheiden, wie das Projekt weitergeht. Drei Optionen liegen auf dem Tisch:

- **Option A — Eskalation:** Junior schreibt eine deutliche Mail an die Senior-Werkmeister, mit Hinweis auf Verbindlichkeit.
- **Option B — Verhandlung:** Persönliches Gespräch mit Brockmann, Bedingungen klären, Win-Win suchen.
- **Option C — Reduktion:** Pilot-Scope reduzieren, Projekt zeitlich strecken, Akzeptanz priorisieren.

### Projektmonat 6 (entspricht Tag 17) — Projektabschluss und Übergabe

**Was hier passiert:** Das Projekt erreicht den geplanten Endmonat. Je nachdem, was in Projektmonat 5 entschieden wurde, sind drei Endungen denkbar:

- Erfolgreicher Rollout (verkleinert oder vollständig)
- Geordneter Projektabbruch
- Skalierter Pilot, der erst in 12 Monaten produktiv wird

Was in Projektmonat 6 tatsächlich passiert, hängt vom Verlauf ab. **Mehr dazu am Ende der Akte.**

---

## 5. Das Senior-Motto in der Praxis

> *„Qualität kann man nicht nachträglich hineinkontrollieren, man muss es immer in den Prozess hineinbauen."*

Dieser Satz strukturiert die sechs Projektmonate. In jeder Phase stellt sich die Frage: **Wo bauen wir Qualität in den Prozess hinein?**

| Projektmonat | Wo Qualität in den Prozess hineingebaut wird |
|---|---|
| 1 | Anforderungen werden messbar formuliert (nicht „besser werden", sondern z. B. „Ø Antwortzeit < 30 Sekunden, Falschpositiv-Rate < 5 %") |
| 2 | Abnahmekriterien werden VOR der Implementierung definiert — nicht nach |
| 3 | Datenqualität wird VOR dem Training geprüft — nicht nach |
| 4 | Pilotmessungen sind Teil der Architektur — nicht nachträgliches Reporting |
| 5 | Konflikt-Eskalations-Pfade waren VOR dem Konflikt definiert — nicht erfunden, wenn er eintritt |
| 6 | Übergabe-Kriterien an den Betrieb stehen seit Monat 1 fest — nicht ad hoc verhandelt |

**Wenn das Senior-Motto gilt, ist Qualitätssicherung nicht ein Schritt — sie ist der Charakter des Projekts.**

---

## 6. Was du am Ende von Tag 17 wissen wirst

Am Ende der sechs Tage wirst du:

- Konkrete QS-Anforderungen an ein KI-System formulieren können
- Test- und Abnahmeverfahren für KI-Systeme entwerfen können
- Datenqualität als operatives Konzept verstehen — nicht als abstraktes Schlagwort
- Datenmanagement-Strukturen aufbauen und beschreiben können
- Stakeholder-Widerstand strukturiert analysieren können
- Eskalationspfade entwickeln und bei Bedarf gehen können
- Einschätzen können, wann ein Projekt gerettet werden sollte und wann nicht

**Und du wirst die Antwort auf die Frage haben, wie dieses Projekt endet — denn die hängt davon ab, was du in Projektmonat 5 entschieden hättest.**

---

## 7. Drei mögliche Endungen — Stand Projektmonat 6

### Endung A — Erfolgreicher Rollout
Das Wissensmanagement-System geht in vollem Umfang produktiv. Brockmann hat — nach intensiven Gesprächen und einer offiziellen Würdigung seiner Rolle — alle Dienstbücher freigegeben. Die alte Garde ist mit an Bord, weil sie als Co-Autoren erscheinen. Das System läuft. Schreiber ist vorsichtig zufrieden. Junior triumphiert.

### Endung B — Geordneter Projektabbruch
Das Projekt wird in Projektmonat 6 offiziell beendet. Die Datenbasis hat sich als zu dünn erwiesen, die Akzeptanz war nicht zu erreichen. WellSeal nimmt das M365-Copilot-System weiter in Betrieb — als KI-Werkzeug ohne Unternehmensspezifik. Das ist kein Triumph, aber auch kein Skandal. Was verloren geht: 280.000 € und sechs Monate. Was gewonnen wird: Die Erkenntnis, dass die Organisation noch nicht reif ist. Junior ist enttäuscht, Schreiber sachlich, Brockmann erleichtert.

### Endung C — Skalierter Pilot mit Verlängerung
Das Projekt wird auf 12 Monate gestreckt. Der Pilot wird auf Yokohama beschränkt, wo Bernd Kruse und die japanischen Kollegen ein funktionierendes Mini-System aufbauen. Bremen wartet ab. Brockmann beobachtet — und beginnt allmählich, sich von Yokohama eines Besseren belehren zu lassen. In 18 Monaten könnte das System auch in Bremen produktiv gehen — oder auch nicht.

**Welche Endung wahrscheinlich ist, hängt davon ab, was in Projektmonat 5 entschieden wurde — und wie die Stakeholder darauf reagiert haben.**

---

## 8. Zum Abschluss

Diese Projektakte ist deine Begleitlektüre für sechs Kurstage. Behandelt sie nicht als Lehrbuch — sondern als Realität. Schreibt euch Notizen rein. Markiert die Stellen, an denen ihr unsicher seid. Diskutiert in den Gruppen, was ihr getan hättet.

Am Ende geht es nicht darum, „die richtige" Lösung zu finden. Es geht darum, zu erkennen, **welche Lösung in welcher Lage angemessen ist** — und das zu begründen.

Viel Erfolg.

---

*alfatraining · KI-Beauftragte:r · Projektakte UC-02 · Wissensmanagement-RAG WellSeal · Mai 2026*

# Simulation: Pre-Mortem (Übung 3) aus Sicht der D³-Teilnehmenden

> **Archiv.** Stand vor der Überarbeitung der Folien, nicht mehr gepflegt. Aktuell gelten [index.qmd](index.qmd) und [uebungen_vorbereitung.md](uebungen_vorbereitung.md).

Gedankenexperiment zur Vorbereitung: Wie laufen die vier Räume, wenn typische D³-Teilnehmende drinsitzen? Pro Raum: wer sitzt da, was denken sie beim Lesen der Karte, wie läuft die Diskussion, was steht nach 8 Minuten im Pad, was fehlt. Am Ende: Folgerungen für Moderation und Material.

**Annahmen zum Publikum (D³ Kongress, online):** gemischt aus Hauptamtlichen kleiner und mittlerer Vereine, Ehrenamtlichen, Digital-Verantwortlichen „nebenbei“, ein paar Leuten aus Stiftungen/Förderung und einzelnen Tech-affinen (Entwickler*innen, Data-Leute). Viele haben ChatGPT ausprobiert, wenige ein KI-Projekt umgesetzt. Grundhaltung eher skeptisch-neugierig. 3–6 Personen pro Raum, nicht alle mit Kamera, 1–2 sagen wenig.

---

## Raum A · Migrationsberatung: Gespräche transkribieren und zusammenfassen

### Wer sitzt im Raum

- **Sevgi**, Sozialarbeiterin in einer Flüchtlingsberatung – kennt die Doku-Last aus eigener Erfahrung
- **Martin**, Geschäftsführer eines Wohlfahrtsverbands-Kreisverbands – denkt an Förderung und Haftung
- **Lena**, Datenschutz-Ehrenamtliche in einem Netzwerk – sieht sofort das Problem
- **Tobi**, Entwickler, engagiert bei einer Civic-Tech-Gruppe – hat Whisper schon lokal laufen lassen
- 1 Person ohne Kamera, schreibt nur im Pad

### Gedanken beim Lesen der Karte (1 min)

- Sevgi: *„Ein Drittel Doku – stimmt. Das wäre ein Traum.“*
- Lena: *„Aufenthaltsstatus und Gesundheit in einen Cloud-Dienst? Art. 9 DSGVO. Das ist doch tot, bevor es anfängt.“*
- Tobi: *„Transkription ist gelöst, Whisper läuft lokal. Das Problem ist die Zusammenfassung.“*
- Martin: *„Handy-Aufnahme? Wessen Handy? Dienst- oder Privathandy?“*
- Stille Person: *„Wollen die Ratsuchenden überhaupt aufgenommen werden?“*

### Diskussion (6 min, verdichtet)

> **Lena:** Ich fang mal an: Datenschutzbehörde oder Träger hat das gestoppt. Gesundheitsdaten, Aufenthaltsstatus, US-Cloud – das geht nicht.
> **Tobi:** Muss ja keine US-Cloud sein. Mit lokalem Modell ginge das.
> **Martin:** Aber das stand nicht im Antrag. Im Antrag steht „Cloud-Dienst“. Und wer betreibt den lokalen Server, wenn die Förderung nach 2 Jahren endet?
> **Sevgi:** Ich glaube, es scheitert schon früher. Die Leute sagen im Gespräch nicht mehr alles, wenn das Handy auf dem Tisch liegt. Gerade wenn es um den Aufenthalt geht.
> **Tobi:** Und die Gespräche sind ja oft mit Dolmetscher*in oder halb Deutsch, halb was anderes. Das Transkript wird Müll.
> **Sevgi:** Und dann steht in der Akte was Falsches. „Hat keine Familie im Herkunftsland“ – und das wird später im Asylverfahren relevant.
> **Martin:** Wer liest die Zusammenfassung gegen? Wenn die Berater*innen jede Zusammenfassung prüfen müssen, ist die Zeitersparnis weg.
> **Lena:** Einwilligung ist auch nicht freiwillig, wenn man in der Beratung sitzt und auf Hilfe angewiesen ist.


### Pad nach 8 min (wahrscheinlich)

- **Gescheitert, weil …**
  - Datenschutz: sensible Daten (Aufenthalt, Gesundheit) in der Cloud → Träger/Datenschutzbeauftragte stoppt Projekt
  - Ratsuchende fühlen sich durch Aufnahme unwohl, erzählen weniger, Vertrauen leidet
  - Transkripte bei Mehrsprachigkeit/Dolmetschen schlecht, Fehler landen in der Akte, Prüfen kostet so viel Zeit wie vorher
- **Damit es 🦊 wird, müsste …**
  - lokales/EU-gehostetes Modell, kein Audio verlässt die Beratungsstelle
  - Ratsuchende können ohne Nachteil Nein sagen; Aufnahme nur mit echter Einwilligung
  - Berater*in diktiert nach dem Gespräch selbst eine Zusammenfassung statt das Gespräch aufzunehmen
- **Einschätzung:** 🤔 – Problem ist echt, aber so wie beantragt nicht machbar; Diktat statt Mitschnitt wäre realistisch

### Was die Gruppe gut trifft / was fehlt

- **Trifft:** Kriterium 6 (Datenschutz, Betroffene) sehr stark, Kriterium 4 (Fehlerkosten) indirekt über „Fehler in der Akte“
- **Kommt oft spät oder gar nicht:** Kriterium 5 (wer betreibt das nach 2 Jahren?) – kommt nur, wenn jemand wie Martin dabei ist. Kriterium 2 (einfachere Lösung) taucht als „Diktat“ auf, wird aber nicht als „keine KI nötig“ erkannt – Diktat + Spracherkennung ist immer noch KI, nur weniger riskant
- **Typischer Denkfehler:** „Lokales Modell“ wird als Allheilmittel genannt, ohne Frage nach Betrieb und Kompetenz
- **Gute Debrief-Frage:** „Wer sitzt mit im Raum, wenn aufgenommen wird – und wurde die Person gefragt?“

---

## Raum B · Mieterverein: semantische Suche über 15 Jahre Rundbriefe

### Wer sitzt im Raum

- **Karin**, Ehrenamtliche in einem Mieterverein/einer Mieterinitiative – kennt die Rundbriefe
- **Jonas K.**, Referent Kommunikation bei einem Umweltverband – will das Gleiche fürs eigene Archiv
- **Petra**, Programmleitung bei einer Stiftung – denkt an Förderlogik
- **Ali**, Data Scientist im Ehrenamt (CorrelAid-nah) – kennt RAG
- 1–2 Stille

### Gedanken beim Lesen der Karte

- Karin: *„Was 2012 im Rundbrief stand, ist heute oft falsch. Mietrecht ändert sich ständig.“*
- Jonas K.: *„Das klingt eigentlich gut, das wollen wir auch.“*
- Petra: *„Einmalig 25.000 €, laufende Kosten trägt der Verein – klassisch.“*
- Ali: *„600 Ausgaben ist klein, das ist technisch machbar. PDFs sind die Frage.“*

### Diskussion (verdichtet)

> **Karin:** Das größte Problem: alte Artikel sind veraltet. Mietpreisbremse, Heizkosten, Kündigungsfristen – das hat sich alles geändert. Der Bot gibt dann eine Antwort von 2013 aus.
> **Ali:** Man könnte Datum mit ausgeben und neuere Artikel bevorzugen.
> **Karin:** Und wer merkt, welcher Artikel nicht mehr stimmt? Das macht doch keiner.
> **Petra:** Und dann fragt ein Mitglied „Darf mein Vermieter X?“ und bekommt eine Rechtsauskunft. Darf der Verein das ohne Beratung? Rechtsdienstleistungsgesetz?
> **Jonas K.:** Hm. Und wenn die Antwort falsch ist, haftet wer?
> **Ali:** Die API-Kosten sind übrigens klein bei 8.000 Mitgliedern, das ist nicht das Problem. Eher: wer wartet das, wenn die Agentur weg ist?
> **Petra:** Das Stiftungsgeld ist für den Bau, nicht für den Betrieb. Nach einem Jahr läuft die Lizenz aus oder das Ding geht kaputt und keiner kann es fixen.
> **Jonas K.:** Vielleicht reicht ja auch eine gute Volltextsuche mit Schlagworten?
> **Karin:** Die Mitglieder rufen ja nicht an, weil sie nichts finden. Die rufen an, weil sie mit einem Menschen sprechen wollen.


### Pad nach 8 min (wahrscheinlich)

- **Gescheitert, weil …**
  - Antworten auf Basis veralteter Artikel (Mietrecht geändert), Mitglieder handeln danach
  - Niemand pflegt das Archiv / keine Kapazität nach Ende der Stiftungsförderung; technischer Betrieb ungeklärt
  - Rechtliche Unsicherheit: Ist eine automatische Antwort eine Rechtsberatung?
- **Damit es 🦊 wird, müsste …**
  - Suche zeigt Fundstellen mit Datum statt eine fertige Antwort zu formulieren
  - jemand ist zuständig, alte Artikel als „veraltet“ zu markieren
  - Betrieb und Kosten für mind. 3 Jahre im Vereinshaushalt eingeplant
- **Einschätzung:** 🤔 – als interne Suche für die Beratenden 🦊, als Antwortmaschine für Mitglieder 🧙

### Was die Gruppe gut trifft / was fehlt

- **Trifft:** Kriterium 5 (Betrieb nach Förderende) stark, Kriterium 2 (Volltextsuche) wird angesprochen, Kriterium 4 indirekt (falsche Antworten)
- **Spannende Erkenntnis, die oft kommt:** „Für die Beratenden statt für die Mitglieder“ – deckt sich mit dem Debrief zu C (Wer sitzt vor der KI?). Im Debrief verbinden!
- **Fehlt oft:** Wie misst man, ob die Suche gut ist? (Kriterium 4: 50 echte Mitgliederfragen sammeln, prüfen, ob der richtige Artikel kommt.) Niemand denkt von sich aus an Testfragen
- **Typischer Denkfehler:** API-Kosten werden überschätzt oder unterschätzt – die eigentlichen Kosten sind Personal und Pflege, nicht Tokens. Auf der Karte steht „API-Kosten“, Leute bleiben daran hängen
- **Hinweis:** Raum B ist der „sympathischste“ Fall; Gefahr, dass die Gruppe schnell bei 🦊 landet und wenig Gründe findet. Zeitwächter*in sollte nach 3 min fragen: „Wir haben erst einen Grund.“

---

## Raum C · Schuldnerberatung: Chatbot für Erstfragen

### Wer sitzt im Raum

- **Andreas**, Schuldnerberater bei einem kirchlichen Träger – Fachexperte, sehr kritisch
- **Mia**, Digitalisierungsbeauftragte einer Kommune – hat solche Pilotprojekte gefördert
- **Jana**, Ehrenamtliche in einer Tafel – kennt die Zielgruppe
- **Felix**, UX-Designer, engagiert bei einem Civic-Tech-Projekt
- 1 Stille

### Gedanken beim Lesen der Karte

- Andreas: *„Pfändungsschutz ist hochgradig einzelfallabhängig. Ein Chatbot, der das beantwortet, ist gefährlich.“*
- Mia: *„Klingt nach den Projekten, die wir genau so gefördert haben. 12 Monate Pilot, danach Schluss.“*
- Jana: *„Die Leute, die zu uns kommen, haben oft kein gutes Deutsch, manche kein Smartphone mit Datenvolumen.“*
- Felix: *„Das eigentliche Problem sind 10 Wochen Wartezeit. Das löst kein Chatbot.“*

### Diskussion (verdichtet)

> **Andreas:** Das Ding hat jemandem falsch gesagt, sein Konto darf gepfändet werden – oder eben nicht – und der hat eine Frist verpasst. Das ist mein Szenario Nummer eins.
> **Felix:** Und das Grundproblem: 10 Wochen Wartezeit, weil es zu wenige Berater*innen gibt. Der Chatbot macht die Wartezeit nicht kürzer.
> **Mia:** Ehrlich gesagt: Das ist oft der Grund, warum sowas gefördert wird. Ein Chatbot ist billiger als eine Stelle.
> **Andreas:** Und die Telefonsprechstunde fällt weg. Gerade die zwei Stunden waren für Notfälle.
> **Jana:** Wer in Panik ist, weil das Konto gesperrt ist, will nicht mit einem Bot schreiben.
> **Felix:** Man könnte die Infoseiten verbessern. Ein gutes FAQ zum P-Konto, klar strukturiert. Dafür braucht's keine KI.
> **Mia:** Und nach 12 Monaten ist das Geld weg, dann hängt da ein Bot, den keiner aktualisiert, und die Pfändungsfreigrenzen ändern sich jedes Jahr.


### Pad nach 8 min (wahrscheinlich)

- **Gescheitert, weil …**
  - Falsche Auskunft zu Pfändung → Person verpasst Frist, öffentlicher Skandal, Projekt gestoppt
  - Eigentliches Problem (zu wenig Personal, 10 Wochen Wartezeit) bleibt; Bot ersetzt Telefonsprechstunde → Notfälle gehen verloren
  - Nach 12 Monaten keine Förderung, niemand aktualisiert Freigrenzen/Rechtslage
- **Damit es 🦊 wird, müsste …**
  - Chatbot gibt keine Rechtsauskunft, sondern nur Orientierung + schnelle Weiterleitung bei Fristen/Notfall
  - Telefonsprechstunde bleibt, Bot ist zusätzlich
  - besser: KI unterstützt die Berater*innen (z. B. Unterlagen vorsortieren), damit mehr Termine möglich sind
- **Einschätzung:** 🧙 – das Problem ist Personalmangel, nicht fehlende Erreichbarkeit

### Was die Gruppe gut trifft / was fehlt

- **Trifft:** Kriterium 1 (systemisches Problem) sehr deutlich – das ist der Fall, an dem Kriterium 1 am besten landet. Kriterium 2 (bessere Website), 4 (Fehlerkosten), 5 (12 Monate) alles drin
- **Fehlt eher:** Kriterium 6 Datenschutz – Ratsuchende tippen Schulden, Kontodaten, Namen von Gläubigern in den Bot. Wird selten genannt, weil der Fokus auf falschen Antworten liegt. Im Debrief ergänzen
- **Raum C ist der stärkste Raum fürs Debrief**, weil sich alle schnell einig sind. Gefahr: Gruppe ist nach 4 min „fertig“ und redet über Förderpolitik allgemein. Frage 2 (🦊-Bedingung) zwingt zurück zur Konstruktion
- **Erwartbar:** Die Gruppe kommt selbst auf „KI für die Fachkraft statt für Ratsuchende“ → direkt Brücke zu KIA im Debrief

---

## Raum D · Verein: Agent bereitet Förderanträge vor

### Wer sitzt im Raum

- **Ute**, Vorstand eines kleinen Naturschutzvereins – schreibt selbst Anträge, findet die Idee verlockend
- **Daniel**, Fundraiser bei einer mittelgroßen NGO – nutzt ChatGPT schon für Antragsentwürfe
- **Sarah**, Referentin bei einer Förderstiftung – liest die Anträge auf der anderen Seite
- **Kai**, Student, interessiert an KI-Agents, technisch neugierig
- 1 Stille

### Gedanken beim Lesen der Karte

- Ute: *„Wenn das klappt, wäre das großartig. Wir sind zu zweit und schreiben nachts.“*
- Daniel: *„Machen wir eh schon, nur halt manuell mit ChatGPT.“*
- Sarah: *„Wir kriegen gerade massenhaft Anträge, die alle gleich klingen. Wir merken das.“*
- Kai: *„Was heißt ‚Agent durchsucht Förderdatenbanken‘ konkret? Viele haben keine API, sind hinter Login.“*

### Diskussion (verdichtet)

> **Sarah:** Ich sag's mal von der anderen Seite: Die Anträge klingen generisch, alle gleich. Die fallen durch, weil man nicht merkt, wer der Verein ist.
> **Ute:** Aber unsere alten Anträge sind ja von uns. Der nimmt doch unsere Texte.
> **Daniel:** Ja, aber aus 20 Anträgen, nur 8 bewilligt. Der lernt auch aus den 12 schlechten.
> **Kai:** Und der Agent reicht vielleicht was ein oder füllt ein Formular mit falschen Zahlen aus, Finanzplan mit erfundenen Beträgen.
> **Ute:** Wir würden doch drüber schauen.
> **Sarah:** Würdet ihr? Wenn er sagt „nur noch unterschreiben“? Und dann steht da eine Kooperation drin, die es nicht gibt.
> **Daniel:** Und die Förderdatenbanken: Der Agent findet 50 Programme, davon passen 3, aber man muss trotzdem alle 50 prüfen.
> **Kai:** Und 40 € im Monat ist nicht teuer, aber wenn das Tool die Daten ins Training gibt, sind eure Anträge bei allen anderen.
> **Ute:** Ehrlich: Das Problem ist, dass zwei Leute alles machen. Wenn eine aufhört, ist der Verein weg. Daran ändert der Agent nichts.


### Pad nach 8 min (wahrscheinlich)

- **Gescheitert, weil …**
  - Anträge klingen generisch / KI-erkennbar, werden schlechter bewertet oder ausgeschlossen
  - Agent übernimmt falsche Angaben (erfundene Kooperationen, Zahlen) in den Antrag; Ärger mit Förderin, Rückforderung
  - Eigentliches Problem bleibt: nur 2 Personen, eine hört auf
- **Damit es 🦊 wird, müsste …**
  - KI nur für Recherche/Fristen-Übersicht und Strukturierung, Text schreiben die Menschen selbst
  - Kein „nur noch unterschreiben“: jede Angabe gegen Quelle geprüft
  - Transparent gegenüber Förderin, was mit KI gemacht wurde
- **Einschätzung:** 🤔 – als Recherche-Hilfe 🦊, als Antragsautomat 🧙

### Was die Gruppe gut trifft / was fehlt

- **Trifft:** Kriterium 4 (Fehlerkosten, falsche Angaben), Kriterium 1 (zu wenig Leute), Kriterium 7 nur wenn jemand wie Sarah im Raum ist (Prüfarbeit wird verlagert)
- **Fehlt oft:** Kriterium 7 als gesellschaftlicher Effekt – wenn *alle* Vereine so arbeiten, ertrinken Förderinnen in Anträgen und vergeben schlechter. Ohne Person von der Förderseite kommt das kaum. Im Debrief explizit nennen (Workslop-Rückbezug)
- **Fehlt oft:** Messbarkeit eines Agents (Kriterium 4) – „Woran merkt ihr, ob der Agent gut ist? Bewilligungsquote? Nach wie vielen Anträgen?“ Bei 8 von 20 Bewilligungen braucht man Jahre, um einen Effekt zu sehen
- **Typischer Verlauf:** Daniel relativiert („machen wir eh schon“), dadurch wird die Diskussion pragmatisch statt grundsätzlich. Gut so – genau die Schatten-KI-Situation von der Folie „Was oft vergessen wird“

---

## Querschnitt: Was im Debrief vermutlich passiert

| Raum | Stärkster Grund aus dem Pad | Kriterium | Einschätzung | Was du ergänzen musst |
|---|---|---|---|---|
| A | Sensible Daten in der Cloud, Vertrauen der Ratsuchenden | 6 | 🤔 | 5 (Betrieb nach 2 Jahren) |
| B | Veraltete Artikel, keiner pflegt nach Förderende | 5 | 🤔 | 4 (Wie messen? Testfragen) |
| C | Falsche Auskunft, eigentliches Problem Personalmangel | 1 / 4 | 🧙 | 6 (Daten im Chat) |
| D | Generische/falsche Anträge, 2 Personen bleiben 2 Personen | 4 / 1 | 🤔 | 7 (Prüfarbeit bei der Förderin) |

**Beobachtung:** Kriterium 1 (systemisches Problem) und 4 (Fehlerkosten) werden aus Teil 1 sehr oft genannt, obwohl die Debrief-Folie nach 5–7 fragt. Nicht abwürgen, sondern kurz würdigen: „Das ist Kriterium 1 von vorhin – gut, dass das hängen geblieben ist.“ Dann gezielt nach 5–7 fragen.

**Gemeinsames Muster aller Räume:** „KI für die Fachkraft statt für die Betroffenen / Öffentlichkeit“ (A: Diktat, B: interne Suche, C: Unterstützung der Berater*innen, D: Recherche statt Text). Das ist die stärkste Botschaft, die sich aus den Pads ergibt – im Debrief als Muster benennen, wenn Zeit ist.

**Erwartbare 🦊-Bedingungen, die sich als „Kriterium in euren Worten“ eignen:**

- „Ein Mensch prüft, bevor etwas bei Betroffenen ankommt“ (A, C, D)
- „Die Betroffenen können Nein sagen, ohne Nachteil“ (A)
- „Betrieb ist nach Förderende bezahlt und jemand ist zuständig“ (B, C)
- „Die KI ersetzt keine bestehende menschliche Anlaufstelle“ (C)

---

## Folgerungen für Material und Moderation

*Umgesetzt: Kriterien 1–4 + Hinweise im Pad, Rollenregel, „Jede\*r nennt eine Bedingung“, Taskname bei A, Debrief-Notizen. Twist-Feature entfernt.*

1. **Kartenbezeichnung bei A prüfen:** Auf der Karte steht „③ Spracherkennung“, in der Task-Liste aus Übung 2 heißt ③ „Texterkennung“. Aufmerksame Teilnehmende stolpern kurz („Ist das das Gleiche?“). Entweder Task-Liste auf „Text-/Spracherkennung“ ändern oder auf der Karte „③ Texterkennung (aus Audio)“
2. **Raum B braucht einen Schubs:** Sympathischstes Projekt, Gruppe landet schnell bei „eigentlich gut“. Im Pad bei B evtl. einen Hinweis ergänzen: „Denkt auch an: Wer pflegt das Archiv? Wie wisst ihr, ob die Antworten stimmen?“
3. **Raum C ist schnell fertig:** Einigkeit nach 3 min. Frage 2 ist hier wichtig, damit die Gruppe konstruktiv wird. Eventuell im Pad bei C: „Wenn ihr den Chatbot ganz streicht: Was könnte KI stattdessen hier tun?“
4. **Rollenverteilung kostet Zeit:** Online braucht „Wer schreibt?“ realistisch 30–60 s Schweigen. Vorschlag in der Kurzanleitung: „Die Person, deren Vorname im Alphabet zuerst kommt, schreibt.“ Spart die Verhandlung
5. **Zeit:** 6 min Diskussion reichen für 2–3 Gründe in allen Räumen; Frage 2 kommt in mindestens einem Raum zu kurz. Broadcast bei 1 min ist wichtig, sonst bleibt „Einschätzung“ leer
6. **Expertise-Ungleichgewicht:** In A und C sitzen wahrscheinlich Fachleute (Beratung), die die Diskussion dominieren und schnell „das geht nicht“ sagen. Das ist im Pre-Mortem erwünscht, aber Frage 2 braucht dann jemanden, der positiv denkt. Ggf. in der Anleitung: „Frage 2: Jede*r nennt eine Bedingung, auch wer skeptisch ist“

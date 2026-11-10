# Simulation 2: Pre-Mortem (Übung 3), ein Agent pro Raum

> **Archiv.** Stand vor der Überarbeitung der Folien, nicht mehr gepflegt. Aktuell gelten [index.qmd](index.qmd) und [uebungen_vorbereitung.md](uebungen_vorbereitung.md).

Zweiter Durchlauf mit dem überarbeiteten Pad (Kriterien 1–4 im Kopf, Alphabet-Regel, „Jede*r nennt eine Bedingung“, Hinweise bei B und C, ohne Twist). Jeder Raum wurde unabhängig simuliert, ohne Kenntnis der ersten Simulation ([pre_mortem_simulation.md](pre_mortem_simulation.md)). Raum D wurde versehentlich zweimal simuliert, beide Läufe stehen unten; das ist ein nützlicher Konsistenz-Check.

---

## Zusammenfassung

### Was in allen Räumen schiefgeht (Logistik)

Anders als in Simulation 1 kostet die Logistik in jedem Raum 1–1,5 Minuten. Das ist das größte Risiko der Übung.

| Problem | Räume | Folge |
|---|---|---|
| **Pad-Link fehlt im Breakout** (Hauptchat dort nicht sichtbar) | alle 5 Läufe | 30–40 s Suchen, jemand postet ihn in den Raum-Chat, Handy-Nutzer*innen finden ihn trotzdem nicht |
| **Zoom nennt die Räume „Breakout-Raum 1–4“**, nicht A–D | A, D (2. Lauf) | Raten, welche Karte gilt |
| **Alphabet-Regel bricht an Anzeigenamen** („iPhone von Bernd“, „Gast 47“, „KR \| Stiftung“) und an Handy-Teilnehmenden | alle | Schreiben landet beim Vielredner oder bei der Fachperson, die eigentlich reden soll |
| **Zeitwächter*in handelt nicht** | alle | Frage 2 beginnt erst bei Minute 5,5–6 |
| **Erst am Ende schreiben** | B, C, D | letzter Satz bricht ab, wenn der Raum schließt |
| **„Jede*r nennt eine Bedingung“** kostet bei 5 Personen ~2 min; die Stillen kommen zuletzt (oder gar nicht) dran | alle | in A kommt der beste Punkt (einfache Lösung) von der stillsten Person in der letzten Minute |
| **Einschätzung unklar**: die Karte bewerten oder die verbesserte Version? Gruppe uneinig | B, C, D | Streit in der letzten Minute, „🤔 (X: 🧙)“ |

### Inhalt: was die Räume treffen und was fehlt

| Raum | Stärkster Grund im Pad | Kriterium | Einschätzung | Fehlt (im Debrief ergänzen) |
|---|---|---|---|---|
| A | Art.-9-Daten in der US-Cloud; Ratsuchende schweigen, Einwilligung nicht freiwillig | 6 | 🤔 (1× 🧙) | 1 (warum so viel Doku?), 2 (selbst diktieren statt aufnehmen), 7 (Sprach-Bias wird nicht als Bias erkannt) |
| B | Veraltete Rechtsinfos aus alten Rundbriefen → falsche Auskunft | 4 / 5 | 🤔 | 2 (FAQ, Volltextsuche), 6 (Mitgliederfragen mit Wohn- und Vermieterdetails gehen an API), 7 |
| C | Förderung weg nach 12 Monaten, Freigrenzen veralten; „Erstfragen“ sind Einzelfallberatung | 5 / 4 | 🧙 / 🤔 uneinig | 7 (Ratsuchende tragen das Risiko), 2, 3 (nur ① Triage?) |
| D | Generische Anträge, Portale ohne Schnittstelle, Wissen hängt an 2 Personen | 5 / 4 | 🤔 (1× 🧙) | **6 in beiden Läufen** (Namen, Fotos, Lebensläufe in alten Anträgen), 7 nur wenn jemand aus einer Stiftung im Raum ist |

**Quer über alle Räume:**

- **Kriterium 7 fehlt fast überall.** „Kosten für wen?“ wird als „Wer zahlt die Rechnung?“ gelesen. Umwelt, Klickarbeit und Bias kommen in keinem Raum. Verlagerte Kosten (Prüfarbeit bei der Förderin, Risiko bei Ratsuchenden) werden beschrieben, aber als Qualitätsproblem.
- **Kriterium 2 kommt spät oder gar nicht.** Steht eine Technik auf der Karte, wird nur über diese Technik geredet.
- **Das stärkste Scheitern hängt an Fachwissen im Raum** (Mietrecht in B, Förderseite in D). Ohne diese Personen landen die Gruppen bei Technik-Gründen.
- **Muster „KI für die Fachkraft statt für Betroffene“ kommt wieder** (A Formular/Diktat, B intern für Beratende, C Haushaltsplan/Unterlagen, D nur Recherche) und wird teils als „anderes Projekt, gilt nicht“ abgewertet. Im Debrief ausdrücklich aufwerten.
- **Typische Missverständnisse:** „lokal = Datenschutz gelöst“, „RAG auf Gesetzestexte halluziniert nicht“, „Datenschutzhinweis löst das“, „40 €/Monat = keine Kosten“, „nach Datum gewichten“ als Lösung für veraltete Inhalte, Agent = besseres ChatGPT.
- **Begriffe:** „Agent“ sitzt nicht (D, beide Läufe), „RAG“ ebenfalls nicht (B), „Fable(haft)“ wurde als „Fabel = erfunden“ verstanden (D), „Pre-Mortem“ als „Klappt das?“ (D).

### Vergleich mit Simulation 1

- Simulation 1 war zu glatt: Gruppen fanden in Ruhe 3 Gründe und 3 Bedingungen. Simulation 2 zeigt, dass online vor allem Zeit und Logistik knapp sind.
- Inhaltlich decken sich die Ergebnisse weitgehend (A → 6, B → veraltete Artikel und Betrieb, C → systemisch und Förderende, D → generische Anträge und 2 Personen).
- Neu in Simulation 2: Datenschutz fehlt bei D komplett, Kriterium 7 fehlt fast überall, Kartentext A hat einen Widerspruch, und die Hinweis-Zeile bei C konkurriert mit Frage 2.

---

## Empfehlungen

### Tech-Support

1. **Räume umbenennen**: „A · Migrationsberatung“, „B · Mieterverein“, „C · Schuldnerberatung“, „D · Förderanträge“.
2. **Pad-Link direkt nach dem Öffnen als Broadcast** an alle Räume: *„📝 Pad: [Link] – scrollt zu eurem Raum, lest die Karte, los geht's.“*
3. **Zweiter Broadcast bei Halbzeit (4 min)**: *„Halbzeit – wechselt jetzt zu Frage 2.“*
4. Uhrzeit im Pad-Kopf bei Verzug **im Pad** korrigieren, nicht nur mündlich.

### Pad-Kopf

- **Zeit**: *„⏱ 8 Minuten · ab Minute 4: Frage 2 · letzte Minute: fertig schreiben“*
- **Rollen**: *„Sagt kurz eure Vornamen. Wer im Alphabet zuerst kommt und am Laptop sitzt, schreibt, und zwar von Anfang an mit (Stichworte reichen). Die nächste Person achtet auf die Zeit und sagt bei Minute 4: ‚Frage 2!‘“*
- **Frage 2**: *„Reihum, wer noch wenig gesagt hat zuerst, je ein Satz: ‚Es klappt nur, wenn …‘“*
- **Einschätzung**: *„Eine Einschätzung zum Projekt, so wie es auf der Karte steht: 🧙 / 🤔 / 🦊 + ein Satz. Bei Uneinigkeit beide Emojis.“*
- **Fable(haft)** einmal erklären: *„🦊 Fable(haft) = hält, was es verspricht“*
- **Hinweis-Zeile schärfen**: *„Denkt auch an das, was gerade kam: Daten & Infrastruktur (auch nach Förderende?), Datenschutz (wessen Daten stecken drin?), Kosten für wen, auch für andere (Betroffene, Förderer, Umwelt)?“*

### Projektkarten

- **A**: Widerspruch beheben. „Digitalisierung im Ehrenamt“ passt nicht zu 6 Hauptamtlichen → *„Landesförderprogramm ‚Digitalisierung in der Sozialen Arbeit‘, 2 Jahre“*. Hinweis-Zeile ergänzen, die vom ohnehin dominanten Datenschutz weglenkt: *„Denkt auch an: In welchen Sprachen finden die Gespräche statt? Wer merkt, wenn in der Akte etwas Falsches steht?“*
- **B**: Personenbezogene Daten und Anbieter sichtbar machen: *„Daten: rund 600 Rundbrief-Ausgaben, teils Word, teils gescannte PDFs; dazu die Fragen der Mitglieder (oft mit Details zu Wohnung und Vermieter)“*. Hinweis-Zeile schärfen: *„… Was passiert mit einem Artikel von 2012, der heute nicht mehr stimmt? …“*
- **C**: Hinweis-Zeile ersetzen; die bisherige konkurriert mit Frage 2 und die Idee wird als „anderes Projekt“ abgewertet. Vorschlag: *„Denkt auch an: Wer hält die Merkblätter aktuell? Was passiert, wenn eine Antwort falsch ist, und wer trägt den Schaden?“*. Die Pointe „KI für die Berater*innen“ kommt im Debrief.
- **D**: Hinweis-Zeile fehlt bisher (beide Läufe übersehen Datenschutz): *„Denkt auch an: Welche Daten aus alten Anträgen landen beim Tool-Anbieter? Wer liest die Entwürfe am Ende, bei euch und bei der Förderin?“*

### Debrief

- A nicht noch einmal bei Kriterium 6 lassen, sondern auf 4 (Fehler in der Akte, Sprachen) und 2 (selbst diktieren statt das Gespräch aufnehmen) lenken.
- B: „veraltete Daten“ ausdrücklich als Kriterium 5 benennen, nicht nur API-Kosten. Fragt jemand nach dem Rechtsdienstleistungsgesetz: als offene Frage stehen lassen, keine Rechtsauskunft geben.
- C: die Ratsuchenden als Risikoträger*innen benennen (6/7).
- D: Kriterium 7 (Prüfarbeit bei der Förderin, Workslop) selbst einbringen, falls niemand aus einer Stiftung im Raum war.
- Während der Räume im Pad nach Zeilen im falschen Abschnitt schauen (in B landete „veraltete Rechtslage“ unter Raum A).

---

## Raum A · Migrationsberatung: Beratungsgespräche transkribieren und zusammenfassen

### Wer sitzt im Raum
- **Dilara**, hauptamtliche Beraterin im Jugendmigrationsdienst, Kamera an. Kennt den Alltag aus erster Hand. Hin- und hergerissen: „Die Doku frisst mich auf, aber Aufnahmen? Puh.“
- **Frank (DSB KV)**, externer Datenschutzbeauftragter, nebenbei für einen Kreisverband der Wohlfahrtspflege. „Geht so nicht.“ Redet lange und in Paragrafen.
- **Gast 47** (Hildegard), Rentnerin in einer Willkommensinitiative, ohne Kamera, zum ersten Mal in einem Breakout-Raum. Offen, aber unsicher, ob das Projekt echt ist.
- **Jana**, Förderreferentin bei einer Stiftung. Schaut mit der Brille der Förderin und fragt nach dem „Danach“.
- **Lukas**, Student, ehrenamtlich in der Geflüchtetenhilfe, hat Whisper schon lokal laufen lassen. Technikoptimistisch: „Lokal geht das alles.“

### Die ersten 60 Sekunden
- **[0:00–0:15]** „Hallo? … Hört man mich?“ Raumname: „Breakout-Raum 1“. Lukas: „1 ist A, oder?“ Alle nicken.
- **[0:15–0:45] Rollen:** Jana liest die Regel vor. Nach Alphabet würde Dilara schreiben, dann Frank, dann „Gast 47“. Dilara: „Ich würde lieber reden, ich mach das ja beruflich. Kann jemand anders tippen?“ Kurzes Hin und Her, dann schreibt Jana, Frank nimmt die Zeit, stellt aber keinen Timer. **Die Regel wird ausgehebelt. Das ist hier sinnvoll, weil die Fachperson reden soll, kostet aber ca. 30 Sekunden.** Hildegard bleibt „Gast 47“ und wird nie mit Namen angesprochen.
- **[0:45–1:15]** Hildegard: „Wo ist denn die Karte?“ Der Pad-Link stand nur im Hauptchat. Lukas postet ihn in den Raum-Chat. Hildegard findet den Raum-Chat erst nach ca. 30 Sekunden und liest bis Minute 2 nur halb mit.
- **Gedanken beim Lesen der Karte:**
  - *Dilara:* „Ein Drittel? Bei mir eher die Hälfte. Aber ich würde nie ein Handy auf den Tisch legen, wenn jemand über seine Abschiebung redet.“
  - *Frank:* „Art. 9 DSGVO, Gesundheitsdaten, Cloud-Dienst … ich hab schon drei Absätze im Kopf.“
  - *Jana:* „‚Digitalisierung im Ehrenamt‘, aber das sind 6 Hauptamtliche? Passt nicht zusammen.“
  - *Lukas:* „Whisper lokal plus ein offenes Modell, das geht auf einem Laptop.“
  - *Hildegard:* „Gibt es das wirklich? Bei uns in der Initiative nimmt keiner was auf … Und was heißt hier Pre-Mortem?“

### Diskussion (verdichtet)
**[min 1:30]** Frank: „Also, gescheitert ist das an der DSGVO, ganz klar. Besondere Kategorien nach Art. 9, Gesundheit, dazu Aufenthaltsstatus. Cloud-Dienst, vermutlich USA, kein AVV, keine Datenschutz-Folgenabschätzung …“ Er redet ca. 90 Sekunden. Jana tippt mit: „DSGVO / Cloud / Art. 9“.

**[min 3]** Dilara: „Ganz praktisch: Die Leute sagen nichts mehr, wenn das Handy läuft. Viele haben Angst, dass das bei der Ausländerbehörde landet. Dann ist die Beratung schlechter, nicht besser.“
Jana: „Und die Einwilligung? Die unterschreiben doch alles, was man ihnen hinlegt, oder?“
Dilara: „Genau das ist das Problem. Freiwillig ist das nicht, die brauchen uns.“

**[min 3:45]** Lukas: „Man könnte das aber lokal machen, Whisper auf einem Rechner im Büro. Dann ist Datenschutz gelöst.“
Frank: „Nicht gelöst. Gespeichert werden die Audios trotzdem, auf Diensthandys oder Privathandys? Wer hat Zugriff?“
Lukas: „Okay, aber besser.“

**[min 4:15]** Dilara: „Und in welcher Sprache sind die Gespräche? Bei mir Deutsch, Arabisch, Dari, oft mit Sprachmittler*in, alles durcheinander.“
Lukas: „Hm. Whisper ist bei Dari deutlich schlechter. Tigrinya kannst du vergessen.“
Hildegard (zum ersten Mal mit Mikro): „Und wenn da was Falsches in der Akte steht? Ein falsches Datum oder so?“
Dilara: „Dann steht's da. Und ich unterschreibe es, weil ich abends keine Zeit hab, alles nachzulesen.“

**[min 5]** Jana: „Darf ich kurz was Komisches sagen? ‚Digitalisierung im Ehrenamt‘ für sechs Hauptamtliche, das würden wir so gar nicht bewilligen.“
Frank: „Vielleicht ist das Absicht?“ *(40 Sekunden Grübeln, ob das ein Trick ist.)*

**[min 5:45]** Frank (Zeit): „Oh, Frage 2! Jede*r eine Bedingung.“
Dilara: „Die Ratsuchenden müssen echt Nein sagen können, ohne Nachteile. Und vorher gefragt werden.“
Frank: „Kein US-Cloud-Dienst, DSFA, AVV, Audio sofort löschen.“
Lukas: „Lokal, und erst mal nur Deutsch testen.“
Jana: „Was ist nach zwei Jahren? Wer zahlt dann? Sonst lieber gar nicht anfangen.“

**[min 6:40]** Jana: „Gast 47, magst du auch was sagen?“
Hildegard: „Ach so, ich? … Vielleicht, dass man die Notizen nicht abends abtippen muss, sondern gleich am Computer schreibt?“
Dilara: „Das ist eigentlich … gar nicht so dumm. Ein gutes Formular.“

**[min 7] Broadcast.** Frank: „🧙, so wie beschrieben.“ Dilara: „🤔, die Idee ist richtig, die Umsetzung nicht.“ Lukas: „🤔.“ Jana: „🤔, ich schreib das.“ Selbst diktieren nach dem Gespräch kommt nicht mehr dran.

### Pad nach 8 Minuten
```
- Gescheitert, weil …
  - DSGVO: Art 9 Daten (Gesundheit, Aufenthalt) in US-Cloud, kein AVV/DSFA -> gestoppt
  - Ratsuchende sagen nix mehr wenn Handy läuft (Angst Ausländerbehörde), Einwilligung nicht wirklich freiwillig
  - Spracherkennung bei Arabisch/Dari/mit Dolmetsch schlecht, Fehler landen in der Akte und keiner liest nach
- Damit es Fable(haft) (🦊) wird, müsste …
  - Ratsuchende werden vorher gefragt + können ohne Nachteil nein sagen (D.)
  - keine US-Cloud, DSFA, Audio sofort löschen (F.)
  - lokal + erst nur deutschspr. Gespräche testen (L.)
  - Finanzierung nach den 2 Jahren klar (J.)
  - evtl reicht auch ein gutes Formular direkt am PC statt abtippen (H.)
- Einschätzung + ein Satz: 🤔 (Frank 🧙) - Doku-Entlastung ja, aber nicht durch Aufnahme von Gesprächen in denen es um Aufenthalt geht
```

### Was trifft die Gruppe, was fehlt
- **1 Systemisches Problem: kaum.** Niemand fragt, warum die Doku ein Drittel der Zeit kostet (Nachweispflichten, Personalmangel).
- **2 Einfachere Lösung: spät, über Hildegard** (Formular am PC). Selbst diktieren statt das Gespräch aufzunehmen fehlt, obwohl es fast alle Gründe entschärft.
- **3 Klare Tasks: implizit.** ③ und ⑤ werden nicht getrennt, alle Fehler gehen auf „die KI“.
- **4 Performance: angerissen.** Wie man vorher misst (Fehlerquote pro Sprache), fehlt. Die Fehlerkosten (aufenthaltsrechtliche Folgen) werden nicht als solche benannt.
- **5: nur über Jana**, als Finanzierungsfrage. Betrieb, Diensthandys und Anbindung an die Aktenführung fehlen.
- **6: sehr stark, dominiert den Raum.** Gut: Machtgefälle bei der Einwilligung, Vertrauensverlust.
- **7: indirekt.** Die schlechtere Erkennung von Dari und Tigrinya wird nicht als Bias erkannt. Big Tech nur als „US-Cloud“.
- **Missverständnisse:** „lokal = Datenschutz gelöst“, „DSGVO = unmöglich“, nach dem Datenschutz gilt das Problem als erledigt.

### Hinweise für Moderation & Material
- **Widerspruch im Kartentext** (Ehrenamt vs. 6 Hauptamtliche) → *„Landesförderprogramm ‚Digitalisierung in der Sozialen Arbeit‘“*.
- **Hinweis-Zeile für A** auf das Übersehene: *„Denkt auch an: In welchen Sprachen finden die Gespräche statt? Wer merkt, wenn in der Akte etwas Falsches steht?“*
- **Rollenregel:** Oft schreibt die Fachperson. *„Sagt kurz eure Vornamen. Wer zuerst kommt, schreibt (oder gibt weiter).“*
- **Frage 2** beginnt erst bei Minute 6, die stillste Person hat den besten Punkt → Wechsel zu Frage 2 fest auf Minute 4, reihum je ein Satz.
- **Raumnamen und Pad-Link:** Räume umbenennen, Pad-Link als Broadcast schicken.

---

## Raum B · Mieterverein: semantische Suche über 15 Jahre Rundbriefe

### Wer sitzt im Raum
- **Birgit** (58), Kamera an, ehrenamtlich in der Mieterberatung eines Sozialverbands. Kennt das Mietrecht aus der Praxis, skeptisch („Mitglieder wollen einen Menschen“).
- **Dennis** (41), Geschäftsführer eines kleinen Wohlfahrtsvereins mit halber Stelle. Begeistert, weil er „genau sowas“ für 30 Jahre Vorstandsprotokolle will. Schweift ab.
- **Jonas** (29), „Digitalkoordination“ (50 %) bei einem Landesverband. Hat schon einen RAG-Prototyp gebaut, redet viel und technisch.
- **Katrin** (47), Kamera aus, Kachel „KR | Stiftung“. Förderreferentin, leicht selbstkritisch („so was würden wir fördern“).
- **„Galaxy A52“** (Ute, 63), per Handy, kommt 90 Sekunden zu spät, hat das Pad nicht offen. Ehrenamtlich in einer Seniorenbegegnungsstätte.

### Die ersten 60 Sekunden
- Dennis: „Alphabet: Birgit, Dennis, Jonas, Katrin … Birgit!“ Birgit: „Oh nee, ich bin am Laptop so langsam.“ Jonas: „Kann ich machen.“ **Die Rolle geht an den, der ohnehin am meisten redet.** Dennis wäre Zeitwächter, merkt es aber nicht. Faktisch achtet niemand auf die Zeit.
- **Gedanken beim Lesen:**
  - Jonas: „Alte PDFs sind bestimmt gescannt, also OCR. Chunking pro Artikel. Machbar.“
  - Birgit: „‚Sofort die passende Antwort‘. Ein Rundbrief von 2012 zur Mieterhöhung? Da gab's noch keine Mietpreisbremse.“
  - Katrin: „‚Laufende Kosten trägt der Verein.‘ Den Satz kenne ich aus unseren Bewilligungen.“
  - Dennis denkt an seine Protokolle.

### Diskussion (verdichtet)
**[min 1]** Jonas: „Technisch kein Hexenwerk. Die Frage ist, wie gut die PDFs sind. Scans von 2010 mit Spalten und Kästen, da kommt Matsch raus.“
Dennis: „Aber das kriegt man doch hin, man lädt einfach alles hoch.“

**[min 2]** Birgit: „Darf ich mal was Inhaltliches sagen? Das Mietrecht hat sich seit 2010 dauernd geändert. Mietpreisbremse 2015, CO₂-Kosten seit 2023, jedes Jahr neue BGH-Urteile. Wenn das System den Artikel von 2012 nimmt, ist die Antwort schlicht falsch.“
Jonas: „Man könnte nach Datum gewichten …“
Birgit: „Und wer entscheidet, welcher Artikel noch gilt? Und darf ein Mieterverein ohne Beratung überhaupt Rechtsauskünfte geben?“ *(Niemand weiß es genau.)*

**[min 3]** Katrin: „Als Geldgeberin: Wir geben einmal 25.000, und nach zwei Jahren fragt keiner mehr, wer die API-Rechnung zahlt. Bei uns wäre das durchgegangen, weil es gut klingt.“
Dennis: „API-Kosten sind doch Cent-Beträge?“
Jonas: „Läppert sich, aber nicht dramatisch. Das Teure ist, dass es jemand betreuen muss.“
Katrin: „Und die drei Hauptamtlichen haben dafür keine Stunde übrig.“

**[min 4]** Dennis erzählt 40 Sekunden von seinen Protokollen. Ute kommt dazu: „Bin ich hier richtig, Raum B? … Was ist denn das RAG da?“ Jonas erklärt 50 Sekunden lang mit „Vektordatenbank“ und „Embeddings“. Ute: „Ah ja.“ *(Hat es nicht verstanden.)*

**[min 5:30]** Katrin: „Wie lange haben wir noch? Und jede*r soll eine Bedingung nennen.“ Jonas: „Ach, echt? Überlesen.“ Schnelle Runde:
- Birgit: „Jeder Artikel braucht ein Datum, was nicht mehr gilt, fliegt raus. Und eine Juristin schaut drüber.“
- Jonas: „Vorher mit 100 echten Mitgliederfragen testen, wie bei den Mails vorhin.“
- Katrin: „Laufende Kosten schon im Haushalt, bevor man anfängt.“
- Dennis: „Erst mal nur intern für die Beratung.“ Birgit: „Ja! Das würde ich nutzen.“
- Ute (auf Nachfrage): „Viele Ältere gehen gar nicht auf die Website. Das Telefon darf nicht wegfallen.“

**[min 7]** Broadcast. Birgit tippt „veraltete Rechtslage“ unter **Raum A** und merkt es nicht. Einschätzung: Birgit 🧙, Jonas und Dennis 🦊, Katrin: „Dann 🤔.“ **[min 8]** Raum schließt mitten im Satz.

### Pad nach 8 Minuten
```
- Gescheitert, weil …
  - veraltete infos aus alten rundbriefen (Mietrecht geändert, mietpreisbremse etc) -> falsche Auskunft an Mitglieder, evtl haftung??
  - PDFs schlecht (Scans), Suche findet Murks
  - nach Stiftungsgeld kein Geld/keine Zeit für betrieb, 3 HA haben keine kapazität
- Damit es Fable(haft) (🦊) wird, müsste …
  - Artikel mit Datum/gültigkeit, veraltetes raus (B.)
  - vorher mit 100 echten Fragen testen, Berater prüfen (J.)
  - laufende Kosten im Haushalt eingeplant (K.)
  - erst intern für Berater*innen statt direkt Mitglieder (D.)
  - Telefon bleibt! ältere nutzen website nicht (U.)
- Einschätzung + ein Satz: 🤔 als internes tool für die beratung sinnvoll, direkt für mitglieder eher
```
Außerdem verirrt unter Raum A: `veraltete Rechtslage`

### Was trifft die Gruppe, was fehlt
- **4: stark.** Falsche Rechtsauskunft ist der Kern, „100 echte Fälle“ wird selbst übertragen. Wer labelt (Juristin) und ob die Suche den richtigen Artikel findet, fehlt.
- **3: implizit.** „Erst intern“ verschiebt den Task von ④+⑤ zu ④, wird aber nicht so benannt.
- **2: fehlt komplett** (aktuelle FAQ, Volltextsuche, Themenregister).
- **1: gestreift.** Dass die Anrufe vielleicht die eigentliche Leistung sind, sagt niemand. Am nächsten dran: Utes „Telefon darf nicht wegfallen“.
- **5: gut, doppelt** (Datenqualität und Betrieb nach dem Stiftungsgeld).
- **6: halb.** Beteiligung über Ute, Datenschutz gar nicht: Mitglieder tippen Mietsituation und Vermieterkonflikte in ein Feld, das an eine API geht.
- **7: fehlt.**
- **Missverständnisse:** „15 Jahre Archiv = Schatz“ (für Rechtsfragen eher Belastung), API-Kosten als Hauptrisiko, „nach Datum gewichten“ als Lösung für ein inhaltliches Problem.

### Hinweise für Moderation & Material
- **Rollenregel** bricht an Anzeigenamen. Zeitrolle braucht ein Signal: *„… sagt bei Minute 4: ‚Frage 2‘.“*
- **„Jede*r nennt eine Bedingung“** wird überlesen. Ablauf mit Minuten in den Pad-Kopf schreiben, „**Eine** Einschätzung für die Gruppe“.
- **Karte B macht Datenschutz und Big Tech unsichtbar.** Mitgliederfragen als Daten und den Anbieter nennen.
- **Hinweis-Zeile schärfen:** *„Was passiert mit einem Artikel von 2012, der heute nicht mehr stimmt?“*
- **Pad mit vier Räumen:** Im Pad-Kopf ergänzen: *„Findet euren Raum mit Strg+F → ‚Raum B‘. Am Handy? Lasst euch die Karte vorlesen.“*

---

## Raum C · Schuldnerberatung: Chatbot für Erstfragen

### Wer sitzt im Raum
- **Anna-Lena** („A. Lenz (sie/ihr)“), Ehrenamtliche in einer Ombudsstelle für Bürgergeld, mit dem Handy im Zug, Kamera aus, wackliges Netz.
- **Birgit**, Schuldnerberaterin bei einem Wohlfahrtsverband, einzige Fachperson im Raum. Skeptisch bis gereizt („schon wieder ein Chatbot“).
- **Dilek** („Stiftung XY – Programmteam“), Förderreferentin, lange still, denkt in Förderlogik.
- **Klaus** („iPhone von Klaus“), ehrenamtlich bei der Tafel und im Seniorenverein, nutzt ChatGPT privat begeistert, weicht oft vom Thema ab.
- **Tobias**, „Digitalbeauftragter“ mit halber Stelle, kennt RAG aus LinkedIn-Posts, redet am meisten.

### Die ersten 60 Sekunden
- Tobias: „Wer schreibt? Alphabet, oder?“ Auf dem Bildschirm stehen „A. Lenz“, „iPhone von Klaus“, „Stiftung XY“. Anna-Lena: „Ich bin im Zug, ich kann echt nicht schreiben.“ Birgit schreibt. *(Sie denkt: Ich bin die Einzige, die das Thema kennt, und muss jetzt auch noch tippen.)* Tobias: „Ich behalt die Zeit im Blick.“ Das tut er nicht.
- Klaus findet das Pad nicht, auch nicht den Raum-Chat auf dem iPhone. Birgit liest die Karte vor (ca. 40 s).
- **Gedanken beim Lesen:**
  - Birgit: „‚Darf mein Konto gepfändet werden?‘ ist keine Erstfrage, das ist Einzelfallberatung. Und ‚verweist auf einen Termin‘ … in 10 Wochen.“
  - Tobias: „Paradebeispiel für RAG. Gesetzestexte sind öffentlich.“
  - Dilek: „Kommune, 12 Monate Pilot. Und danach?“
  - Klaus: „P-Konto hat mir ChatGPT neulich auch super erklärt.“

### Diskussion (verdichtet)
**[min 1:30]** Tobias: „Technisch gar nicht so schwer. Sauber mit RAG auf die Gesetzestexte, dann halluziniert der auch nicht …“
Birgit: „Doch, trotzdem. Und die Leute haben keine Erstfrage. Die haben einen Brief vom Gerichtsvollzieher und Panik. Das hängt vom Einzelfall ab.“

**[min 2:15]** Tobias: „Aber dafür verweist er ja auf einen Termin.“
Birgit: „In zehn Wochen! Dann denkt die Person, alles ist geklärt. Oder die Pfändungsfreigrenze war veraltet, die ändert sich jedes Jahr zum 1. Juli.“

**[min 2:40]** Dilek (Kamera an): „Aus Förderperspektive: 12 Monate Kommune. Wer aktualisiert danach die Merkblätter? Bei uns scheitern solche Piloten fast immer genau da.“

**[min 3:10]** Klaus und Tobias reden 40 Sekunden über ihre Lieblingsmodelle.

**[min 3:50]** Birgit: „Sorry, wir haben noch die zweite Frage.“
Anna-Lena (Ton hakt): „Benutzen die Leute das überhaupt? Bei uns rufen die an …“
Birgit: „Genau. Und die geben dann im Chat ihre ganze Schuldensituation ein, mit Namen, Gläubigern, alles.“
Tobias: „Da muss halt ein Datenschutzhinweis hin.“
Birgit: „Das liest keiner, der gerade Panik hat.“

**[min 4:40]** Tobias liest die Hinweis-Zeile vor: „Ist das jetzt Frage 2?“
Birgit: „KI für uns Beraterinnen, zum Beispiel ein Entwurf für den Haushaltsplan, Unterlagen vorsortieren. Dann schaffen wir mehr Termine.“
Tobias: „Aber das ist ja dann ein anderes Projekt.“ *(30 Sekunden Streit, ob das zählt.)*

**[min 5:20]** Bedingungen: Dilek: „Vorher klären, wer es nach der Förderung betreibt.“ Tobias: „Vorher testen, 100 echte Fragen.“ Birgit: „Nur allgemeine Infos, bei akuter Pfändung sofort die Notfallnummer.“ Klaus (vage): „Die Älteren nicht vergessen.“ Anna-Lena hat keine Verbindung mehr.

**[min 7]** Broadcast. Birgit: „🧙.“ Tobias: „🤔.“ Dilek: „Schreib beides.“ Der Satz bleibt halb.

### Pad nach 8 Minuten
```
- Gescheitert, weil …
  - Förderung weg nach 12 Mon, keiner pflegt Merkblätter/Freigrenzen (ändern sich jährlich!!) -> falsche Auskünfte
  - "Erstfragen" sind eigentlich Einzelfallberatung, Bot kann das nicht + Haftung? Leute verlassen sich drauf, Termin trotzdem in 10 Wo
  - Zielgruppe nutzt es nicht (lesen/schreiben, Panik, ruft lieber an) / Datenschutz: Leute geben alles ein
- Damit es Fable(haft) (🦊) wird, müsste …
  - vorher klären wer es nach Förderung betreibt (Dilek)
  - vorher mit echten Fragen testen (100 Fälle) (Tobias)
  - nur allg. Infos, bei akuter Pfändung sofort Notfall-Nr (Birgit)
  - Zielgruppe muss es nutzen können, auch Ältere (Klaus)
  - eigentlich: KI lieber für die Berater*innen (Haushaltsplan, Unterlagen sortieren) -> mehr Termine
- Einschätzung + ein Satz: 🧙 / 🤔 (uneinig) – Das eigentliche Problem ist die Wartezeit, das löst kein Bo
```

### Was trifft die Gruppe, was fehlt
- **1: implizit.** „Das eigentliche Problem ist die Wartezeit“ ist Kriterium 1, steht aber nur halb in der Einschätzung.
- **2: kaum.** Dass der Bot die Telefonsprechstunde *ersetzt*, also menschlichen Kontakt streicht, bemerkt niemand.
- **3: nicht diskutiert** (Triage ① für sich allein?).
- **4: angerissen.** Was eine „richtige“ Antwort ist, wenn es auf den Einzelfall ankommt, fragt niemand.
- **5: stärkster Punkt** (12 Monate, Freigrenzen jährlich). Gut zum Vorlesen im Debrief.
- **6: halb.** Datenschutz wird mit „Hinweis hinsetzen“ abgetan, Betroffene nur als Nutzbarkeit, nicht als Beteiligung.
- **7: fehlt.** Das Risiko für Ratsuchende wird als Qualitätsproblem gerahmt.
- **Missverständnisse:** „RAG auf Gesetzestexte halluziniert nicht“, „Disclaimer löst das“, „KI für Berater*innen = anderes Projekt, gilt nicht“.

### Hinweise für Moderation & Material
- **Alphabet-Regel** scheitert an Zoom-Namen und Handys → *„Wer am Laptop sitzt und zuerst kommt, schreibt.“*
- **Von Anfang an mitschreiben** statt in der letzten Minute; Halbzeit-Broadcast bei 4 min.
- **Hinweis-Zeile C konkurriert mit Frage 2** → ersetzen: *„Wer hält die Merkblätter aktuell? Was passiert, wenn eine Antwort falsch ist?“*
- **Bedingungen mit Satzanfang:** *„Es klappt nur, wenn …“*
- **Pad-Link** per Broadcast; Uhrzeit bei Verzug im Pad korrigieren.

---

## Raum D · Verein: Agent bereitet Förderanträge vor (Lauf 1)

### Wer sitzt im Raum
- **Anke**, Geschäftsführerin (30 Std.) eines kleinen Jugendhilfevereins. Schreibt alle Anträge selbst, nutzt ChatGPT „für den ersten Wurf“. Pragmatisch.
- **Dilara**, Programmreferentin einer Stiftung (Bildung). Anträge werden „immer glatter und immer gleicher“. Skeptisch.
- **Malte**, „Digitalbeauftragter“ eines Landesverbands, baut privat mit n8n. Redet viel, landet schnell bei Lösungen.
- **„iPhone von Bernd“**, ehrenamtlich in einer Naturschutz-Ortsgruppe, im Zug, Mikro rauscht.
- **Kathrin**, Freiwilligenkoordinatorin, Kamera an, sagt fast nichts, hat noch nie ein KI-Projekt gemacht.

### Die ersten 60 Sekunden
- Anke ist klar die Erste („Och nee, ich, okay“). Wer Zweite*r ist, bleibt unklar („iPhone von Bernd“ = B?). Malte: „Dann mach ich Zeit.“ **Die Zeit hält, wer ohnehin am meisten redet.**
- Pad-Link fehlt, Dilara postet ihn in den Raum-Chat. Lesezeit schrumpft auf ~30 s.
- **Gedanken:** Anke: „‚Nur noch unterschreiben‘, ja klar. Aber das Recherchieren wär schon geil.“ Dilara: „Genau das landet bei mir. 40 Seiten Agenten-Prosa.“ Kathrin: „Was ist jetzt der Unterschied zwischen Agent und ChatGPT?“

### Diskussion (verdichtet)
**[min 1]** Malte: „‚Nie wieder eine Frist verpassen‘: Dafür braucht man einen Kalender, keinen Agent.“
Anke: „Das Problem ist, dass wir zu zweit 20 Anträge geschrieben haben und 8 durchgekommen sind.“

**[min 2]** Dilara: „Wir kriegen seit einem Jahr deutlich mehr Anträge, viele klingen gleich. Wenn ich merke, dass einer nur breit gestreut wurde, ist der raus. Wir diskutieren schon eine KI-Erklärung im Formular.“
Malte: „Die Detektoren funktionieren eh nicht.“ Dilara: „Darum geht's mir gar nicht.“

**[min 3]** Malte: „Grund eins: Der Agent kommt nicht in die Portale. Login, Captcha, PDF-Formulare. Ich würd das so bauen: n8n, RSS …“
Anke: „Malte, wir sollen sagen, warum's gescheitert ist, nicht wie man's baut.“
Kathrin: „Ein Agent ist schon was anderes als ChatGPT, oder?“ Malte erklärt 40 Sekunden zu Function Calling.

**[min 4]** Bernd (Ton hakt) schreibt in den Chat: *„bei uns stehen in jahresberichten namen von kindern/schulen drin. und wenn die 2 leute aufhören weiß keiner wie das tool eingestellt ist“*. Anke schreibt nur den zweiten Teil auf. **Der Datenschutz-Punkt geht verloren.**

**[min 5]** Dilara: „Der Agent lernt aus 20 Anträgen, 12 davon abgelehnt. Woher weiß der, was gut war?“
Anke: „Wir schreiben fünf Anträge im Jahr. Wenn zwei durchkommen, war dann der Agent gut?“
Kathrin: „Das wär wie vorhin mit den 100 Fällen, nur dass man keine 100 hat.“

**[min 6]** Bedingungen: Malte: „Nur die Recherche automatisieren.“ Dilara: „Offenlegen, wo KI drinsteckt.“ Anke: „Erst mal Textbausteine aus den bewilligten Anträgen, ganz ohne KI.“ Kathrin: „Ist ‚Fable(haft)‘ jetzt gut oder erfunden? Fabel?“ Kathrin und Bernd nennen keine Bedingung.

**[min 7]** Broadcast. Anke 🤔, Dilara 🧙, Malte 🤔. Anke: „Bewerten wir die Karte oder unsere Version? … Ich schreib beides.“ Der letzte Satz bricht ab.

### Pad nach 8 Minuten
```
- Gescheitert, weil …
  - Agent kommt nicht in die Förderportale (Login, PDF, captcha) -> lief nie richtig
  - die 2 Antragsschreiberinnen hören auf, keiner weiß wie das Tool eingestellt ist
  - Anträge klingen alle gleich/generisch, Förderer lehnen ab bzw merkt dass breit gestreut wurde (Dilara: Förderer haben mehr Arbeit!)
  - nicht messbar ob besser: nur ca 5 Anträge/Jahr, 12 von 20 Vorlagen abgelehnt
- Damit es Fable(haft) (🦊) wird, müsste …
  - nur Recherche automatisieren, Schreiben bleibt beim Menschen (Malte)
  - Transparenz ggü Förderer wo KI drin ist
  - erstmal Textbausteine aus den bewilligten Anträgen sammeln, ohne KI
- Einschätzung + ein Satz: 🧙/🤔 so wie auf der Karte Mythos ("nur unterschreiben"), Recherche-Teil könnte klapp
```

### Was trifft die Gruppe, was fehlt
- **1: angedeutet** (Projektförderlogik), nicht im Pad.
- **2: gut** (Kalender, Textbausteine ohne KI). Stärkste 🦊-Bedingung.
- **3: indirekt** (Recherche = ④ + ①).
- **4: getroffen** (wenige Fälle, abgelehnte Anträge als Vorlage). Dass ein Agent eine Folge von Handlungen ausgibt und schwer messbar ist, fehlt.
- **5: klar** (Portale ohne Schnittstelle, Wissen an 2 Personen).
- **6: fast verloren** (Bernds Hinweis geht im Tonproblem unter). Fehlannahme: „Sind doch unsere eigenen Texte.“
- **7: halb, nur wegen Dilara.** „Kosten“ = 40 €.
- **Missverständnisse:** „Detektoren funktionieren nicht, also kein Problem“ (verwechselt Transparenz mit Erwischtwerden). Lösungsmodus statt Pre-Mortem.

### Hinweise für Moderation & Material
- **Karte D hat keine Hinweis-Zeile** → *„Wer liest die Anträge am Ende, und was ändert sich für diese Person? Woran würdet ihr merken, dass der Agent gute Arbeit macht?“*
- **Rollen** bei Anzeigenamen „wie in Zoom angezeigt“; Schreiben von Anfang an.
- **Halbzeit-Broadcast** „Wechselt jetzt zu Frage 2“.
- **Einschätzung zur Karte**, „Fable(haft)“ erklären, Bedingungen reihum, Stille zuerst.
- **Hinweis-Zeile im Kopf** ausführlicher („Kosten für wen, auch für andere?“).

---

## Raum D · Verein: Agent bereitet Förderanträge vor (Lauf 2)

### Wer sitzt im Raum
- **Anke** („Anke (sie/ihr)“), Teilzeit-Bildungsreferentin einer Naturschutz-Kreisgruppe. Schreibt Anträge nachts, heimlich mit ChatGPT.
- **Benedikt H.**, Programmmanager einer Stiftung. Genervt von KI-Anträgen, redet gern und lange.
- **Tobias | Digitalisierung**, halbe Stelle als Digitalbeauftragter, n8n-Fan, begeistert von Agents.
- **Mareike**, Koordinatorin einer Freiwilligenagentur. Ruhig, stellt die unbequemen Grundsatzfragen.
- **„iPhone“** (Sevgi), Vorstand eines Sportvereins, Handy, schreibt lieber in den Raum-Chat.

### Die ersten 60 Sekunden
- „Breakout-Raum 4. Ist das jetzt D?“ Tobias: „4 = D, passt schon.“ *(Niemand prüft das.)*
- Anke schreibt. „iPhone ist wohl kein Vorname.“ Benedikt nimmt die Zeit, stellt aber keinen Timer.
- Pad-Link fehlt, Tobias postet ihn. Sevgi kann das Pad auf dem Handy kaum lesen.
- **Gedanken:** Mareike: „Warum schreiben zwei Ehrenamtliche ALLE Anträge? Das ist doch das Problem.“ Sevgi: „Was ist ein Agent nochmal? Sollen wir sagen, ob es klappt?“

### Diskussion (verdichtet)
**[min 1:30]** Sevgi: „Sollen wir jetzt sagen, ob das funktioniert?“ Benedikt: „Nee, wir tun so, als wär's schon gescheitert.“

**[min 2]** Benedikt: „Die Anträge klingen generisch, ‚innovativ, partizipativ, nachhaltig‘. Und manchmal stimmen die Zahlen nicht.“ Anke: „Die Teilnehmendenzahl von 2023.“ Benedikt: „Und wir müssen das alles prüfen. Dreimal so viele Anträge im Stapel.“ *(Kriterium 7, wird aber als Benedikts Ärger gehört.)*

**[min 3]** Tobias: Portale mit Login und Captcha, dann 40 Sekunden n8n vs. Make.

**[min 4]** Mareike: „Was passiert, wenn die zwei aufhören? Und ist Schreiben überhaupt das Problem, oder die Förderlogik?“ Benedikt: „Projektitis.“ *(1 Minute Abschweifung, inhaltlich Kriterium 1.)*

**[min 5]** Anke: „Ich hab beim letzten Antrag ChatGPT genutzt und länger korrigiert als geschrieben. Man prüft 15 Seiten Text, den man nicht selbst gedacht hat.“
Tobias: „40 Euro im Monat ist nix. Kosten sind hier kein Problem.“ *Niemand widerspricht.*

**[min 5:30]** Bedingungen: Benedikt: „KI-Nutzung angeben, jede Zahl prüft ein Mensch.“ Tobias: „Kein Agent, nur Suche und Matching.“ Mareike: „Mehr Leute im Verein müssen Anträge können.“ Anke: „Messen, ob es wirklich Zeit spart.“

**[min 6:30]** Sevgi im Chat: *„förderer sollten sagen ob KI erlaubt ist“*. Mareike liest es vor.

**[min 7]** Broadcast. Anke 🤔, Benedikt 🧙, Tobias 🤔, Mareike 🤔. Sevgis Bedingung kommt halb rein. **Datenschutz hat niemand angesprochen.**

### Pad nach 8 Minuten
```
- Gescheitert, weil …
  - Anträge klingen alle gleich/generisch -> abgelehnt, teils falsche Zahlen aus alten Berichten
  - Förderportale (Login, PDF) -> Agent kommt nicht durch
  - die 2 Ehrenamtl. hören auf, keiner versteht mehr was der Agent macht; prüfen dauert länger als schreiben
- Damit es Fable(haft) (🦊) wird, müsste …
  - KI-Nutzung transparent machen + Mensch prüft jede Zahl (B.)
  - kein Agent, nur Suche/Matching automatisiern (T.)
  - mehr Leute im Verein können Anträge (M.)
  - messen ob es wirklich Zeit spart (A.)
  - Förderer klären ob KI erlaubt (S
- Einschätzung + ein Satz: 🤔 (Benedikt: 🧙) – Fördersuche automatisieren ja, Anträge schreiben lassen nein, „nur unterschreiben“ ist Mythos
```

### Was trifft die Gruppe, was fehlt
- **1: halb** (Mareike), landet nur als Bedingung im Pad.
- **2: halb.** Datenbank-Alerts, Textbausteine, Förderlots*innen nennt niemand.
- **4: schwach.** Nur „spart es Zeit?“.
- **5: getroffen.**
- **6: fehlt komplett** (Lebensläufe, Namen, Fotos von Teilnehmenden beim Tool-Anbieter).
- **7: inhaltlich da** (Prüfarbeit bei der Förderin), nicht als Kostenfrage erkannt.
- **Missverständnisse:** „40 € = keine Kosten“, „Mensch prüft am Ende“ als Lösung für alles, Agent = besseres ChatGPT, Pre-Mortem als „Klappt das?“.

### Hinweise für Moderation & Material
- **Räume umbenennen** oder im Pad: *„Raum 1 = A, 2 = B, 3 = C, 4 = D“*.
- **Pad-Link** als Broadcast; Kurzlink auf die Folie.
- **Wechsel zu Frage 2 fest um 16:24**; Antwortvorlage „eine Zeile pro Person“; bei Uneinigkeit beide Emojis.
- **Hinweis-Zeile für D:** *„Welche Daten aus alten Anträgen landen beim Tool-Anbieter? Wer liest die Entwürfe am Ende, bei euch und bei der Förderin?“*
- **Alphabet-Regel:** *„Sagt kurz eure Vornamen. Wer am Handy ist, gibt das Schreiben weiter.“*

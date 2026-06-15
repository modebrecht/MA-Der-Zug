# Workflow — Der Zug / Albula

> **Status:** CANON WORKFLOW v1  
> **Basis:** übernommen aus dem Bero-Workflow, aber für den Albula-Mystery-Thriller neu kalibriert.  
> **Output-Regel:** Alle Romanprosa wird auf Deutsch geschrieben. Arbeitsanweisungen dürfen Englisch nutzen, wenn es der Modellführung hilft.

---

## 0. Warum dieser Workflow existiert

Ein Makro-Prompt wie „Schreib Kapitel 1“ produziert fast immer Zusammenfassung statt Roman. Für *Der Zug / Albula* ist das besonders gefährlich, weil das Konzept von Atmosphäre, psychologischer Verzögerung, Wahrnehmungslücken und streng dosierten Enthüllungen lebt.

Der Workflow erzwingt deshalb:

- **Micro-Prompting:** eine Szene / ein Beat pro Antwort, keine automatische Fortsetzung.
- **Aktives Pacing:** langsam genug für Kälte, Geräusche, Erinnerung und Misstrauen.
- **Strenge Logik-Gates:** Mystery-Regeln, Motivation und Weltlogik werden vor der Prosa geprüft.
- **Hidden-Truth-Kontrolle:** Levins Rolle am Unglück wird vorbereitet, aber nicht zu früh gedacht oder benannt.
- **Kontinuierliches Tracking:** Wortzahl, Motive, Hinweise, Tilgungen und Figurenstatus bleiben sichtbar.
- **Anti-Drift:** keine Rückkehr zur verworfenen Transit-/GPT-Fassung.

---

## 1. Canon-Quellen

Vor jedem neuen Schreibabschnitt gelten diese Dokumente als verbindlich:

1. `albula-canon.md` — Projektentscheidung, Weltregeln, Timeline, No-Gos.
2. `figuren-dossier.md` — Figuren, Schuld, Maske, Spiegelung von Levin.
3. `unglueck-2008.md` — sobald erstellt: genaue Rekonstruktion des Ursprungsunglücks.
4. `kapitelplan.md` — sobald erstellt: Kapitelstruktur und Informationsverteilung.
5. `motiv-ledger.md` — sobald erstellt: Motive, Seeds, Payoffs.

Wenn ein späterer Entwurf einem dieser Dokumente widerspricht, gilt zuerst der Canon. Der Text wird angepasst, nicht der Canon heimlich verbogen.

---

## 2. Project Locks — nicht verletzen

Diese Locks stehen über jedem Kapitel und jeder Szene.

```text
PROJECT LOCKS — DER ZUG / ALBULA

- Sprache der Romanprosa: Deutsch.
- POV: 3. Person limitiert, standardmäßig eng an Levin.
- Tense: Präteritum. Direkte innere Gedanken nur sparsam und bewusst.
- Register: atmosphärischer Mystery-Thriller, literarischer als Standard-Fitzek, aber nicht prätentiös.
- Setting: Albula / RhB-Anmutung / Filisur / Bergün / Landwasserviadukt / Winter 2025/2026.
- Ursprungsunglück: 14. Februar 2008, 02:47 Uhr, Landwasserviadukt / Albulalinie.
- Levin Gegenwart: 36/37, Historiker / wissenschaftlicher Mitarbeiter, nicht 24.
- Marlene Gegenwart: 43/44, Fotografin, ehemalige Lokführerin, nicht 26.
- Der Zug ist kein Jenseits und kein generischer Transitraum.
- Haupttwist ist NICHT: „Alle waren die ganze Zeit tot.“
- Finale ist NICHT: Wasser / Flut / Tür öffnen.
- Finale ist NICHT: echte Zeitreise-Reparatur.
- Finale: Levin bremst. Er weiß, dass es nichts ändert. Er tut es trotzdem.
- Schaffner Mancini ist kein Gott, Dämon oder Erklärmeister.
- Schuld wird nicht gepredigt. Schuld wird körperlich, sozial und szenisch sichtbar.
- Jede zentrale Figur spiegelt einen Teil von Levins verdrängter Verantwortung.
- Jede Szene braucht mindestens 3 aktive Wahrnehmungskanäle aus: Sicht, Klang, Kälte/Berührung, Geruch/Geschmack, Körperreaktion, Erinnerungslücke.
```

---

## 3. Länge und Kapitelarchitektur

### 3a. Buchziel

Der Albula-Roman ist auf **ca. 70.000–80.000 Wörter** angelegt. Das entspricht grob einem 280–320-Seiten-Thriller.

Der genaue Umfang darf organisch entstehen, aber das Buch darf nicht in eine 35.000-Wörter-Zusammenfassung kollabieren.

### 3b. Kapitelziel

Solange `kapitelplan.md` noch nicht final ist, gilt als Arbeitsrahmen:

| Kapiteltyp | Zielumfang |
|---|---:|
| ruhiges Übergangs-/Atmosphärenkapitel | 2.800–3.300 Wörter |
| normales Mystery-/Ermittlungskapitel | 3.300–4.000 Wörter |
| Ensemble-/Konfliktkapitel | 4.000–4.800 Wörter |
| Pivot-/Reveal-/Finalkapitel | 4.800–5.800 Wörter |

Mögliche Pivot-Kapitel, sobald der Kapitelplan steht:

- erstes Verschwinden / Platz 47
- erster harter Beweis der Tilgung
- Midpoint: Albula-Unglück verbindet alle
- Marlenes Erinnerung / Marlenes Verschwinden
- Levins Uniform / Formular / Unterschrift
- Führerstand / Bremsentscheidung
- Schlusskapitel mit Sarah

### 3c. Beat-Größe

Beats sind inhaltlich bestimmt, nicht nach Schema erzwungen.

| Beat-Größe | Verwendung |
|---|---|
| <300 Wörter | meist zu dünn, eher Fragment |
| 400–600 Wörter | ideal für atmosphärische Einzelbewegung |
| 600–900 Wörter | Dialog, Ensemble-Konflikt, Recherchefund, psychologischer Umschlag |
| >900 Wörter | prüfen: wahrscheinlich zwei Beats |

Ein Beat muss immer eine dramatische Veränderung tragen:

> Zustand A → Ereignis / Wahrnehmung / Entscheidung → Zustand B

Ein Beat, der nur eine frühere Szene erklärt, nachfühlt oder kommentiert, ist kein eigener Beat.

---

## 4. Seam Discipline — Übergänge zwischen Beats

Der Zug lebt von Motiven: Schnee, kalter Kaffee, metallisches Splittern, Notlicht, Kamera, Fenster, Uhrzeit 02:47, leere Plätze, Durchsagen.

Diese Motive dürfen wiederkehren, aber nicht als redundante Inventarliste an jeder Beat-Grenze.

### Regel

Wenn Beat N+1 einen Wahrnehmungsanker ausarbeiten soll, darf Beat N ihn nur **anteasern**.

| Position | Funktion |
|---|---|
| Ende Beat N | Fakt + körperliche Reaktion |
| Anfang Beat N+1 | volle sinnliche Ausarbeitung |

### Gutes Muster

> Dann sah Levin, dass der Schnee nicht fiel.  
> Er bewegte sich seitwärts an der Scheibe vorbei, als hätte jemand die Welt gekippt.  
> Sein Daumen blieb auf dem kalten Rand der Tasse liegen.

Beat endet. Der nächste Beat darf dann Schnee, Scheibe, Kälte, Tasse und Raum detailliert entfalten.

### Schlechtes Muster

Beat N listet bereits Schnee, Fenster, Kälte, Tasse, Licht, Schaffnerdurchsage, Geruch nach Metall — und Beat N+1 listet dieselben Elemente erneut. Das macht die Naht sichtbar.

---

## 5. Hidden-Truth Guardrails

### 5a. Levins Hauptschuld

Die zentrale verborgene Wahrheit lautet:

> Levin war 2008 der 19-jährige RhB-Praktikant / Lehrling, der die defekte Weichenheizung als geprüft unterschrieb.

Der Leser darf diese Wahrheit rückblickend als vorbereitet empfinden. Levin darf sie vor dem geplanten Reveal nicht bewusst denken.

### Erlaubte Kanäle vor dem Reveal

| Kanal | Beispiel |
|---|---|
| Körperreaktion | Bei „Weiche“, „Formular“, „02:47“ zieht sich sein Brustkorb zusammen. |
| Unpassende Fachkenntnis | Er kennt Bahnabläufe, ohne die Quelle sofort zu greifen. |
| Vermeidung | Er weicht harmlosen Fragen zu früheren Jobs aus. |
| Sinnesfragment | Metallisches Splittern, Geruch nach kaltem Strom, nasser Wolle, Bremsstaub. |
| Objekt-Trigger | Formular, Stempel, orange Warnweste, alte RhB-Uniform, Dienstplan. |
| Fremdwahrnehmung | Marlene oder Hediger merkt, dass Levin zu präzise reagiert. |

### Nicht erlaubt vor dem Reveal

- Levin denkt: „Ich war schuld.“
- Levin erinnert sich vollständig an die Unterschrift.
- Der Erzähler erklärt Levins Verdrängung direkt.
- Mancini oder Hediger sagt ihm die Wahrheit zu früh.
- Ein Fundstück löst den Twist ohne psychologische Vorbereitung vollständig aus.

### Pre-commit-Test

Vor jedem Beat mit Albula-/RhB-/Formular-/Weichen-Material prüfen:

1. Könnte ein Re-Read-Leser den Hinweis erkennen?
2. Weiß Levin dadurch schon zu viel?
3. Ist die Reaktion körperlich/szenisch statt erklärend?
4. Vermeidet die Szene Therapiesprache und moralische Selbstdiagnose?

Wenn Antwort 2 „ja“ ist: Szene zurücknehmen.

---

## 6. Marlene-Guardrail

Marlene ist emotionale Achse und professionelle Gegenfigur. Sie darf nicht zur reinen Love-Interest-Funktion schrumpfen.

### Canon

- Gegenwart: 43/44.
- 2008: 26, Lokführerin des Unglückszuges.
- Juristisch freigesprochen, innerlich nicht.
- Heute Fotografin, alte mechanische Kamera.

### Regeln

- Ihre Nähe zu Levin entsteht aus gemeinsamem Erinnern, nicht aus Thriller-Romanze.
- Ihr Verschwinden muss emotional treffen, weil sie vorher als Mensch funktioniert hat.
- Ihre Kamera darf Hinweise geben, aber nicht jedes Rätsel lösen.
- Sie darf Levin widersprechen. Sie ist kein Echo seiner Hypothesen.
- Ihr Freispruch muss ambivalent bleiben: rechtlich entlastet, seelisch belastet.

---

## 7. Schaffner-Guardrail

Mancini ist stark, solange er wenig erklärt.

### Er ist

- Wächter des Moments.
- Dienstpersonal der Schuld.
- Zeuge ohne einfache Erlösung.
- höflich, knapp, schwer.

### Er ist nicht

- Gott.
- Dämon.
- Orakel.
- Expositionsmaschine.
- Twist-Lieferant auf Abruf.

### Dialogregel

Mancini beantwortet Fragen indirekt. Wenn er direkt wird, muss der Satz kurz und kalt sein.

Schlecht:
> „Der Zug bringt euch alle dazu, eure verdrängte Schuld zu akzeptieren.“

Besser:
> „Der Zug fährt nicht weiter, Herr Brand. Er fährt zurück.“

---

## 8. Motive und Wiederholungen

Jedes Kapitel soll 1–3 Leitmotive führen, nicht alle gleichzeitig.

### Verbindliche Leitmotive

- Schnee in falscher Richtung
- 02:47
- kalter Kaffee
- metallisches Splittern
- leere Sitzplätze
- Fotos, auf denen Menschen fehlen
- Marlenes Kamera
- Fahrkarten ohne klares Ziel
- Fenster als Spiegel
- Landwasserviadukt als Schweben über Abgrund
- Bremsen als moralische Handlung

### Motiv-Regel

Ein Motiv muss sich bei jeder Wiederkehr verändern:

1. erstes Auftauchen: Atmosphäre
2. zweites Auftauchen: Irritation
3. drittes Auftauchen: Zusammenhang
4. spätes Auftauchen: Payoff / emotionale Bedeutung

Wenn ein Motiv nur dekorativ wiederholt wird, streichen oder verwandeln.

---

## 9. Master Prompt — neues Kapitel starten

Beim Start eines neuen Kapitels diesen Prompt verwenden und ausfüllen:

```text
We are starting Chapter [X] of DER ZUG / ALBULA.

CANON SOURCES:
- albula-canon.md
- figuren-dossier.md
- [unglueck-2008.md, if available]
- [kapitelplan.md, if available]
- [motiv-ledger.md, if available]

CONTENT GOAL:
[One sentence: what must have changed by chapter end.]

TARGET LENGTH:
~[2,800 quiet | 3,500 average | 4,500 ensemble/pivot | 5,500 major reveal] German words.

CARRY-OVER:
- Levin emotional state: [ ]
- Levin physical location: [ ]
- Last unresolved clue / fear / conflict: [ ]
- Current known disappearances: [ ]
- Current state of the train: [ ]

PROJECT LOCKS:
[Paste §2 or summarize the relevant locks.]

STEP 1 — Beat plan only.
Identify the chapter's natural dramatic beats. Do not force a fixed number.
For each beat, list:
- Location & time
- POV character (default: Levin)
- Dramatic purpose
- Character want / resistance / cost
- Mystery information gained, withheld, or distorted
- Motif carried
- Sensory anchor
- Target word count

STEP 1b — Logic & motivation gate.
Before writing prose, check:
- Does every action follow from character incentive?
- Is any obvious action being artificially withheld?
- Does every beat cause the next beat?
- Does any beat only explain or re-feel the previous beat? If yes, merge.
- Does the chapter preserve the world rules of the Zug?
- Does it avoid the forbidden Transit/GPT drift?
- Does it protect Levins hidden truth until its planned reveal?

Report the gate result. If it finds a gap, fix the PLAN before requesting Go.
Then STOP and wait for my "Go".

STEP 2 — On my "Go", write ONLY beat #1.
Do not advance into beat #2.

STEP 3 — After the beat, run the beat-local correction pass in the same response.
Then report:
- Beat-Pass: fixes applied or clean
- Word count for this beat
- Cumulative chapter word count
- Self-evaluation: dense enough or needs expansion?
- Question: expand this beat, or proceed to next beat?
```

---

## 10. Logic & Motivation Gate — Pflicht vor Prosa

Dieser Gate ist der wichtigste Schutz gegen Plotlöcher.

Vor jeder Prosa prüfen:

### 10a. Motivated Action

Für jede aktive Figur:

- Was will sie in dieser Szene?
- Was fürchtet sie?
- Was kostet sie die Wahrheit?
- Warum handelt sie jetzt und nicht später?

### 10b. Obvious-Action-Test

Wenn eine Figur eine naheliegende Handlung nicht ausführt, muss der Grund in der Szene klar sein.

Beispiele:

- Warum ziehen die Passagiere nicht einfach die Notbremse?
- Warum öffnet niemand dauerhaft eine Tür?
- Warum prüft Levin ein Foto nicht sofort?
- Warum ruft niemand Hilfe?
- Warum sagt Frau Hediger nicht sofort alles?
- Warum erklärt Mancini nicht alles?

Nicht die Handlung künstlich verzögern. Einen in-world Grund setzen.

### 10c. Mystery-Regel-Test

Jede neue Unmöglichkeit muss mit den Weltregeln vereinbar sein.

Erlaubt:

- Fotos verändern sich, weil Tilgung Spuren umschreibt.
- Menschen vergessen Verschwundene, wenn sie keine Schuld-Erkenntnis tragen.
- Der Zug bewegt sich zu einem Moment, nicht zu einem Ort.

Nicht erlaubt:

- Beliebige Magie, weil es gerade atmosphärisch wirkt.
- Der Zug kann plötzlich alles.
- Der Schaffner löst Regeln nach Bedarf.
- Eine Szene funktioniert nur, weil Leser die Regeln nicht kennen.

### 10d. Beat-Distinctness-Test

Zwei Beats sind eigentlich einer, wenn:

- Beat N das Ereignis zeigt und Beat N+1 nur erklärt, was es bedeutet.
- Beat N eine Ursache künstlich zurückhält, damit Beat N+1 sie „revealen“ kann.
- Beat N+1 keine neue Entscheidung, Wahrnehmung oder Lageveränderung bringt.

Dann: Beats zusammenführen.

---

## 11. Beat-Local Correction Pass

Nach jedem geschriebenen Beat sofort prüfen und still in denselben Antworttext einarbeiten.

### Prüfkategorien

- POV-Slip: Weiß Levin zu viel?
- Hidden-Truth-Leak: Wird seine Schuld zu früh benannt?
- Transit/GPT-Drift: alle-tot, Jenseits, generischer Schuldzug, Flutbilder?
- Ton-Slip: zu reißerisch, zu erklärend, zu therapeutisch?
- Schaffner-Slip: erklärt Mancini zu viel?
- Marlene-Slip: wird sie zur Romanzenfunktion reduziert?
- Logik: Handlungen, Türen, Kälte, Technik, Handy, Strom, Zugregeln plausibel?
- Sprache: German clunks, englische Syntax, unnötige Abstrakta.
- Wiederholung: Häufen sich Schnee, Kälte, Licht, Blick, Erinnerung ohne neue Funktion?

### 3-Stufen-Wortprüfung

1. **Calque-Check:** Klingt der Satz übersetzt aus dem Englischen? Dann neu formulieren.
2. **Beat-weite Häufung:** Die 3–4 häufigsten Inhaltswörter prüfen. Mehr als 3 Wiederholungen brauchen Motiv-Funktion.
3. **Lokaler Cluster-Scan:** Dasselbe Inhaltswort 2× in 1–2 Sätzen? Prüfen: bewusste Parallelität oder Krücke.

### Ausgabe nach jedem Beat

```text
Beat-Pass: [clean / fixes]
Word count for this beat: [N]
Cumulative chapter word count: [N] / [target]
Self-evaluation: [dense enough / expand recommended + why]
Next: expand this beat or proceed to beat #[N+1]?
```

---

## 12. Follow-up Prompts

### 12a. Beat ist zu dünn

```text
Good skeleton, but too compressed. Before [action X], let Levin dwell longer on [sensory / emotional / spatial element]. Add concrete train details, body reaction, and the pressure of the unsaid. Extend by ~300–500 words. Do not advance the plot.
```

### 12b. Beat ist zu erklärend

```text
The beat explains too much. Rewrite keeping all plot points, but move the meaning into action, image, object, body reaction and dialogue subtext. No therapy language. No direct moral summary.
```

### 12c. Beat driftet in alte Version

```text
This drifts toward the discarded Transit/GPT version. Remove all Jenseits/alle-tot/generic Schuldzug/water-finale implications. Restore Albula specificity: one train, one 2008 accident, one suppressed chain of responsibility.
```

### 12d. Beat ist gut

```text
Approved. Continue with beat #[N+1] under the same rules. Keep seam discipline: do not re-catalog the previous beat's sensory anchor.
```

---

## 13. End-of-Chapter Checks — Pflicht

Wenn der letzte Beat eines Kapitels geschrieben ist, laufen automatisch zwei Passes. Nicht warten, bis „polish“ verlangt wird.

### Pass 1 — Chapter Harvest

1. Finale Kapitelwortzahl und Beat-Verteilung melden.
2. 3–7 neu gepflanzte Elemente listen:
   - Objekt
   - Satz / Formulierung
   - Geräusch
   - Bild
   - Erinnerungslücke
   - soziale Spannung
3. Für jedes Element Ziel markieren:
   - Echo im nächsten Kapitel
   - Payoff im selben Akt
   - Payoff im Finale
4. Levins Exit-State notieren:
   - Was weiß er?
   - Was verdrängt er noch?
   - Was fürchtet er jetzt konkret?
5. Figurenstatus aktualisieren:
   - Wer ist noch im Zug?
   - Wer erinnert sich woran?
   - Wer ist verschwunden / getilgt?
6. Motivstatus aktualisieren:
   - Welche Motive wurden getragen?
   - Welche wurden überreizt?
   - Welche müssen pausieren?
7. Falls `motiv-ledger.md` existiert: neue Seeds und Payoffs dort eintragen.

### Pass 2 — Chapter Polish

Kapitel Ende-zu-Ende lesen und chirurgisch korrigieren.

#### Prosa

- zu erklärende Absätze
- klinische / therapeutische Sprache
- schwache Verben / Adjektive
- German clunks / englische Syntax
- ungewollte Wortwiederholung
- Dialog, der Informationen statt Spannung trägt

#### Mystery

- Hinweise zu offensichtlich?
- Hinweise zu unsichtbar?
- Regeln widersprüchlich?
- Reveal zu früh vorbereitet oder zu spät?
- falsche Fährte fair oder billig?

#### Figuren

- handelt jede Figur aus eigener Motivation?
- spiegelt jede zentrale Figur Levin?
- wird jemand nur als Plotwerkzeug benutzt?
- bleibt Marlene eigenständig?
- bleibt Mancini knapp und nicht-allwissend?

#### Kontinuität

- Timeline 2008 ↔ 2025/26 stabil?
- Alter korrekt?
- Ort / Richtung / Wagenlogik nachvollziehbar?
- Kälte / Strom / Netz / Türen konsistent?
- Tilgungsregeln konsistent?

#### Seam Discipline

- Wiederholt ein Beat-Anfang den vorigen Beat-Ende-Anker?
- Katalogisiert ein Beat-Ende schon den nächsten Beat?
- Sind Übergänge sauber, nicht stotternd?

Nach beiden Passes erst fragen, was als Nächstes passieren soll.

---

## 14. End-of-Act Audit — Pflicht

Nach dem letzten Kapitel eines Akts läuft automatisch ein Akt-Audit. Nicht warten, bis der User fragt.

Da `kapitelplan.md` noch entstehen kann, werden Aktgrenzen dort final definiert. Bis dahin gilt grob:

- Akt I: Setup, Stillstand, erstes Verschwinden, Beweis der Tilgung.
- Akt II: Eskalation, Ensemble-Schuld, Marlene-Achse, Midpoint Albula-Verbindung.
- Akt III: Wahrheit des Unglücks, Figuren verschwinden, Levin isoliert.
- Akt IV: Formular / Führerstand / Bremsentscheidung / Sarah-Schluss.

### Block A — Rückblick

1. Welche Fragen wurden eröffnet?
2. Welche wurden geschlossen?
3. Welche bleiben absichtlich offen?
4. Welche sind versehentlich offen oder versehentlich geschlossen?
5. Funktioniert der Akt als eigene Spannungseinheit?
6. Hat das Pacing getragen oder zusammengefasst?

### Block B — Hidden-Truth Inventory

Für jede verborgene Wahrheit:

| Hidden Truth | Reader seeds | POV leak? | Reveal-Ziel | Status |
|---|---|---|---|---|
| Levin unterschrieb Formular | | | Finale / spätes Akt III/IV | |
| Marlene war Lokführerin | | | vor Levin-Reveal | |
| Albula-Unglück verbindet alle | | | Midpoint | |
| Mancinis Rolle | | | spät / teilweise offen | |

Prüfen:

- ausreichend vorbereitet?
- zu offensichtlich?
- unfair versteckt?
- durch falsche Wortwahl verraten?

### Block C — Figuren-Audit

Für jede zentrale Figur:

- äußere Maske klar?
- Schuld / Verdrängung konkret?
- eigene Stimme?
- eigener Wunsch im Zug?
- Spiegelung von Levin?
- Payoff / Verschwinden vorbereitet?

### Block D — World-Rules-Audit

- Tilgung konsistent?
- Erinnerungsschutz konsistent?
- Zug-zum-Moment-Regel konsistent?
- Aussteigen / Türen / Technik / Strom / Netz konsistent?
- Keine Magie-Beliebigkeit?

### Block E — Anti-Drift-Audit

Prüfen, ob der Akt zurückdriftet in:

- alle sind tot
- generischer Transitraum
- beliebige Katastrophen
- Flut / Wasser-Finale
- Schaffner als allwissendes Orakel
- Levin 24 / Marlene 26
- Schuld als platte Strafe
- Action-Thriller statt atmosphärischer Mystery-Thriller

### Block F — Workflow-Lernen

Welche Fehler traten mehrfach auf?

- zu erklärend
- zu generisch
- zu viele Motive gleichzeitig
- zu wenig Albula-Konkretheit
- zu wenig Figurenwunsch
- zu viel Schaffner-Erklärung
- zu frühe Schuld-Andeutung

Wiederkehrende Fehler werden in eine Watchlist für den nächsten Akt aufgenommen.

### Audit-Ausgabe

```text
Fixes applied:
- [file/chapter/beat | fix]

Open issues needing user decision:
1. [issue]
2. [issue]

Recommendation for next step:
[one sentence]
```

---

## 15. Continuity Ledger

Nach jedem Kapitel diesen Stand aktualisieren und bei neuen Sessions wiederverwenden.

```text
CONTINUITY LEDGER — DER ZUG / ALBULA

Current chapter:
Current act:
Current train state:
Current location in train:
Approximate time:

Levin:
- physical state:
- emotional state:
- what he knows:
- what he avoids:
- body triggers currently active:

Marlene:
- status:
- trust level with Levin:
- camera status:
- memory state:

Mancini:
- last appearance:
- last line / hint:
- what he has not explained:

Other passengers:
- Tobias:
- Frau Hediger:
- Anika:
- Jan:
- Selma:
- Eliah:
- Robert:

Disappearances / Tilgungen:
- [name | chapter | what changed in memory/material traces]

Open clues:
- [clue | planted in | target payoff]

Motive status:
- snow:
- 02:47:
- cold coffee:
- metallic splitting:
- empty seat:
- photo/camera:
- window reflection:
- braking:

Canon risks to watch next:
- [ ] hidden truth leak
- [ ] all-dead drift
- [ ] Schaffner explains too much
- [ ] Marlene reduced to romance
- [ ] too much abstract Schuld language
```

---

## 16. Was aus dem Bero-Workflow übernommen wurde

Übernommen:

- Micro-Prompting statt Makro-Kapitel.
- Beat-Plan vor Prosa.
- Stop nach Plan, erst auf „Go“ schreiben.
- Logik- und Motivation-Gate vor Prosa.
- Beat-Distinctness-Test.
- Seam Discipline.
- Per-Beat-Korrekturpass.
- Wortzahl-Tracking.
- End-of-Chapter Harvest + Polish.
- End-of-Act Audit.
- Anti-Pattern-Watchlist.
- Continuity Ledger.

Angepasst:

- YA-/Tier-POV wurde ersetzt durch psychologischen Thriller-POV.
- Anthropomorphismus-Regeln wurden ersetzt durch Albula-/Technik-/Trauma-Logik.
- Vater-Saat wurde ersetzt durch Levins verdrängte Unterschrift.
- Brummsi-/Bärensprache wurde ersetzt durch Transit/GPT-Drift-Schutz.
- Natur-Sensorik wurde ersetzt durch Zug-, Schnee-, Metall-, Kälte- und Erinnerungs-Sensorik.
- Aktstruktur wurde auf Mystery-/Reveal-Architektur umgebaut.

Verworfen:

- Alle Bero-spezifischen Namen, Slurs, Tierkörper-Regeln, Klan-Politik, Brummen-/Seismik-Regeln.
- Pivot-Beispiele aus dem Bärenbuch, sofern sie nicht als abstrakte Prozessregel nützlich waren.

---

## 17. Was nicht passieren darf

- Nicht „schreib weiter“ für ganze Kapitel verwenden.
- Nicht mehrere Beats ungefragt in einer Antwort schreiben.
- Nicht Beat-Plan und Prosa in derselben Antwort liefern.
- Nicht ein Kapitel ohne End-of-Chapter-Checks schließen.
- Nicht einen Akt ohne Audit schließen.
- Nicht bei Logiklücken rationalisieren. Erst prüfen, ob die Prämisse falsch ist.
- Nicht Mystery-Regeln dehnen, nur damit ein cooler Effekt funktioniert.
- Nicht aus Schuld eine Predigt machen.
- Nicht Albula-Konkretheit zugunsten generischer Horrorbilder verlieren.
- Nicht die alten Altersangaben wiederverwenden.
- Nicht den Schaffner erklären lassen, was die Szene selbst zeigen kann.
- Nicht das Ende als Rettung der Vergangenheit missverstehen.

---

## 18. Arbeitssatz

Wenn der Schreibprozess unsicher wird, gilt:

> *Der Zug ist kein Jenseits. Er ist die Form, die Levins verdrängte Verantwortung annimmt, bis er den einen Moment wieder erreicht, an dem er endlich nicht mehr wegsehen kann.*

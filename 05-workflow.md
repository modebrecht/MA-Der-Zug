# Workflow — Der Zug / Albula

> **Status:** CANON WORKFLOW v3  
> **Function:** Writing process, quality gates and anti-drift rules.  
> **Routing rule:** This file does **not** maintain the active file list. File order, current filenames and audit history are controlled by the start guide. If a filename changes, update the start guide — not this workflow.

---

## 0. Why this workflow exists

A macro-prompt like “write chapter 1” almost always produces summary instead of novel.

For *Der Zug / Albula* this is especially dangerous because the book depends on:

- atmosphere,
- slow psychological pressure,
- precise withholding,
- fair clue placement,
- strict world rules,
- seamless act transitions,
- and a hidden truth that must be prepared without being named too early.

The workflow therefore controls **how** to write.

It does not control **which files exist**. That is handled elsewhere.

---

## 1. Responsibility split

### The start guide controls

- current file order,
- current filenames,
- old-to-new filename mapping,
- archive status,
- project audit log,
- which foundation applies to which chapter range.

### This workflow controls

- chapter-start procedure,
- beat planning,
- logic gates,
- prose pacing,
- per-beat correction,
- end-of-chapter harvest,
- end-of-act audit,
- anti-drift checks.

### Rule

Do not duplicate filename lists here.

Before starting a chapter, first read the current start guide. Then use this workflow to build and write the chapter.

---

## 2. Project Locks — never violate

These locks stand above every chapter, beat and scene.

```text
PROJECT LOCKS — DER ZUG / ALBULA

- Roman prose language: German.
- POV: 3rd person limited, normally tight on Levin.
- Tense: Präteritum.
- Register: atmospheric psychological mystery thriller; literary, but not pretentious.
- Setting: Albula / RhB-Anmutung / Filisur / Bergün / Landwasserviadukt / winter 2025/2026.
- Origin accident: 14 February 2008, 02:47, Albula / Landwasser area.
- Levin in present: 36/37, historian / academic worker, not 24.
- Marlene in present: 43/44, photographer, former locomotive driver, not 26.
- The train is not an afterlife, purgatory or generic transit space.
- Main twist is not: “Everyone was dead all along.”
- Finale is not water / flood / door-opening spectacle.
- Finale is not real time-travel repair.
- Finale: Levin brakes. He knows it changes nothing. He does it anyway.
- Mancini is not God, demon, oracle or exposition machine.
- Schuld is not preached. It becomes visible through body, object, action, social relation and omission.
- Every central figure must mirror a part of Levin’s repressed responsibility.
- Every scene needs at least three active perception channels: sight, sound, cold/touch, smell/taste, body reaction, memory gap.
```

---

## 3. Target length, rhythm and pacing

### Book target

The novel’s current working target is **80,000–95,000 words**.

Soft warning line: **100,000 words**.  
Hard compression audit line: **105,000 words projected**.

Recommended ideal working target: **about 85,000–90,000 words / 20 chapters**, with strongly varied chapter lengths.

The book should not become 20 versions of Chapter 2. Chapter 2 may be broad because it carries the first public disruption. That breadth is not the default pattern.

### Chapter target ranges

| Chapter type | Target range |
|---|---:|
| Short pressure / aftermath / sharp turn | 1,800–2,800 words |
| Quiet transition / atmosphere | 2,600–3,400 words |
| Normal mystery / investigation | 3,200–4,200 words |
| Ensemble / conflict | 4,000–5,200 words |
| Pivot / reveal / final chapter | 4,800–6,200 words |

The target may bend if the chapter earns it. It may not collapse into summary and it may not sprawl because every beat sounds good in isolation.

### Rhythm guardrail — added after Chapter 2

Before every chapter beat plan, decide the chapter’s **rhythm function**:

| Function | Likely shape |
|---|---|
| Build atmosphere / transition | fewer beats, sensory precision, no over-explaining |
| Make a figure concrete | objects, habits, speech, contradictions, not abstract theme-language |
| Mystery investigation | clue → resistance → partial misread → new question |
| First-time rupture / reveal | can be broader, but must change the whole state |
| Aftermath / pressure chapter | short, sharp, emotionally specific |
| Payoff chapter | dense, causally tight, no decorative motifs |

### Compression gate

At the beat-plan stage, ask:

1. Does this chapter need 6–7 beats, or would 3–5 stronger beats do the job?
2. Is any beat mainly atmospheric repetition from the previous beat?
3. Is the chapter adding new dramatic state, or only more beautiful pressure?
4. Would a shorter chapter create better rhythm after a broad chapter?
5. Is the chapter’s main job figure-concretion, mystery escalation, payoff, or aftermath?

If the answer is unclear, compress the plan before prose.

### Projection check

After every completed chapter, calculate:

```text
average chapter word count so far × 20 = projected manuscript length
```

If projected length is:

- **under 95k:** fine;
- **95k–105k:** track compression opportunities;
- **over 105k:** mandatory compression audit before the next act.

### Immediate Ch3 pacing directive

Chapter 3 must not simply escalate the mystery again.

Its main job is to make **Tobias Reck physically and socially concrete** so that his later absence damages the world.

Use:

- Platz / seat logic,
- coat / luggage / phone / ticket,
- cold coffee / coffee ring,
- one liability or process sentence,
- one believable self-justification.

Avoid:

- more abstract system-guilt language,
- another display-centered `02:47` beat,
- a second Mancini non-answer as the main engine,
- making Tobias a caricature before Ch5.

### Beat size

| Beat size | Use |
|---|---|
| <300 words | Usually too thin; likely a fragment, unless used as a deliberate pressure cut. |
| 300–500 words | Good for compressed pressure, aftermath or a sharp turn. |
| 400–700 words | Good for atmospheric movement. |
| 600–900 words | Good for dialogue, clue discovery, conflict or psychological turn. |
| >900 words | Check if it should split into two beats or be cut. |

Every beat must change the dramatic state:

> State A → event / perception / decision → State B

A beat that only explains or re-feels the previous beat is not a real beat.

---

## 4. Chapter-start protocol

Before any chapter prose, do this:

1. Read the start guide for current file order and chapter-specific foundations.
2. Read the relevant planning / canon material indicated there.
3. Check the callback ledger for active seeds, motif load, hidden truths and pending payoffs.
4. Decide the chapter’s rhythm function and target range.
5. Build a **beat plan only**.
6. Run the logic, motivation and compression gate.
7. Stop and wait for explicit “Go” before prose.

No full chapter prose without a beat plan.

No beat plan and prose in the same response.

---

## 5. Master prompt — new chapter

Use this structure when starting a chapter.

```text
We are starting Chapter [X] of DER ZUG / ALBULA.

ROUTING:
- Use the current start guide for active file order, filenames and act/chapter foundation.
- Use the current callback ledger for active seeds, motifs, hidden truths and pending payoffs.

CONTENT GOAL:
[One sentence: what must have changed by chapter end.]

RHYTHM FUNCTION:
[atmosphere / figure-concretion / investigation / rupture / aftermath / payoff]

TARGET LENGTH:
~[2,200 sharp | 3,000 quiet | 3,600 average | 4,500 ensemble | 5,500 major reveal] German words.

CARRY-OVER:
- Levin emotional state: [ ]
- Levin physical location: [ ]
- Last unresolved clue / fear / conflict: [ ]
- Current known disappearances: [ ]
- Current state of the train: [ ]
- Active transition seam from previous chapter/act: [ ]

PROJECT LOCKS:
[Paste or summarize the relevant locks.]

STEP 1 — Beat plan only.
Identify the chapter's natural dramatic beats. Do not force a fixed number.

For each beat, list:
- Location & time
- POV character, default Levin
- Dramatic purpose
- Character want / resistance / cost
- What changes by beat end
- Mystery information gained, withheld or distorted
- Hidden-truth risk
- Motif carried
- Sensory anchor
- Seam from previous beat
- Target word count

STEP 1b — Logic, motivation and compression gate.
Before writing prose, check:
- Does every action follow from character incentive?
- Is any obvious action being artificially withheld?
- Does every beat cause the next beat?
- Does any beat only explain or re-feel the previous beat? If yes, merge.
- Does the chapter need this many beats, or would fewer stronger beats work better?
- Does this chapter vary rhythm from the previous chapter?
- Does the chapter preserve the world rules of the train?
- Does it avoid discarded Transit/GPT drift?
- Does it protect Levin's hidden truth until its planned reveal?
- Does it preserve any active transition seam identified in the start guide / ledger?

Report the gate result.
If it finds a gap, fix the PLAN before requesting Go.
Then STOP and wait for my “Go”.
```

---

## 6. Seam Discipline — transitions between beats and acts

The novel must not feel episodic.

Every chapter must begin from the damage left by the previous chapter.

Every act must answer the open question of the previous act and sharpen it.

### Beat seam rule

If Beat N+1 will fully develop a sensory or emotional anchor, Beat N may only introduce it lightly.

| Position | Function |
|---|---|
| End of Beat N | Fact + pressure / body reaction |
| Start of Beat N+1 | Full sensory unfolding |

Do not catalogue the same snow, glass, coffee, light, camera and cold twice in a row unless the repetition changes meaning.

### Act seam rule

The act transitions are:

```text
Akt I  → The world is wrong.
Akt II → The wrongness has a historical pattern.
Akt III → The pattern has human hands.
Akt IV → The last hand is Levin's.
```

### Active seam risks

Track these while drafting:

1. **Tobias → Jan:** Chapter 7 must begin from the residue of Tobias / Platz 47 before moving into Jan’s relational Tilgung.
2. **Jan → Anika payoff:** Anika must remain visibly damaged in the chapters between Jan’s erasure and her later payoff.
3. **Selma / Eliah / Linn:** They need quiet pre-echoes before their central chapter so the emotional turn does not feel isolated.
4. **Marlene → form:** The final reveal chapter must begin with Marlene-aftershock / Levin isolation before the document appears.

---

## 7. Hidden-Truth Guardrail — Levin

The central hidden truth:

> Levin was the 19-year-old railway trainee / practical worker who signed the faulty switch-heater inspection as “in Ordnung.”

The reader must feel this was prepared on re-read.

Levin must not consciously know it before the planned reveal.

### Allowed before reveal

| Channel | Example |
|---|---|
| Body reaction | Chest tightens at words like switch, form, inspection, 02:47. |
| Unplaced knowledge | He knows railway process too precisely. |
| Avoidance | He evades harmless questions about old railway work. |
| Sensory shard | Metallic split, cold electricity, wet wool, brake dust. |
| Object trigger | Form, stamp, warning vest, uniform, duty roster, pen. |
| Other’s perception | Marlene / Hediger notices he reacts too precisely. |

### Not allowed before reveal

- Levin thinks: “I was guilty.”
- Levin remembers the full signature moment.
- The narrator explains his repression directly.
- Mancini, Hediger or Marlene tells him the truth too early.
- A found object solves the twist before the psychological pressure is prepared.

### Pre-commit test

For every beat with railway / accident / form / maintenance material:

1. Could a re-read reader recognize the clue?
2. Does Levin now know too much?
3. Is the reaction physical / scenic instead of explanatory?
4. Does the scene avoid therapy language and moral self-diagnosis?

If answer 2 is yes: pull the scene back.

---

## 8. Marlene Guardrail

Marlene is emotional axis and professional counterfigure.

She may not shrink into love interest, comfort figure or plot device.

### Canon behavior

- She is observant, restrained, adult.
- Her camera is an instrument of memory, not a puzzle-solver.
- She knows train body-language too well before she can name why.
- Her reveal belongs to her, not to Levin.
- Her disappearance hurts because she has become a person, not because the plot needs loss.

### No-go

- No forced romance.
- No sentimental rescue dynamic.
- No “female trauma to motivate male hero.”
- No camera solving every mystery.

---

## 9. Mancini Guardrail

Mancini is strong only while he withholds.

### He is

- threshold marker,
- service presence,
- witness without simple release,
- polite, brief, heavy.

### He is not

- God,
- demon,
- oracle,
- exposition machine,
- twist dispenser.

### Dialogue rule

Mancini may answer indirectly.

When he becomes direct, the sentence must be short and cold.

Bad:

> “This train makes you all confront your repressed guilt.”

Better:

> “Der Zug fährt nicht weiter, Herr Brand. Er fährt zurück.”

---

## 10. Motif handling

Every chapter should carry **1–3 primary motifs**, not all motifs at once.

Core motif families:

- 02:47,
- snow in the wrong direction,
- metallic splitting,
- cold coffee,
- empty seats,
- altered photos / camera,
- ticket without clear destination,
- window as mirror,
- Landwasser / suspended image,
- forms / stamps / signatures,
- braking as moral action,
- Sarah / hand / later listening.

### Motif rule

A motif must transform when it returns:

1. First appearance: atmosphere.
2. Second appearance: irritation.
3. Third appearance: pattern.
4. Late appearance: payoff / emotional meaning.

If a motif repeats decoratively, cut it or transform it.

---

## 11. Logic & Motivation Gate — required before prose

### Motivated action

For every active figure:

- What do they want in this scene?
- What do they fear?
- What does truth cost them?
- Why act now and not later?

### Obvious-action test

If a figure does not take an obvious action, the reason must be clear in-world.

Examples:

- Why not pull the emergency brake?
- Why not keep the door open?
- Why not check the photo immediately?
- Why not call for help?
- Why does Hediger not explain everything?
- Why does Mancini not explain everything?

Do not delay action artificially. Give a scene-level reason.

### Mystery-rule test

Every impossibility must fit the train’s established rules.

Allowed:

- altered photos,
- missing social memory,
- reality rewriting traces,
- train moving toward a moment rather than a place.

Not allowed:

- arbitrary magic,
- a rule that works only once for convenience,
- Mancini changing rules because the plot needs him to,
- spectacle that contradicts the canon.

### Beat-distinctness test

Two beats are probably one if:

- one shows an event and the next only explains it,
- one hides an obvious cause only so the next can reveal it,
- the second beat does not change decision, perception or situation.

Merge or reshape.

---

## 12. Prose protocol after “Go”

On explicit “Go”:

1. Write only the requested beat.
2. Do not advance into the next beat.
3. Stay in German prose.
4. Keep POV tight.
5. End the beat at a natural pressure point.
6. Then run the beat-local correction pass in the same response.

### Beat-local correction pass

Check silently and apply fixes before showing the beat:

- POV slip: does Levin know too much?
- Hidden-truth leak: is his guilt named too early?
- Transit/GPT drift: afterlife, all-dead, generic guilt train, flood imagery?
- Tone slip: too sensational, therapeutic, abstract or explanatory?
- Schaffner slip: does Mancini explain too much?
- Marlene slip: is she reduced to romance / comfort?
- Logic: doors, cold, power, phone, train rules plausible?
- Language: German naturalness, no English syntax, no weak abstraction.
- Repetition: snow / cold / light / memory only if changed in function.
- Seam: does the beat repeat the previous beat’s sensory catalogue?
- Compression: does the beat earn its length, or can it be tightened without losing state-change?

### Output after every beat

```text
Beat-Pass: [clean / fixes applied]
Word count for this beat: [N]
Cumulative chapter word count: [N] / [target]
Self-evaluation: [dense enough / expand recommended / compress recommended + why]
Next: expand, compress, or proceed to beat #[N+1]?
```

---

## 13. Follow-up prompts

### Beat too thin

```text
Good skeleton, but too compressed. Before [action X], let Levin dwell longer on [sensory / emotional / spatial element]. Add concrete train details, body reaction and the pressure of the unsaid. Extend by ~300–500 words. Do not advance the plot.
```

### Beat too broad

```text
The beat is strong but too broad for the chapter's rhythm function. Keep the state-change and best sensory anchors, but cut repetition, ornamental pressure and re-feeling. Compress by ~15–25%. Do not remove causal clarity.
```

### Beat too explanatory

```text
The beat explains too much. Rewrite keeping all plot points, but move the meaning into action, image, object, body reaction and dialogue subtext. No therapy language. No direct moral summary.
```

### Beat drifts toward old discarded version

```text
This drifts toward the discarded Transit/GPT version. Remove all afterlife/all-dead/generic Schuldzug/water-finale implications. Restore Albula specificity: one train, one 2008 accident, one suppressed chain of responsibility.
```

### Beat approved

```text
Approved. Continue with beat #[N+1] under the same rules. Keep seam discipline: do not re-catalogue the previous beat's sensory anchor.
```

---

## 14. End-of-chapter checks — required

When the final beat of a chapter is drafted, run three passes before moving on.

### Pass 1 — Chapter harvest

Report:

1. Final chapter word count and beat distribution.
2. New seeds planted:
   - object,
   - phrase,
   - sound,
   - image,
   - memory gap,
   - social tension.
3. Target for each seed:
   - next-chapter echo,
   - same-act payoff,
   - final payoff.
4. Levin exit-state:
   - what he knows,
   - what he avoids,
   - what he fears now.
5. Figure status:
   - who is still in the train,
   - who remembers what,
   - who is erased / gone / changed.
6. Motif status:
   - carried,
   - overused,
   - needs rest.
7. Transition seam obligations created for the next chapter.
8. Callback ledger updates required.

### Pass 2 — Chapter polish

Check:

#### Prose

- explanatory paragraphs,
- therapeutic language,
- weak verbs / adjectives,
- German clunks / English syntax,
- accidental repetition,
- dialogue that carries information instead of tension.

#### Mystery

- clues too obvious?
- clues too invisible?
- world rules contradictory?
- reveal too early or too late?
- false trail fair or cheap?

#### Characters

- every active figure has motivation,
- every central figure mirrors Levin,
- no one is only a plot tool,
- Marlene remains independent,
- Mancini remains brief and non-omniscient.

#### Continuity

- 2008 ↔ 2025/26 stable,
- ages stable,
- route / carriage logic clear,
- cold / power / phone / doors consistent,
- Tilgung rules consistent.

#### Seam discipline

- no repeated sensory catalogue at beat seams,
- next chapter has a carry-over point,
- act-transition obligations remain visible.

### Pass 3 — Rhythm and projection check

Check:

- final chapter word count;
- average chapter word count so far;
- projected manuscript length at 20 chapters;
- whether this chapter was broad because it earned it, or broad by habit;
- which motifs need rest in the next chapter;
- whether the next chapter should be shorter, sharper or more concrete.

If projection is above 105k, flag mandatory compression before the next act.

Only after all three passes: ask what should happen next.

---

## 15. End-of-act audit — required

After the final chapter of each act, run an act audit.

Use the act boundaries defined in the current planning structure.

### Block A — Act function

- What question did the act open?
- What question did it answer?
- What question does the next act inherit?
- Did the act feel like a unit or a sequence of events?

### Block B — Hidden-truth inventory

For every hidden truth:

| Hidden truth | Reader seeds | POV leak? | Reveal target | Status |
|---|---|---|---|---|
| Levin’s signature | | | final reveal | |
| Marlene’s driver past | | | before Levin reveal | |
| Albula accident connection | | | midpoint | |
| Mancini’s witness status | | | late / partial | |

Check:

- enough preparation?
- too obvious?
- unfairly hidden?
- accidentally revealed by wording?

### Block C — Figure audit

For every central figure:

- outer mask clear?
- guilt / avoidance concrete?
- own voice?
- own desire in the train?
- mirror of Levin?
- payoff / disappearance prepared?

### Block D — World-rule audit

- Tilgung consistent?
- memory protection consistent?
- train-to-moment rule consistent?
- escape / doors / technical limits consistent?
- no arbitrary magic?

### Block E — Anti-drift audit

Check for:

- all-dead drift,
- generic transit space,
- arbitrary catastrophe,
- water / flood finale,
- Schaffner oracle,
- wrong ages,
- guilt as flat punishment,
- action-thriller instead of atmospheric mystery.

### Block F — Rhythm / market-shape audit

Check:

- projected word count;
- chapter length variation;
- whether broad chapters alternate with shorter pressure chapters;
- whether atmosphere is creating suspense or just volume;
- whether each chapter has a distinct rhythm function;
- whether any sequence needs compression before the next act.

### Block G — Workflow learning

List repeated errors:

- too explanatory,
- too generic,
- too many motifs,
- too little Albula specificity,
- too little character want,
- too much Schaffner explanation,
- too early guilt leakage,
- weak seams,
- chapters too consistently broad,
- too much beautiful pressure without state-change.

Add recurring errors to the next act’s watchlist / callback ledger.

---

## 16. Continuity handoff

After each chapter, preserve this state for the next session / next chapter.

```text
CONTINUITY HANDOFF — DER ZUG / ALBULA

Current chapter:
Current act:
Current train state:
Current train location:
Approximate story time:

Levin:
- physical state:
- emotional state:
- what he knows:
- what he avoids:
- active body triggers:

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
- Hediger:
- Anika:
- Jan:
- Selma:
- Eliah:
- Robert:

Disappeaarances / Tilgungen:
- [name | chapter | what changed in memory/material traces]

Open clues:
- [clue | planted in | target payoff]

Motif status:
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
- [ ] weak transition seam
- [ ] chapter sprawl / insufficient rhythm variation
```

---

## 17. Manuscript completion pipeline — after full first draft

The first complete draft is not the sellable manuscript yet. After Chapter 20, run these stages in order.

### Stage 1 — Structural read

Goal: prove the book works as a whole.

Check:

- global causal chain;
- all chapter functions;
- act turns;
- reveal timing;
- disappearance order;
- whether each central figure earns their mirror function;
- whether the ending follows from the whole book rather than merely explaining it.

Deliverables:

- full structural audit;
- list of required scene additions;
- list of cuts / merges;
- revised chapter map.

### Stage 2 — Callback and payoff audit

Goal: make every major seed fair.

Check:

- each clue has a return or payoff;
- each motif transforms when repeated;
- no clue is so hidden that it feels unfair;
- no clue is so obvious that it spoils the reveal;
- ledger entries match manuscript reality.

Deliverables:

- updated callback ledger;
- missing payoff list;
- overused motif list;
- cut/demote list for decorative motifs.

### Stage 3 — Compression / straffung pass

Goal: reduce volume without damaging atmosphere.

Check:

- repeated sensory catalogues;
- doubled beats;
- scenes that only re-feel earlier pressure;
- overlong dialogue;
- abstract Schuld language;
- chapters that do not change enough state for their length.

Target:

- usually cut **8–15%** from the full draft;
- if manuscript exceeds 105k, cut more aggressively before style polish.

### Stage 4 — Character pass

Goal: make every central figure feel like a person before they become a function.

Check:

- Tobias concrete before disappearance;
- Marlene independent before emotional loss;
- Hediger wounded rather than merely knowing;
- Anika/Jan relational damage prepared;
- Selma/Eliah handled without kitsch;
- Mancini not over-explained;
- Sarah has contour beyond illness.

### Stage 5 — World-rule and logic pass

Goal: protect the sacred internal logic.

Check:

- train rules;
- Tilgung mechanics;
- memory rewriting;
- route/time consistency;
- power/signal/door behavior;
- what Mancini can and cannot know/say;
- what Levin can and cannot know at each stage.

### Stage 6 — Line edit / style polish

Goal: keep the voice, remove mannerism.

Check:

- repeated sentence rhythms;
- too many isolated one-line paragraphs;
- German clunks;
- overused words/images;
- decorative darkness/cold/silence;
- dialogue naturalness;
- chapter endings that all use the same pressure shape.

### Stage 7 — Reader / market package

Goal: prepare the book for outside evaluation.

Create:

- 1-page pitch / hook;
- 2–3 page synopsis with ending;
- character list;
- comparable titles / positioning;
- polished first 30–50 pages;
- query/submission package or self-publishing launch checklist, depending on route.

---

## 18. What came from the old Bero workflow

Kept as process:

- micro-prompting,
- beat plan before prose,
- stop after plan and wait for “Go”,
- logic and motivation gate,
- beat distinctness test,
- seam discipline,
- per-beat correction pass,
- word count tracking,
- chapter harvest and polish,
- end-of-act audit,
- anti-pattern watchlist,
- continuity handoff.

Changed for Albula:

- YA / animal POV became psychological thriller POV.
- Animal-body rules became train / snow / metal / memory logic.
- Old family / clan mechanics became hidden signature / guilt-chain mechanics.
- Old motif systems became Albula-specific motif and callback tracking.

Removed:

- all Bero-specific names,
- Bero world rules,
- Bero plot examples,
- archive file routing,
- duplicated active filename lists.

---

## 19. What not to do

- Do not use “write on” for whole chapters.
- Do not write multiple beats unless explicitly asked.
- Do not combine beat plan and prose.
- Do not close a chapter without harvest and polish.
- Do not close an act without audit.
- Do not rationalize logic gaps.
- Do not stretch mystery rules for a cool effect.
- Do not turn Schuld into a sermon.
- Do not lose Albula specificity in generic horror.
- Do not reuse discarded ages.
- Do not let Mancini explain what the scene can show.
- Do not misunderstand the ending as repairing the past.
- Do not let every chapter sprawl just because the prose is atmospheric.
- Do not confuse beautiful pressure with necessary dramatic movement.

---

## 20. Working sentence

When unsure, return to this:

> *The train is not an afterlife. It is the form Levin’s repressed responsibility takes until he reaches the one moment where he can finally stop looking away.*

# Workflow: Crafting "Resonanz – Das Herz des Waldes"

> Instructions are in English for reliable model obedience.
> **All generated prose MUST be in German.** The novel's voice, idiom, and cadence are German.

---

## 1. Why this workflow exists

A single macro-prompt ("write Chapter 1") always collapses a chapter into a summary. To reach true novel length with atmospheric density, the process must enforce:

- **Micro-prompting** — one sub-scene at a time, no auto-continuation
- **Active pacing** — throttle narrative tempo deliberately
- **Continuous word-count tracking** — make pacing violations visible immediately
- **Iterative expansion** — deepen scenes before advancing plot

---

## 1a. Length targets — book and chapter

The book per `concept.md` is 180–220 pages, 20 chapters (Akt I: 1–6, Akt II: 7–15, Akt III: 16–20).

**Per-chapter band:**

| | Words |
|---|---|
| Floor (any chapter) | **2,500** |
| Average target | **~3,000** |
| Pivot chapters may breathe to | **3,500–4,000** |

**Pivot chapters** (allowed to run long):
- Ch6 — banishment
- Ch15 — catastrophe announcement
- Ch18 — confrontation with Grimm
- Ch19 — disaster
- Ch20 — resolution

**Quieter chapters** (hold near floor): mid-Akt-II setup beats, Ch2 clan-establishment, Ch10–12 wilderness routine.

**Whole-book target:** ~60,000 words → ~220 pages. Lower bound acceptable: ~50,000 words → ~180 pages.

**Self-sizing rule:** chapters are allowed to overshoot the planned target organically (Ch1 planned 2,500, landed 2,660 — fine). Do not pad. Do not compress dense material to hit a number.

---

## 1b. Beat sizing — content-determined, not pre-set

**Beats are content-determined.** Identify the natural dramatic units of the chapter first; let their count and size emerge from what the chapter actually needs. A pre-set "always 5 beats" rule is a planning crutch, not a craft rule.

**Per-beat size band:**

| Size | Use |
|---|---|
| <300 words | fragment, no arc — too small |
| **400–500 words** | sweet spot for atmospheric, single-movement beats (most internal/transitional beats live here) |
| 600–800 words | needed for dialogue beats, pivot beats with multiple movements, or social/confrontation scenes |
| >800 words | beat is doing too much — split it |

**Why smaller beats produce better prose:**
The model has a fixed compute budget per response. At 400–500 words the budget goes into texture, sensory detail, and interior. At 600+ the budget gets divided across pacing, planting, *and* texture — texture is what compresses first.

**Beat count guidance (not a rule):**

| Chapter target | Likely beat count | Notes |
|---|---|---|
| 2,500 (quiet) | 5–6 | mostly 400–500 each |
| 3,000 (average) | 6–7 | mostly 400–500 each |
| 3,500 (pivot) | 6–8 | one or two ~700-word beats inside |
| 4,000 (pivot) | 7–8 | dialogue/multi-movement beats earn the 600–800 slots |

**The override:** if the chapter's natural beats give you 4 or 9, plan for 4 or 9. Don't force a number. If beats sum way over/under target, the chapter is mis-scoped — re-plan, don't pad.

**Example from this project:**
- Ch1 originally planned 5 beats × ~500 = 2,500. Landed 5 beats / 320–700 each / 2,660 total. Worked because the dialogue beat (Beat 3, 700) and the expanded internal beat (Beat 1, 690) earned their length.
- Ch2 plan: 5 beats × ~600. Currently fine; if Beat 4 (Bero's failed communication with Grimm) wants more room, split it 4a/4b.

---

## 1c. Seam discipline between beats

When Beat *N+1* has a sensory anchor planned (per its beat-plan entry), Beat *N*'s ending must only **tease** that anchor — not catalog it. The end-hook lands the *fact* and the *body's reflex*; the catalog belongs to Beat *N+1*.

**Failure mode (caught and fixed in Ch2 Beat 1 → Beat 2):**

Beat 1 originally ended with a five-element scent inventory (*Bärenfell, Atem, Blut, Knochenmark, Eingeweide*). Beat 2's planned anchor was smell — and Beat 2 opened with a Schicht-für-Schicht inventory of those same components. The reader was getting the same scent twice. The seam was visible.

**Rule:**

| Slot | What it carries |
|---|---|
| End of Beat *N* | the *fact* of the new sensory channel + the body's involuntary response |
| Start of Beat *N+1* | the layered, detailed inventory of that same channel |

**Concrete pattern (good):**
> *Dann erreichte ihn der Geruch des Lagers.* — single named impression, no list
> *Beros Kopf senkte sich, ohne dass er es ihm befohlen hätte.* — body's reflex
> *(Beat ends here.)*
> *(Beat N+1 opens with the full Gewebe / layered description.)*

**Concrete anti-pattern (bad):**
> *Und dann roch er sie. Nicht eine Spur, sondern ein ganzer Geruch: dichtes Bärenfell, der schwere Atem von vielen, das eiserne Nachhalten von Blut, Knochenmark, Eingeweide.*
> *(Beat N+1 then re-lists the same items.)*

**Also avoid the over-correction:**
Trimming Beat *N*'s ending so hard that it stutters (e.g. *"Dann roch er sie. Den Clan."* — pronoun→noun mismatch + fragment isolation) is worse than the original. The ending should be *one clean named impression*, not telegraphic shrapnel.

**General principle:** every sense, motif, or piece of vocabulary belongs to exactly one beat as its primary handler. Adjacent beats may *anticipate* or *echo* — never duplicate.

---

## 2. Project-wide locks (paste into every new session)

These constants never change. State them at the start of any new chat so the model cannot drift.

```
PROJECT LOCKS — do not violate:

- Language of output: GERMAN only. Never switch to English, even in thought/dialogue.
- POV: 3rd person limited, anchored on Bero (unless a chapter is explicitly
  assigned to Kara, Grimm, or Silas).
- Tense: simple past (Präteritum). Internal thoughts in italics, present tense.
- Register: YA, raw, atmospheric. "Nature is cruel but beautiful."
- NO anthropomorphism: no tea, no clothes, no human tools, no human concepts
  the animals could not plausibly know. They hunt, bleed, eat, mate.
- Name policy: "Brummsi" is a slur used only by antagonists/mockers.
  Allies use "Bero". The narrator never uses "Brummsi" in neutral voice.
- Sensory budget per scene: at least 3 of {sight, sound, smell, touch, interior}.
- Dialogue tags: sparse. Prefer action beats over "said" variants.
```

---

## 2a. POV guardrails for hidden truths

A "hidden truth" is a plot fact designated reader-only — the reader is meant to register it (often subliminally on first pass, consciously on re-read), but the POV character must not know it. In this project the central hidden truth is **Vater-Saat**: Grimm is Bero's biological father; Bero must not know this until the planned Akt-III reveal.

**Rule:** the hidden truth never lands in the POV character's internal monologue, including italicized thoughts. It lands only via channels the POV character can perceive but not fully decode:

| Channel | Example |
|---|---|
| Externally observable behavior | A glance that lasts an extra breath; a posture that mirrors Bero's; a silence where a different bear would speak |
| Other characters' speech | A clan-elder's phrasing that means one thing to Bero and another to the reader |
| Body-level sensory data | A scent Bero recognizes but cannot place; warmth in a touch that he registers without naming |

**Pre-commit test:**
- *"Could an attentive reader notice this on re-read?"* — yes = OK.
- *"Does the POV character explicitly think or feel the hidden fact?"* — yes = revert.

**Failure mode caught and reverted (Ch5 Beat 4, pre-commit):** an italicized internal line had Bero *knowing* that Grimm was weaponizing the mother-invocation through their unspoken father-bond. Bero must not have that framing yet. Line reverted; the same beat now lands the moment through Grimm's posture and Bero's unnamed physical response.

**Heightened-watchlist contexts (Ch15 B4 lesson):** §2a-leak risk peaks in two situations that must trigger a doubled pre-commit test:

- **Clan-memory passages.** When the POV character recalls clan-bears in inventory or sequence, the Vater-Saat-resonant figure (here: Grimm) sits at maximum POV-leak risk. Any memory of physical detail involving that figure (posture, scent, gait, eyes, voice) passes §2a-test *twice* — once as Vater-leak-check, once as Bär-Mutter-Schutz-leak-check (Mutter-memories also resonate with the hidden truth). Pattern that worked at Ch15 B4: keep Mutter *out* of the inventory entirely; let other clan-bears carry the memory; let the Vater-resonant figure (Grimm) appear last and structurally weighted, with §2a-clean framing.
- **Decision-pivot moments.** When the POV character must decide whether to act against the Vater-figure, the temptation to write reluctance-as-Vater-bond is high. The reluctance must read as Bann-respect or moral weight, *not* as filial pull. Test: replace the reluctance phrasing mentally with "Anführer" (clan-leader, no kinship) — if the sentence still works, the framing is clean; if it loses force, the framing was leaking.

**General principle:** hidden truths are a reader-author conspiracy. The POV character is not in on it. If the prose ever puts the POV character "in on it," the reveal stops working.

---

## 2c. Word vs. Image — concept-lock at pivot moments

A **pivot moment** is a beat where the POV character has a conceptual realization. If the character lacks the vocabulary for the concept — and animal POV characters lack the vocabulary for almost every modern abstract concept — the realization must land as an **image**, not as the **word**.

The narrator may know the concept-word. The character must not think it.

**Rule:**
- Identify pivot moments in the beat plan ahead of prose.
- For each, check: does the POV character plausibly have the vocabulary for this concept? If no, replace any concept-word with a concrete bodily/visual image, or a re-naming-cascade that makes the realization happen *through* perception, not labeling.

**Precedent (Ch15 B3):** Bero understands the geological event that is about to occur. He does not name "Bergrutsch" (a German compound a bear would not think). He thinks: *"Der Hang fiel."* The realization is then deepened via a re-naming-cascade that re-categorizes earlier observations:

> *Die Wölbungen waren keine Beulen, sondern Risse, die noch keine Risse waren. Die Risse waren keine Risse, sondern erste Linien des Abgangs. Das stille Wasser an der falschen Stelle war kein Wasser — es war, wo die Erde aufgegangen war.*

The reader infers the concept ("the slope is failing") without the character ever using the concept-word.

**Pre-commit test:**
- *"Does the POV character think the abstract concept-word?"* — yes = revert; replace with image.
- *"Could a reader infer the concept from the image alone?"* — no = expand the image; do not import the word.

**Failure mode to avoid:** smuggling the concept-word in via "as if" or "kind of" constructions (*"Es war eine Art Bergrutsch"* / *"Es war wie ein Bergrutsch"*). These are evasions of the rule, not satisfactions of it. The POV character must reach the realization through perception, not through labeling.

---

## 3. Master prompt — starting a new chapter

```
We are starting Chapter [X].

CONTENT GOAL: [one-sentence description of what must happen by chapter end]
TARGET LENGTH: ~[2,500 quiet | 3,000 average | 3,500–4,000 pivot] German words.
  (See §1a. Pick the band that matches this chapter's role. Default 3,000.)
CARRY-OVER: [1–2 bullets on where the previous chapter left Bero — emotional
state, physical location, unresolved tension].

Apply active pacing. Throttle tempo hard. Do NOT write the whole chapter.

STEP 1 — Beat plan only.
Identify the chapter's natural dramatic beats (typically 4–8 — let the
content decide; do not force a number). For each beat, list:
  - Location & time of day
  - POV character (default: Bero)
  - Purpose (what this beat must accomplish)
  - Target word count (per §1b: 400–500 sweet spot; 600–800 for dialogue
    or pivot beats with multiple movements; the beats should sum to the
    chapter target)
  - Sensory anchor (which senses will dominate)
If your beats sum way over or under the chapter target, the chapter is
mis-scoped — re-plan, don't pad.

STEP 1b — Logic & motivation gate. Run this on the beat plan BEFORE prose, before "Go".
This is the beat-logic-consistency check: catch story-logic holes while it is still
cheap (no prose written yet). It sits ahead of every prose-level pass (§3 STEP 3, §4d,
§4e all run AFTER prose). Check:
  - Motivated action: for each character active in the chapter, name what they want and
    what it costs them. Does each beat have them do what those incentives actually dictate?
  - Obvious-action test: if a beat depends on a character NOT taking an obvious, available,
    in-character action, that inaction MUST have an in-world reason established in the same
    scene the option appears — never retrofitted later, never merely to fill a chapter.
  - Structure-first trap: confirm the beats are derived from character incentive, not bent
    to a pre-decided chapter shape. If you set "Chapter X = event Y" and worked backward,
    re-derive forward from what the characters would actually do.
  - Cause/effect: does each beat follow from the previous one for a reason a reader can feel?
  - Beat distinctness (one beat = one dramatic unit): does each beat have its OWN function —
    its own turn (state A → event → state B) — that no other beat duplicates or steals? Two
    adjacent beats are secretly ONE beat if (a) beat N+1's main job is only to explain,
    re-feel, or re-frame what beat N already showed (it adds no new event), or (b) beat N
    withholds a cause/meaning purely so beat N+1 can "reveal" it. If so, merge them.
    HARD NO-GO: never split one dramatic unit into two beats by telling it first mechanically
    (the *what* — the action/failure) and then emotionally (the *why/meaning*). The meaning
    must be visible IN the event, not deferred to a separate beat. (Precedent: Ch10 planned
    B1 "can't summon the Brummen" + B2 "because of shame" were one unit — the shame had to be
    visible inside the failure; merged to 5 beats.) NB: this guards DRAMATIC-FUNCTION
    duplication; §1c separately guards sensory-anchor duplication. A genuine reflection/
    consequence beat is fine — but only if it carries its own new event (a realization,
    decision, or change), not a mere re-statement of the prior beat.
Report the gate result. If it finds a gap, fix the PLAN before requesting Go — never write
prose over a known logic hole. Then STOP and wait for my "Go".

STEP 2 — On my "Go", write ONLY beat #1.
Spend time on environment, atmosphere, sensory detail, and Bero's interior
world. Do not advance into beat #2 under any circumstances.

STEP 3 — Before reporting, run a beat-local correction pass, folded into THIS SAME response (no separate round-trip — this is what keeps it cheap).
Re-read the beat just written and apply surgical, plot-neutral fixes for BEAT-LOCAL issues only:
  - Voice slippage within the beat (anthropomorphism creep, modern/clinical nouns, English slips)
  - §2a hidden-truth leaks (heightened-watchlist contexts force a doubled check)
  - §2c word-vs-image violations at pivot moments (concept-word in the POV-character's head)
  - Internal logic / factual errors inside the beat
  - Weak verbs/adjectives, German clunks (doubled subordinates, awkward relative clauses)
  - Anti-pattern watchlist categories (the recidivist classes flagged by the last act audit / callback-ledger Note B)
  - **3-stage crutch-word pre-flight (codified from Ch13–Ch14 lessons; details in Note B):**
    - **Stage 1 — calque check:** mentally re-translate each sentence to English. If it sounds more natural in English than in German, it is a calque — revise.
    - **Stage 2 — beat-wide frequency count:** identify the 3–4 most frequent content words in the beat. Each appearance >3× must justify itself as deliberate anaphora/motif, or be varied. The beat-wide count catches motif-overuse a sentence-level read cannot.
    - **Stage 3 — local 1-2-sentence cluster scan:** read each paragraph separately for the same content word appearing 2× within 1–2 sentences. Deliberate parallel = keep; unintentional repetition = vary. The local scan catches what the beat-wide count misses (Ch14 second-round lesson).
Do NOT attempt cross-beat work here — seam discipline (§1c), cross-beat repetition, timing/spatial consistency between beats, motif overuse across the chapter. Those need the whole chapter and belong to §4d. A beat in isolation cannot see them.

Then end every response with:
  - Beat-Pass: fixes applied as `location | before → after | why`, or "clean"
  - Word count for this beat: [N]
  - Cumulative chapter word count: [N] / [chapter target]
  - Self-evaluation: is this beat dense enough, or should we expand?
  - Question to me: expand this beat further, or proceed to the next beat?

STEP 4 — On chapter completion (last beat written):
Automatically run §4d End-of-chapter checks — BOTH the callback harvest
AND the polish pass — before asking what's next. Do NOT wait for "polish"
to be requested. The polish pass is mandatory, not optional.

STEP 5 — On act completion (final chapter of an act is closed):
After STEP 4 finishes, IF this chapter closes an act (Ch6 = Akt I,
Ch15 = Akt II, Ch20 = Akt III + book), automatically run §4e End-of-act
audit before asking what's next. Like the polish pass, the act audit
is mandatory, not optional. If the user has to remind the model to
run §4e, the model has failed the workflow.
```

---

## 4. Follow-up prompts

### 4a. Beat is too thin / too fast

```
Good skeleton, but too compressed. Before [action X], let Bero dwell longer
on [aspect Y]. Add the cold, the smell of [Z], the weight of his own body.
Extend this beat by ~300 words. Do not advance the plot.
```

### 4b. Beat drifted off-voice

```
The prose slipped into [narrated summary / modern idiom / anthropomorphism].
Rewrite this beat keeping all plot points, but restore the raw YA register
and the 3rd-person-limited-on-Bero lens. Check the project locks.
```

### 4c. Beat is good — proceed

```
Approved. Continue with beat #[N+1] under the same rules.
Remind me at the end of the cumulative word count and remaining beats.
```

### 4d. End-of-chapter checks (auto-trigger on final beat — mandatory)

When the last beat of a chapter has been written, the model IMMEDIATELY runs two passes before asking what's next. The user does not need to request "polish" — it is part of every chapter's completion.

#### Pass 1 — Callback harvest

```
1. Report final chapter word count and beat-by-beat distribution.
2. List 3 elements (object, phrase, sensation) introduced in this chapter
   that should return later as callbacks. Mark target chapter / arc.
3. Summarize Bero's emotional state in one sentence for the next chapter's
   CARRY-OVER field.
4. Update the chapter file's continuity ledger to reflect the EXIT state
   (not the entry state).
5. Append the new callback entries to /callback-ledger.md (the project's
   master tracker). Each entry: name, planted-in, status, target act/chapter.
   Re-status any earlier ledger entries that fired in this chapter.
```

#### Pass 2 — Polish pass

Read the chapter prose end-to-end and look for the categories below. **Beat-local issues should already be resolved by the per-beat correction passes (§3 STEP 3); this pass concentrates on the CROSS-BEAT categories a single beat could not see.** If a beat-local slip survived to here, fix it too — but the per-beat pass failing repeatedly is itself a signal to investigate. Apply all surgical, plot-neutral fixes immediately (no permission needed). Document each fix in a "Polish pass" entry appended to the self-evaluations section: `# | location | before | after | why`.

**Prose-level issues:**
- Voice slippage — anthropomorphism creep (human concepts/tools/idioms the bear could not plausibly have); modern colloquialisms (e.g. "vermasselt" → "versagt"); abstract nouns when bodily nouns are available
- Timing or spatial inconsistencies between beats (e.g. Beat 5 says "heute Mittag" when Beat 2 happened at Dämmerung)
- Doubled subordinates and other German clunks (`verstand, dass er es getan hatte`)
- Awkward relative clauses where a noun phrase or short sentence is cleaner
- Word repetition that feels unintentional (vs. deliberate motif repetition — *Wumm.*, *Stille*, *Pranke* are motif-OK)
- Weak verbs/adjectives where precision is available

**Seam discipline issues (per §1c):**
- Sensory anchors duplicated across adjacent beat boundaries
- End-hooks that catalog the next beat's anchor instead of teasing it
- Over-corrected seams (telegraphic stutters, pronoun→noun mismatches)

**File-structure hygiene:**
- Stale headers, leftover blocks, displaced text from mid-chapter edits
- Continuity ledger labels that still say "entry state" after the chapter is complete
- Self-eval entries whose content has been superseded
- Word-count tallies that no longer match after edits

**Continuity issues:**
- Vocabulary inconsistencies (variant spellings, conflicting synonyms for the same concept)
- Character physical/emotional details inconsistent with earlier beats
- Plants that should have fired but were dropped

After both passes complete, THEN ask the user what they want next (next chapter / specific beat expansion / etc.). Not before.

---

### 4e. End-of-act audit (auto-trigger after pivot chapter closes an act — mandatory)

When the final chapter of an act has been completed (Ch6 closes Akt I, Ch15 closes Akt II, Ch20 closes Akt III + book), the model runs §4e immediately after §4d, before asking what's next. The audit is wider than the per-chapter polish pass: it checks cross-chapter coherence, planted-seed accounting, voice drift over the whole act, and forward-feasibility of the next act.

Output the audit as a written report directly in chat. Document any fixes applied to chapter files in a "Act audit" log entry. Open issues that need user decision get flagged at the end of the report as `OPEN — needs user`.

The audit has three blocks: **A** (backward — what the closed act delivered), **B** (forward — what the next act must do and whether it's feasible), **C** (workflow itself).

#### Block A — Backward audit of the closed act

**A.1 Soll-geschlossen / Soll-offen split**
List every plot thread, character arc, and thematic question opened in the act. Mark each as `closed-by-design`, `open-by-design`, `accidentally-open`, or `accidentally-closed`. The last two are bugs. Threads that the next act must inherit get carried into Block B.9.

**A.2 Voice-drift check**
Read Beat 1 of the act's first chapter and the final beat of the act's last chapter back-to-back. Same register? Same sentence-length distribution? Same lakonic density? Same noun-to-abstract ratio? If drift is detectable, name it concretely (which dimension drifted, in which direction) and propose either a re-read fix or an explicit register-recalibration for the next act.

**A.3 Architecture-lock audit**
For every architecture-lock defined for the project, build a `lock × chapter × fired? × how` table. Flag:
- locks that over-fired (frequency too high — risk of inflation)
- locks that under-fired (planted but starved — risk of disappearing)
- locks that fired incorrectly (e.g. allied character used an antagonist-only term)
- locks not yet fired that need to fire in the next act

For this project, the locks are at minimum: Brummsi-as-verbal-seal, Vater-Saat (Grimm = Bero's father, hidden), Bär-Mutter-Schutz, Lura-active, Geist-des-Waldes. Additional locks may be added per act.

**A.4 Anti-pattern recidivism scan**
Read every polish-pass and self-eval log entry across the act. Cluster fixes by category (anthropomorphism, modern/clinical noun, English-slip, POV-leak, meta-narration, etc.). Categories that appeared in 2+ chapters become a **next-act watchlist**: explicit slip-classes to pre-check during drafting of the following act.

**A.5 Time / geography / character-availability consistency**
- Time: Are all temporal markers (sun-counts, moon-phases, "X winters ago", seasonal cues) consistent across the act?
- Geography: Are spatial references (directions, distances, named features) self-consistent? Could a reader draw a coherent rough map?
- Character availability: Where is each named character physically at act-end? Are any required to be elsewhere for next-act plans?

**A.6 Word-count proportion vs. book target**
Compute act word count and compare to expected share of the 60,000-word book target. (Akt I = chapters 1–6 = 6/20 = 30% → expect ~18,000 words. Akt II = 9/20 = 45% → expect ~27,000. Akt III = 5/20 = 25% → expect ~15,000.) Significant deviation forces a decision: re-scope upcoming chapters, or adjust the book target in `concept.md`.

**A.7 Cold-read coherence**
Imagine a reader who has read only this act. Does it function as a self-contained narrative unit (setup → escalation → turn)? Or does it depend on later acts to be coherent? Akt I in particular must work as "status quo → disruption → exile" without Akt II/III to lean on.

**A.8 Hidden-truth inventory**
List every fact the reader does NOT yet know that they will eventually need to know. For each: planted yet? In how many chapters? Adequate for the eventual reveal? (For this project: Vater-Saat is the central hidden truth. Other items may emerge per act.)

#### Block B — Forward audit for the next act

**B.9 Next-act todo from concept.md**
Pull the next act's block from `concept.md` and turn it into an explicit todo list of plot beats, character introductions, and arc obligations.

**B.10 Next-act todo from callback harvest**
Walk the callback harvest from every chapter of the closed act. Every seed that the next act is supposed to pay off becomes a todo item. Seeds that queue for a later act stay tagged but don't enter B.9-B.10's working set.

**B.11 Merge + feasibility check**
Merge B.9 and B.10 into one ordered list. Then check:
- Temporal feasibility: do the events fit the time the act spans? (E.g. if Akt II covers two seasons and the todo has four major events that each need weeks of setup, the act is over-scoped.)
- Geographic feasibility: does the geography allow the planned movements?
- Character feasibility: are all needed characters available when needed?

Items that don't fit get flagged `OPEN — needs user` (cut, defer, or expand the act).

**B.12 Solo-voice / dialogue-availability risk**
If the next act has long stretches without a dialogue partner for the POV character, name the mechanism that will keep the prose dynamic (interior monologue, animal encounters, environmental dialogue, etc.). If no mechanism is identified, this is `OPEN — needs user`.

#### Block C — Workflow self-revision

**C.13 Anti-Gemini-drift check** (project-specific to this novel)
The earlier draft `gemini-story.md` differs from this book at several deliberate decision points (avalanche in Akt III not Akt I; banishment via Bär-Mutter-Schutz not via failure-of-hunt; Grimm = father vs. unspecified; etc.). Re-list those decisions and verify that no chapter of the closed act has drifted toward the Gemini version. Subtle drifts to flag: image vocabulary echoing the Gemini scene, sociological framing reverting to the looser Gemini sketch, "Brummsi" usage drifting from slur toward neutral.

**C.14 Workflow-rule emergence**
Did any rule emerge during the closed act that should be codified into `workflow.md` §1–§4? (Precedent: §4d auto-polish was codified after Akt I's early chapters made it clear the user shouldn't have to ask for polish. §4e itself was codified at the Akt-I close.) If yes, propose the addition and ask user to approve before editing the workflow.

#### Report format

End the audit with:
- **Fixes applied:** list (with file:beat references)
- **Open issues needing user decision:** numbered list, each one paragraph
- **Recommendation for next step:** one sentence

Then — and only then — ask the user what to do next.

---

## 5. Continuity ledger (maintain manually)

Keep a short log the model can be re-fed when context is lost:

```
CONTINUITY LEDGER (current state)

- Bero's location: [ ]
- Bero's physical state: [injuries, hunger level]
- Bero's emotional state: [one sentence]
- Kara's status: [present / separated / wounded / ...]
- Known to the reader but not to Bero: [ ]
- Open callbacks (planted, not paid off): [ ]
- Vocabulary established (invented or stylized terms): [ ]
```

Paste this into the top of any new session so voice and facts stay consistent.

---

## 6. Why this works

- **Beat plan** forces plot into controllable bites; you always know where you are.
- **Hard stop per beat** prevents auto-advancing to the next plot point.
- **Word-count tracking** makes pacing failures visible on the first response,
  not the tenth.
- **Project locks** reduce drift in voice, POV, tense, and tone across sessions.
- **English scaffolding, German output** exploits the model's stronger
  English instruction-following without polluting the prose.

---

## 7. What NOT to do

- Do not ask for "the rest of the chapter" — always request one beat.
- Do not accept a beat under its target word count without expanding it.
- Do not let the model plan and write in the same response (plan → stop → go).
- Do not translate example passages from English drafts. Write German natively.
- Do not allow the narrator to adopt the slur "Brummsi" in neutral voice.
- Do not duplicate the next beat's sensory anchor at the end of the current beat. End-hooks tease (the fact + the body's reflex); inventories belong to the next beat. See §1c.
- Do not over-correct seams into telegraphic stutters (e.g. pronoun→noun mismatches, isolated fragments). One clean named impression beats both an overstuffed catalog and a staccato shrapnel-ending.
- Do not skip the auto-polish pass on chapter completion. The polish pass (§4d Pass 2) is mandatory and runs before asking the user what's next, every time, no exceptions. If the user has to remind the model to polish, the model has failed the workflow.
- Do not skip the end-of-act audit (§4e) when the closed chapter is Ch6, Ch15, or Ch20. It runs immediately after §4d, before asking what's next. If the user has to remind the model to run §4e, the model has failed the workflow.
- Do not skip the per-beat correction pass (§3 STEP 3). It runs folded into the beat-writing response — never as a separate round-trip — and catches beat-local slips at fresh context, before they propagate into later beats. It handles beat-local issues ONLY; cross-beat work stays with §4d. Letting a beat-local slip ride until the chapter-end polish is the failure this pass exists to prevent.
- Do not defer an obvious, available, in-character action across a beat or chapter boundary for pacing. If a plot device creates a trivial solution (a strong bear + a rock that pins a small animal = an obvious rescue), either the character takes it, or an in-world obstacle is established the moment the device appears. Withholding the obvious action to manufacture a later "centerpiece" is the Ch7 Kara-rock failure — caught only because the user flagged it. The §3 STEP 1b gate exists to catch it at plan stage instead.
- Do not split one dramatic unit into two beats by narrating it first mechanically (the *what*) and then emotionally (the *why/meaning*). If beat N+1 only re-frames or explains beat N without its own new event, they are one beat — merge them, and make the meaning visible inside the event. (Precedent: Ch10 planned B1/B2.) Checked at plan stage by the §3 STEP 1b "beat distinctness" test.
- When a logic gap is flagged (by the user or by self-review), the FIRST move is to test whether the premise is wrong — not to defend it. Do not rationalize a contrivance with post-hoc justification (the Ch7 "trust-gating" defense of the rock). Re-examine the root and discard the rotten setup if needed. Defending already-written work over fixing the story is a failure mode in itself.
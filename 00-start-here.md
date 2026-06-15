# Start Here — Der Zug / Albula

> **Purpose:** Reading order, file map and project audit log for the Albula novel project.  
> **Rule:** Use the numbered English filenames as the current working structure. Older German filenames may still appear inside copied documents; this file is the source of truth for file identity.

---

## 0. Why the split is useful

The project is split because each document answers a different kind of question:

| File type | Question it answers | Why it must stay separate |
|---|---|---|
| Canon | What is absolutely true? | Prevents concept drift. |
| Characters | Who carries which wound, mask and guilt? | Prevents flat ensemble writing. |
| Chapter plan | What happens when? | Prevents beautiful scenes without a spine. |
| Accident file | What really happened in 2008? | Prevents vague mystery logic. |
| Workflow | How do we write without collapsing into summary? | Prevents pacing and prose drift. |
| Callback ledger | Which seeds, motifs, clues and payoffs are active? | Prevents dropped setups, repeated motifs and unfair reveals. |
| Act foundations | What must this act achieve before chapter prose starts? | Prevents act-level holes. |
| Chapter files | The actual manuscript prose. | Keeps draft text separate from planning. |
| Archive manifest | What was removed from the active path? | Preserves recovery info without polluting canon. |

The split is not bureaucracy. It protects the novel from mixing different thinking layers.

---

## 1. Current file order

Read / update files in this order:

1. `01-canon.md`
2. `02-characters.md`
3. `03-chapter-plan.md`
4. `04-accident-2008.md`
5. `05-workflow.md`
6. `06-callback-ledger.md`
7. `11-act1-foundation.md`
8. `12-act2-foundation.md`
9. `13-act3-foundation.md`
10. `14-act4-foundation.md`
11. `21-chapter-01.md` once drafting begins
12. `22-chapter-02.md`, etc.

Do **not** read `99-archive-manifest.md` for drafting. It exists only to document removed files.

---

## 2. Filename groups

### 00 — Navigation

- `00-start-here.md` — this file.

### 01–09 — Global foundations

- `01-canon.md` — global canon lock.
- `02-characters.md` — character dossier.
- `03-chapter-plan.md` — full novel route / red thread.
- `04-accident-2008.md` — reconstruction of the fictional Albula accident.
- `05-workflow.md` — writing workflow and quality gates.
- `06-callback-ledger.md` — master tracker for seeds, motifs, clues, hidden truths, disappearances and payoffs.

### 11–19 — Act foundations

- `11-act1-foundation.md` — Akt I foundation.
- `12-act2-foundation.md` — Akt II foundation.
- `13-act3-foundation.md` — Akt III foundation.
- `14-act4-foundation.md` — Akt IV foundation.

### 21+ — Manuscript chapters

- `21-chapter-01.md`
- `22-chapter-02.md`
- `23-chapter-03.md`
- etc.

This keeps planning files and manuscript files visually separated.

### 99 — Archive / inactive material

- `99-archive-manifest.md` — documents removed files. Not part of drafting context.

---

## 3. Old-to-new filename map

| Old filename | New filename |
|---|---|
| `albula-canon.md` | `01-canon.md` |
| `figuren-dossier.md` | `02-characters.md` |
| `kapitelplan.md` | `03-chapter-plan.md` |
| `unglueck-2008.md` | `04-accident-2008.md` |
| `workflow.md` | `05-workflow.md` |
| `motiv-ledger.md` / callback tracker | `06-callback-ledger.md` |
| `akt1-foundation.md` | `11-act1-foundation.md` |
| `akt2-foundation.md` | `12-act2-foundation.md` |
| `akt3-foundation.md` | `13-act3-foundation.md` |
| `akt4-foundation.md` | `14-act4-foundation.md` |

If an internal document reference still points to an old filename, map it through this table.

---

## 4. Removed inactive files

The following files were removed from the active root and documented in `99-archive-manifest.md`:

- `bero-akt2-foundation.md`
- `concept2.md`
- `concept3.md`

They are not current canon. Recover only from Git history if explicitly needed.

---

## 5. Start rule for writing

Before starting chapter prose:

1. Read `01-canon.md`.
2. Read the relevant figure sections in `02-characters.md`.
3. Read the relevant chapter entry in `03-chapter-plan.md`.
4. Check `04-accident-2008.md` for hidden truth / 2008 information boundaries.
5. Follow `05-workflow.md`.
6. Check `06-callback-ledger.md` for active seeds, motifs, hidden truths and pending payoffs.
7. For chapters 1–6, also read `11-act1-foundation.md`.
8. For chapters 7–11, also read `12-act2-foundation.md`.
9. For chapters 12–17, also read `13-act3-foundation.md`.
10. For chapters 18–20, also read `14-act4-foundation.md`.

Then create the relevant manuscript file, beginning with the chapter beat plan. Do not write full prose before the beat plan passes the workflow gates.

After every completed chapter, update `06-callback-ledger.md` before starting the next chapter.

---

## 6. Project audit log — 2026-06-15

This section records what has already been checked and why. It exists so later work does not repeat old uncertainty or accidentally undo decisions.

### 6.1 Concept decision

Checked the available concept variants against hook strength, specificity, internal logic and long-form potential.

Decision:

- The **Albula concept** is current canon.
- Older Transit / Flood / generic afterlife variants are inactive.
- The project spine is: **one train, one accident, one guilt-chain, one repressed moment.**

Resulting active files:

- `01-canon.md`
- `02-characters.md`
- `03-chapter-plan.md`
- `04-accident-2008.md`

### 6.2 File structure / naming audit

Question checked:

> Is the separation of files useful, or should everything be consolidated?

Decision:

- Separation is useful because each document answers a different question.
- Filenames were changed to numbered English names so the reading order is obvious in GitHub / VS Code.
- `00-start-here.md` became the navigation and audit file.

Naming pattern:

- `00` = navigation / meta
- `01–09` = global foundations
- `11–19` = act foundations
- `21+` = manuscript chapters
- `99` = archive / inactive material

### 6.3 Archive cleanup

Question checked:

> Do Bero files, `concept2.md` and `concept3.md` still belong in the active path?

Decision:

- No. They are not current canon.
- They were removed from the active root and documented in `99-archive-manifest.md`.
- They should not be read for drafting unless explicitly recovered from Git history.

Important note:

- A real binary `.zip` could not be produced through the GitHub connector, so the practical solution was: remove from active root + document recovery info in an archive manifest.

### 6.4 Scope / page-count audit

Question checked:

> Is the target page count defined, and what size fits this project?

Decision:

- Target remains: **70,000–80,000 words**.
- Recommended ideal: **ca. 75,000 words / ca. 300 pages / 20 chapters**.
- This fits the psychological Mystery-Thriller scope without letting the closed train setting sprawl.

Practical implication:

- Average chapter length target: roughly **3,500–4,000 words**, with shorter pressure chapters and longer reveal chapters as needed.

### 6.5 Foundation creation sequence

The project foundations were created in this order:

1. `11-act1-foundation.md`
   - establishes route logic, train map, ensemble introduction, first Tilgung and Akt-I end image.
2. `12-act2-foundation.md`
   - establishes relational Tilgung, historical traces and the Midpoint into Albula 2008.
3. `13-act3-foundation.md`
   - establishes individual guilt mirrors and protects Levin’s signature reveal until Akt IV.
4. `14-act4-foundation.md`
   - establishes final object, final choice and Sarah aftermath.

Reason for this order:

- The act foundations were built after the global canon / chapter plan so each act could answer a precise structural task instead of becoming a loose idea document.

### 6.6 Foundation vs. chapter-structure audit

Question checked:

> Do all act foundations still match `03-chapter-plan.md`?

Result:

- Yes, the main structure is coherent.
- Akt I = Ch1–6.
- Akt II = Ch7–11.
- Midpoint = Ch11.
- Akt III = Ch12–17.
- Akt IV = Ch18–20.

Detected stale / cleanup points:

1. `11-act1-foundation.md` still had old proposal language and references to creating the chapter plan.
2. Tobias was still described as a candidate for first disappearance, although the plan now fixes him as first hard Tilgung.
3. `03-chapter-plan.md` still had the Chapter 20 location partly open between Chur and Zürich.
4. Some older internal file references still used German filenames.

Consolidation response:

- Akt I should be marked as current foundation, not proposal.
- Tobias is fixed as first hard Tilgung.
- Chapter 20 final location is **Café in Zürich**.
- Old file references should be mapped through this file if not yet updated internally.

### 6.7 Transition audit — red thread across acts

Question checked:

> Do the act transitions feel seamless, or does the story become episodic?

Overall result:

The red thread is strong:

```text
Akt I  → Is Levin wrong, or is the world wrong?
Akt II → What connects these people?
Akt III → What did each person do / avoid / fail to say?
Akt IV → What does Levin do when the truth names him?
```

Core escalation:

```text
impossible train
→ damaged traces
→ Albula 2008
→ individual guilt-chains
→ Levin's form
→ braking
→ Sarah
```

Three seam risks were identified:

#### Seam risk 1 — Akt I → Akt II

Risk:

- Chapter 7 could feel like a reset if it jumps straight from Tobias to Jan.

Handling:

- Chapter 7 must begin from the residue of Tobias / Platz 47.
- Working seam: first a man is erased from a seat; then a man is erased from a life.

#### Seam risk 2 — Akt II → Akt III

Risk:

- Anika’s Chapter 12 payoff could feel late if she disappears from the text after Jan is erased in Chapter 7.

Handling:

- Anika must remain a damaged presence in Chapters 8–11.
- Mini-echoes: accidental `wir` → `ich`, wrong photo framing, reaction to Filisur / smoke / platform, grief without object.

#### Seam risk 3 — Akt III → Akt IV

Risk:

- Chapter 18 could feel mechanical if it jumps immediately from Marlene’s disappearance to the form reveal.

Handling:

- Chapter 18 must start with Marlene-aftershock / Levin’s isolation.
- The form emerges from that absence, not from plot machinery.

### 6.8 Mini consolidation applied after transition audit

The transition audit led to a small consolidation pass, not a rewrite.

Applied / to be preserved in drafting:

1. **Anika continuity rule**
   - After Jan’s Tilgung, Anika must continue as a visible damaged presence until Chapter 12.

2. **Selma / Eliah / Linn pre-echo rule**
   - Before Chapter 14, Selma and Eliah must receive at least two quiet echoes so their chapter does not feel isolated.

3. **Marlene-aftershock rule**
   - Chapter 18 must not start with the form as a cold plot object. It begins with Levin alone after Marlene, then moves into the document reveal.

4. **Tobias fixed as first hard Tilgung**
   - No longer merely a candidate.

5. **Chapter 20 final location locked**
   - Schlussort: **Café in Zürich**.

### 6.9 Current readiness state

The project is structurally close to drafting.

Before writing `21-chapter-01.md`, do one final check:

1. `11-act1-foundation.md` should no longer contain stale proposal / next-step language.
2. `03-chapter-plan.md` should reflect the Zürich ending and transition echo rules.
3. `05-workflow.md` should use the new numbered filenames where possible.
4. `06-callback-ledger.md` should be ready to receive Ch1 harvest after drafting.

Once these are clean, the next creative step is:

> `21-chapter-01.md` — Chapter 1 beat plan, not prose yet.

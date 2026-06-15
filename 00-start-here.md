# Start Here — Der Zug / Albula

> **Purpose:** Reading order, file map and project audit log for the Albula novel project.  
> **Rule:** Use the numbered English filenames as the current working structure. This file is the source of truth for file identity, active reading order and project-audit history.

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
| Handoff prompt | Where should a new assistant continue? | Prevents context loss when moving to a new chat, but is not part of the drafting read path. |
| Act foundations | What must this act achieve before chapter prose starts? | Prevents act-level holes. |
| Chapter files | The actual manuscript prose. | Keeps draft text separate from planning. |
| Archive manifest | What was removed from the active path? | Preserves recovery info without polluting canon. |

The split is not bureaucracy. It protects the novel from mixing different thinking layers.

---

## 1. Current active reading order

Read / update files in this order for normal drafting work:

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

Do **not** read `07-next-chat-start.md` during normal drafting. It exists only as a copy-paste handoff prompt for a new chat.

Do **not** read `99-archive-manifest.md` for drafting. It exists only to document removed files.

---

## 2. Filename groups

### 00 — Navigation

- `00-start-here.md` — this file. Active navigation, reading order and audit log.

### 01–09 — Global foundations and helper files

- `01-canon.md` — global canon lock.
- `02-characters.md` — character dossier.
- `03-chapter-plan.md` — full novel route / red thread.
- `04-accident-2008.md` — reconstruction of the fictional Albula accident.
- `05-workflow.md` — writing workflow and quality gates. It does **not** control file routing.
- `06-callback-ledger.md` — master tracker for seeds, motifs, clues, hidden truths, disappearances and payoffs.
- `07-next-chat-start.md` — English copy-paste handoff prompt for a new chat. Not part of the normal active reading path.

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
| `00-next-chat-start.md` | `07-next-chat-start.md` |

If an internal document reference still points to an old filename, map it through this table.

---

## 4. Removed inactive files

The following files were removed from the active root and documented in `99-archive-manifest.md`:

- `bero-akt2-foundation.md`
- `bero-callback-ledger.md`
- `bero-workflow.md`
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
5. Follow `05-workflow.md` for method, beat planning and quality gates.
6. Check `06-callback-ledger.md` for active seeds, motifs, hidden truths and pending payoffs.
7. For chapters 1–6, also read `11-act1-foundation.md`.
8. For chapters 7–11, also read `12-act2-foundation.md`.
9. For chapters 12–17, also read `13-act3-foundation.md`.
10. For chapters 18–20, also read `14-act4-foundation.md`.

Then create the relevant manuscript file, beginning with the chapter beat plan. Do not write full prose before the beat plan passes the workflow gates.

After every completed chapter, update `06-callback-ledger.md` before starting the next chapter.

---

## 6. Current handoff state — 2026-06-15

`07-next-chat-start.md` contains the English prompt for starting a new chat. It is a copy-paste handoff helper only, not part of the normal drafting read path.

Last completed step:

```text
06-callback-ledger.md was updated with the Chapter 1 harvest.
```

Next clean step:

```text
Create 22-chapter-02.md as a Beat Plan only.
Do not write Chapter 2 prose before the Beat Plan passes the workflow gates.
```

Important Ch1 → Ch2 carry-over:

```text
The tunnel / metallic splitting sound from Chapter 1 must echo into the first halt / interruption of Chapter 2.
```

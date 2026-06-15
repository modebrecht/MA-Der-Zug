# Start Here — Der Zug / Albula

> **Purpose:** Reading order and file map for the Albula novel project.  
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
6. `11-act1-foundation.md`
7. `12-act2-foundation.md` once created
8. `21-chapter-01.md` once drafting begins
9. `22-chapter-02.md`, etc.

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

### 11–19 — Act foundations

- `11-act1-foundation.md` — Akt I foundation.
- `12-act2-foundation.md` — Akt II foundation, not created yet.
- `13-act3-foundation.md` — Akt III foundation, future.
- `14-act4-foundation.md` — Akt IV foundation, future.

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
| `akt1-foundation.md` | `11-act1-foundation.md` |

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
6. For chapter 1–6, also read `11-act1-foundation.md`.

Then create `21-chapter-01.md` with the chapter beat plan first. Do not write full prose before the beat plan passes the workflow gates.

# Current State

Current phase: outline (`phase-001-outline`) — artifacts written, review findings applied, not closed

Outline status: `outline/volume-01.md` (Chapters 1–60) and `outline/batches/volume-01-batch-0001.md` (Chapters 1–10) exist and pass the section and card requirements in `OUTLINE_GUIDE.md`. A review pass over both files was run and its findings have been applied to the outlines, the terminology register, and the state files. That pass was **not** the independent read-only gate this project intends: the review agent is configured as a subagent but is invoked as a primary agent, the runtime rejects that, and the run fell back to an agent with edit and bash rights. No phase in this novel has therefore passed a genuine independent review, and nothing below may be read as a validated gate. The phase is **not closed and not validated**. Only the controller may mark a phase `done` or `blocked`; `state/phase-ledger.json` and any `workspace/.../.done` marker are controller-owned and were deliberately left untouched by the writer.

Current volume: 1 (outline complete, Chapters 1–60)

Current batch: 1 (cards complete, Chapters 1–10; no prose written)

Last completed chapter: none

Last batch summary: none

No chapter prose exists yet. The next phase (`workspace/phase-002-batch-plan`, mirrored by `workspace/volume-01/batch-0001/PROMPT.md`) is to write Chapters 1–10 as finished scenes.

Active threats: no on-page threat yet. The author-level threat is the accumulated Margin pressure and Soren Rook’s planned One Survey.

Active promises:

- Establish Alderquay, Milo Rook, and the first Bellwether Lane mystery in Volume 1.
- Explain why erased streets form remnant streets and why the official Atlas suppresses, rather than solves, their pressure.
- Keep the Lark Street and Neris Rook mystery as the personal thread without pretending Neris can be resurrected.
- Develop the one slow-burn relationship between Milo and Mara Quill.
- Preserve the planned ending: plural restoration, permanent personal cost, and a distributed civic Atlas.

Volume 1 plan in force:

- **Central pressure:** Bellwether Lane, a river-core street withdrawn from the public map six years ago, appears as an extra stop in Line 7’s active timetable. Closing it again pushes the pressure into the tram line, the housing around it, and the flood-control works.
- **Midpoint, Chapter 30:** the bells were a coordinated evacuation broken by the continuity order, not a massacre echo. The Chapters 1–10 batch must not settle this.
- **Climax, Chapters 54–57:** the pressure that the Chapter 31–40 seamquake redirected concentrates at the river-core interchange and becomes a **pinned seam** — held open by the order rather than sealed, registered in `bible/terminology.md` as a condition only, not a new remnant type, grammar, or failure state. Milo keeps the crossing open long enough to move residents, with Ada, Jo, Tomas, Pell, Iona, and Mara each holding a piece, and refuses to use the Lark token as a private key.
- **Resolution, Chapters 58–60:** temporary route, temporary stay, reopened worker’s death record, suspended order, contested restoration of the public name, and a copied maintenance route that opens the Volume 2 question. Suspending the order and re-cutting the schedule is what unpins the seam, so it ends quiet rather than healed.
- **Cost curve:** the orientation blank arrives in two separate stages. Chapter 4 costs the remembered route — familiar routes drop out of his sense of direction and return only when someone marks them, while the Field Book itself is intact. Chapters 51–53 cost the written line, and it is still blank at the end. Volume 1 ends with that second loss still recoverable; persistence and Mara’s return route belong to Volume 2. The batch must not book the written-line loss early.
- **Pressure distribution:** four of the first ten chapters are civic or institutional in pressure, which overweights the political share against `OUTLINE_GUIDE.md`’s 15% guideline. This is recorded as a deliberate deviation, not drift, and Chapters 11–20 are expected to supply the training, character, and recovery share. See the distribution note in the batch outline.
- **Next-volume question:** who else is using old maps to move people without telling them, and what happened at the first Quieting?

Batch 1 plan in force:

- Beginning (1–2), escalation (3–4), midpoint (5), escalation and action (6–8), climax (9), aftermath (10).
- Stage 1 trace-sight begins in Chapter 3 through contact with the timetable and seam; the first Field Book residue is the incomplete prompt “A return mark is missing.” Chapter 4 is the first cost-bearing crossing, and the orientation blank begins there.
- Chapter 5 earns the second half of the working rule: keep the interval, yield at the third turn rather than fill it, and accept that a witness may refuse without the route failing. Chapter 4 earns the first half. The two halves must not be collapsed into “the third bell needs a witness.”
- Cedar Court carries three incompatible readings of the third turn — check the lane, hand over to whoever is nearest, count who is still on the street — and the closure notice supplies a fourth theory, a count of the dead. All four must survive Chapter 10 intact.
- The batch ends with a supervised one-shift passage, a temporary stay, an incomplete public report, and a copied route pointing at a street with no official address. Orrin’s order still stands.

Current relationship pressure: Milo and Mara begin as professional opponents with mutual competence; neither is willing to surrender independent judgment. The batch ends at mutual competence, which is the Volume 1 relationship milestone, and leaves Mara’s return route for Milo as the Volume 2 step.

Current power state: Stage 0 at the opening, Stage 1 by Chapter 4 and held through Chapter 10. Orientation blank accruing and still recoverable. No sensory failure, personal blank, seam-scar, record blank, or authorial blank may appear in Volume 1.

## Pending controller actions

These are outside the writer’s and fixer’s authority. They are recorded so the next run does not treat an unvalidated checkpoint as a finished phase.

1. **Ratify or reject CR-001** (10 volumes in one city versus the catalog’s 14 traveling volumes). `outline/volume-01.md` and the Chapters 1–10 cards were written before ratification under the outline phase’s own prompt; the deviation is recorded as CR-008 with the mechanical edit required if CR-001 is rejected.
2. **Repair the review gate, then re-run it for the bootstrap and outline phases.** `.opencode/agent/novel-reviewer.md` declares `mode: subagent`, but both call sites — `.github/workflows/novels.yml` and `scripts/novel_runner.sh` — invoke it with `opencode run --agent novel-reviewer`, which the runtime rejects before the agent loads, and it falls back to an agent that has edit and bash rights. Neither phase has passed an independent read-only review, and the review log lives under the gitignored `logs/`, so no committed file can evidence a past gate. The three files are controller-owned; a fixer must not edit them. Until this is fixed, treat every “review” in this repository as self-review.
3. **Reconcile phase selection with the stated contract.** `PHASE_SYSTEM.md` says the selector reads `state/phase-ledger.json`, while `scripts/novel_runner.sh` scans `workspace/**/PROMPT.md` for a missing `.done`. The ledger is stale: it still reads `currentPhase: phase-000-bootstrap`, `status: planned`, with no `phase-001-outline` entry, although `workspace/phase-000-bootstrap/.done` exists. A fix agent must not mark a phase done to hide the mismatch. `workspace/phase-001-outline` currently holds a `.checkpoint` and no `.done`.
4. **Fix the model probe’s failure path.** The workflow truncates one log and then writes each attempt to a different file, so the diagnostic it prints when every model fails is empty. The probe also inherits finding 2, so it can pass while testing the fallback agent rather than the agent it names.
5. **De-duplicate the two next-batch prompts.** `workspace/phase-002-batch-plan/PROMPT.md` and `workspace/volume-01/batch-0001/PROMPT.md` both dispatch Chapters 1–10 and differ materially in their instructions, so the writer gets different guidance depending on which the runner selects. The former also instructs the writer to update the phase ledger, which is controller-owned and contradicts the rules in this file. Both are controller-scaffolded; do not create a third prompt to resolve it.
6. **Record the model and attempt count** for this phase in the ledger when closing it.

# Current State

Current phase: outline (`phase-001-outline`) — artifacts written and reviewed, not closed

Outline status: `outline/volume-01.md` (Chapters 1–60) and `outline/batches/volume-01-batch-0001.md` (Chapters 1–10) exist and pass the section and card requirements in `OUTLINE_GUIDE.md`. An independent read-only review of both files was run in this phase; its findings were applied to the outlines, the terminology register, and the state files. The phase is **not closed and not validated**. Only the controller may mark a phase `done` or `blocked`; `state/phase-ledger.json` and any `workspace/.../.done` marker are controller-owned and were deliberately left untouched by the writer.

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
- **Cost curve:** the written route home goes blank in Chapters 51–53, before the climax, and is still blank at the end. Volume 1 ends with that loss still recoverable; persistence and Mara’s return route belong to Volume 2.
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
2. **Re-run the independent read-only review for the bootstrap and outline phases.** The bootstrap review recorded in `logs/phase-000-bootstrap.review.log` fell back to the default agent instead of `novel-reviewer`, so that phase has not passed its intended gate. The outline phase was reviewed by `novel-reviewer` in this run and its findings are applied, but the phase itself remains unvalidated.
3. **Update the ledger and marker.** `scripts/novel_runner.sh` selects phases by scanning `workspace/**/PROMPT.md` for a missing `.done` marker rather than reading `state/phase-ledger.json`, which contradicts `PHASE_SYSTEM.md` “Self-Dispatch”. The runner or the ledger contract must be reconciled by the controller; a fix agent must not mark the phase done to hide the mismatch. `workspace/phase-001-outline` currently holds a `.checkpoint` and no `.done`.
4. **Record the model and attempt count** for this phase in the ledger when closing it.

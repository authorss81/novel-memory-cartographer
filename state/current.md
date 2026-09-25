# Current State

Current phase: bootstrap (`phase-000-bootstrap`)

Bootstrap status: artifacts written and reviewed. The bible, series outline, ending outline, and state files exist, and the findings from `logs/phase-000-bootstrap.review.log` have been applied. The phase is **not closed and not validated**. Only the controller may mark a phase `done` or `blocked`; `state/phase-ledger.json` and any `workspace/.../.done` marker are controller-owned and were deliberately left untouched by the writer and the fixer.

Current volume: 1 (outline not yet written)

Current batch: 0 (no batch cards populated)

Last completed chapter: none

Last batch summary: none

No chapter prose exists yet. Volume 1 planning must not begin until the scope deviation in `state/canon-changes.md` CR-001 is ratified by the controller.

Active threats: no on-page threat yet. The author-level threat is the accumulated Margin pressure and Soren Rook’s planned One Survey.

Active promises:

- Establish Alderquay, Milo Rook, and the first Bellwether Lane mystery in Volume 1.
- Explain why erased streets form remnant streets and why the official Atlas suppresses, rather than solves, their pressure.
- Keep the Lark Street and Neris Rook mystery as the personal thread without pretending Neris can be resurrected.
- Develop the one slow-burn relationship between Milo and Mara Quill.
- Preserve the planned ending: plural restoration, permanent personal cost, and a distributed civic Atlas.

Current relationship pressure: Milo and Mara begin as professional opponents with mutual competence; neither is willing to surrender independent judgment.

Current power state: Stage 0. Milo is a capable ordinary surveyor. The Field Book and first trace-sight rules are planned, but no magical use is canon on the page yet.

## Pending controller actions

These are outside the writer’s and fixer’s authority. They are recorded so the next run does not treat an unvalidated checkpoint as a finished phase.

1. **Ratify or reject CR-001** (10 volumes in one city versus the catalog’s 14 traveling volumes) before `outline/volume-01.md` is written.
2. **Re-run the independent read-only review.** The review recorded in `logs/phase-000-bootstrap.review.log` fell back to the default agent instead of `novel-reviewer`, so the phase has not yet passed its intended quality gate with an independent reviewer. Fixes from that run are applied; a clean subagent review is still outstanding.
3. **Update the ledger and marker.** `scripts/novel_runner.sh` selects phases by scanning `workspace/**/PROMPT.md` for a missing `.done` marker rather than reading `state/phase-ledger.json`, which contradicts `PHASE_SYSTEM.md` “Self-Dispatch”. The runner or the ledger contract must be reconciled by the controller; a fix agent must not mark the phase done to hide the mismatch.
4. **Record the model and attempt count** for this phase in the ledger when closing it.

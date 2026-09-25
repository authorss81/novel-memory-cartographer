# Canon Change Log

Required by `AGENTS.md`: any change to the premise, world rules, power system, antagonist ladder, or planned ending must be recorded here with its reason. Prose may not introduce a fact that changes these rules without a numbered entry below.

Status vocabulary: **deviation** leaves fleet-level planning material unchanged; **clarification** resolves a contradiction inside this repository’s own bible; **approved** is written by the controller, not by the writer.

**Review provenance.** Entries CR-001 through CR-007 name a review of `phase-000-bootstrap` as their origin. That review log is not retained in the repository, and the review agent is currently not invocable as configured, so those entries record the reasoning rather than a verifiable audit trail. Treat their provenance as unconfirmed, not as disputed; the controller may re-run the gate and re-date them.

---

## CR-001 — Volume count and geographic scope

- **Type:** deviation
- **Raised by:** review of the `phase-000-bootstrap` artifacts. The review log itself is not retained in the repository (`logs/` is gitignored), so this entry cites the phase, not a verifiable file.
- **Status:** recorded, awaiting controller ratification

**Reference material.** `NOVEL_CATALOG.md` entry 11 specifies 700 chapters in **14 volumes of approximately 50 chapters**, with a traveling, multi-location engine: “he travels through cities, family homes, demolished villages, and unfinished buildings.”

**What the current bible plans (proposed, not yet ratified).** `outline/series.md` plans 700 chapters in **10 volumes**, all set in and around the single city of Alderquay, moving through its districts rather than between cities: the river core (Volumes 1–2), Mireward and the fenland villages (Volume 3), Crown Heights and the Registry archive (Volumes 4–6, 9–10), South Salt (Volume 5), and the Outer Reach (Volumes 7–8).

**Why the deviation is defensible.**

- The chapter total is unchanged at approximately 700, so the fleet’s length planning still holds.
- Fourteen volumes of approximately 50 chapters would also sit inside the 40–80 range in `PHASE_SYSTEM.md`, so this is not a compliance shortcut. The argument is continuity density: ten volumes of 60–80 chapters let each one carry a central pressure, several complete local cases, and a real resolution, which is what keeps one city’s institutions, seams, and antagonist ladder legible across 700 chapters. Fourteen shorter volumes would spread the same causal chain thinner and force local cases to end before they pay off.
- The traveling engine is preserved at a smaller scale. Volume 3 sends the team into fenland villages with no legal address, Volume 7 builds a mobile community map that crosses the delta, and Volume 9 requires travel through three regions. Each of these functions like the catalog’s “demolished villages” and “unfinished buildings” cases while keeping one city’s institutions consistent.
- `outline/ending.md` keeps the Margin’s extent beyond Alderquay intentionally open, so the larger geography is preserved as future material rather than foreclosed.

**What this does not change.** The premise, the power system, the antagonist ladder, the relationship policy, the ten-volume arc, and the planned ending are all unchanged. No new city, antagonist, or final enemy is introduced.

**Controller action required.** Ratify the 10-volume single-city scope, or replace `outline/series.md` with a 14-volume structure. `outline/volume-01.md` and the Chapters 1–10 batch cards have since been written under the outline phase’s own prompt; see CR-008 for how that was handled and what ratification would still change.

---

## CR-002 — First Atlas: plural design operated through a singular emergency mode

- **Type:** clarification
- **Raised by:** `phase-000-bootstrap` review, high severity
- **Status:** applied

**Problem.** `outline/series.md` described the First Atlas as something that “could only work” by forcing one authoritative account, while the same document and Volume 6 described the original design as deliberately plural and incomplete. The ending depended on which claim was true.

**Resolution.** The First Atlas was built plural on purpose, with distributed custody and deliberate gaps. It carried an emergency setting, the **Singular Mode**, which forced one account to become the Index’s version and suspended the others. The Quieting happened because that Mode was still engaged after the Long Rain began to recede and because its forced output was then treated as the record. Soren’s One Survey is a deliberate, citywide re-run of the same Mode, published and scheduled as bounded work that turns out to have no reachable end.

**Files updated:** `bible/world.md`, `bible/terminology.md`, `bible/characters.md`, `outline/series.md`, `outline/ending.md`, `state/continuity.md`.

**Plot impact:** none. The Lark order, the Greywake mechanism, and the Volume 6 reversal all keep their planned outcomes; the Volume 6 revelation is now a shutdown failure rather than a hidden weapon.

---

## CR-003 — Canonical remnant triad and the partial-erasure rule

- **Type:** clarification
- **Raised by:** `phase-000-bootstrap` review, high severity
- **Status:** applied

**Problem.** Four descriptions of remnant formation were in circulation: “public name, routes, communal witnessing” (`bible/premise.md`), “Body, Name, Witness” (`bible/power-system.md`), “body, name, and witness” (`outline/series.md`), and a rule stating that failure of one part of an erasure could make a remnant *more* coherent (`bible/world.md`).

**Resolution.** One triad is canonical: **name, route, witness**. A remnant forms only when all three are withdrawn. Severing one support leaves a ruin, a disputed address, or a rumor. Severing two leaves a **thin remnant** — unstable, one service at most, unable to maintain its own witness. The “more coherent” case is preserved and specified: an erasure that has withdrawn two supports and left the third standing forces the last support to carry pressure it was never built for, so a badly executed order can leave a stronger and more dangerous remnant than a competent one.

**Files updated:** `bible/power-system.md`, `bible/premise.md`, `bible/world.md`, `bible/terminology.md`, `outline/series.md`, `state/continuity.md`.

**Plot impact:** none. This adds a rule for thin remnants, which gives Volume 1 and later volumes a cheap, common, dismissible form of seam danger, and it keeps Lark Street a full remnant because all three supports were withdrawn there.

---

## CR-004 — Soren Rook’s stated method and error

- **Type:** clarification
- **Raised by:** `phase-000-bootstrap` review, medium severity
- **Status:** applied

**Problem.** Soren initiates a process that the outline says must end in catastrophe, with no stated belief about what the process will do or why he thinks the Quieting will not repeat. He risked reading as irrational.

**Resolution.** Soren holds three answers to the obvious objection, and each is partly correct: he has a complete inventory of the excluded pressure, he intends a bounded operation with a published shutdown and reopening, and he intends to store the suspended routes in a sealed residual layer rather than cast them out. He says all of this plainly, in his own voice and in the records he leaves, so a reader can be tempted by the argument.

His error is visible inside his own method rather than hidden beneath it: shutting the Mode down requires a plural city to switch back to, and his own corrections organize the city around a single account, so the published date arrives with nowhere to put the excluded routes. Pressure that is stored is not contained, only waiting. He is also the Index’s living anchor, so a singular map is the configuration in which he survives; this is a motive he does not count and the prose does not excuse.

The framing deliberately does not make him secretly aim at permanent rule. A bounded plan that cannot reach its own bound is a stronger antagonist than a scheme that was always meant to last forever, and it keeps his stated virtue and his actual result in open conflict.

**Files updated:** `bible/characters.md`, `bible/terminology.md`, `outline/series.md`, `outline/ending.md`, `state/continuity.md`, `state/open-threads.md`.

**Plot impact:** none. Soren still initiates the One Survey, still keeps the Index stable long enough for evacuation, still releases it, and still dies.

---

## CR-005 — Fixed onset for each power cost

- **Type:** clarification
- **Raised by:** `phase-000-bootstrap` review, medium severity
- **Status:** applied

**Problem.** The power table in `outline/series.md` placed the first personal blank and a physical seam-scar both at Stage 3, while `bible/power-system.md` introduced the personal blank at Stage 3 and the seam-scar at Stage 4.

**Resolution.** `bible/power-system.md` is authoritative. Onset is now fixed: orientation blank with the first crossing in Volume 1; sensory failure at Stage 2; **first personal blank at Stage 3**; **visible seam-scar and dependence on being maintained at Stage 4**; record blank at Stage 5; authorial blank at Stage 6. A cost belonging to a later stage may not appear earlier.

**Files updated:** `outline/series.md`, `state/continuity.md`.

**Plot impact:** none. Volume 1 still ends with an orientation blank, and the final cost is unchanged.

---

## CR-006 — “New grammar for every street” inside seven canonical grammars

- **Type:** clarification
- **Raised by:** `phase-000-bootstrap` review, low severity
- **Status:** applied

**Problem.** `NOVEL_SPEC.md`, `README.md`, and `outline/series.md` promised a new grammar per street, which conflicts with the fixed set of seven canonical grammars and the rule against adding new categories.

**Resolution.** The promise stands as a reader-facing promise and is now scoped: every street presents a rule nobody has met before, built as a new combination of the seven canonical grammars with its own cue, service, demand, and failure condition. Knowing the category tells Milo what question to ask first and nothing more; two Cadence streets can demand opposite things.

**Files updated:** `bible/power-system.md`, `bible/terminology.md`, `outline/series.md`, `NOVEL_SPEC.md`, `README.md`.

**Plot impact:** none. No new grammar category is introduced anywhere in the planned series.

---

## CR-007 — Field Book naming

- **Type:** clarification
- **Raised by:** `phase-000-bootstrap` review, low severity
- **Status:** applied

**Problem.** `bible/characters.md` and `outline/series.md` called Milo’s starting object a “field notebook” while `bible/terminology.md` canonically names it the **Field Book**.

**Resolution.** The object is the Field Book. It remains privately owned and absent from Civic Atlas Office inventory, which is what the original “separate notebook” phrasing was trying to say.

**Files updated:** `bible/characters.md`, `outline/series.md`, `state/continuity.md`.

---

## CR-008 — Volume 1 outline written before CR-001 was ratified

- **Type:** deviation
- **Raised by:** `phase-001-outline`, from a review pass over the two outline files. That pass was not the intended independent read-only gate — see `state/current.md` — so the deviation was detected from the files themselves rather than certified by a separate reviewer.
- **Status:** recorded, awaiting controller ratification

**Problem.** The bootstrap phase left an instruction in `state/continuity.md` and `state/canon-changes.md` that `outline/volume-01.md` and the batch cards must stay empty until the 10-volume single-city scope in CR-001 was ratified. The outline phase was then dispatched with a prompt that explicitly ordered Volume 1 and the first batch to be created, so the artifacts were written while CR-001 was still open and the two state files still described them as placeholders.

**Resolution.** The artifacts are kept, because the phase prompt authorized them and because CR-001 changes the number of volumes, not the content of Volume 1. If the controller rejects CR-001 and restores a 14-volume structure, the required edit is mechanical: Volume 1’s contents stay and the later volume boundaries in `outline/series.md` are re-cut around them. No premise, power rule, character, or ending change is required either way. The stale placeholder lines in `state/continuity.md` and this log have been corrected so the next run does not read a finished phase as a blank one.

**Files updated:** `outline/volume-01.md`, `outline/batches/volume-01-batch-0001.md`, `bible/terminology.md`, `state/continuity.md`, `state/current.md`, `state/open-threads.md`, `state/canon-changes.md`.

**Plot impact:** none. Bellwether Lane, the Cadence-with-Kinship-leak classification, Orrin Sable, the Chapter 30 reversal, and the Stage 1 orientation-blank ending are unchanged from what the series outline and ending outline already planned.

---

## CR-009 — “Pinned seam” is a Volume 01 condition, not a new category

- **Type:** clarification
- **Raised by:** `phase-001-outline`, second review of the climax events
- **Status:** applied

**Problem.** The Volume 01 climax needed a failure state that was neither a second seamquake nor a new remnant form: a seam held open by a live order rather than sealed, which is worse to live beside than a collapse. Without a definition it would have been an unnamed magical effect invented at the climax, and it collided with the personal-map “hole” already in use for Milo’s orientation blank.

**Resolution.** The condition is named **a pinned seam** and registered in `bible/terminology.md`: a seam kept open because a live continuity order keeps feeding pressure into it, which does not close while the order stands and comes loose when the order is suspended and the routes around it are re-cut. It is explicitly a condition. It is not a new remnant type, not an eighth grammar, not a new failure state, and not a new antagonist. The personal-map gap keeps its own language so the two do not read as one thing. It appears once, in Chapters 51–60.

**Files updated:** `outline/volume-01.md`, `bible/terminology.md`, `state/continuity.md`.

**Plot impact:** none. The Chapter 54–57 climax and the Chapter 58–60 resolution keep their planned outcomes; the resolution now states explicitly that suspending the order and re-cutting the schedule is what unpins the seam, which is the same legal victory already planned.

---

## CR-010 — Bellwether is a near-completion full remnant, not a clean three-way severance

- **Type:** clarification
- **Raised by:** review of `phase-001-outline`, high severity, on the Volume 01 outline
- **Status:** applied

**Problem.** `outline/volume-01.md` stated Bellwether’s erasure two incompatible ways. The reader-promise section, the planning-classification section, and the Chapter 30 reversal described the order as withdrawing the public name, closing the ordinary routes, *and* separating the people who had witnessed the street, while also describing Ada’s surviving bell-and-door routine as “the one overloaded witness support left in place.” Under CR-003 and `bible/power-system.md`, a triad severed three ways and a triad severed two ways with the third left standing are different rules with different consequences, and the second is the near-completion exception. A later batch inheriting the file could have written either, and the visible result — a full remnant that a community can still negotiate with — depends on which one is true.

**Resolution.** One canonical accounting, now stated once in the planning-classification section of `outline/volume-01.md` and repeated in the Chapter 30 reversal, which is the chapter that fixes it: the order withdrew the **name** and closed the **route** — two supports. It broke the **witness** support rather than removing it: the routines and the people who kept them were scattered, but Ada’s evening third strike and door-check survived because she never left the river core, so one instance of the third support was left standing and had to carry pressure the other two had held. Bellwether is therefore a **near-completion full remnant**: two withdrawn, one standing and overloaded. It is not a thin remnant that later grew, and the small thin remnant at the western culvert is a separate thing that did not create it.

**Files updated:** `outline/volume-01.md`, `outline/batches/volume-01-batch-0001.md`, `bible/terminology.md`, `state/continuity.md`.

**Plot impact:** none. The Chapter 30 reversal, Ada’s role as the revocable first living witness, the Chapter 9 supervised passage, and the Volume 1 resolution keep their planned outcomes. The reversal now has a single defensible mechanism behind it, and the standing routine is stated as the reason the residents can negotiate with the seam at all.

---

## CR-011 — The western culvert has one physical state track across the volume

- **Type:** clarification
- **Raised by:** review of `phase-001-outline`, medium severity
- **Status:** applied

**Problem.** The culvert’s state read backwards. `bible/terminology.md` said the closure “is being completed in this volume” while `outline/volume-01.md` said the culvert “remain[s] materially changed”; the Chapter 7 card had a foreman shutting the gate at sunrise, yet the Chapter 9 card still had “Orrin’s crew… waiting to close the western culvert” as if it were still open; and the climax depended on “the opening of the western culvert” widening the pinned seam. A later batch could not tell whether the structure was sealed, throttled, or merely closed for the night.

**Resolution.** One track, registered in `bible/terminology.md` and carried in the Chapter 7 and Chapter 9 cards: the Chapter 7 order **throttles and partly seals** the culvert, winding the gate down to a maintenance slit, because a full seal would back water into the flood-control works zone and the low streets behind it — which is why the lawful compromise leaves the structure open enough to keep carrying pressure. The Chapter 9 crew arrives with the seal kit and **does not finish the job**, because the public passage occupies the works site for the whole shift. The climax’s floodgate test then **drives that same throttled gate back out to full flow** to keep the embankment and works zone dry, and that widening is what lets the pinned seam widen. The culvert is therefore throttled and never sealed from Chapter 7 onward. It ends the volume gated, silted, and re-aligned.

**Files updated:** `bible/terminology.md`, `outline/volume-01.md`, `outline/batches/volume-01-batch-0001.md`.

**Plot impact:** outcomes unchanged, one on-page action clarified. The Chapter 7 diversion that separates Jo’s crew, the Chapter 9 refusal, the climax, and the materially-changed resolution all keep their planned results. What did change is the crew’s Chapter 7 action: the foreman no longer shuts the gate, he winds it down to a maintenance slit under a stated hydraulic constraint, and the Chapter 9 crew leaves with the seal unfinished. That constraint is what keeps the structure throttled rather than sealed through the climax, so it is a mechanical fix to a contradiction rather than a new event; the added constraint is that a full seal would flood the works zone. No character, motive, location, or chapter outcome is altered.

---

## CR-012 — The orientation blank has two distinct stages in Volume 1

- **Type:** clarification
- **Raised by:** review of `phase-001-outline`, medium severity
- **Status:** applied

**Problem.** The orientation-blank cost was booked twice in near-identical words. Chapter 4 and the batch’s “first cost” already cost Milo the route to the office or home until another person marks it, and the Chapter 10 pull still had him unable to find home until Pell chalks it, while `outline/volume-01.md` and `state/current.md` reserved a separate escalation for “the written route home goes blank in Chapters 51–53.” As written, a writer could spend the larger cost in the opening batch or describe the same loss twice.

**Resolution.** The distinction that `bible/characters.md` already implies is now stated. **Chapter 4 costs the remembered route:** familiar routes drop out of Milo’s sense of direction and return only when another person marks them, while the Field Book is untouched and the route home stays written in his own hand. **Chapters 51–53 cost the written line:** the entry he has copied out after every survey goes blank. Two stages, two chapters ranges, and they may not be collapsed or swapped. Both remain recoverable inside Volume 1; persistence and Mara’s return route stay in Volume 2.

**Files updated:** `outline/volume-01.md`, `outline/batches/volume-01-batch-0001.md`, `state/current.md`, `state/continuity.md`.

**Plot impact:** none. Onset is unchanged at Stage 1, first crossing, as CR-005 fixes it, and Volume 1 still ends with a recoverable blank.

---

## CR-013 — The opening batch’s on-page commitments that later batches must not contradict

- **Type:** clarification
- **Raised by:** `phase-002-batch-plan`, writing Chapters 1–10
- **Status:** applied

**Why this entry exists.** The batch fixed several facts as prose rather than as plan — a date calendar, a support cast, a method of refusing a record demand, and the exact form of the one line of a report that has to survive October. None of them changes a premise, a power rule, the antagonist ladder, or the ending, but each one is now load-bearing in a way a later batch could break without intending to. They are registered here and in `bible/terminology.md`, `state/continuity.md`, and `state/batch-summaries.md`.

**What was fixed, and where it lives.**

1. **The Volume 01 calendar.** The 4th–10th of Sazur carry Chapters 1–10. Then: Orrin’s contractor’s bond lapses on the **11th**, the hearing sits on the **14th**, the **floodgate test** drives the throttled gate out to full flow on the **22nd**, and the timetable review — which expires Mara’s temporary stay — is the **28th**. `state/batch-summaries.md` and `state/current.md`.
2. **The culvert action, now on the page (CR-011 confirmed in prose).** In Chapter 7 Danner winds the gate down to **eighteen inches of sill**, by hand, in front of witnesses, because a full seal would back water into the works zone and the low streets. In Chapter 9 the one-shift passage occupies the site for the whole shift, so the seal crew has *no window* and Danner writes that on the form twice. The gate is throttled and never sealed in Volume 1, and the 22nd test drives it out to full flow. This is exactly the track CR-011 fixed; it is now stated on the page rather than only in the plan.
3. **Supporting cast, registered in `bible/terminology.md`.** Dilley Farr, Cass Ardery, Danner, and the Streetkeepers Rue and Idar. No new faction, grammar, antagonist, or category has been introduced.
4. **Mara’s countersigned routing slip.** In Chapter 6 she finds her own block capitals on the six-year-old intake routing slip for the Bellwether file, in the box that meant *I have seen that an address is affected and passed it on*. This is the concrete form of her fear of becoming complicit and must be carried forward, not cured inside Volume 1.
5. **The refusal of a record demand is a written offer of an extract.** Chapter 10 has Milo refuse the Field Book in writing and offer a witnessed extraction of the service-court entries instead. This is a precedent: it is how a private book can be entered in evidence without being taken, and later batches should not have him surrender the book.
6. **The one sentence that has to survive October.** At the bottom of the Chapter 9 report, Milo writes that the Civic Atlas Office has no authority to reopen the route and does not claim one. Mara identifies it as the sentence that will protect him and the sentence that will make him unfashionable. Later batches should not let him quietly drop it, and should not let it dissolve into a speech.
6a. **Deleting evidence is a method Milo now uses, and it is a precedent.** In Chapter 9, Idar the Streetkeeper points out that five of the working ways out of the service court — chalked into the fourth column of the official inspection sheet by the four Streetkeepers during the afternoon — are about to enter an office file where they can be shut. Milo strikes all five out **on his own motion** and heads the sheet *no household routes are recorded in this document, and no person has consented to one.* He has no authority to decide, and reasons that a man with no authority has no business publishing a route that belongs to a woman with a pram. The line through them is in his own hand with his name at the foot of the page. This is the batch’s clearest instance of a map refusing to be useful, and later batches should build on it rather than contradict it. It also establishes that Streetkeepers write on the official sheet, and that a document can be made weaker on purpose.
7. **The provisional plan is a plan of a handrail, and it is revocable.** Eleven inches by nine, one shift, four consented names with revocable terms, Lena Marr’s tenancy named in full, *one household has declined to be entered* with no name or address, and a deliberately empty right-hand third headed *for people who are not here yet*. It is **not** the neighborhood-scale provisional map of Chapters 41–50 and must not be inflated into one. It is also not a restoration.
8. **Soren Rook is not named in Chapters 1–10, and the hand is not attributed to him.** An earlier draft of Chapter 5 had Ada Fenn name Soren and assert the parentage. That was cut because it collapsed the clue chain, made Ada a delivery device for a fact she should not have, and read the parentage as a surprise, which `bible/characters.md` forbids. On the page, Soren’s only presence is the bracket-and-dot hand on two confirmed documents plus one recorded as *consistent with, not sworn to*, and the method of a polite young man from Crown Heights who asked Ada what the third bell was for nine years ago and collected her answer. Nothing in Volume 1 may confirm the parentage, the authorship, or the Lark order without evidence established on the page.
9. **Atlas residue frequency.** Two appearances in the batch, both in Chapters 3 and 4, both incomplete and both limited by Milo in his own notes before he acts. Chapter 9 has none and he notices the silence. Later batches should stay at or below this frequency.
10. **The volume calendar already pre-spends part of the Chapter 10 filing.** A temporary stay exists from Chapter 10 and expires on the 28th. The Volume 1 resolution in Chapters 58–60 must therefore *replace* it and show the stay was insufficient, rather than discovering that a filing is possible.

**Plot impact:** none. Every planned outcome of `outline/volume-01.md` is unchanged. The CR-010 triad accounting, the CR-011 culvert track, and the CR-012 two-stage orientation cost are all preserved and, in the culvert’s case, now stated on the page.

---

## CR-014 — The copied maintenance route is dated but unplaceable, not a phantom name

- **Type:** clarification
- **Raised by:** `phase-002-batch-plan`, writing Chapters 9–10
- **Status:** applied

**Problem.** Attachment 9 to the order is a carbon maintenance route whose diversion line names a destination absent from every current map. A later batch could read that as an invented name, a proof of a haunting, or the first hint of the One Survey. All three would be wrong and two of them would be too much too early.

**Resolution.** The destination is a real, ordinary, dated name. It has correct and current streets on both sides, a bus route that stopped serving it in a year Milo can name, and no entry in the current street name index, the alignment sheets, or the six-year-old reconstruction. It went out of use the way names go out of use by people getting older, not by a decision, and it can be dated to within a few years. Milo establishes that in one hour in the records alcove and cannot place it. It is offered to him in Chapter 9 as the demonstration’s route and refused, on the page, for the reason that a name on a public sheet is a claim rather than a discovery. It is a clue about **maintenance records** — who copied it, from which survey book, and who is still using old maintenance maps to move people — and it opens the Volume 2 question. It does not touch the Quieting, the First Atlas, or the One Survey.

**Files updated:** `state/continuity.md`, `state/open-threads.md`, `state/batch-summaries.md`.

**Plot impact:** none. The Volume 1 ending image and the Volume 2 premise are unchanged; this only fixes what the attachment is.

---

## Open items carried forward

- The phase ledger (`state/phase-ledger.json`) and any completion marker for `phase-000-bootstrap` and `phase-001-outline` are controller-owned. Writers and fixers must not mark a phase `done` or `blocked`.
- `bible/terminology.md` now carries a “Volume 01 local register” for cast and places introduced during volume planning. Later batches must reuse those names, roles, and wants instead of renaming or replacing them.
- An annotating hand is confirmed on two documents: the Chapter 1 timetable’s old-ink margin correction and the Chapter 6 annex notation. The Chapter 10 carbon copy carries two unsigned marks in *different* inks, so at least one is a different author and Volume 1 does not settle which. The chain is registered in `outline/volume-01.md` and is not resolved in Volume 1. Later batches must carry it and must not name it as Soren without evidence, and must not treat the Chapter 10 pair as a confirmed third instance.

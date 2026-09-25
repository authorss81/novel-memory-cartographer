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
6a. **Deleting evidence is a method Milo now uses, and it is a precedent.** In Chapter 9, Idar the Streetkeeper points out that five of the working ways out of the service court — chalked into the fourth column of the official inspection sheet by the four Streetkeepers and Pell during the afternoon — are about to enter an office file where they can be shut. Milo's first pass had Idar point at *Rue's* cut and then claim it as his own; **corrected under CR-016** so that the cut he defends is his own and Rue's remains one of the five. Milo strikes all five out **on his own motion** and heads the sheet *no household routes are recorded in this document, and no person has consented to be entered.* He has no authority to decide, and reasons that a man with no authority has no business publishing a route that belongs to a woman with a pram. The line through them is in his own hand with his name at the foot of the page. This is the batch's clearest instance of a map refusing to be useful, and later batches should build on it rather than contradict it. It also establishes that Streetkeepers write on the official sheet, and that a document can be made weaker on purpose.
7. **The provisional plan is a plan of a handrail, and it is revocable.** Eleven inches by nine, one shift, four consented names with revocable terms, Lena Marr’s tenancy named in full, *one household has declined to be entered* with no name or address, and a deliberately empty right-hand third headed *for people who are not here yet*. It is **not** the neighborhood-scale provisional map of Chapters 41–50 and must not be inflated into one. It is also not a restoration.
8. **Soren Rook is not named in Chapters 1–10, and the hand is not attributed to him.** An earlier draft of Chapter 5 had Ada Fenn name Soren and assert the parentage. That was cut because it collapsed the clue chain, made Ada a delivery device for a fact she should not have, and read the parentage as a surprise, which `bible/characters.md` forbids. **Corrected 2026-09-25 under CR-015:** this entry originally claimed the cut had been applied, and it had not been — the spoken name was still in `chapter-0005.md`, and six state files repeated the claim. The line is now actually cut: Ada interrupts before Milo can say the name and refuses in advance to be handed one. On the page, Soren’s only presence is the bracket-and-dot hand on two confirmed documents plus one recorded as *consistent with, not sworn to*, and the method of a polite young man from Crown Heights who asked Ada what the third bell was for nine years ago and collected her answer. Nothing in Volume 1 may confirm the parentage, the authorship, or the Lark order without evidence established on the page.
9. **Atlas residue frequency.** Two appearances in the batch, both in Chapters 3 and 4, **both on the one night of the 4th**, both incomplete and both limited by Milo in his own notes before he acts. **Corrected 2026-09-25 under CR-015:** this entry originally claimed Chapter 9 has none *and that he notices*, and Chapter 9 contained no Field Book beat at all. The noticed silence is now on the page, written into the pressure moment at five minutes to six, so the claim is true rather than aspiratory. **Corrected again under CR-016:** the beat said *two nights* and *two days* when the two lines are from the same night and the silence runs five days. Later batches should stay at or below this frequency.
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

## CR-015 — Review repair of Batch 0001: the state layer had drifted ahead of the prose

- **Type:** correction
- **Raised by:** `phase-002-batch-plan` review, `logs/phase-002-batch-plan.review.log`
- **Status:** applied

**Why this entry exists.** The independent review of Chapters 1–10 found that the batch's spine held and that the power ledger, the triad accounting, and the planned ending were all intact — but that the **state layer had run ahead of the prose and was asserting edits and beats that had never been applied.** Six state files described a cut that was still in a chapter, a noticed silence that was not on the page, a reading of the third turn that existed only in a summary, and a clue whose stated direction contradicted itself in three files. Everything below is a repair of that gap. No premise, world rule, power rule, antagonist, calendar date, or planned outcome changed.

**Corrections made to the prose.**

1. **The Chapter 1 clue contradicted itself and disagreed with canon.** *(Superseded on the ordering by CR-017 item 1 below: a fold cannot predate the sheet it creases. This entry is kept as the record of what CR-015 did, not as current canon.)* The old-ink mark was described with the fold running *through* the ink and, two sentences later, with the ink lying *across* the crease. `outline/volume-01.md` requires the ink to lie across the fold. The contradictory clause is cut; the paragraph now reads the damp-halo evidence first, then the fold, then the ordering — crease older than the mark, mark older than the stock. Four state files were corrected to the same direction.
2. **Chapter 5 spoke the name Soren Rook.** `outline/volume-01.md` permits the annotating hand to be carried only through records and method, and forbids naming it as Soren without evidence. The spoken name is cut. Ada now comes down the stairs, interrupts before Milo can say it, and refuses in advance to be handed a name — which is a stronger beat than the one it replaces, because it makes her refusal to be used apply to the clue as well as to the route.
3. **The third turn's handover reading was missing from the chapter it belonged to.** `outline/batches/volume-01-batch-0001.md` requires three incompatible readings — clear-the-lane, handover, count — and the Ch8 card assigns the handover to Jo Lask. On the page there was no handover at all: the state files had invented it. Jo's works-bell argument is untouched, but he now also gives the handover with a real memory from the end of a run (the count passes door-to-front at the third call and the tram does not move until it has been handed), Ada dismisses it as a tram, and the chapter's three-account arithmetic still holds. The count reading keeps its two voices, the notice keeps its fourth, and Tomas keeps the works shift interval. **The Chapter 30 reversal still has everything to overturn.**
4. **Chapter 7 carried corrupted text in its climactic beat** — a non-sequitur noun and an italicised imperative addressed to the writer rather than the reader. Both are gone; the three bells are now three bells and the 140 metres fold as intended.
5. **Chapter 10 contradicted itself and the calendar.** The hearing is the 14th; the chapter had "a fortnight" and "in fourteen days" on the 10th. Corrected to four days, in Mara's mouth, twice. Also corrected: the closing count to the 22nd is eight days, not six, and the closing reflection is ten days, not a fortnight.
6. **The crossing count was inflated fourfold, including in Milo's signed report.** He crosses exactly twice in the batch — Chapter 4's lane and Chapter 8's loop. Iona Sen now corrects him in Chapter 8 (same answer, different two: the embankment and the arch stone were sightings), he says "twice" in the Chapter 9 yard, and his signed report records *twice between the fourth of Sazur and the ninth*, which also fixes that report's impossible start date. **This is now canonical and registered in `state/continuity.md`: later batches may add crossings but may not retroactively inflate the batch.**
7. **Continuity drifts bundled with it.** The floodgate test is the 22nd everywhere (Chapter 9 said the 15th, which the lapsing contractor's bond also made impossible); the platform is forty-one metres on both the chain and the drawing; the bell interval is thirty-one seconds throughout; Jo is thirty in both chapters; the Chapter 6 corridor reading runs half past five to six, after the annexes are pulled, not across it.
8. **Two card beats that state files had already credited were added to the page.** Chapter 1's card requires Jo Lask to ask whether the stop is still physically there — he now does, on the stair landing, and reports the nameboard's screws still in the coping. Chapter 9 now has the Field Book beat its state files claimed, written into the pressure moment: he opens the book, it is silent, and what he takes from it is that a book which is silent on the afternoon it is most wanted is a book waiting for something.
9. **Chapter 10's montage became a scene.** Three days summarised as a list of actions — and a third-person retrospective register the book does not otherwise use — is now the Ferry Road pie shop, where a woman Milo cannot name walks him round the corner and tells him not to answer her politely. Nothing is lost: the fourteen corrections and the asking-in-the-route-room were cut, and the "solution or a new problem" beat is kept.
10. **Prose tics were thinned, not removed.** Roughly two-thirds of the batch's full-name paragraph openings were rewritten as pronouns, a time clause, or a varied construction, keeping the remaining third for first appearances and scene-break re-entries. The Chapter 7 field-book block was set as italicised lines instead of the manuscript's only bolded block. Chapter 10's reference to "the first ten days of this" — the novel quoting its own structure — is gone.
11. **The two carbon-copy margin questions moved from Chapter 9 to Chapter 10**, where `outline/volume-01.md` and the Ch10 card both place them. Chapter 9 now ends on Mara stopping at *there's writing on this*, which is a cleaner chapter ending and gives Chapter 10 the pull the discovery was diluting. Chapter 10 carries the full reading, the different leads, and the *consistent with, not sworn to* note.
12. **Chapter 5's two door-checks are now one practice with a stated substitute.** Ada demonstrated a stairwell floor count, which is Lena's reading, while claiming it as the door-check, in the chapter whose whole point is that the readings are incompatible. She now says it plainly: it is the door-check with the doors gone, it is the same work, it is not the same work, and she will not pretend otherwise in front of the woman with the list.

**Second pass (an independent verification read of the repairs).** The first repair pass cleared every blocker but introduced two of its own, and a verification read found both plus a set of pre-existing number slips. All of the following are now fixed.

13. **The moved Chapter 10 carbon scene invented a Chapter 9 event.** Having taken the margin reading out of Chapter 9, the new Chapter 10 text described Milo inspecting the margin at the trestle table on the ninth — which Chapter 9 does not contain. That passage is gone; the thirteenth's reading is now the first and only proper look at the margin.
14. **Chapter 10 treated its own date as future.** The alcove scene was dated the fourteenth, the same day as the hearing, and then had Milo and Mara arguing about *not taking it to the fourteenth*. The reading now happens on **the 13th, the day before the hearing**, which fixes the argument, Mara's *dated, from the day before anybody asked you*, and leaves the fourteenth for the hearing and the terrace. The hearing's outcome is still not staged, as the batch plan requires; the batch-0002 prompt now says so explicitly and tells the next batch to decide and show what happened.
15. **The pre-existing number slips.** The Chapter 1 dwell proof branched into *four seconds over* where the sheet says forty-one against a lawful minimum of forty; the chainage gave three irreconcilable figures (4.2 km, 406 m, 4132 m); the print run was *monthly* in one paragraph and *quarterly* in the next; Chapter 5's door-check counted three floors and then named a man in the fourth, and put the boy with the blanket on the second while he was in the ground-floor kitchen; Chapter 7's Pell reported a bell that had gone *at six* in the early morning, when Chapter 6 has it going at six the previous evening; Chapter 8's Jo had been in the loop for ninety-five minutes against a late-morning rescue, and measured the embankment in feet where the rest of the batch uses metres; Chapter 9's yard had *forty-one* people in it against a headcount nearer eighty; Chapter 10 gave Mara eleven years in an office she joined six years ago; and Chapter 3's *at the age of thirty-one* left the age's owner ambiguous. All corrected. None of them changed a date the calendar depends on.

**Files updated:** `chapters/volume-01/chapter-0001.md`, `chapter-0003.md`, `chapter-0005.md`, `chapter-0006.md`, `chapter-0007.md`, `chapter-0008.md`, `chapter-0009.md`, `chapter-0010.md`, `state/chapter-summaries.md`, `state/batch-summaries.md`, `state/character-state.md`, `state/continuity.md`, `state/open-threads.md`, `state/current.md`, `workspace/volume-01/batch-0002/PROMPT.md`.

**Plot impact:** none. No premise, world rule, power rule, cost onset, antagonist, or planned calendar date moved — the 4th, 5th, 6th, 9th, 10th, 11th, 13th, 14th, 22nd and 28th all stand. The triad accounting (CR-010), the culvert state track (CR-011), and the two-stage orientation cost (CR-012) are untouched. The Chapter 30 reversal is unaffected and better armed, since the handover reading is now on the page with a person attached to it. The Volume 1 ending and the Volume 2 question are unchanged. **No new final enemy, grammar, or faction was introduced.** The batch's spine, pressure rotation, and POV policy are as planned.

---

## CR-016 — Second repair pass on Batch 0001: two blockers and five majors the first pass missed

- **Type:** correction
- **Raised by:** `phase-002-batch-plan`, second independent review of Chapters 1–10, plus a verification read of the repairs
- **Status:** applied

*(This item supersedes CR-015 item 1 on the ordering. CR-015 removed the internal contradiction but left a chronology no physical fold can support; the correct reading is in CR-017 item 1.)*

**Why this entry exists.** CR-015 cleared the drift between the state layer and the prose, but the pass that did it did not itself get a clean read. A second independent pass over the ten chapters, followed by a verification read of the repairs, found two blockers and five majors that survived CR-015, plus a set of state files still carrying the pre-repair figures. All are now fixed. **No premise, world rule, power rule, cost onset, antagonist, or planned calendar date moved.** The 4th, 5th, 6th, 9th, 10th, 11th, 13th, 14th, 22nd and 28th all stand. The CR-010 triad accounting, the CR-011 culvert track, and the CR-012 two-stage orientation cost are untouched. No new final enemy, grammar, or faction was introduced.

**The two blockers.**

1. **Chapter 8 had the trapped man calling the interval from outside the seam.** Chapter 7 assigns the call to Pell on the tram side, and Jo Lask is inside the loop for the whole chapter — but Chapter 8 had *Jo Lask's voice* coming down through the embankment and Pell reporting "Jo's calling it." This also destroyed Jo's arc, which depends on wanting to be the man who counts. The caller is now **Pell** in all three places, with Rue on the ramp observing. The state files had recorded the mistaken version, which is almost certainly where it came from; `state/batch-summaries.md`, `state/chapter-summaries.md` and `state/character-state.md` are corrected.
2. **The crossing point was 62 m and 410 m from the same landmark.** The Chapter 3 Field Book note says *approx 62 m S of disused platform end*; the Chapter 6 sworn disclosure said *approximately four hundred and ten metres from the disused platform end*. A 348 m error in the sworn location of the only crossing in the case, in a document Mara writes down word for word before a hearing. The disclosure now reads **about sixty metres from the disused platform end, on the west face of the hoarding**, matching the Field Book. The apparent contradiction with Chapter 4 is not one: Pell's "you came out the middle… there's no middle" is Milo's own disorientation, which is the point.

**The five majors.**

3. **Chapter 8 carried three mutually exclusive times for one half-hour.** The loop forms at about 7:12 on the 6th, but the chapter also had Jo circling "since half past eight," Owen refusing "an hour and a half," and Iona placing the crossing at ten past nine. Jo now says *since the gate went down*, and the crossing is at **ten past eight**, which still puts the chapter in late morning and still matches the amended timetable proof at 11:40. *(The review that produced CR-017 found the justification originally given here — that Owen's hour and a half "reconciles with Chapter 6, where he came at five" — to be **false**: Chapter 6 is the 5th and Chapter 8 is the 6th, and Chapter 7 has Owen in the service court on the 6th. The figure was therefore not reconcilable and has been removed. See CR-017.)*
4. **Chapter 6's dawn sitting was staged as a hearing it explicitly was not.** It is now named on the page as an *application to vary an order in force, Directions Bench, dawn sitting*, with Mara forcing the distinction in front of the clerk, and Chapter 5 was adjusted to promise a *variation listed for first light* rather than an emergency hearing. Three dates are now separable by the reader: **5th** variation, **9th** inspection, **14th** hearing.
5. **Chapter 6's internal clock was impossible.** Forty minutes of Milo's silence in a sitting that began at ten past five put the deal after the annexes that follow it in the text. The room now fills at five, his silence is fifteen minutes, the annexes are pulled at half past five, and the corridor reading runs half past five until six — with Orrin returning at twenty past six into the dawn. Four numbers, no dialogue changed.
6. **Chapter 7's undelivered card beat, and an expired finding.** The card requires Milo to call the interval; he promised *"Then I'll call it"* and then delegated it, so nobody was ever shown calling it. He now **calls it himself from the arch foot for nine minutes**, from seven until nine minutes past seven, until his voice fails on Danner's come-along — and the handoff to Pell is motivated by the lost voice rather than left as a broken promise. Six people in three trades pacing themselves off his count is the batch's first proof that a route can be kept by people who are not him. Separately, Mara invoked her one-hour finding at 5:40 and arrived at seven, so the instrument had expired before she got there; it is now ten to seven.
7. **Chapter 10 was missing the antagonist.** The card's resistance requires Orrin to argue that Milo's map made the seam more coherent, and he had no presence in the chapter at all. He now intercepts Milo in the corridor and puts the case: the map did not make the seam coherent, it made it **legible**; a believed route is a used route; and on the 22nd it will be standing in the way of a river. He demands Milo say so to the yard *before* the test and not after, and Milo writes the argument down in Orrin's words without editing it. This is the batch's sharpest open problem and it is registered in `state/character-state.md` and `state/continuity.md`.

**De-duplication.** Chapters 8 and 9 had been spending the same beat — the road offers a turn, Milo refuses out loud, he shouts a name to stop a man. Chapter 8 keeps it. **Chapter 9 now has a different danger: the threat is that somebody in the yard will answer.** Milo shouts at Danner and the contractors, two of whom already have a hand up, and Jo closes his doors on his own initiative. The two climaxes now rhyme thematically — both are refusals to author — without repeating a mechanic.

**Continuity and arithmetic.**

8. Chapter 1's "since the twenty-second of Sazur" collided with the 22nd floodgate test; it is now the works order that closed the platform, six years back. The chainage is **4.13 km** throughout, matching the register's 4132 m.
9. Chapter 9's surge is at **five minutes to six** in all three places. The crowd's reaction was always correctly ordered — it answers Milo's explanation, not the pressure — and was left in place. The yard is **eighty** people, not forty, in the two places that counted witnesses; Chapter 7's impossible "a hundred and twenty people" became "the whole morning shift."
10. **Chapter 9 contradicted itself about whose route Idar was protecting.** He pointed at "Rue's cut" and then said "That's my cut." It is now his own cut, which also makes the deletion legible, and Rue's remains one of the five. The four Streetkeepers and Pell, five cuts, is now stated.
11. The signed report recorded "crossed twice **between** the fourth of Sazur and the ninth" — a phrase that is wrong as a range and that carried an impossible start date. It now reads **on the fourth of Sazur and again on the sixth**, and "he had been given a first orientation" became "a first orientation blank had cost him a remembered route."
12. The Chapter 9 Field Book beat claimed two nights and two days; both residues fall on the one night of the 4th and the silence runs five days. The Chapter 10 consented-names list is now four names each with its own terms line, then a fifth entry that is not a name. Pell's exit line no longer collides with Iona's *once a night*. The route to the office, the written line, Pell's chalk and the terrace image now agree.

**Files updated:** `chapters/volume-01/chapter-0001.md`, `chapter-0002.md`, `chapter-0003.md`, `chapter-0004.md`, `chapter-0005.md`, `chapter-0006.md`, `chapter-0007.md`, `chapter-0008.md`, `chapter-0009.md`, `chapter-0010.md`, `state/batch-summaries.md`, `state/chapter-summaries.md`, `state/character-state.md`, `state/continuity.md`, `state/current.md`.

**Plot impact:** none. Every planned outcome of `outline/volume-01.md` is unchanged. The batch's spine, pressure rotation, POV policy, and the Chapter 30 reversal are as planned, and the reversal is better armed, since the handover reading, Tomas's works interval, and Orrin's *legible* argument are all now unambiguously on the page with people attached to them. The Volume 1 ending and the Volume 2 question are unchanged.

---

## CR-017 — Third repair pass on Batch 0001: two blockers the previous passes wrote in as canon

- **Type:** correction
- **Raised by:** `phase-002-batch-plan` review, third independent pass over Chapters 1–10, `logs/batch-0001.review.log`
- **Status:** applied

**Why this entry exists.** CR-015 and CR-016 cleared a real drift between the state layer and the prose, but the third pass found that **both blockers are single passages that the earlier passes created or preserved and then propagated as binding instruction into four or five files each.** No chapter needed re-cutting; four passages needed re-reading, and eleven state-file lines needed rewriting so that batch-0002 does not inherit the errors as instructions. **No premise, world rule, power rule, cost onset, antagonist, or planned calendar date moved.** The 4th, 5th, 6th, 9th, 10th, 11th, 13th, 14th, 22nd and 28th all stand. The CR-010 triad accounting, the CR-011 culvert track, and the CR-012 two-stage orientation cost are untouched. No new final enemy, grammar, or faction was introduced.

**The two blockers.**

1. **Chapter 1's forensic deduction was physically impossible, and had been canonised in five files.** The old-ink deduction asserted `crease > mark > paper` — that the fold was older than the mark and the mark older than the paper. But the crease is a fold *in this sheet*, the diagonal kind made by folding a sheet to fit a wire tray, which is this office's own handling of days ago. A fold cannot be older than the stock it creases. The passage also welded two mutually exclusive branches with *either way*: marked on the folded sheet and unfolded again would make the mark **younger** than the print, not older. This is the volume's central mystery and it failed on page one. **The chapter now keeps only the sound evidence and turns the fold into a mechanism rather than a chronology.** The damp halo is still the load-bearing observation: press stock comes off a press dry and hot and goes into a tray dry, so this sheet was not damp until somebody put the water back into it. The fold says the sheet was *shut* when the mark landed, and a mark bridges a fold rather than sitting in it only when the sheet was shut — and nobody in that building draws on a shut sheet, so the mark was pressed, not drawn. A pressed mark has the tell the halo already was: a nib lays ink down and stops, while ink that was already wet when it arrived keeps going afterwards, out into the fibre, and dries there as a shadow of itself a hair's breadth outside the stroke. **So: not written on this sheet. Pressed onto it, on Tuesday or later — and the press is not the clue. The ink is.** The only sound conclusion, and the one the outline actually requires, is that **the mark was not drawn for this stock and came off something older**, so the ink predates the paper. Milo's Field Book note is *Wet ink, bridged the fold. Pressed on, not drawn here — and not made for this stock. The ink is older than the paper. Tuesday is not.* An intermediate draft of this repair did claim the mark was *older than the sheet it sat on*, which its own Tuesday-to-Thursday window forbids; a verification read caught it and the claim was removed, here and in the six files that had inherited it. `state/continuity.md` (two places), `state/batch-summaries.md`, `state/chapter-summaries.md` and `workspace/volume-01/batch-0002/PROMPT.md` are corrected to the same direction, and the prompt now carries an explicit prohibition: **do not turn the fold into a chronology, and do not assert that a crease predates the paper it creases.** `outline/volume-01.md` required only that the ink predate the paper, which is now true as written, so the outline needed no change.
2. **`chapter-0010.md:147` spent Milo's private loss to buy a favour, in one line.** *My mother used to check that stairwell* broke three things at once. Ada explicitly forbids the equation in Chapter 5 — *it is the same work, it is not the same work* — and the stairwell check is her own practice out of her own laundry court. It put **Neris Rook** in this building, collapsing the Lark/Bellwether separation the batch is built on and undoing Chapter 2:99, Chapter 3:127–131, and Chapter 8:89. And it pre-empted a disclosure the volume is deliberately holding: **Mara has still not been told this district is his mother's erased neighbourhood**, and here he gives a stranger the stronger version first. **The line is gone.** The scene is rebuilt around what the plan of a handrail does not have in it: the door-check, and Ada, who is ill and will not ask. Milo asks Owen to take the third floor off her; Owen agrees in his own words, once a night, going up, not the ground floor, stopping when he likes, unwritten, on condition that Milo tell Ada herself and not the yard, because a rota that goes round the yard would stop her doing it altogether. Owen also refuses to let the plan be called clean, which is the same beat as blocker-adjacent major 3 below. **Nothing in the scene costs Milo his mother, his token, or his district, and nothing is disclosed to a man met three days earlier.**

**The majors.**

3. **Owen Fitch was contradicted across four chapters, and CR-016 had papered one of the contradictions with a false rationale.** Chapter 6's Registry authorisation names `O. Fitch`; Chapter 9 has Mara tell him *you're not on a list… there is no list*; Chapter 8 has him refusing *for an hour and a half* on a day Chapter 7 has him in the service court; Chapter 10's plan drops him without a beat. **The decision taken is the one the review recommended and the better story: Mara did enter him, on the 5th.** The protective finding required *persons in temporary accommodation* and there was no other wording that got him into that yard without initials, so she named him herself — and then told him so, in the Chapter 9 yard, in front of eighty people, with the folded instrument in her hand, and could not take him off it. **His refusal is now made on top of an existing entry rather than instead of one**, which turns the volume's best refusal into a blow and makes Chapter 9 the moment she finds out. He requires the refusal line to carry the initials he is already on, so a reader in twenty years can see he knew he was on the sheet and said no anyway. In Chapter 10 he catches Milo on the claim that the sheet is clean, and Milo concedes it aloud: what the plan holds is nothing, and what the Registry holds is his initials, a chainage, a date, and a finding — which is a set of letters on a works inspection, and not a name. **This is now canonical and registered in `state/continuity.md`, `state/character-state.md`, `state/open-threads.md`, `bible/terminology.md`, and the batch-0002 prompt: do not let a later batch treat his line as an absence from the record.** The four names on the plan are untouched — the fifth line is still a hole, and it is now a hole with his initials sitting beside it.
4. **Chapter 8 had an unflagged fifty-five-minute hole inside one unbroken scene.** Pell goes up with the lamp at 7:09 and Chapter 7 has him promise *an hour*; Rue reported him "four minutes" in, which placed the arch exchange near 7:14; Iona then dated the crossing to 8:10. CR-016's move to 8:10 created the gap rather than closing it. **The hour is now the chapter's clock.** Rue reports that Pell went up at seven and is most of the hour through, the landing scene says they have been up there the better part of an hour since before the water came, and Owen's impossible "an hour and a half" is replaced with **since the water came** — which is exactly what Chapter 7 shows. Pell's hour then expires at the rescue, and he says so, refuses any credit, and goes back to his round: *there is not a single mark in it anywhere and there is not a single bell on that embankment either.* The hour promised in Chapter 7 is now paid on the page.
5. **Five files asserted that Owen had taken Ada's third-floor check; the prose had Milo offering it and Owen never agreeing.** This is CR-015's failure mode recurring, and the review was right that it also buried the volume's second source of witnessing. **Both are now true on the page**: the check is taken, in Owen's words, in the rebuilt Chapter 10 scene, and Ada's illness is on the page in Chapters 9 and 10 rather than in one subordinate clause. `state/open-threads.md`, `state/character-state.md`, `state/chapter-summaries.md`, `state/batch-summaries.md` and the batch-0002 prompt are reconciled, and the prompt now records that the next batch must build a **third** source and must treat Ada's withdrawal as legitimate pressure.

**Minors.**

6. **Chapter 7 gave the same event two lengths.** "The whole 140 metres of the alignment folded" and, two sentences later, "a three-hundred-and-forty-foot section" — about 104 m. The 140 m figure belongs to the longer span in Chapter 3:43, Chapter 7:31 and Chapter 8:257, so the fold now reads **three hundred and forty feet** and 140 m stays the embankment span throughout. The loop is 340 feet everywhere.
7. **Chapter 9's headline stake was ambiguous about whom it meant.** *About two hundred people sleep in a building with a footpath behind it* collided with Cedar Court's forty-one, reinforced by Ada's forty-one notices and Lena's forty-one-name list, and the sentence gave the reader no way to tell. It now says what it means: Cedar Court's forty-one are not who goes first, the water takes the low streets off that court before it reaches a fourth-floor landing, and the **levy** households down there — the same low streets that Chapter 6 has losing a footpath they cannot pay to replace — are holding two hundred and something in temporary rooms with no tenancy file. The stake is larger and now legible.
8. **Two mechanical prose tics were thinned, not removed.** *The whole of X* appeared twenty-five times, eight of them as a stock "that is the complete thing" construction across nine of ten chapters; ten were rewritten or cut, keeping the deliberate Ch8 echo of *the whole of the offer* and every physical and temporal use. *Put his hand flat on X* ran eight times in five chapters; four were replaced with a different gesture, keeping only the Chapter 6 cluster, where Mara's palm on a table is a characterisation and is paid off three lines later.
9. **The narrator was rating the reader's own reactions in six places.** The line the review called strongest is kept as an image and loses its verdict: Ch9's *Milo's chalk was still in his fist and never touched the ground* stays. Cut or rewritten: Ch3 *the part of the night that frightened him*, Ch5 *the single largest thing he had done in two years*, Ch8 *the four seconds were the longest anybody in the room had given him since Tuesday*, Ch9 *which is the only thing he could contribute that afternoon, and which was not enough and was the correct amount*, Ch9 *the thing that was going to cost him the most that day*, Ch9 *the yard took that badly, which was correct*, and Ch10's verdict on Mara's filing, now a corridor action — she reads it back twice to check there is nothing in it she cannot afford to lose.
10. **The low-confidence arithmetic checks the review flagged were checked, and three were wrong.** Milo's career does reconcile against `bible/characters.md` and `state/continuity.md`, both of which fix him at **thirty** — twenty-five in his second year, five years ago, in the office six years, with the route-copying habit older still, from his apprenticeship at nineteen — and Iona now says the arithmetic out loud once, so the reader can hold it. The number she gives was twenty-three, which put him at twenty-eight and contradicted the bible; it is now twenty-five. The same six years is also the interval of the erasure, which is why the batch leans on the phrase so heavily; that double use is now reconciled rather than left to be discovered. **Chapter 3's curve was wrong:** eleven inches of deviation on a ten-metre chord is a radius of about forty-five metres, and a forty-five-metre radius is the radius of a house corner, not of anything a tram was laid on. The chapter now says so, which strengthens the point it was making. **Chapter 5's stray three-in-the-morning stamp is gone**, replaced with a non-numeric reflection, so the scene no longer ends later than the enlargement Chapter 6 dates at half past two.
11. **Four proper nouns that had entered the prose were unregistered.** `bible/terminology.md` now carries a **Minor proper nouns fixed for Volume 01** block: **Verrick** (the pump man on Lena's mother's list, *came back at the third*, alive in the Chapter 9 works yard and silent, and not to be used to confirm the evacuation reading), **Ardin Ossick** (the old surveyor who taught Milo to use his eye, named once, not to return as a conveniently living master), **old Mabb** (asleep on Cedar Court's third floor, the reason Ada goes up), and **Wragg Street** (the sluice from Milo's second year, a real piece of the river core and not an omen). Neris and Soren Rook are registered alongside them with the standing prohibitions attached. The Owen Fitch entry in the same file was also corrected: it claimed a refusal of entry on *any map or list*, and now records the initials, the third-floor check, and the Chapter 30 load-bearing role.

**Verification read of the repair (a fourth, independent pass over the same ten chapters).** Six of the seven areas came back clean — the Chapter 10 rebuild, the whole Owen Fitch cluster including the initials order against Chapter 6, the Chapter 8 clock, the loop and embankment lengths, the Chapter 9 two hundred, and the absence of meta language or duplicated paragraphs. It caught three things this pass had got wrong, and all three are now fixed: the Chapter 1 conclusion discussed above; **Chapter 8's Pell saying *fifty minutes out there* after an hour had elapsed**, now *an hour*; and **Chapter 3's leftover inference that forty-five metres is not a radius a tram was ever laid on**, which overclaims — forty-five metres is a street that has to go somewhere, and the chapter now says that instead. It also surfaced five small drifts now closed: Chapter 7's *first landing* becomes the **top landing** to match *the top step* and *the fourth landing*; Chapter 8's *had not gone into the service court at all* becomes **had not gone back down into the court since the water came**, which is what Chapter 7 shows; Chapter 9's *at a walking pace* becomes *at an ordinary pace*, thinning a phrase that had reached four uses; Chapter 10's duplicate one-line *She put her pen down* is replaced; and Lena's Verrick is now distinguished from the Venn on the notice **in her own mouth**, so a fast reader cannot merge the two surnames. And the **Chapter 0010 batch card itself was stale** — it still said Owen agreed *to nothing else*, and still said Milo could not find his route home until Pell chalked it, which Pell does inside this batch before leaving. `outline/batches/volume-01-batch-0001.md` now carries an **Amendment log — CR-017** recording both, and `state/continuity.md`'s claim that the card is authoritative is true again.

**Files updated:** `chapters/volume-01/chapter-0001.md`, `chapter-0003.md`, `chapter-0004.md`, `chapter-0005.md`, `chapter-0006.md`, `chapter-0007.md`, `chapter-0008.md`, `chapter-0009.md`, `chapter-0010.md`, `bible/terminology.md`, `outline/batches/volume-01-batch-0001.md`, `state/batch-summaries.md`, `state/canon-changes.md`, `state/chapter-summaries.md`, `state/character-state.md`, `state/continuity.md`, `state/current.md`, `state/open-threads.md`, `workspace/volume-01/batch-0002/PROMPT.md`.

**Plot impact:** none. Every planned outcome of `outline/volume-01.md` is unchanged. The batch's spine, pressure rotation, and POV policy are as planned, and the Chapter 30 reversal is **better armed**, not less: the handover reading, Tomas's works shift interval, and Orrin's *legible* argument are all on the page with people attached, and the Chapter 9 change gives the reversal a fifth live contradiction — a man who is on the record refusing while being on the record. The Lark/Neris thread is now *more* protected than before, because the one line that broke its discipline is gone rather than softened. The Volume 1 ending and the Volume 2 question are unchanged.

---

## Open items carried forward

- The phase ledger (`state/phase-ledger.json`) and any completion marker for `phase-000-bootstrap` and `phase-001-outline` are controller-owned. Writers and fixers must not mark a phase `done` or `blocked`.
- `bible/terminology.md` now carries a “Volume 01 local register” for cast and places introduced during volume planning. Later batches must reuse those names, roles, and wants instead of renaming or replacing them.
- An annotating hand is confirmed on two documents: the Chapter 1 timetable’s old-ink margin correction — a wet mark pressed onto a folded, damped sheet, so the ink is older than the paper although the press is not — and the Chapter 6 annex notation. The Chapter 10 carbon copy carries two unsigned marks in *different* inks, so at least one is a different author and Volume 1 does not settle which. The chain is registered in `outline/volume-01.md` and is not resolved in Volume 1. Later batches must carry it and must not name it as Soren without evidence, and must not treat the Chapter 10 pair as a confirmed third instance.

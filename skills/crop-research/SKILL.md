---
name: crop-research
description: Research one crop (the next unresearched row in a category's status table, or a named crop) and record it as a sourced research doc under crops/raw-data/<category>/ plus the matching row in crops/raw-data/<category>-status.md. Use when the user says "research <crop>", "next", "next crop", "continue the crop research", or asks to add/update a crop's write-up or status row. Not for writing crops/game-data/, crops/metadata/, or crops/code/ files - those are later steps in the project's high-level crop plan.
---

# Crop research (raw-data pass)

One crop per run. The target shape is whatever the already-migrated docs in `crops/raw-data/<category>/`
already do (e.g. `crops/raw-data/nut/walnut.md`) - read one before writing. Counts and which rows are
open change over time, so read them from `crops/raw-data/<category>-status.md`, never from memory or
from this file.

## Ground rules

- **This is a research-phase skill, not a data or code pass.** It writes Markdown under
  `crops/raw-data/<category>/` and updates the matching `<category>-status.md` row. It never touches
  `crops/game-data/`, `crops/metadata/`, `crops/help/`, or `crops/code/` - those are later steps in the
  project's high-level crop plan (see the top-level `README.md`'s "Current plans" and, if present locally,
  any private step-plan file - never commit one of those).
- **Model every interesting difference.** The point of this project is to let creators see the real
  variety across crops - including a trait only one crop in the category has - so don't flatten or drop
  something unusual just because nothing else shows it yet. Record it, cite it, and say plainly if it's
  surprising or unexplained (walnut.md's own-rooted-vs-grafted finding is the model for this).
- **Flag every candidate, don't gatekeep.** If research turns up a close relative, cultivar, or alternate
  species that might deserve its own row, don't spend time deciding whether it's "distinct enough" and
  don't silently fold it in as a researched row either. Note it in the current crop's "Naming and scope"
  section (precedent: walnut.md's Black Walnut paragraph) and add it to the status table as `PROPOSED`
  with a short reason and a `Related crops` cross-link back to the researched row - every time, so nothing
  found during research gets overlooked later. A genuinely minor difference (flavor, color, yield only,
  everything else the same) can still just be a cultivar note inside the parent crop's own doc (its
  "Agronomic data" → Cultivars line) instead of a proposed row - use judgment there - but when in doubt,
  propose it. If the user specifically asks for a candidate to be researched now instead of proposed, treat
  it as its own crop and run this skill again for it.
- **Multi-cropID files.** One raw-data file may legitimately cover more than one cropID (a source that
  naturally splits into several cultivar or species groups - precedent: `grape.md` covering
  `grape`/`american_grape`/`muscadine`, `banana.md` covering `banana`/`plantain`/`highland_banana`). When
  that's the right call, give each cropID its own status-table row pointing at the same file name, and
  cross-list them in each other's `Related crops` column.
- **Full citations.** Every sourced claim gets a bracketed number inline (`[3]`), and the Sources section
  at the end accounts for every number used. Match the existing docs' style: group citations by what they
  jointly support rather than one entry per URL when several minor sources back the same sentence, and say
  when a source was only skimmed at search-snippet depth rather than opened. A bare link with no description
  of what it supplied isn't a citation.
- **Honesty conventions.** When something wasn't found, say `Not sourced.` plainly (see walnut.md's
  "Days to first bearing: Not sourced.") rather than guessing or omitting the line. When a figure is
  computed rather than found directly, mark it in the body ("see Estimates, below") and give the full
  arithmetic, its inputs (with their own `[n]`), and a plausible range in the "Estimates and derivations"
  section - a number with no shown reasoning behind it isn't acceptable. When two sources disagree, keep
  both findings visible and say so (walnut.md's Finding 2, California commercial yield vs. permaculture
  planning figures) rather than silently picking one or averaging them away.
- **Don't reference anything outside this project.** Write every doc as if this project is the only place
  this research ever existed - no mention of a source project, an internal module or tool name, a private
  file-path convention, or anyone's personal identity. If a contact is ever actually needed, this project's
  own public one is the only one that belongs here. Sanitization against that standard is handled as a
  separate pass outside this skill - don't try to run it yourself.

## Steps

1. **Pick the crop.** The user names it, or "next" means the next row in
   `crops/raw-data/<category>-status.md` - in table order, same category as the last run if there was one -
   whose Status is `LISTED` or `OUT-OF-DATE`. If every row in that category is already `RESEARCHED` or
   later, or there's no clear "last category," ask which category to continue in.
2. **Orient.** Read, in this order: `crops/README.md` (what each subdirectory is for); the target
   category's `<category>-status.md` (the full current table, not just the one row - it tells you what's
   already covered and what's cross-linked); and the **closest already-researched sibling's raw-data file**,
   read in full, to ground the depth and section structure expected (a close relative in the same family or
   use-category is better grounding than a distant one in the same status column).
3. **Research in parallel.** Good general sources: Wikipedia for orientation; FAOSTAT and USDA FoodData
   Central for yield/composition; PFAF, Purdue NewCROP, university extension services and seed-company
   growing guides for agronomy; postharvest handbooks (USDA Handbook 66, commodity storage sheets) for
   storage/chilling behavior; ethnobotany and traditional-processing papers for uses; FAO-56 ("Crop
   Evapotranspiration") if a real water-use figure is findable; NASA/ESA closed-ecosystem-agriculture
   literature if a controlled-environment angle is findable and interesting. Aim to cover: taxonomy and any
   name conflicts, growing cycle and climate range, yield range and any conflicting figures, composition and
   edibility, pollination, propagation, labor if findable, soil/pH, storage and postharvest handling, named
   cultivars, hazards (toxicity, disease, allelopathy), and every real harvested-product/processing use -
   mirroring the section list in step 4, not a fixed schema to fill mechanically. Also specifically check
   for these recurring-but-easy-to-miss angles, each only worth a line if it actually applies: chill-hours/
   vernalization requirement; photoperiod sensitivity, both for flowering and for tuberization/bulbing/
   rhizome yield itself; frost as a quality event (can improve a crop, e.g. sweetening, as well as damage
   it, not only a hazard); flooded/paddy water requirement as distinct from ordinary irrigation need;
   clonal/viral degeneration risk in vegetatively-propagated crops; salinity tolerance as its own soil
   dimension, separate from pH; elevation as a climate dimension climate-zone language doesn't capture;
   ergot/fungal contamination as a hazard distinct from plant-produced toxins; asynchronous/successive-
   ripening as a harvest-pattern shape distinct from ordinary cut-and-come-again; and invasiveness/
   biosecurity - native vs. introduced range, any invasive-species listing or assessment (national/regional
   lists, the IUCN/ISSG "100 of the world's worst" list, etc.), weedy/volunteer escape behavior, and any
   legal restriction on cultivating, importing, or moving the crop or its propagation material.
4. **Write the doc** to `crops/raw-data/<category>/<crop-id>.md` using the Write tool, from
   `templates/research-doc.md`. Use kebab-case for the filename and lowercase snake_case for the cropID,
   matching the existing files.
5. **Propose a row** for every relative, cultivar group, or alternate species the research surfaced that
   might deserve its own entry (ground rules, above) - note it in "Naming and scope" and add it to the
   status table as `PROPOSED`, unless the user asks for it to be researched now instead.
6. **Update the status table**, `crops/raw-data/<category>-status.md`: set the researched cropID's row to
   `Raw data file name` = the new file's name, `Date of last update` = today, `Status` = `RESEARCHED`
   (this project hasn't reached the follow-on-pass stage yet, so `RESEARCHED` is the right ceiling right
   now, not `PRELIMINARY`/`FOLLOW-ON-*`/`DATA-COMPLETE` - check the top-level project plan if that has
   changed). Add any newly proposed rows from step 5, and cross-link every cropID the file now covers in
   each other's `Related crops` column. If the row being researched is `OUT-OF-DATE`, re-research it against
   *every* bullet in the current `templates/research-doc.md` and the full step 3 checklist, not only the
   angles named in `crops/researchNotes/` - that log only covers checklist changes made since 2026-11-08 and
   can't tell you what an older, pre-migration version of this process may have missed, so treat it as a
   pointer to what's newest, never as the complete list of what to check. Still read `crops/researchNotes/`
   first, since it tells you which angles are newest and most likely to need genuinely new sourcing rather
   than just a quick confirmation that the existing doc already covers them.
7. **Report**: the doc's path, the key findings, what's estimated or left unsourced (and the weakest of
   those), any open questions worth flagging, the status-table rows changed, and the sources used.

## Keeping this skill current

Update it when the status-table column spec, the project's directory layout, or the established doc
structure changes. If a new crop category needs a noticeably different processing/use pattern than what's
covered here, a short example reference inside `templates/` is more useful than expanding this file.

**Checklist versioning.** When step 3's angle checklist or the template's "Agronomic data" bullets gain a
genuinely new, broadly-applicable research angle (not a one-off single-crop curiosity), every row already
`RESEARCHED` under the old checklist is out of date against the new one. Mark every such row `OUT-OF-DATE`
in its status table (not `FOLLOW-ON-*` - that status is reserved for a later, not-yet-reached project
stage) and write a dated entry to `crops/researchNotes/` listing exactly what was added, so that when an
`OUT-OF-DATE` row is re-researched (step 6), it's clear which specific angles are newest and most likely to
need genuinely new sourcing. See `crops/researchNotes/` for the log of past additions.

This log is necessarily incomplete for anything that changed before it existed: many of this project's raw-
data files were migrated from an earlier, outside research process with its own history of changes, none of
which was recorded here. Don't treat an `OUT-OF-DATE` row's absence from `crops/researchNotes/` as proof the
doc already covers everything the current checklist asks for - step 6's full-template check against every
current bullet, not just the logged angles, is what actually closes that gap.

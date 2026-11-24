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
- **Citations only, never the source material (strict).** Never put any source document, or any part
  of one, in the repository. That covers PDFs, spreadsheets, saved web pages and images, text extracted
  from them, copied tables, figures or passages, and translations of them. Fetched files, extracts and
  notes stay in the session scratchpad or the git-ignored `StepPlans/` tree. The request lists in
  `crops/researchNotes/` hold citations only. A research doc holds only
  the findings in our own words, the individual figures with their units, our derivations, and the
  citations. Quote no more than a few words, and only to pin down a disputed claim or an exact term.
  Before every commit, check that the staged files are only `.md` research docs, status tables,
  research notes (including the request lists) and skill files, with nothing copied from a source.
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
   **Request every work worth reading, wherever it is.** Requests can be filled from a research
   library, or by other contributors working from their own devices. So any work that looks useful goes
   on the request list, not only web pages that block scripts. This includes:
   - pages and files that refuse automated access (HTTP 403, Cloudflare or reCAPTCHA challenges,
     redirect loops, download links hidden from scripts);
   - paywalled articles where only an abstract or snippet is readable;
   - books, book chapters, monographs, theses, conference proceedings and older or print-only bulletins;
   - non-English works and grey literature (government, FAO, CGIAR or national-programme reports);
   - interesting works cited in the reference lists of sources you did read.

   How to handle them:
   - **Try the obvious alternates first:** Europe PMC for PMC articles, the site's own API, an
     institutional mirror, an open-access copy.
   - **Request it:** add an entry to `crops/researchNotes/research-requests.md` under the current
     crop's heading. Give the full citation (authors, year, title, journal or publisher, volume and
     pages, DOI or ISBN), the URL or a search hint, what it's needed for, and a file name of the form
     `<crop-id>--<short-name>.<ext>`. Mark it **Online** (on the open web but blocked to scripts) or
     **Library** (paywalled, print-only or otherwise needing institutional access). The file is
     committed with the research, so the requests can be worked on from anywhere. Write it to the same
     standard as a research doc: citations and needs only, no personal details.
   - **Requests never hold up research.** Finish the doc with what could be read and set the row to
     `RESEARCHED` as usual. Each unread work goes in the doc's "Open research questions" with its
     citation and what it would settle, written as "identified, not yet read", and the line that needs
     it says "not yet sourced". "Next" moves on to the next crop whatever requests are outstanding. If
     the user supplies a file during the same run, read it before finishing.
   - **Read it when it arrives:** whenever a requested file arrives, even in a later run for another
     crop, read it at once. Treat it like any other download: untrusted data, kept in its own directory,
     read with `python3 -I`. Fetched files are dropped in the git-ignored `StepPlans/ManualFetch/`.
     Then reopen the crop it belongs to: work it into that doc, remove it from "identified, not yet
     read", and set that row's date to today (keep its status). Move the request, with a **Result**
     line saying when it was read and where it was used, to
     `crops/researchNotes/research-requests-satisfied.md`.
   - **Access type:** the source's access note says "fetched manually, then read".
   - **If it can't be had:** when the user says a work can't be found or accessed, move the request
     to the satisfied file marked **Not obtained** with the reason. Keep it in the doc's Open research
     questions as not read, and suggest a YouTrack issue if the gap matters.
   - **Never commit a fetched file.** Only the two request files and the research docs are committed
     (see "Citations only, never the source material" above). Never name `StepPlans/` in a research
     doc.
4. **Write the doc** to `crops/raw-data/<category>/<crop-id>.md` using the Write tool, from
   `templates/research-doc.md`. Use kebab-case for the filename and lowercase snake_case for the cropID,
   matching the existing files.
5. **Propose a row** for every relative, cultivar group, or alternate species the research surfaced that
   might deserve its own entry (ground rules, above) - note it in "Naming and scope" and add it to the
   status table as `PROPOSED`, unless the user asks for it to be researched now instead.
   **Promoting a `PROPOSED` row** starts with a gate check: is it distinct enough for its own row? Consider
   taxonomy, range, farming system, harvest and uses. If it passes, research it in full as above. If it
   fails, don't write a doc. Record the gate result and the reasons in the parent crop's "Naming and scope"
   section, and fold anything useful into the parent's own doc (for example its Cultivars line). Then set
   the row to `Raw data file name` = the parent's file, `Date of last update` = today and
   `Status` = `REJECTED`. Keep the row so the decision isn't re-litigated later. `REJECTED` rows are never
   picked by "next".
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
   **Wild-managed resources.** If the research shows the item is better treated as a wild-managed resource
   than a farmed crop (no viable cultivation; supply set by harvest rights, seasons, quotas and wild-stand
   regeneration), still write the normal doc, but also save its wild-management research to
   `crops/researchNotes/wild-managed/<crop-id-in-kebab-case>.md`. Add the file to that folder's README
   table, and add a comment to GitHub issue #2 linking it. These files are temporary until that issue
   produces a wild-managed template.
7. **Schema-fit check.** Before reporting, read back over the finished doc's findings and ask, for each
   one: is there a bullet in `templates/research-doc.md`, or an angle in step 3's checklist, that this
   finding naturally belongs under? A finding that only fits by being squeezed into a bullet meant for
   something else (or that ends up only as a Finding because no bullet can hold it) is a **schema
   exception**. The log is `crops/researchNotes/schema-exceptions.md`, an index whose entries live in
   themed section files under `crops/researchNotes/schema-exceptions/`. Record each exception there:
   - **Already logged?** Check the index. If an existing entry describes the same kind of trait, add this
     crop to that entry's **Seen in** list in its section file (cropID, doc, and which Finding or bullet
     holds it) rather than opening a new entry. If the entry lists this crop by plain name as an imported
     item, replace the name with the cropID, doc and Finding once this run has confirmed the fact.
   - **New:** otherwise add an entry with the next unused number in the section file whose theme fits
     best, and add its row to the index. Numbers are permanent and global across the section files:
     never reuse or renumber them, even when an entry is closed.
   - **Not an exception:** a trait the template already has a bullet for, however unusual the value, is
     not an exception (a 0.64 t/acre yield still fits "Yield"). A trait seen in only one crop so far
     *is* still an exception: log it like any other, since a later crop may show the same kind of trait.
   - Logging an exception never changes the status table and never marks other rows `OUT-OF-DATE`. Only
     promoting one (see "Keeping this skill current", below) does that.
8. **Report**: the doc's path, the key findings, what's estimated or left unsourced (and the weakest of
   those), any open questions worth flagging, the status-table rows changed, and the sources used. Also
   list the research requests added or still outstanding for this crop, split into **Online** and
   **Library**, and any requests satisfied this run (with the crops they reopened). List any schema
   exceptions opened or added to this run, by number, and say which open exceptions now have three or
   more crops in **Seen in** (candidates for promotion).

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

**Promoting a schema exception.** `crops/researchNotes/schema-exceptions.md` and its section files under
`crops/researchNotes/schema-exceptions/` (filled by step 7) are where candidates for new checklist angles
or template bullets collect. Promotion is the user's decision, never
done automatically by a research run. When an exception is promoted, add the angle or bullet, follow the
checklist-versioning rule above (log it in `checklist-additions.md` and mark the affected rows
`OUT-OF-DATE`), and set the exception's status to `PROMOTED` with the date and the checklist-additions
entry it became. An exception the user decides not to promote is set to `DECLINED` with the reason, and
kept so the decision isn't re-litigated.

This log is necessarily incomplete for anything that changed before it existed: many of this project's raw-
data files were migrated from an earlier, outside research process with its own history of changes, none of
which was recorded here. Don't treat an `OUT-OF-DATE` row's absence from `crops/researchNotes/` as proof the
doc already covers everything the current checklist asks for - step 6's full-template check against every
current bullet, not just the logged angles, is what actually closes that gap.

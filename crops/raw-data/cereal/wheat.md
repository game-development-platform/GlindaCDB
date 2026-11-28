# Wheat (*Triticum* spp.)

**Category:** Cereal · **Path:** `crops/raw-data/cereal/wheat.md`
**Researched:** 2026-11-28

This file is original research synthesis, compiled from the public sources
listed at the end of the document, with citations tracking each sourced
claim. The sources retain their own copyright/license; this synthesis is
licensed under this project's MIT license (see repository `LICENSE`).

## Naming and scope

This is the **genus-level `wheat` row** for *Triticum* spp. (Poaceae), the
umbrella doc for the whole wheat group. Its figures are given for **common
(bread) wheat, *Triticum aestivum*, as the dominant representative** — bread wheat
is **~95% of the world crop** and durum **~5%**, the rest minor [7]. The
individual species have their own rows and carry the species-specific detail
(hulled processing, flavour, niche agronomy); this doc cross-links them and gives
the shared biology:

- **`wheat_bread`** *T. aestivum* — hexaploid, free-threshing, the main crop [7].
- **`wheat_durum`** / **`wheat_durum_spring`** *T. durum* — tetraploid, free-
  threshing, hard; pasta/semolina [3][7].
- **`wheat_einkorn`** *T. monococcum* — diploid, **hulled** [7].
- **`wheat_emmer`** *T. dicoccum* — tetraploid, **hulled** [7].
- **`wheat_spelt`** *T. spelta* — hexaploid, **hulled** [7].
- **`wheat_khorasan`** *T. turanicum* — tetraploid [7].
- **`wheat_club`** *T. compactum* — hexaploid, compact-eared, soft [7].

**Related crops considered, not covered here:** **`triticale`** (×*Triticosecale*,
a wheat × rye amphiploid) and **`rye`**, **`barley`**, **`kernza`** all have their
own cereal rows; wheat's wild relatives (*Aegilops*, incl. the D-genome donor
*Ae. tauschii*, and the noxious weed jointed goatgrass *Ae. cylindrica*) are
discussed under Invasiveness, not given rows [7]. No new rows are proposed from
this pass — the species split is already fully represented in the status table.

## Research findings

**Finding 1 — the winter/spring divide: vernalization and photoperiod set the
whole calendar.** Wheat splits into **winter types**, which need a prolonged
**cold period (vernalization) to flower**, and **spring types**, which do not;
winter wheats are further graded weak / semi / strong by how much cold they
need [2]. The requirement is genetic: the **VRN1, VRN2 and VRN3** loci control it
(dominant *VRN1* gives the spring habit; winter wheat carries the recessive
alleles), while **PPD-1** loci (chromosomes 2A/2B/2D) set **photoperiod**
response once vernalization is satisfied — wheat is broadly a **long-day** plant
[2]. This single gene system decides the agronomy: winter wheat is autumn-sown
and over-winters for a summer harvest (higher-yielding, needs cold but risks
winterkill), spring wheat is sown in spring where winters are too harsh, and
photoperiod-insensitive alleles let the crop move to low latitudes [2].

**Finding 2 — an allopolyploid series is why there are eight wheat rows.** Wheat
is a textbook **ploidy series** built by hybridisation: **diploid einkorn**
(genome AᵐAᵐ, domesticated from wild *T. boeoticum*) → **tetraploid emmer/durum**
(BBAA / AABB, A from *T. urartu*) → **hexaploid bread wheat** (**AABBDD**), formed
when tetraploid wheat crossed with *Aegilops tauschii* to add the **D genome** —
two rounds of allopolyploidisation [7]. The added genomes are what make bread
wheat's dough and adaptability, and the series is the backbone of the species
rows above [7].

**Finding 3 — hulled vs free-threshing: a domestication trait that still decides
processing.** The first domesticated wheats (**einkorn, emmer**) and **spelt**
are **hulled** — the glumes clasp the grain and the ear does not shatter, so
threshing yields intact spikelets that need a **separate dehulling step** before
milling [7]. **Free-threshing** forms (the ancestors of **durum** and **bread
wheat**) arose later (~8,000-10,000 years ago) and release clean grain on
threshing, which is a large part of why they displaced the hulled wheats as the
staple [7]. This is the practical reason the hulled "ancient grains" are handled
differently from modern wheat (detail in their own rows).

**Finding 4 — grain hardness and gluten set the end-use class.** What a wheat is
*for* is set by two structural grain traits, not just by its composition:
**gluten** (the *gliadin* + *glutenin* protein complex, unique in forming an
elastic dough) and **grain hardness** [3][9]. The FAO classes wheat by protein
(water-free): **soft < 13.4%, hard > 15.0%** [3]; hard red winter runs ~12.6 g
protein/100 g vs soft red winter ~10.4 g [3]. **Hard, high-protein, strong-gluten
durum → semolina → pasta**; **hard bread wheats → bread flour**; **soft, weak-
gluten wheats (incl. club) → cake/pastry/biscuit flour** [3][7]. A structural
trait, not the headline composition, decides the product — logged as a schema
exception (Entry 52) [3].

**Finding 5 — self-pollinating, which shaped its whole breeding history.** Wheat
is predominantly **self-pollinated**: fertilisation usually happens **before the
floret opens**, so natural **outcrossing is low — ~0.1-5.6% across bread-wheat
cultivars** (up to ~10% in some experimental populations) [8]. That biology makes
**hybrid wheat** far harder to exploit than hybrid maize (there is no easy way to
force cross-pollination), so improvement has run through **pure-line varieties**;
the landmark gains came from the **Green Revolution semidwarf** wheats carrying
the **Rht (Norin 10) reduced-height genes**, which let the crop take heavy
nitrogen without lodging [8]. It also means small **isolation distances (≈3-30 m)**
keep seed pure, though rare long-distance pollen flow is recorded [8].

**Finding 6 — yield spans an order of magnitude, and the headline figures
conflict by system.** The **world average is ~3.6 t/ha** on ~220 Mha for ~790-800
Mt/yr, but this hides enormous spread: **intensive maritime-temperate systems**
reach **~9+ t/ha** (Scotland's 2023 national average was 9.2 t/ha), while
**rainfed semi-arid** systems sit near **~1.3 t/ha** (Algeria) [1]. Note that
**FAOSTAT's yield is derived** (production ÷ harvested area for dry grain), not
independently measured, so regional figures should be read as management-and-
climate outcomes rather than varietal ceilings [1].

**Finding 7 — the hazard profile is dominated by fungal toxins and gluten
disorders.** Wheat's distinctive hazards are not the plant's own chemistry but
**fungal contaminants** and **immune responses to gluten** (details in Hazards):
**ergot** (*Claviceps purpurea*) and **Fusarium head blight** deoxynivalenol
(DON) are both **regulated** (EU DON limits 1,250 ppb unprocessed common wheat,
1,750 durum, down to 500 in finished products), and **~1% of people have coeliac
disease** [5][9]. On top of these sit the **rust** diseases — stem rust **Ug99**
is a live global biosecurity threat that has overcome 17 of 34 known resistance
genes and can cut yield up to 90% [6].

## Agronomic data

- **Life form / season:** Annual grass; **winter** (autumn-sown, over-wintered) or
  **spring** (spring-sown) habit (Finding 1) [2].
- **Harvest pattern:** **Single annual harvest** at grain maturity; ripening is
  uniform within a crop (not asynchronous), combine-harvested [1][7].
- **Days/years to first bearing:** Grown to maturity in **one season** — roughly
  ~4-5 months (spring) to ~8-10 months including over-wintering (winter); a
  precise days-to-maturity range was **Not sourced** here [2].
- **Climate zones:** Temperate the core; grown from cool-temperate to subtropical
  and to **high elevation** (Andes/Tibet). **Vernalization** required for winter
  types; spring types have none (Finding 1) [2].
- **Composition:** Whole-grain wheat flour per 100 g ≈ **340 kcal, 72 g
  carbohydrate, 13.2 g protein, 10.7 g fibre, 2.5 g fat, 0.4 g sugar** (one
  USDA-derived set; a UK wholemeal set is lower at ~327 kcal / 12 g protein / 10 g
  fibre, reflecting flour type and method) [3]. Protein varies by class (soft
  ~10% to hard >15%, water-free) (Finding 4) [3].
- **Edibility:** **Not raw-palatable** as grain — milled to flour and **cooked**
  (bread, pasta, noodles, porridge); hulled wheats **dehulled** first (Finding 3)
  [7].
- **Pollination:** **Self-pollinating** (cleistogamous-leaning; fertilisation
  before floret opening); outcrossing ~0.1-5.6% (Finding 5) [8].
- **Photoperiod sensitivity:** **Long-day** for flowering, via PPD-1; photoperiod-
  insensitive alleles enable low-latitude culture (Finding 1). Not a tuber/bulb
  crop, so no yield-organ photoperiod effect [2].
- **Yield:** **World avg ~3.6 t/ha**; intensive ~9+ t/ha; rainfed ~1.3 t/ha;
  figures conflict by system and FAOSTAT yield is derived (Finding 6) [1].
- **Water use:** **~450-650 mm** maximum crop evapotranspiration for high yields
  (FAO); a semi-arid Ethiopian lysimeter measured ~427 mm. **Kc** by stage ≈
  0.3-0.4 (initial), 1.05-1.2 (mid-season), 0.2-0.25 (harvest) [4].
- **Propagation:** **Seed** (true-breeding pure-line varieties); no vegetative
  propagation, so no clonal/viral-degeneration route — but seed-borne diseases
  (bunt, loose smut) and virus (wheat streak mosaic, BYDV) are managed by clean/
  treated seed and resistant varieties [6][8]. Hybrid wheat exists but is minor
  (Finding 5) [8].
- **Labor:** Fully mechanised in commercial systems (sow-spray-combine); no
  labour-hour figure sourced. **Not sourced.**
- **Soil:** Prefers **pH ~6.0-7.5**, well-drained loams; **moderately salt-
  tolerant** — threshold **ECe ~6 dS/m** for 0% loss, **~13 dS/m** for 50% loss,
  **~20 dS/m** for total loss, but **ECe ≤4 dS/m** wanted at germination (salinity
  as its own dimension) [4].
- **Storage (postharvest):** **Dry grain**, stored at **≤13-14% moisture** keeps
  for years; main risks are **storage insects** (weevils, grain borers), **storage
  fungi** and **moisture/heating**, plus field-acquired **mycotoxins** carried into
  store (Finding 7) [5]. Specific shelf-life figures Not sourced here.
- **Establishment:** **Drilled** in rows at high seed rates as a dense stand; no
  nursery/transplant stage [1].
- **Cultivars:** Thousands, grouped by **season × hardness × grain colour** (e.g.
  hard red winter, soft red winter, hard red spring, soft white, durum) and by
  **semidwarf Rht** background (Green Revolution) [3][8]. Species-level cultivars
  live in the species rows.
- **Weather response:** **Winterkill** risk for autumn-sown winter wheat; **late-
  spring frost at flowering** causes sterility; **heat and drought at grain-fill**
  cut yield and shrivel grain. Frost is a **hazard here, not a quality-improving
  event** [2]. Dose-response figures Not sourced.
- **Water regime:** **Ordinary rainfed/irrigated** — not a flooded/paddy crop
  (unlike `rice`) [4].
- **Harvest stages / windows:** **Single stage/window** at grain maturity;
  uniform ripening (not successive) [1][7].
- **Soil biology:** Non-mycorrhizal-dependent cereal in rotation; **volunteer
  wheat** acts as a disease "green bridge" (see Invasiveness). Allelopathy/replant
  specifics Not sourced.
- **Invasiveness / biosecurity:** Wheat itself is **not a serious invasive**, but
  (i) **volunteer/feral wheat** bridges pests and diseases between seasons; (ii)
  its wild relative **jointed goatgrass (*Aegilops cylindrica*)** is a listed
  **noxious weed** that can **hybridise with wheat**; and (iii) the crop is a
  **major biosecurity target** — **Ug99 stem rust** is kept out of several
  countries by import rules on grain, plant material and machinery, with wind
  arrival also a concern [6]. (Karnal bunt and wheat blast quarantines noted but
  **not sourced** this pass.)
- **Controlled environment:** A long-day self-pollinating annual grass; grown
  experimentally in growth chambers and a candidate for closed/space agriculture
  (dwarf wheat lines have been studied for life-support systems), but no specific
  trial figure sourced here. **Not sourced.**

## Hazards

- **Ergot (*Claviceps purpurea*).** A fungus that replaces grains with alkaloid-
  rich sclerotia; **yield loss is small but the alkaloids are toxic** to people and
  livestock, and are **regulated** (EU limits on ergot alkaloids in processed
  cereal products since January 2022). Managed by cleaning, rotation and resistant
  husbandry [5].
- **Fusarium head blight / DON.** *Fusarium graminearum*/*culmorum* infect the
  head in wet flowering weather and produce **deoxynivalenol (DON/vomitoxin)** and
  related mycotoxins; **EU limits: 1,250 ppb unprocessed common wheat, 1,750 ppb
  durum, 750 ppb flour, 500 ppb finished products**, and one estimate puts ~20% of
  global crops over EU limits [5].
- **Gluten-related disorders (human).** **Coeliac disease** affects **~1% of
  people** (an autoimmune reaction to **gliadin/glutenin**); **wheat allergy**
  (to gluten *and* non-gluten proteins such as α-amylase inhibitors) affects up to
  ~1%; **non-coeliac gluten/wheat sensitivity** is reported but poorly defined
  (claims of ~6% likely fall with stricter criteria). Gluten also occurs in rye
  and barley [9].
- **Rusts and other diseases.** **Stem rust (incl. Ug99)**, stripe and leaf rust
  are the major yield threats; **Ug99** has overcome 17 of 34 resistance genes and
  can cut yield up to 90%, with ~30% of current varieties moderately-to-highly
  susceptible (Finding 7; see Invasiveness) [6].

## Uses and processing

- **Chain (grain → flour → food):** grain → **milled** (bran/germ/endosperm
  separated for white flour, or whole-milled) → **flour/semolina** → baked
  (bread), extruded (pasta), made into noodles, bulgur, couscous, porridge,
  breakfast cereal; **bran and germ** are byproducts (germ pressed for **wheat-germ
  oil**) [3][7].
- **Chain (hulled wheats):** spikelets → **dehulled** → grain → as above (extra
  step vs free-threshing wheat) (Finding 3) [7].
- **Chain (whole grain / malt / other):** grain → **malted**, **fermented**
  (beer, spirits, vinegar, soy/wheat sauces), or boiled whole; **gluten** is
  extracted as **vital wheat gluten/seitan**; **starch** is separated industrially
  [7].
- **Chain (straw):** the **straw** is a major co-product — bedding, fodder,
  thatch, mushroom substrate, biomass [7].
- **Not otherwise detailed here:** quantitative milling-yield fractions, malting
  specifications, and industrial starch/gluten yields were not chased down this
  pass.

## Open research questions

- **Durum-specific composition** (clean per-100 g breakdown) was not reliably
  sourced [3].
- **Days-to-maturity** ranges for winter vs spring types were not pinned to a
  source [2].
- **Karnal bunt and wheat blast** quarantine status and spread were **identified,
  not yet sourced** this pass [6].
- **Milling-yield fractions, labour-hours, and storage shelf-life** figures were
  not sourced [1][5].
- **Hybrid-wheat seed-production** methods (chemical hybridising agents, CMS) were
  identified as relevant but not sourced [8].
- **Controlled-environment/space-agriculture** dwarf-wheat trial figures were not
  sourced this pass.
- **FAOSTAT's exact 2023 world area/yield** were read only from secondary
  summaries, not the FAOSTAT table itself [1].

## Estimates and derivations

No independent numeric estimate was computed in this pass — all figures above are
sourced ranges, with their conflicts shown rather than averaged (Finding 6). If a
single "typical" yield is needed downstream, the **world average ~3.6 t/ha** [1]
is the right central figure, with the intensive (~9 t/ha) and rainfed (~1.3 t/ha)
ends as the documented spread.

## Sources

[1] Production, area and yield summaries: Our World in Data / FAO wheat production
pages, USDA FAS circulars, an IndexBox 2023 market summary, a national Scottish
2023 harvest estimate, and a USDA Algeria figure. Supplied: world ~790-800 Mt on
~220 Mha at ~3.6 t/ha average; intensive (~9.2 t/ha Scotland) vs rainfed (~1.3
t/ha Algeria); and the FAOSTAT note that cereal yield is derived from production
÷ harvested dry-grain area. Accessed 2026-11-28, search snippets only; the
FAOSTAT 2023 table itself was not opened.

[2] Vernalization and photoperiod literature (a Springer wheat-genetics chapter
and several PMC review articles). Supplied: the winter/spring (weak/semi/strong)
split; the VRN1/VRN2/VRN3 control of vernalization (dominant VRN1 = spring
habit); PPD-1 photoperiod loci on 2A/2B/2D; wheat as a long-day plant; and the
latitude/allele interaction. Accessed 2026-11-28, search snippets/abstracts only.

[3] Composition and grain-class sources (a PMC composition table, AgClassroom and
patient.info flour figures, and FAO grain-classification material). Supplied: the
whole-wheat per-100 g figures (and the UK wholemeal variant); the hard-vs-soft
protein gap; and the FAO soft < 13.4% / hard > 15.0% protein classification.
Accessed 2026-11-28, search snippets only; no clean durum breakdown found.

[4] Water-use and salinity sources: the FAO wheat crop-information page and FAO-56
material, plus a 2024 Ethiopian drainage-lysimeter study. Supplied: 450-650 mm
maximum ETc; stage Kc values (0.3-0.4 / 1.05-1.2 / 0.2-0.25); the ~427 mm
lysimeter measurement; and the salinity classification (moderately tolerant; ECe
≤4 at germination; ~0% loss at 6, ~50% at 13, ~100% at 20 dS/m). Accessed
2026-11-28, search snippets only.

[5] Fungal-toxin and regulatory sources (UK Flour Millers, AHDB, a CONICET
mycotoxin review, EU-limit compilations). Supplied: ergot (*Claviceps purpurea*)
as a toxic-alkaloid contaminant with small yield loss and EU limits from January
2022; Fusarium head blight DON chemistry; the EU DON limits (1,250 / 1,750 / 750 /
500 ppb) and the ~20%-of-global-crops-over-limit estimate. Accessed 2026-11-28,
search snippets only.

[6] Disease and biosecurity sources (New Zealand MPI and Australian government
Ug99 pages, plus an FAO rust document). Supplied: Ug99 origin (Uganda 1999),
its defeat of 17 of 34 resistance genes, spread since 2007 (Yemen/Iran), up-to-90%
yield loss and ~30% susceptible varieties, and the grain/machinery/wind pathways;
plus the jointed-goatgrass and volunteer-wheat context. Accessed 2026-11-28,
search snippets only; Karnal bunt and wheat blast were not sourced.

[7] Taxonomy, ploidy and domestication sources (PMC and Springer wheat-evolution
chapters/articles). Supplied: the diploid einkorn → tetraploid emmer/durum →
hexaploid bread-wheat ploidy series and genome donors (A from *T. urartu*, D from
*Aegilops tauschii*, AABBDD); the hulled-vs-free-threshing domestication
sequence; and the ~95% bread / ~5% durum share. Accessed 2026-11-28, search
snippets/abstracts only; sources differ on the exact bread-wheat origin pathway.

[8] Pollination and breeding sources (outcrossing/isolation studies via HAL/CORE/
CSIRO and the Norin 10 / Green Revolution literature). Supplied: wheat's
predominant self-pollination (fertilisation before floret opening), outcrossing
~0.1-5.6% (to ~10% experimental), isolation distances ~3-30 m; and the Norin 10
semidwarf (Rht1/Rht2) basis of the Green Revolution. Accessed 2026-11-28, search
snippets only; hybrid-wheat seed-production methods were not sourced.

[9] Gluten-disorder clinical literature (PubMed/PMC reviews). Supplied: coeliac
disease ~1% prevalence (gliadin/glutenin trigger); wheat allergy up to ~1% (gluten
and α-amylase-inhibitor proteins); the uncertain non-coeliac gluten/wheat
sensitivity estimates; and gluten's presence in rye and barley. Accessed
2026-11-28, search snippets/abstracts only.

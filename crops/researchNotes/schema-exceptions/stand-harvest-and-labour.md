# Schema exceptions: stand life, harvest and field work

Part of the schema exceptions log. Rules, statuses and the full index are in
[`../schema-exceptions.md`](../schema-exceptions.md).

Entries marked "imported" came from earlier private notes kept before this log existed. Their **Seen in**
lists name crops, not checked Glinda docs: the facts have not yet been re-checked against the crop's
Glinda doc, and some of those crops have no Glinda doc yet. When a research run confirms one, replace the
plain name with the cropID, doc and Finding.

## 28 — Stand life, age-yield curve and replanting

- **Status:** OPEN (imported 2026-11-24; first Glinda doc added the same day).
- **What doesn't fit:** "Life form / season" and "Days/years to first bearing" stop at first bearing.
  Nothing records how yield ramps up with age, when it peaks and declines, the economic replant point
  (often far shorter than the biological life), disease-limited stand life, how the stand renews itself,
  or field operations done only once per stand.
- **Seen in:**
  - `peach_low_chill` (`peach-low-chill.md`, Life form / season and Days/years to first bearing): the
    Florida budget assumes first fruit in year 2, full yield from year 4, a 15-year horizon and 5% of
    trees dying and being replaced every year.
  - `pear` (`pear.md`, Days/years to first bearing and Life form / season): commercial yield from year
    3-4, rising to full production in year 8 (10, 20, 30, 35, 45-50 bins/acre), then 25 productive years;
    perry trees take a decade or more to bear and can stay fully productive for 250 years.
  - `pear_low_chill` (`pear-low-chill.md`, Finding 3): first significant crop in the 4th season, then
    2.5-9.9 lb/tree until a jump to 149-194 lb/tree in the 7th (Mississippi).
  - `purple_passionfruit` / `yellow_passionfruit` (`passionfruit.md`, Finding 4 and Stand life):
    plantings are replanted every 2-4 years, driven by disease (collar rot forces yellow replanting every
    30-35 months in Fiji) more than by the plant's own life; the purple runs about 4 years.
  - `red_currant` (`red-currant.md`, Finding 5 and Yield): *Eutypa lata* canker in the Netherlands is
    reported to cut plantation life from about 15 years to under 10, with the historical 15-20 t/ha yield
    no longer reliably reached; first fruit in year 2, peak by about year 5.
  - Imported: asparagus (no harvest in year 1, light in year 2, full from year 3; cutting in year 1 cost
    23% of the five-year yield; Fusarium decline at 8-20 years); sweet cherry (full at year 6, about 25
    years); plum (0.23 / 0.38 / 0.76 / 1.0 of full yield in years 4-7); mangosteen (6-20 years to bear);
    orange (20-year economic cycle vs centuries-old trees); blackberry (15-20 years commercial vs about
    6); black raspberry (virus limits stands to 2-3 years); mountain papaya (peaks in years
    4-5, 7-8-year cycle); babaco (26-month rotation); yellow pitaya (10-year cycle); pineapple (ratoon
    crop about 0.53 of the plant crop); raspberry and blackberry (canes in age cohorts); dwarf sour
    cherry (regrows from suckers, so the stand doesn't age out); lingonberry (20-year beds); cranberry
    (century-old beds); seed lotus (three-year stand peaking in year 2); arrowroot (dug yearly for 5-6
    years); nutmeg (7-9 years to bear, peak at 35-40); coconut (6-10 years to bear, 60-100-year life);
    Kernza (land preparation and planting recur only once per stand); Texas and American persimmon
    (re-sprout from the root crown after fire).
- **Possible home:** a "Stand life" bullet: juvenile years, yield by age, peak, decline, economic replant
  point, what limits it, and establishment-only operations.

## 29 — Perennial grown as an annual, or annual-type crop that is perennial

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** "Life form / season" takes one value. Many crops are perennial in biology but
  grown as annuals, perennial only in warm climates, or herbaceous perennials harvested like an annual
  crop, and the choice changes the harvest pattern.
- **Seen in (imported):** scarlet runner bean, eggplant, pepper (perennial where frost-free); pigeon pea
  and hyacinth bean (perennial shrubs grown as annuals); lotus, taro, yam, arrowroot, scorzonera,
  horseradish, edible canna, tacca (perennials dug as annuals); Kernza (perennial grain); asparagus and
  wild rocket (herbaceous perennials cut like annual greens); maypop (top dies back each year); cornmint
  (moved from perennial to annual culture to cut cost).
- **Possible home:** let "Life form / season" carry the biological habit and the grown habit separately,
  with the climate that decides it.

## 30 — Crop held on the plant or in the ground past maturity

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** "Harvest stages / windows" says when a crop is ready. It doesn't record how long a
  ripe crop can stay unharvested, using the field as the store, and what changes or is lost meanwhile.
- **Seen in:**
  - `red_currant` (`red-currant.md`, Finding 4): most ripe currants hold on the bush for up to several
    weeks without falling or over-ripening, so the field doubles as the store across a two-week-plus
    window; one commercial supplier disputes this, advising immediate harvest as flavour fades.
  - Imported: cassava (lifted any time from 6 to 24 months, starch rising with age); swiss
    chard (a 150-day picking window); Jerusalem artichoke, parsnip, salsify, celeriac (dug through winter;
    salsify loses roots to rodents); tatsoi and savoy (cut through winter); lotus root (dug to order October
    to March); Chinese water chestnut (sweeter but shorter-keeping after overwintering in the ground);
    cocoyam (cormels sprout and go watery in wet ground); konjac (field overwintering under polythene as an
    alternative to lifting); coontie (starch 20% in winter vs 8% in summer); avocado (never ripens on the
    tree, so fruit is stored there for months); grapefruit (late harvest lowers the next crop, see entry 1).
- **Possible home:** a "Field holding" line under "Harvest stages / windows" (maximum days, quality
  change, losses).

## 31 — Production in several phases, seasons or places

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** the template assumes one sowing leads to one harvest in one place. Some crops
  pass through separate phases: lifted and replanted for several seasons, grown in a field and then
  forced indoors, or replanted from selected roots to make seed.
- **Seen in (imported):** konjac (the same stock is dug, cured, stored and replanted for 3 (2-5)
  seasons); porang; witloof chicory (field roots then forced in the dark); maca, ahipa, jicama, salsify
  (selected roots replanted for seed); chuin (the root top replanted after harvest flowers and seeds but
  forms no new root); lowbush blueberry (prune year then crop year).
- **Possible home:** a "Production cycle" line: phases, where each happens, and its length.

## 32 — Harvests on one plant that compete or exclude each other

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** "Uses and processing" lists every harvested organ, and "Harvest stages" lists
  maturity stages, but neither records that taking one product reduces or prevents another, or that the
  target product changes how the crop is grown.
- **Seen in (imported):** bitter orange (blossoms for neroli are taken at the cost of fruit); coconut
  (a tapped spadix sets no nuts); date palm (trunk tapping means no dates for 2-4 years and can kill the
  palm); okra (pod vs seed); giant granadilla (immature vegetable vs ripe fruit); cassava (five leaf cuts
  dropped root yield from 40 to under 25 t/ha); Jerusalem artichoke (cutting tops for forage removes most
  of the tuber yield); taioba (rhizomes lifted only from plants whose leaves weren't cut); swiss chard
  (leaf cuts lower seed yield); jicama and ahipa (pruning flowers doubles root yield but gives no pods or
  seed; partial pruning is a third path); salsify and wasabi (a chain of products from one plant, each
  ending the last); seed lotus (fresh vs mature pod chosen per pod); coriander (seed rate 10-25 kg/ha for
  seed vs about 50 kg/ha for leaf).
- **Possible home:** a "Product trade-offs" line under "Harvest stages / windows".

## 33 — Harvest method that decides the product

- **Status:** OPEN (imported 2026-11-24; first Glinda doc added the same day).
- **What doesn't fit:** "Labor" takes hours, and "Harvest stages" takes maturity. At the same maturity,
  the way a crop is harvested can decide which product it can become, how long it keeps, and whether a
  co-product is usable.
- **Seen in:**
  - `purple_passionfruit` / `yellow_passionfruit` (`passionfruit.md`, Finding 3): the yellow form is
    gathered off the ground after it falls (daily, or it spoils), while the purple is vine-picked at
    colour; fallen fruit of equal ripeness has less sugar, acid and vitamin C.
  - Imported: durian (cut from the tree vs windfall); cranberry (water harvest for processing vs dry
    harvest for fresh); blueberry (hand vs machine); raspberry (machine-picked fruit is for processing
    only); ume (nets catch fallen ripe fruit); cashew (gathering fallen nuts weekly loses the cashew
    apple, 8-10 times the nut weight, which needs near-daily hand picking and processing within hours);
    lotus root (water-jet digging in the flooded field vs drained hoe digging; water-jet digging of
    arrowhead needs a water allocation).
- **Possible home:** a "Harvest method" line: options, products each allows, labour and co-product loss.

## 34 — Time of day of harvest

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** harvest timing is recorded by stage and season only.
- **Seen in (imported):** spearmint (about 9 am gives the most oil; about 9 pm the most carvone).
- **Possible home:** a note under "Harvest stages / windows".

## 35 — Field operations with no name

- **Status:** OPEN (imported 2026-11-24; first Glinda doc added the same day).
- **What doesn't fit:** "Labor" asks only for hours. Many crops need named operations that matter for
  yield or quality and have to be planned, not just counted.
- **Seen in:**
  - `peach_low_chill` (`peach-low-chill.md`, Findings 2 and 5, Weather response): chemical defoliation in
    late November; summer topping at 100 cm, 150 cm and 200 cm and cutting back after harvest; rootstock
    sucker removal; mounting freeze-protection emitters on PVC risers each winter.
  - `pear_low_chill` (`pear-low-chill.md`, Labor and Hazards): cutting out fire blight 8-10 inches below
    infection with tool sterilising; copper every 10-14 days from bloom for leaf spot; dormant oil in
    mid-January for scale; streptomycin at bloom; trunk wraps against herbicide uptake through thin bark.
  - Imported: potato (hilling; vine kill 7-21 days before harvest to set skins); yam, tomato, eggplant
    (staking; yam poles 2-5 m); cauliflower (blanching; not needed in green cultivars); endive (tying to
    blanch); jicama and arrowroot (flower removal); horseradish (lifting side roots twice a season);
    artichoke (cutting back crowns); asparagus (fern chopping); tatsoi and kai-lan (thinning as an early
    harvest); kai-lan, gat, rutabaga (insect netting; rutabaga's netting lasts 10 years); chayote
    (trellis); girdling (grape, lychee, apricot, orange, avocado, mango, jujube); fruit bagging
    (pomegranate, date palm); tipping and caning out (cane fruit); caprification (fig); lowbush blueberry
    (field burning); makrut lime (leaf stripping, paid by piece); arrowhead (leaf stripping every 20
    days; root pruning; bird netting); lotus (turning runners back from the bund); chuin (stripping 25%
    of old leaves after heat shock); maca (sowing trampled in by sheep); fingerling potato (small units
    raise handling labour).
- **Possible home:** a "Field operations" list under "Labor" (operation, timing, purpose, labour).

## 36 — Growth regulators as routine operations

- **Status:** OPEN (imported 2026-11-24; first Glinda doc added the same day).
- **What doesn't fit:** chemical inputs are not recorded anywhere unless they are a hazard. In some crops
  a growth regulator is a standard step that sets fruit, flowering or shape.
- **Seen in:**
  - `peach_low_chill` (`peach-low-chill.md`, Finding 8): paclobutrazol (or repeated summer pruning) is
    essential at high density in Australia; hydrogen cyanamide was tried as a dormancy breaker.
  - Imported: oriental melon (fruit-set hormones); Korla pear (paclobutrazol to shed the calyx);
    artichoke and citrus (gibberellin); pineapple (ethephon forcing); blueberry (gibberellin for seedless
    fruit); mango (paclobutrazol); low-chill apple and grape (hydrogen cyanamide, see entry 9).
- **Possible home:** a "Growth regulators" line under "Labor" or "Field operations" (product, timing,
  purpose).

## 37 — Fruit-load limits and yield set by canopy, not plant count

- **Status:** OPEN (imported 2026-11-24; first Glinda doc added the same day).
- **What doesn't fit:** "Yield" takes a per-area range. Some crops have a ceiling on fruit a plant can
  carry, trade size against number, or yield by canopy area regardless of density.
- **Seen in:**
  - `peach_low_chill` (`peach-low-chill.md`, Agronomic data, Yield): a *light* crop is also a defect,
    giving up to 50% split pits in 'Flordadawn'; thinning sets size and prevents limb breakage;
    Australian benchmarks are at 1,200-1,800 trees/ha against about 385/ha in the Florida budget.
  - `pear` (`pear.md`, Finding 3 and Yield): revenue falls faster than yield under water deficit (slope
    1.3 against 1.0-1.2) because fruit under 65 mm is penalised; a heavy crop suppresses next year's
    bloom; budget yields run from about 39.5 t/ha at 242 trees/acre to about 70 t/ha at 558.
  - `pear_low_chill` (`pear-low-chill.md`, Labor): Oklahoma says pears need crop-load thinning every
    season, to one fruit per cluster, or they give small fruit, alternate bearing and broken limbs.
  - Imported: giant granadilla (a maximum number of fruit carried at once); peach (thinning curves trade
    fruit size against yield by cultivar); cashew (about 450 kg/ha whether 44 or 278 trees/ha).
- **Possible home:** a "Load and density" note under "Yield".

## 38 — Loss on the plant once ripe

- **Status:** OPEN (imported 2026-11-24; first Glinda doc added the same day).
- **What doesn't fit:** "Harvest stages / windows" gives the window but not how fast quality falls inside
  it, or losses from seed shed before harvest.
- **Seen in:**
  - `pear_low_chill` (`pear-low-chill.md`, Finding 4): fruit left on the tree soften unevenly, soften at
    the core and gain stone cells (grit).
  - `satsuma` (`satsuma.md`, Finding 1): unlike grapefruit, which stores on the tree, satsuma holds
    poorly once ripe and must be picked promptly, so the harvest window is a hard deadline rather than a
    flexible one.
  - Imported: snake melon (hollow fruit rise from 9-17% to 44-64% in two days); salsify (wind blows the
    plumed seed away); American lotus (late pods drop seed into the water); radish (prime for only a few
    days, so it is sown every week or two).
- **Possible home:** a "Deterioration on the plant" line under "Harvest stages / windows".

## 39 — Disorders in the field from water or nutrient swings, and rain cracking

- **Status:** OPEN (imported 2026-11-24; first Glinda doc added the same day).
- **What doesn't fit:** "Storage" holds storage disorders. Disorders that develop in the field from uneven
  water, nutrients, heat or rain have no bullet.
- **Seen in:**
  - `pear` (`pear.md`, Finding 5): black end, a calyx-end disorder of 'd'Anjou', is linked to waterlogged
    spring subsoil and to Asian (*P. serotina*) rootstocks.
  - Imported: tomato (cracking); cabbage (head splitting); radish (root splitting, 5-30% losses);
    celeriac and rutabaga (brown heart from boron; rutabaga resistance by cultivar); napa cabbage
    (tipburn); celery (blackheart, pithiness); sweet cherry (rain cracking up to 90%); nectarine (rain
    cracking); lime (stylar-end breakdown from field heat, up to 40%); mangosteen (translucent flesh from
    excess water); broccoli, cauliflower, romanesco (buttoning); cauliflower (ricing); jicama (cracking
    after rain in heat); pomegranate (cracking, sunburn).
- **Possible home:** a "Field disorders" bullet (disorder, trigger, losses, resistant cultivars).

## 40 — Fruit formed underground

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** a crop that buries its own fruit needs a soil texture and a digging harvest that
  are usually root-crop traits.
- **Seen in (imported):** groundnut, Bambara bean.
- **Possible home:** a note under "Soil" and "Harvest pattern".

## 67 — Value set by a calendar market window against other regions

- **Status:** OPEN (logged 2026-11-24).
- **What doesn't fit:** "Harvest stages / windows" records when a crop can be picked. It has no place
  for a crop whose value depends on ripening inside a calendar window set by *other* regions' supply, so
  that otherwise-normal phenology (late bloom, late chill) counts as failure.
- **Seen in:**
  - `peach_low_chill` (`peach-low-chill.md`, Finding 1): Florida peaches earn higher prices from March
    to early May, before northern states harvest. Trees must bloom by the third week of January to make
    it, so chill gained after mid-January is "not useful for commercial production" even though the trees
    still flower.
- **Possible home:** a "Market window" line under "Harvest stages / windows" (dates, competing regions,
  what it does to price, and the phenology deadline it sets).

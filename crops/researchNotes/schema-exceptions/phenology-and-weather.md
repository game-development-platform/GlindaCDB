# Schema exceptions: phenology, weather and site

Part of the schema exceptions log. Rules, statuses and the full index are in
[`../schema-exceptions.md`](../schema-exceptions.md).

Entries marked "imported" came from earlier private notes kept before this log existed. Their **Seen in**
lists name crops, not checked Glinda docs: the facts have not yet been re-checked against the crop's
Glinda doc, and some of those crops have no Glinda doc yet. When a research run confirms one, replace the
plain name with the cropID, doc and Finding.

## 1 — Effects that carry over to the next season's crop

- **Status:** OPEN (logged 2026-11-24; imported crops added the same day).
- **What doesn't fit:** the template describes one season at a time. "Water use", "Weather response"
  and "Harvest pattern" have no way to say that a stress in *this* season changes *next* season's yield
  or quality, through flower-bud initiation after harvest.
- **Seen in:**
  - `peach` (`peach.md`, Finding 4): water stress after harvest (around August, while next year's
    flower buds form) raises doubled and deep-sutured fruit and lowers fruit set the following year,
    sharply below −2.0 MPa midday stem water potential.
  - `peach_low_chill` (`peach-low-chill.md`, Finding 2 and Hazards): defoliating too early cuts the
    carbohydrate and nitrogen reserves for next season's flowering, giving erratic set; peach rust's
    summer defoliation harms next season's flowers and fruit.
  - `pear` (`pear.md`, Finding 3): moderate stress in the season or after harvest *raises* next year's
    bloom and yield (SWP above −2.2 MPa); below −2.8 MPa the next crop falls; over-irrigation cuts later
    flowering; relieved severe stress can cause autumn re-bloom; a heavy crop suppresses next year's bud
    initiation (Finding 2).
  - Imported: olive (alternate bearing; an off year about 57% lower in fruit); longan (off-year crop
    20-40%); mandarin (alternate bearing managed by chemical thinning); coyo; grapefruit (a late harvest
    lowers the next crop); ume (water stress July-March cuts next spring's flowers); lowbush blueberry
    (irrigation in the prune year raises the next year's buds; fields alternate prune and crop years);
    blackberry (alternate-year cropping).
- **Possible home:** a "Carry-over effects" angle, covering any management or weather event whose main
  effect lands on a later season (post-harvest stress, alternate bearing triggers, bud-initiation
  windows), plus a way to record a field cycle that alternates by year.

## 5 — Flowering that growers induce or schedule

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** "Photoperiod sensitivity" and the chill angle cover natural flowering triggers.
  Nothing records flowering that growers *cause* (water withholding, a cool spell, night lighting, a
  chemical) to set when or whether a crop flowers, or how many crops a year it gives.
- **Seen in (imported):** pineapple (ethylene forcing); guava and pomegranate (water withheld to choose
  the flowering season, the Indian bahar system); lychee (cool spell below about 20 °C at the flush,
  plus cincturing); durian, mango, champedak (a dry spell; rain then gives shoots, not flowers; mango also
  KNO3 and paclobutrazol); dragon fruit (night lighting); rambutan, mangosteen, loquat (water stress;
  mangosteen also a bud-age gate); longan (potassium chlorate); lemon (drought forcing, *forzatura*);
  low-chill apple and tropical grape (leaf stripping or pruning plus a dormancy breaker gives 2-3 crops a
  year). Counter-cases: pulasan flowers only every few years; mata kucing needs no induction.
- **Possible home:** a "Flowering control" angle: trigger, method, timing, and the harvest windows it
  produces.

## 6 — Stress applied on purpose to raise quality or set fruit

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** "Water use" and "Weather response" treat stress as a loss. Some crops are
  stressed deliberately because it improves quality, sets more fruit, or changes the product's
  chemistry.
- **Seen in:**
  - `satsuma` (`satsuma.md`, Finding 2): a plastic sheet laid over the orchard floor through the rainy
    season excludes rain and imposes deliberate water stress, raising fruit sugar by active
    osmoregulation (~2 °Brix); the leaf-water-potential target is about −0.7 to −1.0 MPa, and excessive
    fruit load instead raises acidity.
  - Imported: snow mustard (water
    withheld 10-15 days before harvest); pepper (water stress raises capsaicin); pomegranate (spring water
    stress raises fruit set, the opposite of citrus); sugar beet (irrigation stopped 2-4 weeks before
    lifting); arrowroot (irrigation raises rhizome yield but lowers starch recovery); cumin (the water
    regime at seed set switches the dominant essential-oil compound).
- **Possible home:** a "Deliberate stress" line under "Water use" (stage, stress level, quality or set
  effect, yield cost).

## 7 — Bolting as a failure, with different trigger shapes

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** the chill and photoperiod angles cover what triggers flowering. They don't
  record bolting as the event that *ends* the harvest or ruins the product, which trigger shape applies
  (cold only, heat only, long days, or two-sided), whether there is a juvenile threshold, or what
  happens to the product once the plant bolts.
- **Seen in (imported):** spinach, lettuce, broccoli, celery (cold only), bok choy (cold and heat),
  napa cabbage, arugula (heat, drought, long days), mustard greens, endive, mizuna, tatsoi, komatsuna
  (sensitive from germination) vs *B. oleracea* (plant-size threshold), gat, takana, choy sum (no cold
  needed), carrot and celeriac (no cold response before about 8 and 6-8 leaves), radish, swiss chard
  (cold then long days), table beet, scorzonera (bolted roots stay edible) vs salsify (roots go woody),
  scorzonera (cold irrigation water as a trigger). Bolt is the product: kai-lan, Aso takana, snow mustard.
  Florence fennel breeding is organised around bolt resistance.
- **Possible home:** a "Bolting" bullet: trigger shape, juvenility threshold, consequence for the
  product, resistant cultivars.

## 8 — Harvested organ forms only inside a temperature window

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** "Photoperiod sensitivity" covers day-length gates on tuberization and bulbing.
  Nothing records a *temperature* window that the harvested organ needs in order to form.
- **Seen in (imported):** stem mustard (swells below about 15 °C); head mustard (heads only at
  10-15 °C); napa cabbage (10-24 °C); Amazonian yam bean (30/25 °C day/night stops root formation
  entirely); potato (warm nights suppress tuber initiation); maca (hollow roots below about 2,800 m in
  Yunnan; up to 20% of plants form no swollen root).
- **Possible home:** an "Organ formation" line next to "Photoperiod sensitivity" (temperature range,
  day or night basis, failure mode).

## 9 — Chill requirement that a farm operation can replace, and chill negation

- **Status:** OPEN (imported 2026-11-24; first Glinda doc added the same day).
- **What doesn't fit:** the chill angle records how much chill a crop needs. It has no place for an
  operation that substitutes for chill, for warm spells that cancel chill already gained, or for a
  dormancy breaker that helps one crop and harms another.
- **Seen in:**
  - `peach_low_chill` (`peach-low-chill.md`, Finding 2 and Finding 8): leaves must be removed (zinc
    sulphate, late November) before buds take up chill; prolonged periods above 15 °C hurt accumulation;
    chill after bloom starts, or after mid-January, doesn't help the market crop; too *much* chill aborts
    flower buds in low-chill cultivars, a chill ceiling as well as a floor; hydrogen cyanamide advanced
    maturity 10-19 days but cut set or yield by over 40% in three Australian trials, and worked only when
    timed by bud stage.
  - `pear_low_chill` (`pear-low-chill.md`, Finding 1): in Egypt 'Le Conte' is defoliated with zinc
    sulphate (15 November) and then sprayed with hydrogen cyanamide (15 January); Dormex at 1% plus 3%
    mineral oil was a cheaper substitute for 4% hydrogen cyanamide; garlic extract and urea phosphite
    were tried as alternatives (snippet only).
  - Imported: low-chill apple (hydrogen cyanamide plus oil gave a crop with zero chill hours; hand
    defoliation in the tropics);  artichoke (gibberellin
    substitutes for cold); jujube (chill speeds but is not required); olive (chill counted in weeks below
    12 °C, a different unit).
- **Possible home:** extend the chill angle: unit, substitutes, negation rule.

## 10 — Weather thresholds that depend on stage, organ, duration or cover

- **Status:** OPEN (imported 2026-11-24; first Glinda doc added the same day).
- **What doesn't fit:** "Weather response" takes frost, heat, drought and waterlogging tolerance as
  single values. Many sourced thresholds only hold for one growth stage, one organ, a minimum duration,
  or a condition such as snow cover, and some are about rain or warmth at the wrong moment rather than
  extremes.
- **Seen in:**
  - `peach_low_chill` (`peach-low-chill.md`, Finding 3): bloom nights above 14 °C are needed for good set
    in 'UFGem' but make 'UFBeauty' crop unreliably, so the same threshold points opposite ways by
    cultivar.
  - `pear` (`pear.md`, Weather response): a 10%/90% bud-kill table across eight stages, from 15/0 °F at
    scales separating to 28/24 °F at full bloom (for 'Bartlett'; 'd'Anjou' may bloom earlier and be more
    tender); fire-blight blossom risk is tracked in degree-hours above 65 °F.
  - `pear_low_chill` (`pear-low-chill.md`, Weather response): 26 °F (−3.3 °C) usually kills *open*
    blossoms; early bloom (5-29 March) made all three hybrids very susceptible to late-spring freezes in
    Mississippi.
  - `sour_cherry` (`cherry.md`, Finding 5 and the 2026-11-25 re-research): cherry bud-kill is
    stage-specific — about −2.2 °C (10% kill) to −3.9 °C (90%) at full bloom but only ~−15 °C for 90%
    kill at the earliest swelling stage for a standard cherry, with sour-cherry bud-kill documented at
    two separate bloom stages.
  - Imported: grapefruit (−2.2 °C for 6 hours or more); Korla pear (a table of thresholds by organ, and
    freeze wounds that lead to canker); lingonberry (hardiness depends on snow cover); blackcurrant (2 °C
    for two days at bloom cut yield about 60%, with no frost); passionfruit and date palm (rain at
    pollination; date palm seasons rated down by more than 50 mm in a harvest month); seed lotus (rain or
    wind at the morning bee visits); maypop (top dies back each winter); mandarin, feijoa, raspberry,
    blackberry (different thresholds for tree, flower, fruit, cane and bud).
- **Possible home:** let "Weather response" hold a list of rules, each with stage, organ, threshold,
  duration and effect.

## 11 — Weather that sets product quality, not yield

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** "Frost as a quality event" is promoted, but other weather affects quality
  without frost or any yield loss.
- **Seen in (imported):** blood orange (red colour needs cold nights); table beet (fast growth in warm
  weather gives pale rings); carrot (soil above 25 °C makes roots fibrous and pale); maca (freeze-thaw
  field drying forms its active compounds).
- **Possible home:** widen the frost-quality angle to "weather-driven quality", with the trigger and the
  quality trait it changes.

## 12 — Properties of the growing water itself

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** "Water regime" separates ordinary irrigation from flooded or paddy culture.
  Aquatic and flood-dependent crops also need the water to have a temperature, flow, depth schedule or
  clarity, or are timed by a river's flood calendar. Some crops also use water for purposes other than
  evapotranspiration.
- **Seen in (imported):** wasabi and watercress (constantly flowing cool water, 10-15 °C, well
  oxygenated); taro (corm rot in warm stagnant water; roots best at 27-29 °C water); lotus root (flood
  depth by stage, and flow-through water far above evapotranspiration); American lotus (pond depth
  0.6-2.1 m); Chinese water chestnut (turbid water shades emerging shoots); chuin (sown as the river
  falls and lifted before the next flood); cranberry (winter, late and harvest floods); strawberry and
  blueberry (sprinkling for frost protection).
- **Possible home:** extend "Water regime" with water temperature, flow, depth schedule, flood calendar,
  and non-evapotranspiration water uses.

## 13 — Shade as a tolerance, requirement or yield input

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** no bullet records light level. Some crops tolerate shade, some need it when
  young, and some yield *more* under shade.
- **Seen in (imported):** rice bean, cocoyam (25-50% shade raises yield), arrowroot (understorey under
  coconut and arecanut), konjac (+66% under 50% shade cloth), elephant foot yam (50-60% shade), edible
  canna, mangosteen (young trees need shade), wasabi, taioba (sun and heat raise oxalate), salsify.
- **Possible home:** a "Light / shade" line under "Climate zones" or "Weather response".

## 14 — Low humidity as a requirement

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** climate and weather bullets describe tolerances. Nothing records a crop that
  actively *needs* dry air, rather than merely tolerating it.
- **Seen in (imported):** cumin. Related: date palm (harvest-season rain and humidity at the khalal
  stage downgrade the crop).
- **Possible home:** a humidity ceiling as part of the climate envelope.

## 15 — Photosynthetic pathway

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** no bullet records C3, C4 or CAM, which affects water use and heat response.
- **Seen in (imported):** pineapple and dragon fruit (CAM); cassava (C3 vs C3-C4 intermediate,
  disputed); Chinese water chestnut (unknown; the genus has C3, C4 and intermediates).
- **Possible home:** a "Photosynthetic pathway" line under "Water use".

## 16 — Maturity timed by heat units

- **Status:** OPEN (imported 2026-11-24; first Glinda doc added the same day).
- **What doesn't fit:** "Life form / season" and "Days to first bearing" are in days or years. Some
  crops are timed by accumulated heat (degree-days) with a stated base temperature.
- **Seen in:**
  - `pear` (`pear.md`, Harvest pattern): harvest date predicted from heat units in the 9 weeks after full
    bloom (base 45 °F), e.g. days from full bloom = 147.5 − 0.0353 × heat units for 'Bartlett'.
  - Imported: grape (maturity groups by degree-days, base 10 °C); date palm (base 18 °C); Andean potato
    (base 0 °C).
- **Possible home:** a degree-day line beside the days-to-maturity figure (base, cap, sum by cultivar
  group).

## 68 — Irrigation scheduled by plant water status and deficit windows by stage

- **Status:** OPEN (logged 2026-11-24).
- **What doesn't fit:** "Water use" takes Kc values and seasonal demand, and "Water regime" the kind of
  irrigation. Neither records plant water-status thresholds (such as midday stem water potential) by
  growth stage, the stages when a deficit is safe or costly, or a production function where yield or
  revenue falls only past a deficit threshold.
- **Seen in:**
  - `pear` (`pear.md`, Finding 3 and Water use): unstressed trees sit at −0.65 to −0.95 MPa;
    'Conference' should stay above −1.1 MPa in Stage II; no yield loss up to a 15-20% ETc deficit, then
    slopes of 1.0-1.2 (revenue 1.3); Stage I deficit saves 6%, Stage II saves 33% but costs revenue,
    post-harvest is safest; a combined strategy cuts 600 mm to 400 mm.
- **Possible home:** a "Deficit tolerance by stage" line under "Water use" (threshold, measure, safe and
  costly stages, water saved, yield and revenue slopes).

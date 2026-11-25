# Schema exceptions: postharvest, processing and products

Part of the schema exceptions log. Rules, statuses and the full index are in
[`../schema-exceptions.md`](../schema-exceptions.md).

Entries marked "imported" came from earlier private notes kept before this log existed. Their **Seen in**
lists name crops, not checked Glinda docs: the facts have not yet been re-checked against the crop's
Glinda doc, and some of those crops have no Glinda doc yet. When a research run confirms one, replace the
plain name with the cropID, doc and Finding.

## 2 — Storage injury that is worse at a middle temperature than near freezing

- **Status:** OPEN (logged 2026-11-24; imported crops added the same day).
- **What doesn't fit:** "Storage (postharvest)" takes a regime, temperature, humidity and shelf life,
  and implicitly assumes colder is safer down to the freezing point. It has no way to record a danger
  band *above* the optimum where injury is faster than at the optimum itself, with symptoms that only
  show after removal.
- **Seen in:**
  - `peach` (`peach.md`, Finding 5): internal breakdown develops faster at 2-7 °C than at 0 °C or below,
    and shows only on ripening after storage.
  - `nectarine` (`nectarine.md`, Finding 2): the same disorder, with a 2.2-7.8 °C band.
  - `peach_low_chill` (`peach-low-chill.md`, Finding 7): injury can start below about 10 °C and is most
    severe in a 2.2-7.8 °C "killing zone"; storage is 0-1.1 °C; immature fruit are more susceptible and
    ripe fruit less so (a ripeness qualifier).
  - `pear` (`pear.md`, Finding 5): 2.5-10 °C is harmful to some cultivars; 'Bartlett' held there turns
    dry-textured with poor flavour; storage is at −1 °C.
  - Imported, the same band: plum, Japanese plum, apricot; Asian persimmon ('Fuyu' hurt at 2-15 °C, worst
    at 5-7 °C, not at 0 °C).
  - Imported, related shapes that a danger-band field would also need to hold:
    - a time-temperature dose: eggplant (no injury at 10 °C; about 12 days at 7.2 °C, 6-7 days at 5 °C,
      1-2 days at 0 °C); sweet potato (weeks at 10 °C equal 1-2 days at 3-4.4 °C; shows only on cooking);
    - symptoms only after rewarming: pineapple;
    - a threshold that depends on ripeness: pepper, guava, papaya, cantaloupe;
    - a threshold that depends on where the fruit was grown: orange (Florida and Texas fruit stored at
      0-1 °C, California and Arizona fruit chilled below 3-5 °C);
    - a penalty for changing temperature: nectarine (moving from 0 to 5 °C after 1-2 weeks injures as
      badly as 5 °C throughout);
    - a squeeze between two disorders: pomegranate (chilling below 5 °C, husk scald at 7 °C or below
      after 3 months);
    - a deadline after leaving the store: taro (2 days).
- **Possible home:** a storage sub-field for a "danger band" (range, time to injury, delayed-symptom
  flag), separate from the chilling threshold, with optional ripeness, origin and dose qualifiers.

## 41 — Ripening off the plant, or a conditioning step before the product is usable

- **Status:** OPEN (imported 2026-11-24; first Glinda doc added the same day).
- **What doesn't fit:** "Edibility" says what preparation is needed and "Storage" gives a regime. Neither
  records that the harvested product must ripen or be conditioned off the plant, under what conditions,
  for how long, and what happens when that fails.
- **Seen in:**
  - `peach_low_chill` (`peach-low-chill.md`, Agronomic data, Edibility): the fruit is climacteric and
    softens off the tree, but sugar does not rise, so non-melting cultivars are bred to be picked
    tree-ripe.
  - `pear` (`pear.md`, Finding 4): winter cultivars need 15-60 days at −1 °C by cultivar (or ethylene at
    100 µL/L, 20 °C, 2-3 days) before they will ripen, then 4-9 days at 15-24 °C; unchilled fruit shrivel
    without ripening; most fail to soften at 30 °C.
  - `pear_low_chill` (`pear-low-chill.md`, Finding 4): picked hard as it yellows and ripened off the
    tree; Florida ripens it at room temperature, while Oklahoma says hybrids need 2 days to 2 weeks of
    chilling first or they shrivel and rot; the imported 15.5-18 °C window for 'Kieffer' was not re-found
    this pass (request `pear_low_chill--kieffer-ripening`).
  - Imported: peach, plum, apricot, papaya, guava, kiwifruit (off-plant ripening); avocado (never ripens
    on the tree); banana (scheduled ethylene ripening at 14-18 °C over 4-10 days; fails above about 25
    °C); cantaloupe (softens but gains no sugar off the vine); honeydew (ethylene treatment); durian (the
    husk gives off ethylene); quince (stored, then ripened at 20 °C); medlar (inedible until bletted, 2-3
    weeks cool or frost on the tree);
     Asian persimmon (astringent types need CO2 or ethanol
    treatment, drying, or freezing); Asian pear (climacteric in some cultivars, not others).
    Counter-cases: pomegranate and sweet cherry don't ripen off the plant.
- **Possible home:** a "Ripening / conditioning" line under "Storage" (required or not, regime, days,
  failure band, prerequisite cold).

## 42 — Quality or composition that changes in store or in the ground

- **Status:** OPEN (imported 2026-11-24; first Glinda doc added the same day).
- **What doesn't fit:** "Storage" gives shelf life as a single end point. Many products change in value
  or composition while they keep: sugars convert, starch or sugar is respired away, a compound needed by
  a processor falls below a threshold, the product keeps growing, or cooking quality declines.
- **Seen in:**
  - `pear` (`pear.md`, Finding 5): two storage groups. Slow-senescing cultivars ('d'Anjou', 'Packham's
    Triumph') keep their ripening capacity but scald after removal; fast-senescing ones ('Bartlett',
    'Bosc', 'Comice') lose the ability to ripen after long storage and develop senescent scald.
  - Imported: potato (cold sweetening, reversed by warm reconditioning; light raises glycoalkaloids, see
    entry 63); sugar beet (piled roots respire about 0.25 kg of sugar per tonne per day, 0.55 if
    bruised); Jerusalem artichoke, salsify, scorzonera (inulin converts to sugars; canneries need
    scorzonera inulin at or below about 7%); jicama (starch to sugar in store); Chinese water chestnut
    and parsnip (sweetening; parsnip gets the same from 2 weeks at 0-1 °C as from 2 months of field
    frost); arrowroot (about 59% of extractable starch lost in 30 days); konjac (mannan falls once buds
    move in spring); common bean (hard-to-cook defect develops in storage); asparagus (keeps growing and
    bends in store); chayote (sprouts in store); sweet potato and rutabaga (grading or waxing resets
    storage life).
- **Possible home:** a "Change in store" line under "Storage" (what changes, rate, threshold, reversible
  or not).

## 43 — Product that improves with age

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** "Storage" assumes quality only declines.
- **Seen in (imported):** dried mandarin peel, *chenpi* (value rises with years of ageing); lemon
  (curing improves keeping and quality); persimmon tannin, *kakishibu* (aged 1-3 years).
- **Possible home:** a note under "Storage" or the processing chain (ageing period and value change).

## 44 — Very long keeping without cold storage

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** the counter-case to processing deadlines: products that keep for months without a
  cold store or processing, which changes how they can be traded and stockpiled.
- **Seen in (imported):** lingonberry (self-preserving fruit); tacca (tubers keep 6 months in pits);
  pickling melon (months at ambient, hung in rope).
- **Possible home:** an explicit "no deadline" value for the processing time limit, plus the ambient
  keeping period under "Storage".

## 45 — Ethylene sensitivity and incompatible storage mates

- **Status:** OPEN (imported 2026-11-24; first Glinda doc added the same day).
- **What doesn't fit:** "Storage" covers one product at a time. Some products are damaged by very low
  ethylene, or give off enough to damage what is stored beside them.
- **Seen in:**
  - `peach_low_chill` (`peach-low-chill.md`, Finding 5): ethylene released during dormant pruning aborts
    flower buds in 'UFO', so it is pruned only in summer (a field, not storage, ethylene sensitivity).
  - `pear` (`pear.md`, Finding 4): 'Bartlett' is the most ethylene-sensitive, 'd'Anjou' the least; stored
    pears are kept away from ethylene-producing produce; ethylene at harvest is under 0.1 µL/kg·h,
    peaking at 80-200 in 'Bartlett'.
  - `purple_passionfruit` / `yellow_passionfruit` (`passionfruit.md`, Finding 3): among the highest
    ethylene producers of any fruit (160-370 µL/kg·h at the climacteric peak), so it would over-ripen
    ethylene-sensitive produce stored with it; the yellow form is also force-ripened off-vine with 100
    ppm ethylene for 1-2 days.
  - Imported: kiwifruit (5-10 ppb softens fruit); watermelon (5 µL/L); kai-lan (1 ppm cuts shelf life
    about 30%); carrot (bitter from under 1 ppm; apples and pears are bad storage mates); celeriac
    (ethylene toughens roots); quince (ripens its neighbours).
- **Possible home:** "Ethylene: sensitivity and production" and "Do not store with" lines under
  "Storage".

## 46 — Processing capacity that limits harvest

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** the processing time limit is per lot. Where the processor can only take so much
  a day, that capacity sets how much can be harvested, or the harvest queues for a processing campaign.
- **Seen in (imported):** sugar beet (factories run about 90 days a year; roots queue in piles);
  arrowroot (a 48-hour limit after digging caps how much can be dug a day).
- **Possible home:** a "Processing capacity" note in "Uses and processing".

## 47 — Processing that depends on the weather

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** processing steps are recorded as fixed. Some need particular weather to work.
- **Seen in (imported):** maca (9-10 weeks of open-air drying with night freezes and day thaws forms its
  active compounds); ahipa (sun-sweetening of roots before market).
- **Possible home:** a weather condition on the processing step.

## 48 — Storage pests

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** "Storage" records regime and disorders but not insects that attack the stored
  product, or resistance to them.
- **Seen in (imported):** pigeon pea (bruchids and weevils); rice bean (resistant); chuin (seed beetle
  controlled by smoke, camphor and harvest timing).
- **Possible home:** a "Storage pests" line under "Storage".

## 49 — Product eaten in grams

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** "Composition" assumes the product is food eaten by the plateful. For condiments
  and supplements, energy per kilogram hardly matters; what matters is pungency, active content or
  dose.
- **Seen in (imported):** horseradish, wasabi, maca.
- **Possible home:** a "Use intensity" note under "Composition".

## 50 — A living plant as the product

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** "Uses and processing" lists harvested organs. Sometimes the whole living plant is
  sold.
- **Seen in (imported):** Buddha's hand (sold as a potted plant).
- **Possible home:** an "Ornamental / living plant" use in "Uses and processing".

## 51 — Product made without growing the plant in a field

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** the template assumes a planted crop. Some plant products come from engineered
  crops producing a pharmaceutical, or from plant cells grown in bioreactors.
- **Seen in (imported):** transgenic carrot and tobacco cell culture (an approved enzyme drug); *Taxus*
  cell culture (paclitaxel).
- **Possible home:** a note under "Controlled environment", or a separate production-mode field. Not
  urgent.

## 52 — Product behaviour set by a structural trait

- **Status:** OPEN (imported 2026-11-24).
- **What doesn't fit:** "Composition" gives amounts, not structure. Starch granule size changes how a
  starch settles and gels, and so what it is used for.
- **Seen in (imported):** edible canna (30-100 µm granules, among the largest known; fast settling, clear
  firm gels for glass noodles) vs arrowroot (fine granules).
- **Possible home:** a note under "Composition".

## 69 — A luxury product defined by extreme hand-processing labour

- **Status:** OPEN (first Glinda doc 2026-11-24).
- **What doesn't fit:** "Uses and processing" records the steps and any yield fraction, and "Labor"
  records field and harvest hours. Neither captures a processing step whose sheer manual labour per unit
  of finished product is the defining fact — the thing that makes the product rare, slow and expensive —
  rather than an ordinary cost line.
- **Seen in:**
  - `red_currant` (`red-currant.md`, Finding 6): Bar-le-Duc jelly is made by hand-seeding each whole
    berry with a sharpened goose quill (the *épépineuses*), ~7 seeds flicked from each of ~200 berries per
    85 g jar, with the whole run done in a single day; output is only ~5,000-20,000 jars a year and a
    worker manages "several kg/day". The labour, not any agronomic trait, is what defines the product.
- **Possible home:** a "Processing labour intensity" note under "Uses and processing" for steps whose
  per-unit hand labour defines the product.

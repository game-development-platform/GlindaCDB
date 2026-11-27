# Schema exceptions log (index)

Findings that the current `skills/crop-research/templates/research-doc.md` bullets and the step 3
checklist in `skills/crop-research/SKILL.md` have no natural place for. Step 7 of the skill (the
schema-fit check) adds to this log on every research run.

The log is split by theme. This file holds the rules and the index. The entries themselves are in the
section files under [`schema-exceptions/`](schema-exceptions/):

| Section file | Covers |
|---|---|
| [`phenology-and-weather.md`](schema-exceptions/phenology-and-weather.md) | Seasonal cycle, flowering, bolting, chill, weather rules, water, light, site |
| [`reproduction-and-propagation.md`](schema-exceptions/reproduction-and-propagation.md) | Sex, pollination, seed, seed systems, planting stock, rootstocks, grafting |
| [`stand-harvest-and-labour.md`](schema-exceptions/stand-harvest-and-labour.md) | Stand life, harvest timing and method, competing harvests, field operations, field disorders |
| [`postharvest-and-products.md`](schema-exceptions/postharvest-and-products.md) | Storage, ripening, change in store, processing, product types |
| [`interactions-hazards-and-rules.md`](schema-exceptions/interactions-hazards-and-rules.md) | Other crops, rotation, environment, hazards, legal, religious and cultural rules |

## Rules

- **Numbers are permanent.** Each exception keeps its number for good; numbers are never reused or
  renumbered, including after an entry is closed or moved to another section file. Numbers are global
  across all section files.
- **One entry per kind of trait.** When another crop shows the same kind of trait, add it to that
  entry's **Seen in** list instead of opening a new entry.
- **Single-crop traits are logged too.** A trait seen in only one crop so far still gets an entry, so
  nothing is missed before later research shows whether it recurs.
- **Logging changes nothing else.** An entry here never changes a status table or marks rows
  `OUT-OF-DATE`. Only promotion does, and promotion is the user's decision (see "Promoting a schema
  exception" in the skill).
- **Status:** `OPEN` (collecting), `PROMOTED` (became a checklist angle or template bullet; give the date
  and the `checklist-additions.md` entry), or `DECLINED` (not promoted; give the reason).
- **Adding an entry:** take the next unused number, put the entry in the section file whose theme fits
  best, and add a row to the index below. When an entry's status changes, update it both in the section
  file and in the index.
- **Imported entries.** Entries 5-66, and the crops marked "Imported" in entries 1-3, were brought in on
  2026-11-24 from earlier private notes kept before this log existed. Their **Seen in** lists name crops
  rather than Glinda docs: the facts have not yet been re-checked against a Glinda doc, and some of the
  crops have no Glinda doc yet. When a research run confirms one, replace the plain name with the cropID,
  doc and Finding, as for entries logged by step 7.

## Index

| # | Exception | Status | Section |
|---|---|---|---|
| 1 | Effects that carry over to the next season's crop | OPEN | phenology-and-weather |
| 2 | Storage injury that is worse at a middle temperature than near freezing | OPEN | postharvest-and-products |
| 3 | Plant sex that has to be managed at planting | OPEN | reproduction-and-propagation |
| 4 | Propagation material restricted by licence or intellectual property | OPEN | reproduction-and-propagation |
| 5 | Flowering that growers induce or schedule | OPEN | phenology-and-weather |
| 6 | Stress applied on purpose to raise quality or set fruit | OPEN | phenology-and-weather |
| 7 | Bolting as a failure, with different trigger shapes | OPEN | phenology-and-weather |
| 8 | Harvested organ forms only inside a temperature window | OPEN | phenology-and-weather |
| 9 | Chill requirement that a farm operation can replace, and chill negation | OPEN | phenology-and-weather |
| 10 | Weather thresholds that depend on stage, organ, duration or cover | OPEN | phenology-and-weather |
| 11 | Weather that sets product quality, not yield | OPEN | phenology-and-weather |
| 12 | Properties of the growing water itself | OPEN | phenology-and-weather |
| 13 | Shade as a tolerance, requirement or yield input | OPEN | phenology-and-weather |
| 14 | Low humidity as a requirement | OPEN | phenology-and-weather |
| 15 | Photosynthetic pathway | OPEN | phenology-and-weather |
| 16 | Maturity timed by heat units | OPEN | phenology-and-weather |
| 17 | Planted pollinizers that are never harvested, and pollen as an input | OPEN | reproduction-and-propagation |
| 18 | Pollination that lowers quality or changes the product | OPEN | reproduction-and-propagation |
| 19 | Seed that comes true to type, or seed that won't | OPEN | reproduction-and-propagation |
| 20 | Seed storage behaviour outside the normal range | OPEN | reproduction-and-propagation |
| 21 | Seed dormancy and pre-sowing treatment | OPEN | reproduction-and-propagation |
| 22 | Seed unit or seed size that sets labour | OPEN | reproduction-and-propagation |
| 23 | Seed-production systems and isolation between rows | OPEN | reproduction-and-propagation |
| 24 | Planting stock with its own storage, dormancy and multiplication | OPEN | reproduction-and-propagation |
| 25 | Crop grown mainly as rootstock or planting material for another crop | OPEN | reproduction-and-propagation |
| 26 | Graft compatibility rules | OPEN | reproduction-and-propagation |
| 27 | Rows separated by a single gene or a bud sport | OPEN | reproduction-and-propagation |
| 28 | Stand life, age-yield curve and replanting | OPEN | stand-harvest-and-labour |
| 29 | Perennial grown as an annual, or annual-type crop that is perennial | OPEN | stand-harvest-and-labour |
| 30 | Crop held on the plant or in the ground past maturity | OPEN | stand-harvest-and-labour |
| 31 | Production in several phases, seasons or places | OPEN | stand-harvest-and-labour |
| 32 | Harvests on one plant that compete or exclude each other | OPEN | stand-harvest-and-labour |
| 33 | Harvest method that decides the product | OPEN | stand-harvest-and-labour |
| 34 | Time of day of harvest | OPEN | stand-harvest-and-labour |
| 35 | Field operations with no name | OPEN | stand-harvest-and-labour |
| 36 | Growth regulators as routine operations | OPEN | stand-harvest-and-labour |
| 37 | Fruit-load limits and yield set by canopy, not plant count | OPEN | stand-harvest-and-labour |
| 38 | Loss on the plant once ripe | OPEN | stand-harvest-and-labour |
| 39 | Disorders in the field from water or nutrient swings, and rain cracking | OPEN | stand-harvest-and-labour |
| 40 | Fruit formed underground | OPEN | stand-harvest-and-labour |
| 41 | Ripening off the plant, or a conditioning step before the product is usable | OPEN | postharvest-and-products |
| 42 | Quality or composition that changes in store or in the ground | OPEN | postharvest-and-products |
| 43 | Product that improves with age | OPEN | postharvest-and-products |
| 44 | Very long keeping without cold storage | OPEN | postharvest-and-products |
| 45 | Ethylene sensitivity and incompatible storage mates | OPEN | postharvest-and-products |
| 46 | Processing capacity that limits harvest | OPEN | postharvest-and-products |
| 47 | Processing that depends on the weather | OPEN | postharvest-and-products |
| 48 | Storage pests | OPEN | postharvest-and-products |
| 49 | Product eaten in grams | OPEN | postharvest-and-products |
| 50 | A living plant as the product | OPEN | postharvest-and-products |
| 51 | Product made without growing the plant in a field | OPEN | postharvest-and-products |
| 52 | Product behaviour set by a structural trait | OPEN | postharvest-and-products |
| 53 | Crop that hosts another crop's disease | OPEN | interactions-hazards-and-rules |
| 54 | Disease shared with neighbouring or nursery crops | OPEN | interactions-hazards-and-rules |
| 55 | Disease that decides where a crop can be grown | OPEN | interactions-hazards-and-rules |
| 56 | Crop that persists as a weed of the next crop | OPEN | interactions-hazards-and-rules |
| 57 | Rotation, fallow and effects on the next crop | OPEN | interactions-hazards-and-rules |
| 58 | Intercropping, relay cropping and agroforestry | OPEN | interactions-hazards-and-rules |
| 59 | Effects on the land and neighbours beyond the crop | OPEN | interactions-hazards-and-rules |
| 60 | Crop that supports another farm enterprise | OPEN | interactions-hazards-and-rules |
| 61 | Hazards outside the toxin, allergen and ergot classes | OPEN | interactions-hazards-and-rules |
| 62 | Contamination taken up from the growing water or soil | OPEN | interactions-hazards-and-rules |
| 63 | Growing or storage conditions that raise a toxin | OPEN | interactions-hazards-and-rules |
| 64 | Legal limits on the product or the harvest | OPEN | interactions-hazards-and-rules |
| 65 | Religious and cultural rules and uses | OPEN | interactions-hazards-and-rules |
| 66 | Quality tied to a named place | OPEN | interactions-hazards-and-rules |
| 67 | Value set by a calendar market window against other regions | OPEN | stand-harvest-and-labour |
| 68 | Irrigation scheduled by plant water status and deficit windows by stage | OPEN | phenology-and-weather |
| 69 | A luxury product defined by extreme hand-processing labour | OPEN | postharvest-and-products |
| 70 | A processing step bounded on both sides, with an over-processing defect | OPEN | postharvest-and-products |
| 71 | A crop blended into another crop's product as a quality or processing additive | OPEN | interactions-hazards-and-rules |

## Reviewed during the 2026-11-24 import and judged already covered

These came up in the earlier private notes but already have a home in the current template or step 3
checklist, so they were not given entries. If a research run finds the home doesn't actually hold them,
open an entry then.

- Two or more harvest flushes a year, a season offset (autumn bloom, spring harvest), several maturity
  stages from one planting, and cultivar groups that fix the product: "Harvest stages / windows" and
  "Cultivars".
- Processing deadlines measured in hours, including minimum soak times: the "Uses and processing" time
  limit.
- Rain-fed (dryland) culture: "Water regime".
- Rootstock effects on quality, delayed rootstock failure as a general rootstock note, clonal stock and
  virus carry-over: "Propagation".
- Short-day tuberization and photoperiod by cultivar: "Photoperiod sensitivity".
- Storage regime chosen by end use, curing, grading, controlled atmosphere, humidity limits, moisture-set
  keeping: "Storage (postharvest)".
- Repeat partial harvests of root crops ("milking") and dual harvest patterns: "Harvest pattern".
- Salinity tolerance that differs by stage or organ: "Soil" (salinity).
- Aluminium sensitivity, pH amendment, cluster roots: "Soil" and "Soil biology".
- Detoxification as the processing step, caustic shells, smoke and other toxins: "Hazards" plus the
  processing chain.
- Fresh-to-dried ratios, oil-mill variants, by-products returned to the land: "Uses and processing".
- Nursery-raised transplants, including of vegetatively propagated crops: "Establishment".
- Cultivar differences in chemistry, bolt resistance or disease resistance: "Cultivars".
- Non-food fibre products and multi-organ edibility: "Uses and processing" (every organ).
- Heat stress as distinct from drought, and tissue-specific frost thresholds in general: "Weather
  response" (see entry 10 for the stage- and duration-specific cases that don't fit).

Not imported because they are about classification, naming or sourcing rather than a crop trait:
category placement, hybrid origin, ploidy and genome-size disputes, landrace diversity, orphan-crop
status, which source to trust, and game-level mechanics.

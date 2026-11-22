# Research requests: outstanding

Works the crop research wants to read but couldn't get by script. Filled
requests move to [research-requests-satisfied.md](research-requests-satisfied.md).
Outstanding requests never hold up research on other crops. When one is
filled, the crop it belongs to is reopened and its doc updated.

## How to fill a request

Anyone can work on these, from any device. The fetched documents themselves
are never committed: this project keeps citations and findings only.

1. Pick an open request. **Online** ones are on the open web but block
   automated access (HTTP 403, Cloudflare or reCAPTCHA pages, redirect
   loops). **Library** ones are paywalled, print-only or otherwise need
   institutional access (books, chapters, theses, proceedings, older
   bulletins).
2. Find the work from its citation, URL or search hint, and check the title,
   year and edition match.
3. Save the document itself, not a landing page:
   - **PDF:** download the PDF, or scan the pages needed for a print work.
   - **Excel or other data files:** download the original file (`.xlsx`,
     `.csv`).
   - **HTML article:** use File → Save Page As → "Web Page, HTML Only", or
     print to PDF if the page builds its text with scripts.
4. Name it `<crop-id>--<short-name>.<ext>`, using the short name given in
   the request, for example `mango--litz-2009.pdf`.
5. Get it to whoever runs the research: in a working copy of this project,
   save it to the git-ignored `StepPlans/ManualFetch/` folder; otherwise send
   it to the researcher directly. Never add it to the repository.
6. Note in the request if what you found differs (a different edition or
   year, an abstract only, only some chapters), or if it can't be had at all.
   Ticking the box is optional; the researcher moves the entry to
   `research-requests-satisfied.md` once the file is read.

## Outstanding requests

### mandarin (2026-11-20)

- [ ] **`mandarin--ufifas-mandarin-guide`** (Online): any UF/IFAS EDIS publication
  on growing tangerines and mandarins (home or commercial).
  - **Where:** search EDIS for "tangerine" or "mandarin". The EDIS site
    blocks scripted search.
  - **Needed for:** years to first bearing, spacing, soil pH, yield per
    tree.
  - **Search result (2026-11-20):** no general guide was found. The
    "Tangerine, Mandarin and Tangelo Varieties" topic page
    (ask.ifas.ufl.edu → topics) lists per-cultivar fact sheets instead.
    The requests below replace this one; tick it if they cover the gaps.
- [ ] **`mandarin--ufifas-cross-pollination`** (Online): Cross-Pollination
  Planting Plans, UF/IFAS HS170 (https://edis.ifas.ufl.edu/publication/CH070,
  also on the topic page). Needed for which cultivars need
  pollinators and the row layouts (Finding 2).
- [ ] **`mandarin--ufifas-hs182`** (Online): Futch and Jackson, *Pollination of
  Citrus Hybrids*, UF/IFAS HS182 (cited in the Sunburst sheet).
  - **Where:** https://edis.ifas.ufl.edu/publication/CH082
  - **Needed for:** which hybrids need pollenizers, compatible pairs, and
    seediness effects (Finding 2).
- [ ] **`mandarin--ufifas-robinson`** (Online): Robinson Tangerine fact sheet.
  Needed for pollination, seed count and the 'Orlando' pollen effect.
- [ ] **`mandarin--ufifas-murcott`** (Online): HS174/CH078, Murcott (Honey
  Tangerine). Needed for excessive fruiting and alternate bearing.

### mango (2026-11-20)

- [ ] **`mango--ufifas-hs2`** (Online): Crane, Balerdi and Maguire, *Mango Growing
  in the Florida Home Landscape*, UF/IFAS EDIS HS2 (publication MG216).
  - **Where:** https://edis.ifas.ufl.edu/publication/MG216, or search
    Ask IFAS for "Mango Growing in the Florida Home Landscape". EDIS blocks
    scripts.
  - **Needed for:** cold-damage temperatures for young trees, mature
    trees and flowers; years to bearing; per-tree yield; spacing;
    fertilizer and irrigation; pollinators and fruit set per panicle.

- [ ] **`mango--cabi-datasheet`** (Online): CABI Compendium datasheet,
  *Mangifera indica* (mango): invasive species compendium.
  - **Where:** https://www.cabidigitallibrary.org/doi/10.1079/cabicompendium.32354
    (CABI returns 403 to scripts). The genus article also cites ISC
    datasheet 34505; save whichever is the *M. indica* datasheet.
  - **Needed for:** introduced and naturalized range, invasive listings,
    weediness and dispersal.

#### mango: Library requests (2026-11-22)

- [ ] **`mango--litz-2009`** (Library): Litz, R.E. (ed.), *The Mango:
  Botany, Production and Uses*, 2nd edn. CABI, Wallingford, 2009 (ISBN
  978-1-84593-489-7, to confirm). The standard monograph.
  - **Most wanted chapters:** ecophysiology (cold, waterlogging, salinity),
    the crop-production chapter (spacing, yields, labour, picking rate),
    malformation and other diseases, and postharvest.
  - **Needed for:** cold-damage temperatures; waterlogging and salinity
    thresholds; per-picker harvest rates; soil biology (mycorrhizae);
    whether malformation spreads in scionwood; the floral-induction
    model. Any chapter alone is useful.
- [ ] **`mango--kostermans-bompard-1993`** (Library): Kostermans, A.J.G.H.
  and Bompard, J.-M., *The Mangoes: Their Botany, Nomenclature,
  Horticulture and Utilization*. Academic Press (for IBPGR), London, 1993.
  - **Needed for:** the cultivated *Mangifera* relatives proposed as rows:
    kuini (*M. odorata*), bachang (*M. foetida*), binjai (*M. caesia*) and
    bambangan (*M. pajang*). Uses, toxicity of the sap, range and whether
    any is farmed rather than gathered.
- [ ] **`mango--kumar-1993`** (Library): Kumar, J., Singh, U.S. and
  Beniwal, S.P.S., "Mango malformation: one hundred years of research,"
  *Annual Review of Phytopathology* 31: 217-232 (1993).
  - **Needed for:** the cause of malformation, how it spreads (scionwood,
    mites, soil), yield losses and control.
- [ ] **`mango--schaffer-andersen-1994`** (Library): the mango chapter in
  Schaffer, B. and Andersen, P.C. (eds.), *Handbook of Environmental
  Physiology of Fruit Crops*, Vol. II: Sub-Tropical and Tropical Crops.
  CRC Press, Boca Raton, 1994.
  - **Needed for:** temperature limits for leaves, wood, flowers and fruit;
    flooding and salinity tolerance; light and water relations. A second
    source for the same gaps as Litz.
- [ ] **`mango--azevedo-2003`** (Library): Azevedo, P.V., Silva, B.B. and
  Silva, V.P.R., "Water requirements of irrigated mango orchards in
  northeast Brazil," *Agricultural Water Management* 58(3): 241-254
  (2003), doi:10.1016/S0378-3774(02)00083-5 (cited in the 'Kent' Kc
  paper).
  - **Needed for:** seasonal crop water use and Kc by phase from the same
    region, to check the 'Tommy Atkins' and 'Kent' figures already used.
- [ ] **`mango--hatton-1965`** (Library): Hatton, T.T. Jr., Reeder, W.F.
  and Campbell, C.W., *Ripening and Storage of Florida Mangos*. Marketing
  Research Report 725, USDA, Washington, 1965 (cited in USDA Handbook 66).
  - **Needed for:** cultivar-by-cultivar storage temperatures and chilling
    injury, to settle the 10 °C vs 13 °C threshold conflict.
- [ ] **`mango--mukherjee-1953`** (Library, may be on JSTOR): Mukherjee,
  S.K., "The mango: its botany, cultivation, uses and future
  improvement, especially as observed in India," *Economic Botany* 7(2):
  130-162 (1953).
  - **Needed for:** traditional uses and processing in India, landrace
    groups and the older yield figures.

### ackee (2026-11-22)

- [ ] **`ackee--ekue-2010`** (Online): Ekué, M.R.M., Sinsin, B.,
  Eyog-Matig, O. and Finkeldey, R., "Uses, traditional management,
  perception of variation and preferences in ackee (*Blighia sapida*
  K.D. Koenig) fruit traits in Benin: implications for domestication and
  conservation," *Journal of Ethnobiology and Ethnomedicine* 6: 12 (2010).
  - **Where:** https://ethnobiomed.biomedcentral.com/articles/10.1186/1746-4269-6-12
    (open access, but the PDF link returns a page instead of the file to
    scripts).
  - **Needed for:** West African uses (soap, food, shade, the "myth"
    value), management in farm systems, preferred fruit traits.
- [ ] **`ackee--cabi-datasheet`** (Online): CABI Compendium datasheet,
  *Blighia sapida* (akee).
  - **Where:** search cabidigitallibrary.org for "Blighia sapida
    datasheet" (CABI returns 403 to scripts).
  - **Needed for:** introduced and naturalized range, invasive listings,
    pests and diseases, plant-quarantine rules.
- [ ] **`ackee--bowen-forbes-2011`** (Library): Bowen-Forbes, C.S. and
  Minott, D.A., "Tracking hypoglycins A and B over different maturity
  stages: implications for detoxification of ackee (*Blighia sapida* K.D.
  Koenig) fruits," *J. Agric. Food Chem.* 59(8): 3869-3875 (2011),
  doi:10.1021/jf104623c.
  - **Needed for:** 'Butter' vs 'Cheese' toxin levels, the season effect,
    and whether the 271 mg/kg ripe-aril figure is dry or fresh weight.
- [ ] **`ackee--kean-1975`** (Library): Kean, E.A. (ed.), *Hypoglycin*
  (Academic Press, New York, 1975).
  - **Needed for:** toxin levels by fruit part and stage, the history of
    vomiting sickness, dose data.
- [ ] **`ackee--goldson-barnaby-2016`** (Library): Goldson-Barnaby, A. and
  Bailey, D., "Ackee (*Blighia sapida* K.D. Koenig): a review of its
  economic importance, bioactive components, associated health benefits
  and commercial applications," *International Journal of Fruit Science*
  16(4) (2016).
  - **Needed for:** production and export figures, processing steps and
    yields, product range.
- [ ] **`ackee--sinmisola-2019`** (Library): Sinmisola, A., Oluwasesan,
  B.M. and Chukwuemeka, A.P., "*Blighia sapida* K.D. Koenig: a review on
  its phytochemistry, pharmacological and nutritional properties,"
  *J. Ethnopharmacol.* 235: 446-459 (2019), doi:10.1016/j.jep.2019.01.017.
  - **Needed for:** composition, the cultivar count (up to 48), years to
    bearing from cuttings, ethnomedical uses.

### satsuma (next time its OUT-OF-DATE row comes up)

- [ ] **`satsuma--ufifas-hs195`** (Online): HS195/CH116, The Satsuma Mandarin
  (ask.ifas.ufl.edu → publication; save the main page or PDF, not the
  Explore, About or Metrics tabs).

### tangelo (optional, for the proposed row)

- [ ] **`tangelo--ufifas-lee`** (Online): HS172/CH080, Lee Citrus Hybrid.
- [ ] **`tangelo--ufifas-nova`** (Online): HS177/CH076, Nova Tangelo.

### Backlog from docs already committed

- [ ] **`lychee--isenberg-2016`** (Online): Isenberg, Carter, Hayes and others,
  "Quantification of Toxins in Soapberry (Sapindaceae) Arils: Hypoglycin A
  and Methylenecyclopropylglycine," *J. Agric. Food Chem.* 64(27):
  5607-5613 (2016).
  - **Where:** https://pmc.ncbi.nlm.nih.gov/articles/PMC5098216/ (PMC
    shows scripts a reCAPTCHA).
  - **Needed for:** the litchi aril HGA and MCPG values (ranges, n); only
    the abstract was read.
- [ ] **`lychee--shrivastava-2017`** (Online): Shrivastava, Kumar, Thomas and
  others, "Association of acute toxic encephalopathy with litchi
  consumption in an outbreak in Muzaffarpur, India, 2014: a case-control
  study," *Lancet Global Health* 5(4): e458-e466 (2017).
  - **Where:** https://pmc.ncbi.nlm.nih.gov/articles/PMC5354576/ or the
    Lancet page (both block scripts).
  - **Needed for:** full-text detail beyond the abstract: age
    distribution, the timing of litchi eating, the orchard-visit and
    unripe-fruit findings.
- [ ] **`lowbush-blueberry--umaine-budget-2024`** (Online): the University of Maine
  Cooperative Extension 2024 wild blueberry enterprise budgets (Excel,
  15-500 acre farm sizes).
  - **Where:** extension.umaine.edu/blueberries → enterprise budget page.
    The Excel links aren't exposed to scripts.
  - **Needed for:** labour hours by operation, costs, yields assumed.
- [ ] **`loquat--ciheam-2003`** (Online): the loquat production and market paper
  in Llácer and Badenes (eds.), *First International Symposium on
  Loquat*, Options Méditerranéennes Série A no. 58 (CIHEAM Zaragoza,
  2003).
  - **Where:** om.ciheam.org (its host did not resolve and its mirror
    gave 404 to scripts). Search the volume's table of contents for the
    production or market chapter.
  - **Needed for:** the 13-country production table, labour-by-operation
    shares, purple-spot incidence, calcium-spray results, rootstock
    lifespans.

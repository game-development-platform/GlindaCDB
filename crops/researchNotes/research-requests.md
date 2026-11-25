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

### bachang (2026-11-22)

- [ ] **`bachang--iucn-2021`** (Online): Ganesan, S.K., "*Mangifera
  foetida*," *IUCN Red List of Threatened Species* 2021:
  e.T31392A67735676, doi:10.2305/IUCN.UK.2021-3.RLTS.T31392A67735676.en.
  - **Where:** iucnredlist.org (the page needs JavaScript and returns no
    content to scripts).
  - **Needed for:** population trend, threats (felling, forest loss) and
    the range by country.
- [ ] **`bachang--fshs-2016`** (Online): "Finding a suitable interstock
  for three *Mangifera* species from tropical Asia," *Proceedings of the
  Florida State Horticultural Society* 129 (2016).
  - **Where:** https://journals.flvc.org/fshs/article/view/106017 (the
    PDF host denies automated access).
  - **Needed for:** the graft success rate on the *M. lalijiwa*
    interstock, and cold or soil notes from South Florida.
- [ ] **`bachang--campbell-2004`** (Library): Campbell, R.J., "Graft
  compatibility between *Mangifera* species and *Mangifera indica* L.
  'Turpentine' rootstocks and their subsequent horticultural traits,"
  *Acta Horticulturae* 645 (2004), doi:10.17660/ActaHortic.2004.645.35.
  - **Needed for:** the graft-failure details and any horticultural
    traits recorded in Florida.
- [ ] **`bachang--lim-2012`** (Library): Lim, T.K., "*Mangifera
  foetida*," in *Edible Medicinal and Non-Medicinal Plants*, Vol. 1:
  Fruits, pp. 82-86 (Springer, Dordrecht, 2012).
  - **Needed for:** composition, the irritant's chemistry, medicinal uses,
    and any yield or postharvest data.
- [ ] **`bachang--wong-ong-1993`** (Library): Wong, K.C. and Ong, C.H.,
  "Volatile components of the fruits of bachang (*Mangifera foetida*
  Lour.) and kuini (*Mangifera odorata* Griff.)," *Flavour and Fragrance
  Journal* 8(3): 147-151 (1993).
  - **Needed for:** the compounds behind the turpentine smell.
- [ ] **`bachang--tyug-2010`** (Library): Tyug, T.S., Johar, M.H. and
  Ismail, A., "Antioxidant properties of fresh, powder, and fiber products
  of mango (*Mangifera foetida*) fruit," *International Journal of Food
  Properties* 13(4): 682-691 (2010), doi:10.1080/10942910902741834.
  - **Needed for:** the 56% edible share (seen only in a snippet) and the
    processing of powder and fibre products.
- [ ] **`bachang--davison-1995`** (Library): Davison, J. (ed.), *Fruit of
  Indonesia* (PT Mekar Unggul Sari, Jakarta, 1995), p. 47, ISBN
  981-3018-11-9.
  - **Needed for:** years to bearing, fruit weight and uses (the
    encyclopedia's source).
- [ ] **`bachang--amron-2010`** (Library): Amron, A., Awang, K., Mat Lin,
  R., Idris, S., Hasran, M. and Milan, A.R., "Distribution and diversity
  of *Mangifera* species on farm in Malaysia," *Journal of Tropical
  Agriculture and Food Science* (Malaysia), pp. 89-95 (2010).
  - **Needed for:** tree counts by state and how the trees are kept.
- The genus monograph (Kostermans and Bompard 1993) is already requested
  under mango as `mango--kostermans-bompard-1993`; it serves bachang too.

### bambangan (2026-11-22)

- [ ] **`bambangan--iucn-1998`** (Online): World Conservation Monitoring
  Centre, "*Mangifera pajang*," *IUCN Red List of Threatened Species*
  1998: e.T31394A9625586, doi:10.2305/IUCN.UK.1998.RLTS.T31394A9625586.en.
  - **Where:** iucnredlist.org (the page needs JavaScript).
  - **Needed for:** the basis of the Vulnerable listing and any threats
    named.
- [ ] **`bambangan--ums-proximate-2016`** (Online): Mohd Hafizuddin
  Shaiful Amran, "Analisis proksimat *Mangifera pajang* (buah bambangan)"
  (Universiti Malaysia Sabah, 9 June 2016; in Malay).
  - **Where:** cited by the Wikipedia article "Mangifera pajang"; search
    the UMS site.
  - **Needed for:** fresh-pulp water, energy, protein, fat and sugars.
- [ ] **`bambangan--jahurul-2019`** (Library): Jahurul, M.H.A., Zaidul,
  I.S.M., Beh, L., Sharifudin, M.S., Siddiquee, S., Hasmadi, M., Sahena,
  F., Mansoor, A.H., Lee, J.S. and Jinap, S., "Valuable components of
  bambangan fruit (*Mangifera pajang*) and its co-products: a review,"
  *Food Research International* 115: 105-115 (2019),
  doi:10.1016/j.foodres.2018.08.017.
  - **Needed for:** proximate composition, production and trade figures,
    seed and kernel shares, and the kernel-fat yield basis.
- [ ] **`bambangan--regis-baptist-2012`** (Library): Regis, P. and
  Baptist, J.J., *Food Heritage of Sabah: A Cultural Perspective*
  (Department of National Heritage, Malaysia, 2012), ISBN
  978-983-3862-19-1.
  - **Needed for:** the traditional pickle method and salt ratio, and any
    ritual or festival use.
- [ ] **`bambangan--ibrahim-2013`** (Library): Ibrahim, M., Ismail, A.,
  Al-Sheraji, S.H., Azlan, A. and Hamid, A.A., "Effects of *Mangifera
  pajang* Kostermans juice on plasma antioxidant status and liver and
  kidney function in normocholesterolemic subjects," *Journal of
  Functional Foods* 5(4): 1900-1908 (2013), doi:10.1016/j.jff.2013.09.011.
  - **Needed for:** the juice processing and dose, and any safety
    findings.
- [ ] **`bambangan--prosea-2-1991`** (Library): Verheij, E.W.M. and
  Coronel, R.E. (eds.), *Plant Resources of South-East Asia* No. 2:
  Edible Fruits and Nuts (Pudoc, Wageningen, 1991), the *Mangifera*
  entries by J.M. Bompard.
  - **Needed for:** whether the printed bambangan entry really shares
    bachang's agronomy paragraph (spacing, budding, pests, West Java
    harvest), as the Pl@ntUse copy does.
- The Fairchild graft paper (`bachang--campbell-2004`) and the genus
  monograph (`mango--kostermans-bompard-1993`) serve bambangan too.

### bilberry (2026-11-22)

- [ ] **`bilberry--finland-seasonal-act-2025`** (Online): Finnish Government
  and Ministry for Foreign Affairs notices on wild-berry pickers under the
  Seasonal Workers Act (2025), including "2,600 seasonal work visas
  granted to foreign wild-berry pickers".
  - **Where:** valtioneuvosto.fi and um.fi (the pages return no content to
    scripts).
  - **Needed for:** the permit rules, pay terms and visa numbers.
- [ ] **`bilberry--abo-caesium-2023`** (Online): the 2023 Åbo Akademi study
  of caesium-137 in bilberries picked in 2019, *Journal of Food
  Composition and Analysis* (article S0889157523004970).
  - **Where:** research.abo.fi (the PDF link returns a page to scripts).
  - **Needed for:** current activity levels and the dose estimate.
- [ ] **`bilberry--nestby-2014`** (Online): Nestby, R. and colleagues,
  planted *V. myrtillus* on agricultural land in mid-Norway, *Journal of
  Berry Research* 4(3) (2014), and the NIBIO forest-field trial report
  (NIBIO Brage handle 11250/2499538).
  - **Needed for:** semi-cultivation yields, fertilizer and pruning
    effects, and years to bearing.
- [ ] **`bilberry--herbalgram-2012`** (Online): Foster, S. and Blumenthal,
  M., "The adulteration of commercial bilberry extracts," *HerbalGram* 96
  (2012).
  - **Where:** herbalgram.org (returns a stub page to scripts).
  - **Needed for:** the full adulterant list and test methods.
- [ ] **`bilberry--kardell-eriksson-1995`** (Library): Kardell, L. and
  Eriksson, L., the Swedish 15-year bilberry and lingonberry yield and
  fertilization study (1990 and 1995 reports).
  - **Needed for:** year-by-year yields, the frost link, fertilizer
    response.
- [ ] **`bilberry--turtiainen-2011`** (Library): Turtiainen, M. and
  colleagues (2011), Finnish bilberry and lingonberry yields in poor and
  abundant years and the share picked.
  - **Needed for:** the 92-312 million kg range and the 5-6% share picked.
- [ ] **`bilberry--small-catling-1999`** (Library): Small, E. and Catling,
  P.M., *Canadian Medicinal Crops* (NRC Research Press, Ottawa, 1999),
  the bilberry chapter.
  - **Needed for:** the North American range and the medicinal trade.

### binjai (2026-11-22)

- [ ] **`binjai--iucn-2021`** (Online): Ganesan, S.K., "*Mangifera
  caesia*," *The IUCN Red List of Threatened Species* (2021).
  - **Where:** iucnredlist.org (needs JavaScript).
  - **Needed for:** the current status, native range and threats.
- [ ] **`binjai--cacah-ambuyat-2020`** (Online): Rokiah Mahmud, "Dipping
  into the world of 'cacah ambuyat'," *Borneo Bulletin* (5 June 2020).
  - **Where:** borneobulletin.com.bn (returns no content to scripts).
  - **Needed for:** how the binjai *cacah* is made.
- [ ] **`binjai--maid-2017`** (Online): Maid, M. and colleagues (2017),
  the Dusun medicinal plant survey cited by Tanbuda and colleagues
  (2025).
  - **Needed for:** what the medicinal use of binjai is.
- [ ] **`binjai--kostermans-bompard-1993`** (Library): Kostermans,
  A.J.G.H. and Bompard, J.M., *The Mangoes: Their Botany, Nomenclature,
  Horticulture and Utilization* (Academic Press, London, 1993),
  pp. 149-151.
  - **Needed for:** fruit weight, yield, years to bearing, flood
    tolerance and the native-range question.
- [ ] **`binjai--lim-2012`** (Library): Lim, T.K., "*Mangifera caesia*,"
  in *Edible Medicinal and Non-Medicinal Plants*, Vol. 1: Fruits
  (Springer, Dordrecht, 2012).
  - **Needed for:** composition, the irritant's chemistry, medicinal uses.
- The printed PROSEA entry is already requested as
  `bambangan--prosea-2-1991`.

### clementine (2026-11-22)

- [ ] **`clementine--montalt-2021`** (Online): Montalt, R. and colleagues,
  "Parthenocarpy and self-incompatibility in
  mandarins," *Agronomy* 11(10): 2023 (2021).
  - **Where:** mdpi.com (returns a stub page to scripts).
  - **Needed for:** set and seed counts across clementine cultivars.
- [ ] **`clementine--corse-igp`** (Online): the "Clémentine de Corse" IGP
  specification (INAO, IG/19/01).
  - **Where:** inao.gouv.fr (the extranet PDF did not download).
  - **Needed for:** the exact colour, size, juice, leaf and
    no-degreening rules.
- [ ] **`clementine--morocco-stats`** (Online): Moroccan clementine area,
  production and exports by season (Ministry of Agriculture, Office des
  Changes, or the USDA GAIN Morocco Citrus Annual).
  - **Needed for:** replacing snippet figures that mix clementines with
    other mandarins.
- [ ] **`clementine--spain-area`** (Online): MAPA *Anuario de
  Estadística* or the *Encuesta sobre superficies y rendimientos*,
  clementine area and yield.
  - **Needed for:** yield per hectare.
- [ ] **`clementine--agusti-fruit-set`** (Library): Agustí, M. and
  colleagues on girdling and gibberellic acid for clementine fruit set
  (for example, *Citricultura*, Mundi-Prensa).
  - **Needed for:** practice timings and responses.
- [ ] **`clementine--samaan-1982`** (Library): Samaan, L.G., "Studies on
  the origin of Clementine tangerine," *Euphytica* 31: 167-173 (1982).
  - **Needed for:** the origin debate.

### kasturi (2026-11-22)

- [ ] **`kasturi--iucn-2016`** (Online): Rhodes, L. and Maxted, N.,
  "*Mangifera casturi*," *The IUCN Red List of Threatened Species*
  (2016), doi:10.2305/IUCN.UK.2016-3.RLTS.T32059A61526819.en.
  - **Where:** iucnredlist.org (needs JavaScript).
  - **Needed for:** the assessment's range, threats and population notes.
- [ ] **`kasturi--ayala-silva-2013`** (Online): Ayala-Silva, T., Gubbuk,
  H. and Urbina, C., "Physico-chemical evaluation of 'Casturi' mango,"
  *Proc. Fla. State Hort. Soc.* 126 (2013), full text.
  - **Where:** journals.flvc.org (the PDF link returns a viewer page to
    scripts).
  - **Needed for:** flowering, tree data and the full descriptor set.
- [ ] **`kasturi--pertanian-repository`** (Online): the Ministry of
  Agriculture document on kasturi at repository.pertanian.go.id
  (bitstream 148f1d74-…; the download failed).
  - **Needed for:** confirming the Rp 7,500/kg price and its year, and
    the farmers' reasons for not planting.
- [ ] **`kasturi--gunawan-2024`** (Online): Gunawan and colleagues,
  ethnobotany and conservation of kasturi by the Banjar people,
  *Biodiversitas* (2024).
  - **Needed for:** local uses, harvest practice, any ritual use.
- [ ] **`kasturi--barbosa-gamez-2017`** (Library): Barbosa Gámez, I. and
  colleagues, "Changes in the nutritional quality of five *Mangifera*
  species harvested at two maturity stages," *J. Sci. Food Agric.*
  (2017).
  - **Needed for:** composition values per 100 g.
- [ ] **`kasturi--ledesma-2025`** (Library): Ledesma, N. and Arisandi,
  N., *Acta Horticulturae* 1415: XIII International Mango Symposium
  (2025), doi:10.17660/ActaHortic.2025.1415.22.
  - **Needed for:** accessions in the US and South Kalimantan, bearing
    and propagation.
- Kostermans and Bompard (1993) is already requested as
  `binjai--kostermans-bompard-1993`; its *M. casturi* entry is needed
  too (bearing, embryony, sap).

### kuini (2026-11-23)

- [ ] **`kuini--production-stats`** (Online): kuini area and production
  for any country (Malaysia DOA *Statistik Tanaman Buah*, Indonesia BPS
  *Statistik Hortikultura* "kweni" line, Philippine PSA "huani").
  - **Needed for:** scale, yield per hectare and price.
- [ ] **`kuini--bondad-1982`** (Library): Bondad, N., "Mango and its
  relatives in the Philippines," *Philippine Geographical Journal*
  26(2): 88-100 (1982).
  - **Needed for:** huani and sangay in the Philippines: season, yield,
    uses.
- [ ] **`kuini--ochse-1931`** (Library): Ochse, J.J. and Bakhuizen van den
  Brink, R.C., *Vruchten en vruchtenteelt in Nederlandsch-Indië* (Kolff,
  Batavia, 1931), pp. 15-17.
  - **Needed for:** the Javanese forms, kernel flour preparation, and
    years to bearing.
- Kostermans and Bompard (1993) is already requested as
  `binjai--kostermans-bompard-1993`; its *M. odorata* entry is needed
  too.

### mamoncillo (2026-11-23)

- [ ] **`mamoncillo--bystrom-2009`** (Online): "Phenolics, sugars,
  antimicrobial and free-radical-scavenging activities of *Melicoccus
  bijugatus* Jacq. fruits from the Dominican Republic and Florida"
  (2009), PMID 19444610.
  - **Needed for:** pulp sugars and composition, and its author list.
- [ ] **`mamoncillo--pulp-hga`** (Online): any measurement of hypoglycin
  A in mamoncillo pulp, and in roasted or cooked seeds.
  - **Needed for:** the Hazards section (pulp safety, roasted-seed use).
- [ ] **`mamoncillo--yield`** (Online): yield per tree and years to first
  bearing in Puerto Rico, Florida or Colombia (for example, UF/IFAS or
  the Puerto Rico Agricultural Experiment Station).
  - **Needed for:** Yield and first bearing, both Not sourced.
- [ ] **`mamoncillo--acevedo-monograph`** (Library): Acevedo-Rodríguez,
  P., the monograph on *Talisia* and *Melicoccus* (Flora Neotropica).
  - **Needed for:** taxonomy, sexes and native range.

### mangosteen (2026-11-23)

- [ ] **`mangosteen--thai-flowering-stress`** (Online): the Prince of
  Songkla University studies of soil-moisture stress, irrigation and
  flowering in mangosteen (Sdoodee and colleagues), seen only as search
  snippets. Search hints: Songklanakarin Journal of Science and
  Technology; ISHS Acta Horticulturae articles 575_96 and 975_47
  (https://ishs.org/ishs-article/575_96/, https://ishs.org/ishs-article/975_47/).
  - **Needed for:** Finding 3 (dry-spell length, any overshoot penalty)
    and Finding 4 (the -70 kPa preharvest deficit, gamboge incidence).
- [ ] **`mangosteen--pankasemsuk-1996`** (Online): Pankasemsuk, T.,
  Garner, J.O. Jr., Matta, F.B. and Silver, J.L. (1996), "Translucent
  flesh disorder of mangosteen fruit (*Garcinia mangostana* L.),"
  *HortScience* 31:112-113.
  - **Needed for:** the translucent-flesh cause and its effect on sugars
    and acidity.
- [ ] **`mangosteen--osman-milan-2006`** (Library): Osman, M. bin and
  Milan, A.R. (2006), *Mangosteen: Garcinia mangostana L.* (Fruits for
  the Future 9), Southampton Centre for Underutilised Crops, ISBN
  0854328173.
  - **Needed for:** named types, costs, labour, yields and agronomy.
- [ ] **`mangosteen--yaacob-tindall-1995`** (Library): Yaacob, O. and
  Tindall, H.D. (1995), *Mangosteen Cultivation*, FAO Plant Production
  and Protection Paper 129, FAO, Rome.
  - **Needed for:** spacing, fertilizer, labour and flowering practice.
- [ ] **`mangosteen--richards-1990`** (Library): Richards, A.J. (1990),
  "Studies in *Garcinia*, dioecious tropical fruit trees: the origin of
  the mangosteen (*G. mangostana* L.)," *Botanical Journal of the
  Linnean Society* 103(4):301-308.
  - **Needed for:** the hybrid-origin theory and chromosome counts.
- [ ] **`mangosteen--wong-klemmer-2008`** (Library): Wong, L.P. and
  Klemmer, P.J. (2008), "Severe lactic acidosis associated with juice of
  the mangosteen fruit *Garcinia mangostana*," *American Journal of
  Kidney Diseases* 51(5):829-833, doi:10.1053/j.ajkd.2007.12.043.
  - **Needed for:** the dose and duration in the supplement case.

### marang (2026-11-23)

- [ ] **`marang--primack-1985`** (Library): Primack, R.B. (1985),
  "Comparative studies of fruits in wild and cultivated trees of
  chempedak (*Artocarpus integer*) and terap (*Artocarpus
  odoratissimus*) in Sarawak, East Malaysia, with additional information
  on the reproductive biology of the Moraceae in South-East Asia,"
  *Malayan Nature Journal* 39:1-39.
  - **Needed for:** wild versus cultivated fruit, flowering biology and
    pollination (Finding 4).
- [ ] **`marang--coronel-1986`** (Library): Coronel, R.E. (1986),
  *Promising Fruits of the Philippines*, 2nd ed., College of
  Agriculture, University of the Philippines Los Baños, pp. 500-502.
  - **Needed for:** Philippine agronomy, yield per tree and storage.
- [ ] **`marang--gacus-gomez-2026`** (Online): Gacus, R.B. and Gomez, N.U.
  (2026), "Profitability, efficiency, and productivity of marang
  (*Artocarpus odoratissimus*) in Southern Mindanao, Philippines,"
  *International Journal of Agricultural Technology* 22(1):131-144,
  doi:10.63369/ijat.2026.22.1.131-144
  (https://li04.tci-thaijo.org/index.php/IJAT/article/view/9676).
  - **Needed for:** current Mindanao production, yields, costs and
    seasons.
- [ ] **`marang--alvarado-2023`** (Library): Alvarado, M.C. (2023),
  "Marang fruit (*Artocarpus odoratissimus*) waste: a promising resource
  for food and diverse applications," *Food Bioengineering* 2:350-359.
  - **Needed for:** processing chains and byproducts.
- [ ] **`marang--horticulturae-2023-browning`** (Online): the 2023
  *Horticulturae* study of terap peel browning in storage (DOAJ record
  https://doaj.org/article/7044a1a0aed84db5ae90e01608eabcd9).
  - **Needed for:** storage temperature and shelf life (Finding 3).
- [ ] **`marang--gardner-2022`** (Library): Gardner, E.M. and colleagues
  (2022), *Current Biology* 32(11):R511-R512,
  doi:10.1016/j.cub.2022.04.062, full text.
  - **Needed for:** the traits separating *A. mutabilis* from marang.

### mata_kucing (2026-11-23)

- [ ] **`mata_kucing--wong-1988-isau`** (Online): Wong, K.C., Ibrahim
  Yusof, Pearce, K.G. and Alau Tayan, D. (1988), "ISAU - A potential
  tropical longan (Dihocarpus longan) of Sarawak," 3rd National Biology
  Symposium, 22-24 Nov. 1988, Subang Jaya, Selangor. UPM repository
  record 51601 (http://psasir.upm.edu.my/id/eprint/51601/); also a CORE
  copy (https://core.ac.uk/download/153827606.pdf). Both timed out or
  returned a challenge page.
  - **Needed for:** fruit and aril weights by accession, taste,
    propagation results (Finding 3).
- [ ] **`mata_kucing--doa-fruit-statistics`** (Online): Jabatan Pertanian
  Malaysia (Department of Agriculture), *Statistik Tanaman Buah-Buahan*
  (Fruit Crop Statistics), any recent year, with its mata kucing row.
  doa.gov.my timed out; a 2021 copy is on Scribd (document 696554090).
  - **Needed for:** planted area, harvested area and production by state
    (Finding 2, Yield).
- [ ] **`mata_kucing--unimas-2006-isau-cuttings`** (Online): UNIMAS thesis,
  "Vegetative propagation of Isau (Dimocarpus Longana var. Malesianus
  Leenh.) by cuttings" (2006), https://ir.unimas.my/id/eprint/18089/
  (timed out).
  - **Needed for:** rooting success and the planting-material constraint.
- [ ] **`mata_kucing--jitipari-2024-ihau`** (Online): a 2024 paper in
  *JITIPARI* (Universitas Slamet Riyadi) on Kalimantan local fruits
  including *ihau*,
  https://ejurnal.unisri.ac.id/index.php/jtpr/article/download/10314/5887
  (timed out; authors and title not yet recorded).
  - **Needed for:** proximate composition and vitamin C.
- [ ] **`mata_kucing--lim-2013`** (Library): Lim, T.K. (2013), *Edible
  Medicinal and Non-Medicinal Plants*, Vol. 6, *Fruits*, Springer,
  pp. 30-38 (var. *echinatus*, doi:10.1007/978-94-007-5628-1_5; var.
  *malesianus*, doi:10.1007/978-94-007-5628-1_6).
  - **Needed for:** composition, uses and agronomy for both varieties.
- [ ] **`mata_kucing--wong-2001`** (Library): Wong, K.C. (2001),
  "Variations of local longan in Malaysia," *Acta Horticulturae*
  558:103-106, doi:10.17660/ActaHortic.2001.558.12.
  - **Needed for:** the full fruit and vegetative data for the four groups.
- [ ] **`mata_kucing--wong-gan-1992`** (Library): Wong, K.C. and Gan, Y.Y.
  (1992), "The diversity of Dimocarpus longan ssp. malesianus var.
  malesianus in Sarawak," *Acta Horticulturae* 292:29-39.
  - **Needed for:** the Sarawak race survey.
- [ ] **`mata_kucing--leenhouts-1971`** (Library): Leenhouts, P.W. (1971),
  "A revision of Dimocarpus (Sapindaceae)," *Blumea* 19:113-131.
  - **Needed for:** variety definitions and ranges.
- [ ] **`mata_kucing--van-welzen-1988`** (Library): van Welzen, P.C., Lamb,
  A. and Wong, W.W.W. (1988), "Edible Sapindaceae in Sabah," *Nature
  Malaysiana* 13:10-25.
  - **Needed for:** var. *echinatus* and *kakus* in Sabah.

### medlar (2026-11-23)

- [ ] **`medlar--cristofori-2019`** (Library): Cristofori, V., Silvestri,
  C., Pica, A.L., Bertazza, G. and Bignami, C. (2019), "Evaluation of four
  medlar cultivars: agronomical, pomological and qualitative traits,"
  *European Journal of Horticultural Science* 84(6):350-358,
  doi:10.17660/eJHS.2019/84.6.4.
  - **Needed for:** measured yield per tree and per hectare on quince
    (Yield, Estimates).
- [ ] **`medlar--baird-thieret-1989`** (Library): Baird, J.R. and Thieret,
  J.W. (1989), "The medlar (*Mespilus germanica*, Rosaceae) from antiquity
  to obscurity," *Economic Botany* 43(3):328-372, doi:10.1007/BF02858732.
  - **Needed for:** history, cultivars, uses and any ritual use.
- [ ] **`medlar--glew-2003`** (Library): Glew, R.H., Ayaz, F.A., Sanz, C.,
  VanderJagt, D.J., Huang, H.-S., Chuang, L.-T. and Strnad, M. (2003),
  "Changes in sugars, organic acids and amino acids in medlar (*Mespilus
  germanica* L.) during fruit development and maturation," *Food
  Chemistry* 83(3):363-369.
  - **Needed for:** the sugar-during-bletting conflict (Finding 1).
- [ ] **`medlar--selcuk-erkan-2015`** (Library): Selcuk, N. and Erkan, M.
  (2015), medlar quality during long-term storage in the Palliflex
  controlled-atmosphere system, *Postharvest Biology and Technology*
  100:81-90.
  - **Needed for:** controlled-atmosphere storage life of hard fruit.
- [ ] **`medlar--tuik-series`** (Online): Turkish Statistical Institute,
  crop production statistics, medlar (*muşmula*) tree numbers, area and
  production by year and province (https://data.tuik.gov.tr or
  veriportali.tuik.gov.tr; not reached this pass).
  - **Needed for:** a yield per bearing tree and the trend after 2020
    (Finding 2).
- [ ] **`medlar--eu-2019-2072-consolidated`** (Online): the current
  consolidated text of Commission Implementing Regulation (EU) 2019/2072,
  Annexes III and IX, on EUR-Lex.
  - **Needed for:** confirming the current fire-blight protected zones
    and host-genus wording (Invasiveness / biosecurity).

### meyer_lemon (2026-11-23)

- [ ] **`meyer-lemon--curk-2016`** (Online): Curk et al. (2016), "Phylogenetic origin of limes and lemons revealed by cytoplasmic and nuclear markers," *Annals of Botany* 117(4) (PMC4817432). The PMC OAI service would not return it.
  - **Needed for:** the maternal parent and the first cytoplasm placement.
- [ ] **`meyer-lemon--citrus-nz-stats`** (Online): Citrus New Zealand industry statistics: Meyer area, production, export volume and value.
  - **Needed for:** a Meyer-only area, yield per hectare and the export figure (only all-lemon census area so far).
- [ ] **`meyer-lemon--freshplaza-date`** (Online): the publication date of the FreshPlaza Gisborne citrus report (the date was missing from the extracted page).
  - **Needed for:** dating the 24% Japan sales rise.
- [ ] **`meyer-lemon--postharvest`** (Online): a Meyer-specific storage temperature and storage-life study.
  - **Needed for:** the Storage line; the lemon regime is unsafe given chill sensitivity.
- [ ] **`meyer-lemon--juice-chemistry`** (Online): measured soluble solids, titratable acidity and juice yield for Meyer.
  - **Needed for:** Composition and the "sweeter lemon" claim.
- [ ] **`meyer-lemon--citrus-industry-1967`** (Library): *The Citrus Industry*, Vol. 1 (1967), the Meyer lemon description.
  - **Needed for:** reading the full text that UC Riverside quotes, including the ban and the historical plantings.
- [ ] **`meyer-lemon--te-ara-1966`** (Online): the 1966 New Zealand encyclopedia (Te Ara archive) citrus table.
  - **Needed for:** confirming the snippet-level 58 ha Meyer figure.

### mountain_papaya (2026-11-23)

- [ ] **`mountain-papaya--inia-status-bulletin`** (Online): the INIA (Chile) bulletin on the current status of papayo cultivation used in the 2026-10-03 doc (regional yields, year-4/5 peak, 7-8-year cycle); not re-found this pass.
  - **Needed for:** a sourced yield per hectare and the yield-by-age curve.
- [ ] **`mountain-papaya--nrc-1989`** (Online): National Research Council, *Lost Crops of the Incas* (1989), "Highland Papayas," pp. 252-261, via the free NAP PDF (the online reader serves page images only).
  - **Needed for:** Andean (non-Chilean) cultivation, frost tolerance and yield.
- [ ] **`mountain-papaya--moya-leon-2004`** (Online): Moya-León et al. (2004), *Postharvest Biology and Technology* 34(2): 211-218, full text.
  - **Needed for:** storage temperature and storage life.
- [ ] **`mountain-papaya--mendez-2025`** (Online): Méndez et al. (2025), *Horticulturae* 11: 1165, full text (MDPI blocked automated access).
  - **Needed for:** postharvest temperatures, packaging and 1-MCP practice.
- [ ] **`mountain-papaya--fia-pyt-2014-0033`** (Online): the FIA final report for project PYT-2014-0033.
  - **Needed for:** the replant-barrier cause, the viruses present, planting density and selection yields.
- [ ] **`mountain-papaya--ciren-odepa-area`** (Online): CIREN/ODEPA fruit cadastre series for papayo by region.
  - **Needed for:** reconciling 180 ha (2019), 225 ha and 103 ha (Coquimbo 2024).

### nectarine (2026-11-23)

- [ ] **`nectarine--wen-1995`** (Library): Wen, I.-C., K. E. Koch and W. B. Sherman (1995), "Comparing fruit and tree characteristics of two peaches and their nectarine mutants," *Journal of the American Society for Horticultural Science* 120: 1-3.
  - **Needed for:** measured peach-versus-nectarine differences in fruit size, firmness, colour and tree traits.
- [ ] **`nectarine--weinberger-1975`** (Library): Weinberger, J. H. (1975), *Growing Nectarines*, USDA Agricultural Research Service, Agriculture Information Bulletin 379.
  - **Needed for:** pollination and self-fertility, cracking, disease susceptibility and US practice.
- [ ] **`nectarine--crisosto-1999`** (Online): Crisosto, C. H., F. G. Mitchell and Z. Ju (1999), "Susceptibility to chilling injury of peach, nectarine, and plum cultivars grown in California," *HortScience* 34: 1116-1118.
  - **Needed for:** per-cultivar chilling-injury ratings for nectarines.
- [ ] **`nectarine--gibert-cracks`** (Online): Gibert et al., the INRAE papers on natural cuticular cracks of nectarine, their link to irrigation, and *Monilinia laxa* infection (search hint: HAL record hal-03935451; Gibert et al. 2007 and 2009). HAL served a bot-challenge page.
  - **Needed for:** crack density, timing, the irrigation effect and infection rates.
- [ ] **`nectarine--ufifas-mg374`** (Online): UF/IFAS EDIS MG374, *Florida Peach and Nectarine Varieties* (current revision), https://ask.ifas.ufl.edu/publication/MG374 (redirect loop for scripts).
  - **Needed for:** the current Florida nectarine cultivar table (chill units, fruit development period, flesh type) and settling the 100-200 vs. 200-300 chill-unit conflict.
- [ ] **`nectarine--amygdalin-review`** (Online): the review "Amygdalin: Toxicity, Anticancer Activity and Analytical Procedures for Its Determination in Plant Seeds," *Molecules* (2021), PMC8069783 (reCAPTCHA).
  - **Needed for:** confirming the 196 vs. 710 mg HCN/kg kernel figures and their primary source.
- [ ] **`nectarine--jin-2020`** (Library): Jin, J., et al. (2020), "Selection of Pru p 3 hypoallergenic peach and nectarine varieties," *Allergy* 75(5): 1256-1260, doi:10.1111/all.14102, with its supplementary table.
  - **Needed for:** nectarine Pru p 3 contents by variety and month.
- [ ] **`nectarine--hpwra`** (Online): Hawaii-Pacific Weed Risk Assessment, *Prunus persica*, https://plantpono.org/wp-content/uploads/Prunus-persica.pdf (text not extractable by script).
  - **Needed for:** the score, outcome and naturalisation evidence.
- [ ] **`nectarine--layne-bassi-2008`** (Library): Layne, D. R. and D. Bassi (eds.) (2008), *The Peach: Botany, Production and Uses*, CAB International, Wallingford.
  - **Needed for:** nectarine-specific chapters on world production, cultivars, pollination, elevation and replant.

### olive (2026-11-23)

- [ ] **`olive--ucanr-8267`** (Online): Yada, S. and L. J. Harris (2007), *Olives: Safe Methods for Home Pickling*, UC ANR Publication 8267, doi:10.3733/ucanr.8267, https://escholarship.org/uc/item/55d9628m (bot-challenge page for scripts).
  - **Needed for:** the primary curing recipes and canning times, in place of the county summary.
- [ ] **`olive--cold-review-2022`** (Online): the 2022 *Plants* review "Cold Stress, Freezing Adaptation, Varietal Susceptibility of *Olea europaea* L." (PMC9144808; reCAPTCHA, MDPI access denied).
  - **Needed for:** frost thresholds by organ and stage, cultivar hardiness, frost effects on oil, and any elevation limits.
- [ ] **`olive--saumitou-2017`** (Online): Saumitou-Laprade, P., et al. (2017), "Elucidation of the genetic architecture of self-incompatibility in olive," *Evolutionary Applications* 10(9): 860-880, with the replies in the same issue (PMC5680433, PMC5680419, PMC5680420).
  - **Needed for:** the incompatibility groups of major cultivars and pollinizer planning.
- [ ] **`olive--haberman-2017`** (Library): Haberman, A., et al. (2017), *Plant, Cell and Environment* 40(8), on *FT* genes and olive flower induction.
  - **Needed for:** the winter-cold flowering mechanism and whether photoperiod plays any part.
- [ ] **`olive--fdc-table-olives`** (Online): USDA FoodData Central, SR Legacy "Olives, ripe, canned" and "Olives, pickled, canned or bottled, green" (API rate-limited this pass).
  - **Needed for:** composition per 100 g of cured olives.
- [ ] **`olive--connor-fereres-2005`** (Library): Connor, D. J. and E. Fereres (2005), "The physiology of adaptation and yield expression in olive," *Horticultural Reviews* 31: 155-229.
  - **Needed for:** alternate bearing, chill, cold limits, photoperiod and elevation in one review.
- [ ] **`olive--milling-delay`** (Online): an IOC or university technical note on maximum fruit holding time before milling, and two-phase versus three-phase decanter mass balance.
  - **Needed for:** the oil processing chain dropped this pass.
- [ ] **`olive--el-cultivo-del-olivo`** (Library): Barranco, D., R. Fernández-Escobar and L. Rallo (eds.), *El Cultivo del Olivo* (Mundi-Prensa, latest edition).
  - **Needed for:** propagation, cultivars, alternate bearing, nutrition and replant.

### orange (2026-11-23)

- [ ] **`orange--uc-navel-costs`** (Online): the latest UC Cooperative Extension / UC Agricultural Issues Center sample cost study for navel oranges, San Joaquin Valley (coststudies.ucdavis.edu returned 403).
  - **Needed for:** spacing, years to bearing, yield by age, water, nitrogen, frost protection, labour hours by operation.
- [ ] **`orange--ufifas-production-guide`** (Online): UF/IFAS *Florida Citrus Production Guide*, current edition (HLB, nutrition and irrigation chapters).
  - **Needed for:** HLB management, its yield effect, and nutrient rates.
- [ ] **`orange--faostat-area`** (Online): FAOSTAT Crops and Livestock, "Oranges" (item 0571), area harvested, yield and production for 2023-2024.
  - **Needed for:** world area and yield (FAS gives tonnage only).
- [ ] **`orange--blood-anthocyanin`** (Online): a peer-reviewed paper on temperature and anthocyanin accumulation in blood oranges (e.g. work on 'Tarocco' or 'Moro' in Sicily and the Ruby gene).
  - **Needed for:** the cold-night colour threshold for the blood group.
- [ ] **`orange--hlb-first-detection`** (Online): a primary record of HLB's first US detection (Miami-Dade, 2005) and Florida production since.
  - **Needed for:** dating the HLB decline in Finding 2.

### persimmon (2026-11-23)

- [ ] **`persimmon--faostat-production`** (Online): FAOSTAT Crops and Livestock, "Persimmons" (item 0587), area harvested, yield and production by country for 2023-2024.
  - **Needed for:** world totals (snippets give 5.07 vs. 5.9 Mt), Spain's tonnage, and world yield.
- [ ] **`persimmon--queensland-kit`** (Library): George et al. (2005), *Sweet Persimmon Information Kit*, Queensland DAFF Agrilink Q105102.
  - **Needed for:** labour hours by operation, water use, yields by tree age, and tropical/subtropical climate limits.
- [ ] **`persimmon--rojo-brillante-irrigation`** (Online): Intrigliolo et al. (2012), "Regulated Deficit Irrigation of 'Rojo Brillante' Persimmon," *Acta Horticulturae* 1038: 415-422, or a Spanish (IVIA) persimmon irrigation guide.
  - **Needed for:** seasonal water use and crop coefficients (no FAO-56 row).
- [ ] **`persimmon--bezoar-review`** (Online): full text of Iwata et al. (2015), review of gastrointestinal bezoars, *World J. Gastrointest. Endosc.* (PMC4400622), or another peer-reviewed review of diospyrobezoars.
  - **Needed for:** confirming the snippet-level Hazards entry.
- [ ] **`persimmon--kakishibu`** (Online): a primary or scholarly source on kakishibu (fermented persimmon tannin juice): production, ageing and uses.
  - **Needed for:** a non-food processing chain (old snippet claims were dropped).
- [ ] **`persimmon--japan-research-review`** (Online): Yakushiji and Nakatsuka (2007), "Recent Persimmon Research in Japan," *Japanese Journal of Plant Science* 1(2): 42-62.
  - **Needed for:** Japanese area, yields, dwarfing rootstock performance and photoperiod.

### pomegranate (2026-11-23)

- [ ] **`pomegranate--uc-2010-costs`** (Online): Day, Klonsky and De Moura (2010), UCCE *Sample Costs to Establish and Produce Pomegranates*, southern San Joaquin Valley (the UF/IFAS mirror returned an HTML page), or any newer UC pomegranate cost study.
  - **Needed for:** current yields by age, water, nitrogen and labour hours (the doc uses the 2005 study).
- [ ] **`pomegranate--spanish-rdi`** (Online): Intrigliolo et al. (2013), *Irrigation Science* 31: 959-970, doi:10.1007/s00271-012-0372-y, or the 2012 *Options Méditerranéennes* A 103 paper (CIHEAM refused the download).
  - **Needed for:** crop coefficients, seasonal water use, yield under full and deficit irrigation, and the spring-stress fruit-number effect.
- [ ] **`pomegranate--nrcp-bahar`** (Online): an ICAR-NRCP (National Research Centre on Pomegranate, Solapur) production guide or the 'Bhagwa' status report.
  - **Needed for:** bahar regulation steps, Indian spacing, yields, nutrient rates and the blight schedule.
- [ ] **`pomegranate--production-stats`** (Online): FAOSTAT Pomegranates (if the item exists) or a peer-reviewed world production review, plus NHB area and production for 2023-24.
  - **Needed for:** world and Indian production (snippets conflict).
- [ ] **`pomegranate--cold-chill`** (Online): a research source on pomegranate cold hardiness by cultivar and on chill requirement.
  - **Needed for:** chill (Not sourced) and cultivar cold limits beyond Morton's −11 °C.
- [ ] **`pomegranate--warfarin-review`** (Online): full text of the 2014 warfarin-fruit interaction review (PubMed 25112306) or the Komperda (2009) case report.
  - **Needed for:** confirming the snippet-level Hazards entry.

### persimmon_american (2026-11-23)

- [ ] **`persimmon_american--fdc-composition`** (Online): USDA FoodData Central 169943, "Persimmons, native, raw" (the API was rate-limited).
  - **Needed for:** full composition per 100 g (only energy and a derived vitamin C figure are in the doc).
- [ ] **`persimmon_american--cultivar-ploidy`** (Online/Library): a horticultural source listing named American persimmon cultivars by chromosome race (60 vs. 90), e.g. Reich, *Uncommon Fruits for Every Garden*, or the American Pomological Society's work on northern persimmon cultivars.
  - **Needed for:** which cultivars need a matching pollinizer.
- [ ] **`persimmon_american--wsu-overview`** (Online): Washington State University, *Persimmons: An Over-View of Cultivars, Production, Harvesting, and Marketing* (57 pp), or ATTRA (2010), *Persimmons, Asian and American*.
  - **Needed for:** chill, water use, nutrient rates, yields by age and orchard harvest labour.
- [ ] **`persimmon_american--equine-impaction`** (Online): the Banse et al. retrospective on persimmon impaction in equids, or Cummings et al. (1997), *J. Vet. Diagn. Invest.*
  - **Needed for:** confirming the snippet-level Hazards entry.

### persimmon_dateplum (2026-11-23)

- [ ] **`persimmon_dateplum--floras`** (Online): the Flora of China and Flora of Pakistan treatments of *Diospyros lotus* on eFloras (both refused automated fetches), or Kew's Plants of the World Online entry.
  - **Needed for:** native range, elevation, flowering and fruiting months, local names and uses (e.g. amlok in Pakistan).
- [ ] **`persimmon_dateplum--rootstock-trial`** (Online): the full text of the Turkish (Mustafa Kemal University) *D. lotus* vs. *D. kaki* rootstock and graft trial, and the 2018 Shiraz stratification study.
  - **Needed for:** graft take, seedling growth and germination by stratification time.
- [ ] **`persimmon_dateplum--fruit-production`** (Online/Library): any source on *D. lotus* grown for fruit: bearing age, yield per tree, named varieties (Italy, East Asia), drying.
  - **Needed for:** yield, bearing age and cultivars (all Not sourced).
- [ ] **`persimmon_dateplum--composition`** (Online): *Acta Scientiarum Polonorum Hortorum Cultus* (2020), on *D. lotus* fruits grown in Turkey, or another proximate analysis giving energy and moisture.
  - **Needed for:** composition per 100 g, including energy.
- [ ] **`persimmon_dateplum--kakishibu`** (Online): a source confirming whether *D. lotus* (mamegaki/shinanogaki) is used for kakishibu in Japan.
  - **Needed for:** the old doc's tannin-use claim, now dropped.

### persimmon_texas (2026-11-23)

- [ ] **`persimmon_texas--seed-papers`** (Online): full text of Everitt (1984), *J. Range Manage.* 37(2): 189-192; Vora (1989), *J. Range Manage.* 42(1): 36-40; and Van Auken & Bush (1992), *Texas J. Sci.* 44(2): 167-174 (the Arizona archive blocks automated fetches).
  - **Needed for:** germination by temperature, salinity response, and the 33% vs. >90% conflict.
- [ ] **`persimmon_texas--fna`** (Online): the Flora of North America treatment of *Diospyros texana* (eFloras blocked).
  - **Needed for:** elevation (0-1,800 m vs. 300-1,700 m), phenology and sex system.
- [ ] **`persimmon_texas--composition`** (Online/Library): any proximate analysis of the fruit.
  - **Needed for:** composition and energy (Not sourced).
- [ ] **`persimmon_texas--yield-sex-ratio`** (Online/Library): a population survey of sex ratio, or any fruit-yield figure per tree.
  - **Needed for:** yield (Not sourced) and the anecdotal 10:1 male ratio.
- [ ] **`persimmon_texas--cold`** (Online): a killing temperature or documented freeze event (e.g. February 2021) for this species.
  - **Needed for:** hardiness beyond the 7A-9B zone rating.

### pineapple (2026-11-23)

- [ ] **`pineapple--faostat`** (Online): FAOSTAT item 486 (pineapples), world and top producers, latest year: area harvested, production, yield.
  - **Needed for:** world-average yield (now 26.4-28 t/ha from snippets).
- [ ] **`pineapple--labour`** (Online/Library): an itemised labour study giving hours or person-days per hectare by operation (Costa Rica, Ghana, Nigeria, India or Hawaii).
  - **Needed for:** labour (Not sourced as hours; the NHB budget does not state its area).
- [ ] **`pineapple--costa-rica`** (Online): the full Costa Rica Huetar Norte case study (54,000 plants/ha, 67 t/ha average, 360- and 668-day cycles).
  - **Needed for:** modern 'MD-2' density, yield range and plant-crop/ratoon cycle lengths.
- [ ] **`pineapple--handbook`** (Library): Bartholomew, Paull & Rohrbach (2002), *The Pineapple: Botany, Production and Uses* (CABI).
  - **Needed for:** forcing-to-harvest days, photoperiod response, cold-damage temperatures, nutrient removal per tonne.

### plum (2026-11-23)

- [ ] **`plum--composition`** (Online): FDC 169949 ("Plums, raw") and 168162 ("Plums, dried (prunes), uncooked") directly (the API was rate-limited), or a European-plum-specific composition table.
  - **Needed for:** raw-fruit composition and energy (not confirmed this pass).
- [ ] **`plum--faostat`** (Online): FAOSTAT item 521 (plums and sloes), world and top producers, latest year.
  - **Needed for:** world yield (now 4.8 t/ha from snippets).
- [ ] **`plum--cost-study`** (Online): the current UC prune (dried plum) cost study, and any European fresh-plum or Serbian/Romanian budget with hours.
  - **Needed for:** harvest and thinning hours, orchard life (20 vs. 30 years), fresh-market yields.
- [ ] **`plum--chill-ph`** (Online): University of Tennessee W895F (blocked) or another extension source on European plum chill hours, pH range and self-fertility by cultivar.
  - **Needed for:** chill, pH and pollination (partly snippet-level now).
- [ ] **`plum--harvest-timing`** (Online/Library): bloom-to-harvest days for prune and fresh European plum cultivars.
  - **Needed for:** days to harvest (Not sourced).

### ponderosa_lemon (2026-11-23)

- [ ] **`ponderosa_lemon--parentage`** (Online): the full text of Curk et al. (2016), *Annals of Botany* 117(4): 565-583 (PMC and Europe PMC refused automated fetches), for its Ponderosa genotype.
  - **Needed for:** lemon × citron vs. pummelo × citron (F2) parentage.
- [ ] **`ponderosa_lemon--culture`** (Online/Library): any extension or horticultural source with Ponderosa-specific cold limits, bearing age, yield per tree, soil and water needs, pests (e.g. Pieniążek 1983 on the Skierniewice lemon, or Florida/California extension pages).
  - **Needed for:** nearly every agronomic item (Not sourced).
- [ ] **`ponderosa_lemon--composition`** (Online): juice content, acidity, SSC or proximate composition for Ponderosa fruit.
  - **Needed for:** composition and energy (Not sourced).

### pomelo (2026-11-23)

- [ ] **`pomelo--storage`** (Online/Library): a postharvest-handbook entry or dedicated study giving pummelo storage temperature, RH, storage life and chilling-injury threshold.
  - **Needed for:** storage (12 °C vs. 8-10 °C vs. 5 °C conflict).
- [ ] **`pomelo--cold`** (Online/Library): a pummelo frost or freeze threshold (tree and fruit), e.g. from UC Riverside, USDA or Japanese buntan work.
  - **Needed for:** climate zones and weather response (Not sourced).
- [ ] **`pomelo--production`** (Online): FAOSTAT or national statistics for Vietnam and China separating bearing from total area, plus Thai figures.
  - **Needed for:** yield (12-15 t/ha reported vs. 8.6-9.5 t/ha derived).
- [ ] **`pomelo--pollination`** (Online): full text of the Chinese nine-cultivar hand-pollination study and the 'Guiyou No. 1' paper; any pollinator study.
  - **Needed for:** pollination and seediness (snippets only).
- [ ] **`pomelo--culture`** (Library): Groff, *Culture and Varieties of Siamese Pummelos*, and *The Citrus Industry* Vol. I pummelo section.
  - **Needed for:** bearing age, labour, soil, cultivar seasons (Not sourced).

### pulasan (2026-11-23)

- [ ] **`pulasan--statistics`** (Online): Malaysian Department of Agriculture fruit statistics (or DOSM crop tables) with pulasan planted area, harvested area and production for recent years (the DOA site did not respond).
  - **Needed for:** yield and production scale (Not sourced).
- [ ] **`pulasan--flower-biology`** (Online): full text of Djuita et al. (2016), *Int. J. Plant Biology* 7(1): 6149, and Junaidi et al. (2025), *Jurnal Biodjati* 10(2): 217-228.
  - **Needed for:** bisexual-flower pollen conflict and pollinators.
- [ ] **`pulasan--culture`** (Library/Online): bearing age, yield per tree, storage life and soil needs, e.g. PROSEA Timbers (Uji 1998), Mardaleni et al. (2022) full text, Malaysian or Indonesian extension material.
  - **Needed for:** bearing age, storage, soil, labour (Not sourced).

### rambutan (2026-11-23)

- [ ] **`rambutan--irrigation`** (Online): Northern Territory agnotes 662 and D38 on rambutan irrigation (the NT site refused automated fetches), or any Kc or sap-flow study.
  - **Needed for:** water use, rooting depth, induction soil tension (snippets only).
- [ ] **`rambutan--flowering`** (Online/Library): Kawabata et al. (2005) on Hawaii rambutan phenology and the NAA male-flower work, with induction temperatures and stress duration.
  - **Needed for:** flowering induction and pollen management (snippets only).
- [ ] **`rambutan--storage`** (Online): O'Hare (1995), *Postharvest Biol. Technol.* 6: 189-199, for cultivar chilling floors.
  - **Needed for:** storage conflict (10 °C lowest safe vs. 5 °C for 3 weeks).
- [ ] **`rambutan--composition`** (Online): a raw-rambutan composition table (FoodData Central has only canned).
  - **Needed for:** composition (only Morton's Ceylon analysis).
- [ ] **`rambutan--statistics`** (Online): Thai OAE or NSO rambutan area, production and yield, plus FAOSTAT if listed.
  - **Needed for:** national yields (2014 tonnage only).

### raspberry (2026-11-23)

- [ ] **`raspberry--cost-study`** (Online): a current WSU or OSU red raspberry enterprise budget (establishment and annual operations, machine vs. hand harvest).
  - **Needed for:** non-harvest labour, planting-year yields (Not sourced).
- [ ] **`raspberry--nutrient-removal`** (Online/Library): N-P-K removed per tonne of fruit and prunings.
  - **Needed for:** soil nutrient uptake (Not sourced).
- [ ] **`raspberry--composition`** (Online): FoodData Central 167755 read directly (API was rate-limited).
  - **Needed for:** confirming composition taken via Wikipedia.
- [ ] **`raspberry--pollination`** (Online): self-fertility of commercial red raspberry cultivars and bee contribution to drupelet set.
  - **Needed for:** pollination (hive density only).

### black_raspberry (2026-11-24)

- [ ] **`black_raspberry--nraes35`** (Library/Online): Bushway, Pritts & Handley (2008), NRAES-35 *Raspberry and Blackberry Production Guide*, black raspberry chapters.
  - **Needed for:** stand life, labour, chill, nutrients (all Not sourced).
- [ ] **`black_raspberry--composition`** (Online): proximate composition per 100 g fresh fruit (energy, sugars, fibre, vitamin C), e.g. a USDA or peer-reviewed analysis.
  - **Needed for:** composition (only juice anthocyanins sourced).
- [ ] **`black_raspberry--oregon-history`** (Online): NASS Oregon black raspberry historical series, 1936-2013 (old data.nass.usda.gov URL is dead).
  - **Needed for:** longer yield record.
- [ ] **`black_raspberry--high-tunnel`** (Online): the Cornell high-density high-tunnel black raspberry results (NIFA project 1007702 or its publications).
  - **Needed for:** controlled environment (Not sourced).
- [ ] **`black_raspberry--bokbunja-identity`** (Online/Library): a source on which species Korean commercial bokbunja plantings are.
  - **Needed for:** scope between `black_raspberry` and `bokbunja`.

### blackberry (2026-11-24)

- [ ] **`blackberry--cost-study`** (Online): a current OSU, UC or Arkansas blackberry enterprise budget (trailing machine-harvest and erect/semi-erect fresh), with labour hours by operation and picking rates.
  - **Needed for:** labour (Not sourced).
- [ ] **`blackberry--pollination`** (Online): self-fertility by cane type and recommended hive density.
  - **Needed for:** pollination.
- [ ] **`blackberry--chill-hardiness`** (Online): chill-hour requirements and bud cold hardiness for the main erect and semi-erect cultivars (only 'Marion' sourced).
  - **Needed for:** climate zones.
- [ ] **`blackberry--soil-disease`** (Online): Phytophthora, Verticillium and crown gall susceptibility in blackberry, from an extension or IPM source opened directly.
  - **Needed for:** soil biology.
- [ ] **`blackberry--us-statistics`** (Online): a current US or Oregon blackberry area and yield series (NASS releases read this pass no longer include blackberries; try Census of Agriculture 2022 or Oregon Raspberry and Blackberry Commission).
  - **Needed for:** US yield record.
- [ ] **`blackberry--weed-law`** (Online): NSW WeedWise full page (Weed of National Significance status) and Oregon noxious-weed quarantine rules for *R. armeniacus*.
  - **Needed for:** legal restrictions.

### oriental_melon (2026-11-24)

- [ ] **`oriental_melon--wa-weed-risk.pdf`** (Online): Department of Primary Industries and Regional Development, Western Australia (2022), *Cucumis melo - environmental weed risk assessment 2022*, https://library.dpird.wa.gov.au/bs_wra/25 (the download link returned an HTML page instead of the PDF).
  - **Needed for:** invasiveness (weed risk score for the species).
- [ ] **`oriental_melon--au-import-korea.html`** (Online): Australian Department of Agriculture, Fisheries and Forestry, plant import risk analysis "Melons from Korea", https://www.agriculture.gov.au/biosecurity-trade/policy/risk-analysis/plant/melons-from-korea (timed out to scripts), plus its final report PDF.
  - **Needed for:** biosecurity (quarantine pests and import conditions for fresh oriental melon).
- [ ] **`oriental_melon--food-composition.html`** (Online): Rural Development Administration, *Korean Standard Food Composition Table*, entry "참외, 생것" (raw oriental melon), https://koreanfood.rda.go.kr/.
  - **Needed for:** composition (energy is Not sourced; checks the 132 µg folate figure).
- [ ] **`oriental_melon--income-data.pdf`** (Library): Rural Development Administration (2025), *2024 농축산물 소득자료집* [2024 farm and livestock income data book], protected oriental melon tables.
  - **Needed for:** labour breakdown by task (only the 219 h/10a total is sourced), yields by system.
- [ ] **`oriental_melon--pollination-2005.pdf`** (Online): "Effect of Pollination Method on Fruit Setting and Quality of Oriental Melon (*Cucumis melo* L. var. *makuwa* Makino)", Seongju trial on pumpkin-grafted plants (bees vs. hand vs. growth regulators); AGRIS record https://agris.fao.org/search/en/records/6472466f53aa8c89630472d7.
  - **Needed for:** pollination (bee use, fruit-set rates by method).
- [ ] **`oriental_melon--heat-treatment-2005.pdf`** (Online): "Effects of Postharvest Heat Treatment on Alleviation Chilling Injury and Improvement Storability of Oriental Melon", *Journal of Bio-Environment Control* (2005), KoreaScience JAKO200504840787603.
  - **Needed for:** storage (heat treatment, chilling thresholds).
- [ ] **`oriental_melon--postharvest-2010.pdf`** (Online): oriental melon postharvest-management paper, *Korean Journal of Horticultural Science & Technology* (2010), KoreaScience JAKO201018651619359 (the PDF download timed out).
  - **Needed for:** storage and handling.
- [ ] **`oriental_melon--lim-2012.pdf`** (Library): Lim, T. K. (2012), "Cucumis melo (Makuwa Group)", *Edible Medicinal and Non-Medicinal Plants*, vol. 2, pp. 219-221, Springer, doi:10.1007/978-94-007-1764-0_34, ISBN 978-94-007-1763-3.
  - **Needed for:** the botany and climate figures Wikipedia takes from it, and the drought-tolerance conflict.

### papaya (2026-11-24)

- [ ] **`papaya--faostat.csv`** (Online): FAOSTAT Crops and livestock products (QCL), item "Papayas", world and top-producer harvested area, yield and production, 2015-2024 (the API needs an authorization token; download the CSV from the FAOSTAT web interface).
  - **Needed for:** world area and yield (Not sourced).
- [ ] **`papaya--nakasone-paull-1998.pdf`** (Library): Nakasone, H. Y. and Paull, R. E. (1998), *Tropical Fruits*, CAB International, papaya chapter pp. 239-269, ISBN 0-85199-254-1.
  - **Needed for:** photoperiod, rooting depth, flowering physiology, cultivar groups.
- [ ] **`papaya--migliaccio-2010.pdf`** (Library): Migliaccio, K. W., Schaffer, B., Crane, J. H. and Davies, F. S. (2010), papaya irrigation scheduling (ET vs. soil-water-sensor) in south Florida, *Agricultural Water Management* 97 (search hint: "Plant response to evapotranspiration and soil water sensor irrigation scheduling methods for papaya production in south Florida").
  - **Needed for:** seasonal water use in mm and the source of the Kc values.
- [ ] **`papaya--crane-mossler.pdf`** (Online): Crane, J. H. and Mossler, M. A. (2008), UF/IFAS papaya cultural practices and pest-management guidelines cited by AE540 (search EDIS for "papaya" by Crane).
  - **Needed for:** Florida spacing, fertiliser, pests and labour.
- [ ] **`papaya--seed-storage.html`** (Online): Kew Seed Information Database entry for *Carica papaya* (storage behaviour).
  - **Needed for:** seed-storage class (old "intermediate" claim dropped).
- [ ] **`papaya--hawaii-stats.pdf`** (Online): USDA NASS Hawaii Field Office, latest Hawaii papaya statistics (area, yield, GM share).
  - **Needed for:** a current Hawaii yield series.
- [ ] **`papaya--gm-acceptance.html`** (Online): dates on which Japan, Canada and other markets accepted 'Rainbow'/'SunUp' fruit (for example the Japanese approval announcement).
  - **Needed for:** the GM trade restriction in Finding 4.

### peach (2026-11-24)

Also relevant to peach, already requested under nectarine: `nectarine--crisosto-1999` (per-cultivar chilling-injury ratings) and `nectarine--layne-bassi-2008` (*The Peach*, CABI).

- [ ] **`peach--uc-cost-processing-2011`** (Online): Norton, M., J. Hasey, R. Duncan, K. M. Klonsky and R. L. De Moura (2011), *Sample Costs to Establish and Produce Processing Peaches, Cling and Freestone, Late Harvested Varieties, Sacramento and San Joaquin Valleys*, University of California Cooperative Extension (and the companion extra-early study). Search hint: coststudies.ucdavis.edu or fruitsandnuts.ucdavis.edu (Cloudflare-blocked to scripts).
  - **Needed for:** labour hours by operation, yield curve, water and nitrogen for a California high-chill peach orchard.
- [ ] **`peach--uc-cost-fresh`** (Online): the most recent UC Cooperative Extension sample-cost study for fresh-market peaches, San Joaquin Valley (search hint: coststudies.ucdavis.edu, "peaches fresh market").
  - **Needed for:** fresh-market yield, packout and labour, to set beside the Ontario figures.
- [ ] **`peach--wsu-bud-hardiness`** (Online): Washington State University Extension bulletin EB0914, *Critical Temperatures for Frost Damage on Fruit Trees* (or the 1989 spray guide EB0419), the original 'Elberta' peach bud-stage tables.
  - **Needed for:** the primary source of the 10%/90% kill table and settling the dormant-bud hardiness conflict (−7 to −10 °C against −15 to −25 °C).
- [ ] **`peach--uga-2023-freeze`** (Online): UGA Extension or USDA reports on the 2023 Georgia peach loss (warm winter, chill shortfall and the 11-23 March freezes). Search hint: site.extension.uga.edu climate blog; Georgia Farm Bureau, March 2023.
  - **Needed for:** chill-hour totals for winter 2022/23 and the loss attributed to chill versus freeze.
- [ ] **`peach--aphis-ppv`** (Online): USDA APHIS, "Plum Pox" programme page, https://www.aphis.usda.gov/plant-pests-diseases/plum-pox (access denied to scripts).
  - **Needed for:** US eradication date, regulated articles and certification rules for peach nursery stock.
- [ ] **`peach--crisosto-2004`** (Library): Crisosto, C. H., et al. (2004), the commercial controlled delayed cooling ("preconditioning") study for California and Chilean peach cultivars, *Postharvest Biology and Technology* (volume and pages to confirm).
  - **Needed for:** per-cultivar market-life gains and the delay protocol.

### peach_low_chill (2026-11-24)

Also relevant here, already requested under nectarine and peach: `nectarine--layne-bassi-2008` (*The Peach*, CABI) and `peach--crisosto-2004` (delayed cooling).

- [ ] **`peach_low_chill--jnematol-2022-flordaguard`** (Online): "Susceptibility of Flordaguard peach rootstock to a resistant-breaking population of *Meloidogyne floridensis* and two populations of *Meloidogyne arenaria*," *Journal of Nematology* (2022), https://pmc.ncbi.nlm.nih.gov/articles/PMC8784979/ (bot check blocks scripts).
  - **Needed for:** the authors, galling and reproduction figures, and the orchard survey behind the resistance-breaking claim (Finding 6).
- [ ] **`peach_low_chill--sherman-1991-flordaguard`** (Online): Sherman, W. B., P. M. Lyrene and R. H. Sharpe (1991), "Flordaguard peach rootstock," *HortScience* 26: 427-428, doi:10.21273/HORTSCI.26.4.427.
  - **Needed for:** the release description, parentage, chill and nursery figures from the primary source.
- [ ] **`peach_low_chill--george-nissen-hcn`** (Library): George, A. P., and R. J. Nissen (1993), *Australian Journal of Experimental Agriculture*, CSIRO EA9930787; and George, A. P., J. Lloyd and R. J. Nissen (1992), CSIRO EA9920089 (full texts paywalled).
  - **Needed for:** the hydrogen cyanamide rates, timing, fruit-set and yield results on 'Flordaprince' (Finding 8).
- [ ] **`peach_low_chill--george-1997-acta`** (Library): George, A. P. (1997), "Research and development of temperate fruits in subtropical Australia," *Acta Horticulturae* 441: 115-124, doi:10.17660/ActaHortic.1997.441.14.
  - **Needed for:** the survey method behind the 27 and 51 t/ha benchmarks, densities and labour for subtropical Australia.
- [ ] **`peach_low_chill--nass-florida-peach`** (Online): USDA NASS or Florida Department of Agriculture statistics for Florida peach bearing acres, production and yield, most recent years.
  - **Needed for:** a measured state yield to replace the 2017 estimate (about 3.4 t/ha).
- [ ] **`peach_low_chill--egypt-florida-prince`** (Online): the 2015 *Egyptian Journal of Horticulture* study of 'Florida Prince', 'Early Grand' and 'Desert Red' in the North Delta (journals.ekb.eg, article_1065).
  - **Needed for:** Egyptian bloom, maturity, yield and fruit-quality figures.
- [ ] **`peach_low_chill--tropics-cycling`** (Online): the *Journal of the American Pomological Society* article on peach production in the new-world tropics, and "Temperature in relation to peach culture in the tropics," *Acta Horticulturae* 199 (ISHS 199_12).
  - **Needed for:** the cycle length, crops a year, the forcing method and the yield per cycle in tropical systems.
- [ ] **`peach_low_chill--mexico-low-chill`** (Online): INIFAP (Mexican national agricultural research institute) material on low-chill peach area, production, yield and cultivars by region.
  - **Needed for:** the Mexican system dropped this pass.
- [ ] **`peach_low_chill--hs1223-budget`** (Online): Olmstead, M., and K. Morgan (2013), "Orchard Establishment Budget for Peaches and Nectarines in Florida," UF/IFAS HS1223, doi:10.32473/edis-hs1223-2013 (the EDIS page now returns "Gone"; try the journals.flvc.org archive).
  - **Needed for:** a second Florida yield and cost budget to compare with FE1016.

### pear (2026-11-24)

- [ ] **`pear--orchard-chill`** (Online): a primary study of winter chill requirement for 'Bartlett', 'd'Anjou' and 'Bosc' (UC Davis / UC Cooperative Extension chill work, the López et al. European pear bud-break trial, Mississippi State P3067).
  - **Needed for:** orchard chill hours by cultivar to replace snippet-level figures (Climate zones; Open research questions).
- [ ] **`pear--wsu-rootstocks`** (Online): Washington State University Tree Fruit, pear rootstock pages (site down "temporarily unavailable" on 2026-11-24), or the OSU Hood River OH×F rootstock trial reports.
  - **Needed for:** OH×F selection vigour and yield, quince incompatibility by cultivar, and interstems (Finding 6).
- [ ] **`pear--soil-extension`** (Online): Virginia Cooperative Extension 422-017 and Penn State PlantVillage pear pages, opened directly; plus a pear nutrient guide (e.g. OSU or WSU leaf-analysis standards).
  - **Needed for:** pH, drainage and nutrient figures now at snippet level (Soil).
- [ ] **`pear--linsmith-2019-genome`** (Online): Linsmith et al. (2019), *GigaScience* 8(12): giz138, PMC6901071 or hal-02563877.
  - **Needed for:** confirming the genome figures opened directly (Naming and scope).
- [ ] **`pear--naturalisation`** (Online): Flora of New Zealand vol. IV, the DOC weeds database, VicFlora and FloraBase entries for *Pyrus communis*, opened directly.
  - **Needed for:** naturalisation status now at snippet level (Invasiveness / biosecurity).
- [ ] **`pear--patulin-pear`** (Online): FDA CPG 510.150 and the current EU contaminants regulation (EU 2023/915) text, plus any patulin survey of pear juice or pear products.
  - **Needed for:** whether the 50 µg/kg limits cover pear products, and pear-specific patulin data (Hazards).
- [ ] **`pear--kilayim-table`** (Online): the Torah VeHa'aretz Institute table "Grafting Scion and Rootstock Combinations for Fruit Trees" (2025), opened directly.
  - **Needed for:** confirming the pear-on-quince listing (Uses and processing, religious rules).
- [ ] **`pear--perry-pgi-specs`** (Online): the Gloucestershire Perry and Worcestershire Perry product specifications (assets.publishing.service.gov.uk), and the Poiré Domfront AOP cahier des charges (INAO).
  - **Needed for:** the other protected-name rules, and the Herefordshire sorbitol limit's unit (Finding 7).
- [ ] **`pear--quince-incompatibility`** (Library): a pear propagation or rootstock reference (e.g. Webster & Wertheim, "Apple and pear rootstocks"; or *Pear: Production, Postharvest and Biotechnology*).
  - **Needed for:** which cultivars are quince-incompatible, how soon it shows, and interstem practice.

### pear_low_chill (2026-11-24)

Also relevant here, already requested under pear: `pear--orchard-chill`, `pear--kilayim-table`.

- [ ] **`pear_low_chill--egypt-dormancy`** (Online): Fathi and Hussein (2007), "Better combination of defoliation and dormancy breaking agent for pear orchards," https://journals.ekb.eg/article_220647.html; Samra et al. (2009), https://journals.ekb.eg/article_116620.html (the journal site timed out on 2026-11-24).
  - **Needed for:** the rates, dates, bud-burst and yield figures opened directly (Finding 1).
- [ ] **`pear_low_chill--egypt-rootstock`** (Online): "Effect of some pear rootstocks on growth, fruiting and resistance to fire blight disease of 'Le-Conte' pear cultivar," https://fjard.journals.ekb.eg/article_192988.html; and the 2016 North Middle Nile Delta rootstock study, https://journals.ekb.eg/article_176567.html.
  - **Needed for:** yields by rootstock, the fire-blight and chlorosis results, and salt tolerance (Finding 5).
- [ ] **`pear_low_chill--kieffer-ripening`** (Library): the 1940s Southern horticulture bulletin giving a 15.5-18 °C (60-65 °F) ripening window and 2-3 month cold storage for 'Kieffer' (seen in an earlier pass via a university digital-collections search; title to identify).
  - **Needed for:** the ripening temperature window and whether a chilling step is needed (Finding 4; Open research questions).
- [ ] **`pear_low_chill--uga-c742`** (Online): Krewer, G., and P. Bertrand (2017), *Home Garden Pears*, University of Georgia Extension Circular 742 (the fieldreport.caes.uga.edu link returned 404).
  - **Needed for:** Georgia cultivar, pollination (sterile-pollen cultivars) and blight notes.
- [ ] **`pear_low_chill--texas-pears`** (Online): Lipe, J. A., C. Lyons and L. Stein, "Home Fruit Production—Pears," Texas A&M AgriLife (B-1598; the aggie-horticulture page returned 404, the county copy a bot check).
  - **Needed for:** the Texas zones, chill figures and the 'Kieffer' blight rating opened directly.
- [ ] **`pear_low_chill--sc-callery-rule`** (Online): the South Carolina Department of Plant Industry (Clemson) rule text banning sale of Bradford pear and pears on Callery rootstock from 1 October 2024.
  - **Needed for:** the exact scope of the rootstock ban and what stocks nurseries now use (Finding 5).
- [ ] **`pear_low_chill--cultivar-releases`** (Library): Andrews, C. P., and W. B. Sherman (1979), "Hybrid pear cultivars for Florida," *Proc. Fla. State Hort. Soc.* 92: 266-267; Deyton, D. E., and J. C. Cummins (1991), "History of pear breeding in Tennessee," *Fruit Varieties Journal* 45(3): 143-146.
  - **Needed for:** parentage and release dates of 'Flordahome', 'Hood', 'Orient' and 'Tenn' (Open research questions).
- [ ] **`pear_low_chill--hedrick-pears`** (Online): Hedrick, U. P., *The Pears of New York* (1921), Project Gutenberg 46994 (503 on 2026-11-24), 'Kieffer' and 'Le Conte' entries.
  - **Needed for:** opening the cultivar histories directly (Finding 6).
- [ ] **`pear_low_chill--florida-rootstock-trial`** (Library): the five-year UF/IFAS rootstock study of 'Flordahome' and 'Hood' on *P. calleryana*, *P. betulifolia*, OH×F 51/97/333 and quince cited in HS1393 (authors to identify; probably *Proc. Fla. State Hort. Soc.*).
  - **Needed for:** growth and survival figures by rootstock (Finding 5).

### purple_passionfruit / yellow_passionfruit (2026-11-24)

Covers both forms; the one doc `passionfruit.md` serves both rows. A
same-day yellow-focused deepening pass opened MAFES Bulletin 1153 directly
and added snippet-level ethylene, pollination, CABMV and yellow-juice
figures, so some items below are now partly answered but still want the full
texts.

- [ ] **`passionfruit--usda-hb66`** (Online): the USDA Agriculture Handbook 66 passionfruit chapter (Gross, Wang & Saltveit eds., *The Commercial Storage of Fruits, Vegetables, and Florist and Nursery Stocks*); the archived ba.ars.usda.gov/hb66 path returned 404.
  - **Needed for:** the ethylene output (~160-400 µL/kg·h), respiration, the 7 °C chilling-injury threshold for the yellow form, CA and grading (Finding 3; Open research questions).
- [ ] **`passionfruit--ibge-pam`** (Online): IBGE SIDRA, Produção Agrícola Municipal 2023, maracujá at Brazil level (area, production, yield), and the Embrapa chapter citing it.
  - **Needed for:** a measured national area, output and yield to replace the ~15 t/ha snippet (Yield).
- [ ] **`passionfruit--kc-lysimeter`** (Online): the Piracicaba Irriga Kc study, the USP master's thesis (teses.usp.br 11/11143), and the Botucatu drip lysimeter study, all Brazilian.
  - **Needed for:** opening the stage Kc values and seasonal ETc directly (Water use).
- [ ] **`passionfruit--cyanogens`** (Library): the food-chemistry study identifying and quantifying prunasin and sambunigrin in *P. edulis* by tissue and ripeness (the ~285 mg/kg peel figure seen in an earlier pass).
  - **Needed for:** the glycoside identities and concentrations (Finding 5; Hazards).
- [ ] **`passionfruit--fdc-values`** (Online): USDA FoodData Central SR Legacy 169108 (purple) and any yellow-form record, via the standard FDC API (the portal-data JSON returned null amounts).
  - **Needed for:** the full purple and yellow nutrient profiles (Composition).
- [ ] **`passionfruit--salinity`** (Online): a salt-tolerance source for passionfruit (FAO-61 lists no numeric rating; check Ayers & Westcot FAO-29 or regional trials).
  - **Needed for:** a sourced salinity threshold (Open research questions).
- [ ] **`passionfruit--woodiness-virus`** (Online): a current review of Passion fruit woodiness virus (PWV / CABMV) epidemiology and the breakdown of mild-strain cross-protection.
  - **Needed for:** updating the 1978 Morton account with current virus taxonomy and control (Finding 4).
- [ ] **`passionfruit--rain-pollination`** (Library): the Knight & Winters USDA reports on yellow passionfruit pollination and yield, or a Jaboticabal (São Paulo) pollination study.
  - **Needed for:** the "rain within 1.5 h prevents set" figure still not re-sourced (hand-pollination rates now have the Yamamoto snippet) (Weather response; Pollination).
- [ ] **`passionfruit--taco-yellow`** (Online): the Brazilian TACO food-composition table entry for maracujá-amarelo (yellow) pulp and juice, and any full yellow-form nutrient study.
  - **Needed for:** a full yellow-form composition to sit beside the purple FDC figures (Composition).
- [ ] **`passionfruit--yamamoto-2012`** (Library): Yamamoto et al. (2012), the central-Brazil hand-pollination study giving the 23.3% → 69.8% fruit-set increase, and the *Xylocopa* trap-nest management papers.
  - **Needed for:** opening the fruit-set and carpenter-bee figures directly (Pollination).
- [ ] **`passionfruit--cabmv`** (Online): a Brazilian review of cowpea aphid-borne mosaic virus (CABMV) in passionfruit — the reattribution from PWV, the aphid vectors and the annual-renewal control.
  - **Needed for:** opening the virus taxonomy, vectors and management directly (Finding 4; replaces part of `passionfruit--woodiness-virus`).

### red_currant (2026-11-24)

Re-research of the previously fully-anonymised doc. The crop report (Hummer &
Barney 2002), the Eutypa report, the WFLO storage manual and the Wikipedia
article were opened directly; the items below would upgrade snippet-level
material or close the conflicts flagged in the doc's Open research questions.

- [ ] **`red_currant--hb66-currants`** (Online): the USDA Agriculture Handbook
  66 chapter on currants, gooseberries and elderberries (Prange et al. eds.,
  *The Commercial Storage of Fruits, Vegetables, and Florist and Nursery
  Stocks*), full text — only an excerpt was readable this pass.
  - **Needed for:** the exact red-currant CA set-points and CO₂-injury
    threshold, and the ~2.5-week fresh-storage figure, to reconcile the
    "several days" / "1-2 weeks" / "2.5 weeks" conflict (Finding 1; Storage;
    Open research questions).
- [ ] **`red_currant--eutypa-control`** (Online): Wenneker et al., the ISHS
  *Acta Horticulturae* / research.wur.nl follow-up papers on control of Eutypa
  dieback in red currant (pruning-wound treatments, sanitation, epidemiology).
  - **Needed for:** the stand-life decline figures and the current management
    programme (Finding 5; Stand life).
- [ ] **`red_currant--dutch-ulo`** (Online): the primary Dutch ULO/CA storage
  trial behind the 'Rotet'/'Rondom'/'Rovada' 10/12/12-week figures, and the
  Dutch trade-press source for the historical 15-20 t/ha yield and its
  Eutypa-driven decline.
  - **Needed for:** opening the CA durations and the yield-decline figure
    directly (Finding 1; Yield; Open research questions).
- [ ] **`red_currant--danish-organic-trial`** (Library): the *Journal of the
  American Pomological Society* / DARCOF organic currant cultivar trial
  (Lindhard Pedersen, Aarslev) — the PDF found this pass was image-only.
  - **Needed for:** the red-currant-specific leaf-spot/defoliation ratings and
    per-cultivar yields (Finding 5; Cultivars).
- [ ] **`red_currant--barleduc-rate`** (Library): a Lorraine food-history or
  Maison Dutriez source giving a seeding rate per hour for the Bar-le-Duc
  *épépineuses*.
  - **Needed for:** quantifying the per-worker labour of the goose-quill
    seeding (Finding 6).
- [ ] **`red_currant--poland-stats`** (Online): a red-currant-specific
  Polish/Eurostat area-and-production series (not lumped with black currant).
  - **Needed for:** a clean world-average yield derivation (Yield; Estimates).

### satsuma (2026-11-24)

Re-research of the previously fully-anonymised doc. HS195 (now satisfied), the
Wikipedia entries and Morton were opened directly; the items below would
upgrade snippet-level material or close the Open research questions.

- [ ] **`satsuma--jp-food-composition`** (Online): the Japanese Standard
  Tables of Food Composition entry for *unshū mikan* (温州みかん), fresh.
  - **Needed for:** a satsuma-specific nutrient profile to replace the
    mandarin-group analogy (Composition; Open research questions).
- [ ] **`satsuma--mulch-primary`** (Library): the primary sheet-mulch papers —
  Yakushiji et al. (1996) on osmoregulation, and a prefectural/experiment-
  station マルチ栽培 report giving sugar targets by cultivar group and date and
  the leaf-water-potential → fruit-growth-rate indicator.
  - **Needed for:** opening the deficit-stress thresholds and sugar targets
    directly (Finding 2).
- [ ] **`satsuma--aoshima-storage`** (Online): a Japanese source on stored
  ('Aoshima') satsuma — the air-drying weight-loss target and storehouse
  temperature/humidity by shipping month.
  - **Needed for:** the curing and storage figures, and reconciling the
    storage-temperature conflict (Finding 3; Open research questions).
- [ ] **`satsuma--maff-production`** (Online): MAFF crop statistics
  (作物統計 / 果樹) for unshu production and area by year and prefecture.
  - **Needed for:** a measured national yield and the per-prefecture split
    (Finding 4; Yield).
- [ ] **`satsuma--cyp3a-pxr`** (Library): the pharmacology paper (Xenobiotica
  2019 or related) on satsuma/citrus-peel induction of CYP3A and
  P-glycoprotein via PXR.
  - **Needed for:** confirming the drug-interaction mechanism and clinical
    relevance (Finding 5; Hazards).
- [ ] **`satsuma--gulf-budget`** (Online): a US Gulf Coast satsuma enterprise
  budget (LSU AgCenter, Auburn, or Texas AgriLife).
  - **Needed for:** stand-life years, planting density and itemised grove-care
    labour (Stand life; Labor; Estimates).

### seed_watermelon (2026-11-25)

Re-research of the shared `watermelon.md` seed profile against the current
checklist. Two CGC reports (Zhang & Jiang 1990; Zhang 1996) were opened and
read; the items below would close the remaining gaps.

- [ ] **`seed_watermelon--gansu-production`** (Online): "Watermelon
  Production of Gansu Province in China," Cucurbit Genetics Cooperative
  Report, article cgc25-10 (https://cucurbit.info/wp-content/uploads/2019/03/cgc25-10.pdf).
  - **Where:** the PDF is on the open web but is a Chinese-font scan that
    this pass could not extract to text.
  - **Needed for:** current Gansu edible-seed-watermelon area, output and
    per-hectare seed yield, to reconcile the national ~140,000 ha /
    >200,000 t vs. improved-variety 2,250 kg/ha figures (Finding 4; Yield;
    Open research questions).
- [ ] **`seed_watermelon--chinese-seed-composition`** (Library): a measured
  nutrient/oil profile for the Chinese edible-seed (guazi) kernel
  specifically — a Chinese food-composition table or a Gansu Academy of
  Agricultural Sciences paper.
  - **Needed for:** a Chinese-group composition figure to replace the
    protein-/oil-rich generality (Composition).
- [ ] **`seed_watermelon--egusi-aflatoxin-primary`** (Library): the primary
  Nigerian egusi-aflatoxin papers (Bankole and co-workers, "Fungal
  contamination and aflatoxin B1 of 'egusi' melon seeds in Nigeria" and
  "Storage practices and aflatoxin B1 contamination...").
  - **Needed for:** exact contamination incidence, storage-time thresholds
    and the ogiri-detoxification figures now cited at snippet depth
    (Finding 7; Hazards) [25].

### watermelon (2026-11-25)

Re-research of the shared `watermelon.md` dessert profile against the current
checklist. Photoperiod, a numeric salinity benchmark [30], invasiveness [29],
weather-response, soil-biology and controlled-environment lines were added and
the profile was given full inline citations; the items below would upgrade the
snippet-depth additions.

- [ ] **`watermelon--salinity-primary`** (Library): a primary watermelon
  salinity dose-response study reporting the metric explicitly (irrigation
  water EC vs. soil ECe) — e.g. the Lucena/Martins or Colla et al. (2006)
  papers behind the review figures.
  - **Needed for:** a firm threshold and yield-decline slope to replace the
    ~2.2 dS/m review figure and resolve the EC-vs-ECe ambiguity (Soil
    salinity) [30].
- [ ] **`watermelon--volunteer-weed`** (Online): a regional weed guide or
  risk assessment that evaluates volunteer dessert *C. lanatus* seedlings (from
  discarded fruit/seed) specifically, as distinct from wild/bitter/citron
  forms.
  - **Needed for:** a sourced weed status for the dessert type itself
    (Invasiveness / biosecurity) [29].

### wet_tropics_mangoes (2026-11-25)

Re-research of the grouped `wet-tropics-mangoes.md` entry (four *Mangifera*
species) against the current checklist. The per-species profiles (`kuini.md`,
`bachang.md`, `binjai.md`, `bambangan.md`) were used as internal source [11];
they confirmed the gaps below rather than closing them.

- [ ] **`wet_tropics_mangoes--flowering-induction`** (Library): a pomology
  study of flowering/fruiting induction in *M. odorata/foetida/caesia/pajang*
  (or wet-tropics *Mangifera* generally).
  - **Needed for:** the photoperiod/seasonal-cue bullet, currently only
    inferred (rainy-season fruiting, non-photoperiodic) [11].
- [ ] **`wet_tropics_mangoes--yield-survey`** (Library): any regional
  production/yield survey giving per-tree or per-hectare figures for these
  species.
  - **Needed for:** replacing the spacing-plus-"thousands of fruits" yield
    estimate (Yield; Estimates) [11].

### quince (2026-11-25)

Re-research of the previously fully-anonymised doc against the current
checklist. Production, chill, salinity, fire-blight and virus-certification
material was added at search-snippet depth; the items below would upgrade it.

- [ ] **`quince--ucdavis-rootstock`** (Online): University of California,
  "Quince as Pear Rootstock" (https://fruitsandnuts.ucdavis.edu/quince-pear-rootstock).
  - **Where:** open web; not opened this pass.
  - **Needed for:** the named-clone vigour figures and the delayed
    (reportedly 8-10 year) pear-on-quince incompatibility timing — also the
    quince side of the outstanding `pear--quince-incompatibility` request
    (Finding 1; Propagation).
- [ ] **`quince--fireblight-breeding`** (Library): the Eastern European
  conference article behind source [9] on breeding fire-blight-resistant
  quince selections (two decades of industry damage; a hybrid population on a
  named rootstock; infection-rate figures).
  - **Needed for:** pinning the specific country and the devastation/recovery
    figures now cited only at abstract depth (Finding 3; Open research
    questions).

### sour_cherry (2026-11-25)

Re-research of the shared `cherry.md` sour-cherry profile against the current
checklist. Production, chill, salinity, leaf-spot, plum-pox and melatonin
material was added at search-snippet depth; the items below would upgrade it.

- [ ] **`sour_cherry--faostat-area`** (Online): FAOSTAT sour-cherry
  harvested-area and yield-per-hectare tables by country (recent years).
  - **Where:** the FAOSTAT crops database (blocks scripted queries).
  - **Needed for:** a directly-sourced world-average sour-cherry yield to
    replace the ~5 t/ha estimate, and to reconcile the Russia-led (~1.6 Mt)
    vs. Turkey-led (700-900 kt) production-ranking conflict (Finding 10;
    Yield; Open research questions) [60].
- [ ] **`sour_cherry--chill-extension`** (Library): a university-extension or
  breeding record giving a firm chilling-hour requirement for 'Montmorency'
  and 'North Star'.
  - **Needed for:** replacing the 600-1,000 hour nursery-snippet range with a
    measured figure (chill bullet in the re-research section) [62].

### sweet_cherry (2026-11-25)

Re-research of the shared `cherry.md` sweet-cherry profile against the current
checklist. Production ranking, chill, photoperiod, elevation, virus/certification,
brown-rot disease profile, invasiveness and melatonin material was added at
search-snippet depth; the items below would upgrade it.

- [ ] **`sweet_cherry--faostat-area`** (Online): FAOSTAT sweet-cherry (not
  combined "cherries") harvested-area and yield-per-hectare tables by country
  (recent years).
  - **Where:** the FAOSTAT crops database (blocks scripted queries); most public
    rankings report combined sweet+sour "cherries" rather than sweet alone.
  - **Needed for:** a directly-sourced world-average sweet-cherry yield to
    replace the ~6 t/ha derivation and the ~9 t/ha Türkiye-area-implied
    cross-check (Finding 10; Yield; Open research questions) [66].
- [ ] **`sweet_cherry--melatonin`** (Library): Xia et al. 2020 (*Molecules*) and
  the Hongdeng/Rainier sweet-cherry melatonin-rhythm study, full texts.
  - **Needed for:** firm ripe-fruit melatonin ng/g values for sweet cherry, to
    replace the ~0.1 ng/g review-table snippet and confirm the contrast with
    tart cherry (composition/health bullet) [72].
- [ ] **`sweet_cherry--chill-extension`** (Library): a university-extension or
  breeding record giving a firm chilling-hour requirement for standard
  sweet-cherry cultivars.
  - **Needed for:** replacing the 800-1,200 hour EcoCrop/snippet range and the
    scattered cultivar units with a measured figure (chill bullet) [67].

### sweet_granadilla (2026-11-25)

Re-research of the `sweet-granadilla.md` profile against the current checklist.
Fusarium-wilt/rootstock, photoperiod, salinity, invasiveness and virus material
was added at search-snippet/database depth; the items below would upgrade it.

- [ ] **`sweet_granadilla--alata-rootstock`** (Library): the INIFAP *Revista
  Mexicana de Ciencias Agrícolas* study evaluating *Passiflora alata* as a
  Fusarium-tolerant rootstock for granadilla, full text.
  - **Needed for:** firm incidence/graft-take figures and field (not just
    greenhouse) performance behind the rootstock-grafting management (Finding 6)
    [12].
- [ ] **`sweet_granadilla--virus-survey`** (Online): a *P. ligularis*-specific
  virus survey (woodiness potyvirus, CMV/SMV/CABMV) from a Colombian or Andean
  programme.
  - **Needed for:** confirming the genus-level virus picture for this species
    rather than relying on analogy (disease/pest profile; Finding 7) [14].
- [ ] **`sweet_granadilla--icbf-composition`** (Online): the Colombian ICBF
  *Tabla de Composición de Alimentos* row for granadilla.
  - **Where:** the ICBF food-composition table (not well indexed to scripts).
  - **Needed for:** a species-specific composition figure to replace the
    analogy-based estimate and the conflicting generic snippets (Composition;
    Open research questions) [15].

### sweet_lemon (2026-11-25)

Re-research of the `sweet-lemon.md` profile (*Citrus limetta* / Palestine sweet
lime) against the current checklist. Rootstock virus-decline, photoperiod/chill,
salinity, cold-hardiness and composition material was added at search-snippet
depth; the items below would upgrade it.

- [ ] **`sweet_lemon--iocv-xyloporosis`** (Library): a modern IOCV / UC
  Riverside review of Palestine sweet lime (*C. limettioides*) rootstock virus
  and viroid behaviour (xyloporosis/cachexia, tristeza, exocortis).
  - **Needed for:** replacing the older conference-paper snippets with current
    recommendations behind Finding 4 and the disease/propagation lines [8].
- [ ] **`sweet_lemon--ifct-composition`** (Online): a clean *C. limetta* row
  from the Indian Food Composition Tables or USDA FoodData Central (not the
  "mosambi" sweet-orange entry).
  - **Needed for:** a species-specific composition figure to replace the
    analogy estimate and the conflated mosambi snippets (Composition; Open
    research questions) [12].
- [ ] **`sweet_lemon--cold-killing-temp`** (Library): a measured cold-hardiness
  / killing-temperature figure for *C. limetta* specifically.
  - **Needed for:** replacing the RHS/zone hardiness-rating databases with a
    measured threshold (Weather response; Finding 5) [10].

### ume (2026-11-25)

Re-research of the `ume.md` profile (*Prunus mume*) against the current
checklist. Plum-pox identity/eradication, photoperiod, salinity and
invasiveness material was added at snippet/report depth; the items below would
upgrade it. (A doc-wide inline-citation pass was also done in the same work, so
all 42 sources are now cited inline.)

- [ ] **`ume--ppv-maff-status`** (Online): the current MAFF / plant-protection
  station status and demarcated-area map for plum pox virus on Japanese apricot.
  - **Where:** Japanese government plant-protection pages (often not script-
    accessible).
  - **Needed for:** confirming the post-2021 surveillance status and residual
    movement restrictions behind Finding 7 [39].
- [ ] **`ume--salt-tolerance`** (Library): a systematic *P. mume* salinity /
  rootstock salt-tolerance study.
  - **Needed for:** a species-specific salt-tolerance threshold to replace the
    *Prunus*-genus analogy (Soil salinity bullet) [42].

### strawberry (2026-11-25)

Re-research of the garden-strawberry profile in the shared `strawberry.md`
against the current checklist. Salinity, viral-decline, certification,
methyl-bromide, invasiveness, elevation and market-window material was added at
search-snippet depth; the items below would upgrade it.

- [ ] **`strawberry--fao29-salt-table`** (Online): FAO Irrigation and Drainage
  Paper 29 (Rev. 1), Table A1.1, the strawberry salt-tolerance row.
  - **Where:** the FAO document repository (the salt-tolerance tables are in
    Paper 29, not the FAO-56 evapotranspiration manual already used as [14]).
  - **Needed for:** confirming the ~1.0 dS/m ECe threshold and ~33%/dS/m slope
    from the primary FAO table rather than secondary USDA-ARS/extension sources
    (Salinity bullet in the re-research section; Open research questions) [18].
- [ ] **`strawberry--cdfa-cert-regs`** (Online): California Code of Regulations,
  Title 3, §§3049-3049.5, plus the CDFA Strawberry Registration and
  Certification Program and Foundation Plant Services nursery documents.
  - **Where:** the CDFA Nursery Services and UC Davis FPS sites (PDFs not opened
    in full this pass).
  - **Needed for:** sourcing the certification, virus-testing, phytosanitary and
    high-elevation runner-nursery specifics directly rather than from search
    snippets (Biosecurity and nursery certification bullet; Open research
    questions) [20][21].

### woodland_strawberry (2026-11-25)

Re-research of the woodland/musk profile in the shared `strawberry.md` against
the current checklist. Photoperiod genetics [24] and invasiveness [22] were
added; salinity, soil biology and yield remain by-analogy. The items below would
upgrade it.

- [ ] **`woodland_strawberry--moschata-reproduction`** (Library): a pomology
  source on *Fragaria moschata* sex expression (dioecy/subdioecy), male-plant
  ratio and flowering season.
  - **Needed for:** firming the musk-strawberry pollination requirement, now
    sourced only as "needs separate males" (Reproduction bullet; schema entry 17)
    [8].
- [ ] **`woodland_strawberry--alpine-yield`** (Library): an alpine (*F. vesca* f.
  *semperflorens*) production trial giving per-plant or per-area yield and berry
  weight.
  - **Needed for:** replacing the per-plant-per-week-times-density yield estimate,
    among the weakest in the entry (Yield; Estimates) [12].

### yellow_pitaya (2026-11-25)

Re-research of the `yellow-pitaya.md` profile (*Selenicereus megalanthus*)
against the current checklist. Photoperiod, salinity, weather-response and
invasiveness [10] lines were added and the profile was given full inline
citations; the items below would upgrade the snippet-depth additions.

- [ ] **`yellow_pitaya--plantpono-wra`** (Online): the PlantPono / Hawaii
  Pacific Weed Risk Assessment PDF for *S. megalanthus* (final score not shown in
  the snippet).
  - **Needed for:** a firm weed-risk score to anchor the Invasiveness/biosecurity
    bullet, now resting on "naturalised but not a serious weed" [10].
- [ ] **`yellow_pitaya--cactus-virus`** (Library): a virology source naming the
  cactus virus carried in *S. megalanthus* cutting material (likely cactus virus
  X).
  - **Needed for:** naming the clonal/viral-degeneration pathogen behind the Soil
    biology and Propagation bullets [1].

### artocarpus_mutabilis (2026-11-25)

First research of the wild Bornean sister species of marang (pingan /
tonggom-tonggom), after it passed its gate check. Only snippet/abstract-level
material was readable; the full texts below hold almost all the species-specific
data.

- [ ] **`artocarpus_mutabilis--telopea-2026`** (Online): Ruslan, [N.A.], Gardner,
  E.M. and Ahmad Puad, A.S. (2026), "Comparative leaf anatomy between two sister
  species: *Artocarpus odoratissimus* (Lumok) and *A. mutabilis* (Pingan) in
  Sarawak," *Telopea* 30:25-34 (Sydney Open Journals, openjournals.library.sydney.edu.au/TEL/article/view/21732).
  - **Needed for:** the anatomical measurements, habitat/ecology and any range or
    phenology detail for *A. mutabilis* specifically (Climate zones; Findings 2-3)
    [2].
- [ ] **`artocarpus_mutabilis--gardner-2022`** (Library): Gardner, E.M. and others
  (2022), "Engagement with indigenous people preserves local knowledge and
  biodiversity alike," *Current Biology* 32(11):R511-R512,
  doi:10.1016/j.cub.2022.04.062.
  - **Needed for:** the complete diagnostic character set separating pingan from
    lumok (Finding 3; Naming) [1].

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

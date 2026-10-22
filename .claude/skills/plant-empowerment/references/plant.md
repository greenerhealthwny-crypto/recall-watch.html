# Plant Empowerment — The Plant (Chapters 2–3)

Paraphrased from the book. Numbers are the book's examples and rules of thumb, mostly for a full-grown tomato crop.

## Contents
- §1 The plant energy balance and evaporation
- §2 Stomata, leaf temperature and VPD
- §3 The plant water balance: roots, stem, buffer, root pressure
- §4 The assimilates balance: photosynthesis, temperature, CO2, LAI, light, sinks, plant load, RTR
- §5 Secondary balances: nutrients, rootzone microbiology, hormones
- §6 Common problems explained by the balances

---

## §1 The plant energy balance and evaporation

- Plants can't raise their own temperature by burning sugars (except a few thermogenic flowers). Leaf temperature is set entirely by external energy flows; inputs minus outputs must equal zero (conservation of energy).
- **Energy flows:**
  - **Short-wave radiation** (sun, lamps) is the main input. Most absorbed energy is discharged by evaporating water; only a small part goes into photosynthesis. Leaves reflect some light: tomato reflects about 20%; glossy sweet pepper leaves reflect more.
  - **Long-wave radiation** (heating pipes, HPS fixtures) is minor overall but matters locally, e.g. it warms plant heads under lamps and fruit near a hot "growing pipe".
  - **Heat emission:** long-wave exchange with colder bodies such as the roof, a cold screen or the sky. Usually a loss.
  - **Convection:** heat from moving air. It is an input when the leaf is colder than the air and an output when it is warmer. For non-evaporating parts (flowers, fruits) under high radiation, convection is the main way to cool.
- **Evaporation needs an energy surplus.** It is passive: the plant spends no assimilates on it. There are two sources:
  - **Convection evaporation ("wet bulb"):** needs air movement and a leaf colder than the air, so RH must be below 100% (HD > 0). This is the classic RH/HD-driven evaporation measured in an aspirator box. The convectively active leaf area is about 2 × LAI (both leaf sides).
  - **Radiation evaporation ("tea kettle"):** radiation heats the leaf's spongy inner cells, and vapour escapes through the stomata. Under high radiation, evaporation is roughly proportional to radiation and **largely independent of air humidity**.
  - At night, only convection drives evaporation. After sunrise, radiation dominates in the top of the crop, while convection still prevails lower down.
- **New insights the book stresses:**
  1. Evaporation is driven by absorbed energy, not by RH, HD or VPD as such. Even at high RH a plant evaporates if energy is supplied.
  2. Evaporation doesn't depend on leaf temperature itself, only on the leaf-to-air temperature difference.
  3. The Penman-Monteith (1948) assumption that leaf temperature equals air temperature misses convection's role. If it held, stomata couldn't regulate evaporation.
  4. **Air movement** feeds convective energy at night and on dark days, and is needed for stomatal control under high radiation.
  5. **Heat emission** at night, and at the start and end of the day under a cold roof, can push evaporation and calcium uptake below the critical minimum.
- **Light source energy:** PAR (400–700 nm) drives photosynthesis. Other wavelengths and fixture heat drive evaporation. LEDs give much less long-wave heat than sun or HPS, so crop evaporation and nutrient uptake under full LED can be about half that under sunlight or HPS. This means nutrient deficiencies are possible, and growing chambers often rely on intense forced air movement to compensate.

## §2 Stomata, leaf temperature and VPD

- **Mechanism (tea-kettle analogy):** a smaller valve opening needs a higher internal vapour pressure, so a hotter kettle, to release the same steam. Partly closing the stomata therefore raises leaf temperature relative to air. That shifts the convection term:
  - **Evaporation energy = radiation + convection** while the leaf is colder than the air (stomata open, plenty of water).
  - **Evaporation energy = radiation − convection** once the leaf is warmer than the air (stomata pinching as water runs short). Air then helps cool the leaf.
- **Control range example:** at 500 W/m² sun with a leaf 1 °C below air, open stomata give about 550 W/m² for evaporation. With stomata closed until the leaf is 1 °C above air, about 450 W/m². That is roughly ±10%: small, but it is the difference between high photosynthesis and just surviving. Leaf convection is about 10–20 W/m²·°C per m² of leaf, or about 50 W/m²·°C per m² of soil for a crop with LAI 3–4.
- **VPD** (vapour pressure difference leaf–air) is a *result* of evaporation rate and stomatal conductance, not the driver. You need leaf temperature to calculate it.
  - **Typical healthy range: 0.3–1.5 kPa**, depending on radiation. Tomato and cucumber can evaporate a lot at low VPD when the stomata are wide open, even at high RH.
  - **Above ~1.5 kPa (1.5–2 kPa for most plants):** stomata are closing, the leaf heats up and vapour is being "squeezed out". This is real water stress.
  - **Below ~0.2 kPa:** almost no driving force. This happens at night with RH > 95% plus heat emission. Then there is hardly any evaporation or calcium uptake, and the leaf may be at or below dew point (condensation).
  - Very young leaves have immature stomata and can leak even at moderate VPD.
- **Leaf temperature as a signal:**
  - Leaf colder than air: ample water.
  - Leaf briefly rising above air after a jump in light, then recovering: normal lag.
  - Leaf staying above air: water shortage, stomata partly closed.
- **How stomata work:**
  - Guard-cell turgor is driven by potassium pumps under light. Root-made **cytokinin** promotes opening; **abscisic acid (ABA)**, made under water shortage, closes them fast and takes hours to break down. Avoid water-stress episodes, because recovery lags.
  - Stomata also follow an internal daily clock.
  - **"Use it or lose it":** stomata in very steady climates (e.g. roses under constant lighting) can lose the ability to close, and the cut flowers then wilt in the vase. Trigger normal stomatal action about once a day.
- **CO2 and stomata:**
  - With enough water, stomata stay open whatever the CO2 level.
  - High CO2 lets stomata close earlier to save water. But then evaporation falls, temperature rises, RH drops, vents open further and CO2 is lost. This is a **negative spiral**.
  - Better under high radiation: keep vents more closed so humidity keeps the stomata open and CO2 stays in.
  - CAM plants (e.g. some orchids) open at night: their CO2 buffer explains a reversed rhythm.
- **Night:** a full-grown tomato still evaporates about 25 g/m²·h. Stomatal opening has little effect on night evaporation; convection energy does.
- **Air movement:** in still air there's no convective transfer, so stomatal regulation can't work. Horizontal fans mainly even out temperature, with limited and sometimes counterproductive effect. **Vertical fans** are effective at activating the microclimate, especially under closed vents and screens.
- **Humidity's real role:** with no radiation, evaporation is roughly proportional to HD (wet-bulb behaviour). Under high sun (e.g. about 90% radiation, 10% convection), high RH doesn't stop cooling. It just lets the stomata stay open with a slightly lower leaf temperature, which favours CO2 uptake and photosynthesis.

## §3 The plant water balance

- Output is mostly evaporation; little water is stored. Plants evaporate for nutrient uptake, growth and cooling. Uptake must at least equal evaporation, so align irrigation with evaporation energy.
- **Water availability** depends on three things:
  - **Root uptake capacity:** number of young white root tips, oxygen (aeration), root temperature, substrate volume and properties, cultivar and rootstock.
  - **Stem transport resistance:** stem length (older, long tomato stems suffer more in summer), the graft union, and stems per root.
  - **The plant's water buffer:** leaves and especially fruits (tomato, cucumber). Harvesting heavily at once removes buffer, so keep plant load regular.
- **Watering strategy:**
  - Low water content early in the crop promotes rooting.
  - No need to keep slabs saturated at night; lowering water content lets oxygen in.
  - From sunrise, raise water content ahead of rising evaporation with frequent drip cycles, and possibly a lower EC on sunny days. Anticipate, because even a short stress hampers photosynthesis for hours.
- **Root pressure vs suction:** at night, active roots build overpressure (osmotic pump, up to ~5 bar, small capacity). By day, leaf evaporation creates suction. Too-high root pressure can be countered by keeping a low but active evaporation level.
- **Layer competition:** extra convective evaporation in lower layers (e.g. dry air from tubes under the gutter in semi-closed greenhouses) steals water from the plant head under high light. Long stems and weak roots make this worse.
- **Daily growth pattern:** on a sunny day, uptake lags evaporation until about noon. Fresh-weight growth is low or even negative in the morning, then catches up in the afternoon and night. The maximum is reached just before the next sunrise. Dark days show steady growth.
- **Self-balancing design:** radiation drives temperature (growth rate), photosynthesis (building blocks) and evaporation (nutrient supply) in proportion, so each part gets the right mix. Light that differs strongly from sunlight (e.g. heavy LED) breaks this proportionality.

## §4 The assimilates balance

- **Production = photosynthesis** (6 CO2 + 6 H2O + light → sugars + O2). **Consumption = dissimilation and growth.** Dissimilation (respiration) releases energy as ATP for building cell walls, proteins and so on, and for transport and nutrient uptake.
- Unused assimilates pile up as starch in leaves or as thick cell walls. That is waste, and it slows photosynthesis by feedback.
- **High temperature is not "waste":** high growth needs high dissimilation. The more assimilates are made, the higher the plant temperature can and must be to use them. Photosynthesis is especially sensitive to *low* temperature.
- **CO2 + temperature together:** in the book's chrysanthemum example, raising CO2 from 350 to 1000 ppm raised net photosynthesis about +50%; combined with a higher temperature, about +80%. The optimal temperature rises with CO2.
- **Three views of the balance:**
  1. Processes: photosynthesis vs dissimilation and dry matter.
  2. Sources (adult, well-lit leaves) vs sinks (fruits, flowers, roots, young or shaded leaves). Source size = productive leaf area (LAI); source activity = rate set by PAR, CO2, light penetration and so on. Sink size = plant load (fruits/m² or plants/m² × buds); sink activity = rate set mostly by temperature and development stage.
  3. Climate: light, CO2 and RH on the production side; temperature on the consumption side.
- **The art of optimisation:** find and improve the restricting factor, again and again.
- **CO2:** uptake vs PAR follows a saturation curve (enzyme Rubisco, stomata, chlorophyll limits). Align CO2 with light and keep RH high enough for open stomata.
- **LAI (source size):** about **3–4** is optimal to intercept most light. Grow leaf area quickly in young crops. Don't grow too generatively, with too little leaf, e.g. some tomato or high-wire cucumber. Too high an LAI (pepper, eggplant, rose, gerbera, chrysanthemum) turns lower leaves into sinks and hurts air movement and moisture.
- **Light distribution (source activity):**
  - **Open plant architecture** lets light reach lower leaves.
  - **Diffuse light** penetrates deeper, gives middle leaves more light and chlorophyll, and causes less water stress in the head.
  - **Inter-lighting** brings light and heat into the canopy; top leaves of a rose photosynthesize more than lower leaves at the same light.
- **Plant load (sink size):** plan it against the long-term average light curve through the season, and monitor actual vs planned. A **lower plant load** keeps balance more easily, allows higher temperatures on sunny days (less ventilation, more CO2 and RH, more photosynthesis) and means fewer problems with fruit set and quality: a positive spiral. Too high a load gives a negative spiral.
- **Sink activity and temperature profile:** phloem loading and unloading carriers run faster when warm. Warmer sinks pull more assimilates. Well-lit, warm fruits in an open crop pull strongly, which reinforces generative balance; a closed crop with cold fruits reinforces vegetative growth. The **vertical temperature profile** steers development speed at the growing tip, fruit ripening and plant load. Rail pipe, grow pipe, lighting and fans shape it.
- **RTR (Ratio Temperature to Radiation):** align consumption with production every day by keeping a steady ratio of 24-hour average temperature to daily light sum.
  - More light at the same temperature gives a plant that is too strong, thick or vegetative.
  - A higher temperature without more light gives a plant that is too weak or generative, short of assimilates.
  - Both raised at the right ratio give faster development with a balanced shape.
  - A steady RTR also gives a steady rate of fruit set, flowering and ripening, so it is also a plant-load tool. Practice: `practice.md` §3.

## §5 Secondary balances

- **Nutrients:** macro-elements, needed in large amounts, and micro-elements (B, Cu, Mn, Mo, Fe, Zn), needed in small amounts but equally important. Demand shifts with the vegetative/generative ratio. A steady RTR and plant load stabilize the nutrients balance.
- **Rootzone microbiology:** PGPR (plant-growth-promoting rhizobacteria) and AMF (arbuscular mycorrhizal fungi) pre-process nutrients and protect roots in exchange for sugars (root exudates). With an assimilate shortage, the plant stops feeding them, leading to a negative spiral and pathogens gaining ground.
  - Adding biostimulants helps only temporarily if the plant can't feed the extra soil life.
  - Stressed plants seem to signal enemies; healthy plants signal allies.
- **Hormones:** examples include tip dominance, the vegetative-to-generative switch, root initiation, stretching, cytokinin (opens stomata) and ABA (closes them). Shifts are triggered by day length, sudden temperature drops and stress. Artificial hormones have uses (e.g. rooting cuttings), but stabilising the primary balances is the best way to keep hormones, and development, regular.

## §6 Problems explained by the balances

A balanced plant grows regularly, resists pests and diseases and absorbs climate disturbances. An unbalanced one slides into a negative spiral. Typical issues:

- **Calcium shortage** (tip-burn, glassiness, head-burn, blossom-end/tip rot):
  - Calcium moves only with evaporation, especially to young tissue at the growing tip.
  - A surplus at one moment is locked in the vacuole and can't be used later. Evaporation at the tip must not drop below a crop-specific minimum, roughly **5–20 g/m²·h**, for long.
  - Root pressure does *not* reliably supply calcium.
- **Crop condensation** (no nutrient supply there, plus free water for Botrytis):
  - It happens only where a plant part is below the air's dew point, not simply at "high RH".
  - Risk spots: cold places the aspirator box doesn't see (side walls, under vents, under screen gaps, still air); heavy fruits lagging at sunrise while the upper crop raises AH; plant heads cooled by heat emission around sunset to sunrise.
  - A lower RH does not guarantee no condensation.
- **High root pressure and guttation** (inner rot in pepper, Mycosphaerella in cucumber, glassiness, Botrytis, cracked fruit):
  - Cause: active warm roots plus sharply falling evaporation (late afternoon or evening, rising RH, heat emission), or roots warmed in the early morning while evaporation is still low.
  - Weak young cells (short of calcium or assimilates) tear.
  - Fix: steady RTR and plant load for regular root growth, an active climate with fans, RH not too high, and a closed screen against heat emission.
- **Lack of air movement:** RH around leaves approaches 100%, there's no convective energy, nutrient transport stalls, and the aspirator box misreads the canopy. Avoid it at all times.
- **Heat emission:** cools the plant head (the most vulnerable part) and affects all three balances:
  - Energy: lower leaf temperature, condensation.
  - Water: less evaporation and calcium, more root pressure; less cell elongation via aquaporins.
  - Assimilates: less transport to cold fruits, buds and young leaves.
  - Closing one or more screens is the most powerful remedy.
- **Fungal diseases** signal disturbed balances. They usually come from free water (condensation, guttation) or weak cells, not from high RH itself.

# Plant Empowerment — Growing in Practice (Chapters 6–11)

Paraphrased from the book. Numbers are its examples and rules of thumb; adapt them to the crop and site.

## Contents
- §1 GPE climate strategy: the four strategies and practical tips
- §2 Monitoring the balances (graphs to read)
- §3 Assimilates in practice: RTR, plant load, CO2-to-light, photosynthesis
- §4 Water, roots, architecture, health, post-harvest
- §5 Challenging outdoor conditions
- §6 Equipment: cover, ventilation, fans, heating, screens, misting, CO2
- §7 Sensors
- §8 The five roadmaps and integrated adjustment

---

## §1 GPE climate strategy

The best balance comes when all climate factors are continuously **aligned with radiation, or the daily light integral** (sun plus lamps). The book gives four strategies:

1. **Maintain the greenhouse balances:**
   - A homogeneous climate with no cold or wet spots (design, ventilation, heating, screens).
   - AH and temperature inside always **sufficiently above outdoor**, so energy and moisture can leave.
   - Ventilation based on moisture and CO2, not only temperature.
2. **Maintain the assimilates balance:**
   - Average temperature in line with the light sum (RTR).
   - Plant load planned against the expected light for the time of year.
   - CO2 limited according to crop and light.
3. **Maintain the plant energy and water balances:**
   - The more light, the more evaporation, so water supply must follow radiation.
   - To prevent water stress and stomatal closure, keep RH up as PAR rises, mainly by restricting ventilation, and sometimes by misting.
4. **Keep the plant in optimum condition:** prevent heat emission, keep air moving, and support the secondary balances. This is **Data-Driven Growing**: physics plus sensor data plus crop data, a building block for the Autonomous Greenhouse.

**Practical tips (ch. 2):**
- Learn the psychrometric chart.
- Steer on the crop's energy and water balance, not just on temperature and RH set points.
- **Anticipate the weather** (radiation, outdoor temperature, wind, heat emission) instead of reacting after the greenhouse drifts.
- Ensure air movement, with vertical fans rather than minimum pipe temperature.
- Avoid heat emission by closing screens 80–90% or fully at the right time.
- Screen without moisture gaps as much as possible.
- Ventilate *above* a closed screen for humidity, rather than raising pipe temperature.
- **Use leeside and windside vents together:** small openings on both sides give a gentler, more homogeneous exchange than wide-open leeside vents alone.

**Note on photosynthesis vs shading:** for many crops, photosynthetic capacity can be stretched well beyond the usual assumption just by **keeping humidity high under high radiation**: fewer vent openings, sometimes misting. Do this before pulling the shade screen or applying whitewash. Limit light only as a last resort, after humidity and water supply have been fixed.

## §2 Monitoring the balances

Plot inside climate **together with weather** (radiation, outdoor T and AH, wind, heat emission), screen and vent positions, and pipe temperature. That way you see causes, not just results.

- **Greenhouse energy balance:**
  - The temperature trend shows solar input vs losses (outdoor temperature, wind, vents, heat emission).
  - Ventilation need depends on **enthalpy** inside vs outside, not only on temperature difference.
  - Measure solar radiation with a pyranometer and sky heat emission with a pyrgeometer.
- **Ventilation and CO2:** more ventilation always lowers RH and loses CO2. Without enrichment, low ventilation depletes CO2 (about 400 ppm outside → about 200 ppm inside). Monitor inside CO2 either way.
- **Moisture balance:**
  - Read the **AH trend** (flat = balanced), not RH.
  - ΔAH below vs above the screen = capacity to move moisture through the screen.
  - ΔAH above the screen vs outside = whether extra ventilation above the screen will help. If the difference is small, it won't.
  - Roof temperature vs dew point = condensation capacity. Wind brings the roof closer to outdoor temperature.
- **Condensation risk in practice:**
  - *Evening:* dew point close to crop temperature as the greenhouse cools.
  - *Sunrise:* upper leaves warm and raise AH while heavy fruits lag. Raising greenhouse temperature alone doesn't help. Raise temperature gradually well before sunrise, and keep the screen closed longer.
- **Plant energy balance:**
  - An **infrared leaf temperature sensor** (it averages about 3–10 m² of canopy) is the key tool. Leaf colder than air means plenty of water. A brief rise above air after a jump in light is a normal lag. Staying above air means water shortage and closing stomata.
  - Calculate **VPD** from leaf temperature: aim for 0.3–1.5 kPa. Above 1.5 means beginning water stress; below 0.2 means almost no evaporation, possible condensation.
  - **Net radiation at crop level** shows what the crop really gets. The book's example: opening the first screen at about 300 W/m² outside made net radiation *drop*, because the crop then "saw" a colder second screen. Evaporation fell until the screen closed again.
  - A thermographic camera shows local overheating of buds, fruits and leaves.

## §3 Assimilates in practice

- **RTR (temperature-to-light ratio):**
  - Make a scatterplot: daily light sum (J/cm² outside, or better **PAR mol/m² at crop level**) on the X-axis, 24-hour average temperature on the Y-axis. Each dot is one day; the trend line is your realized RTR.
  - Set a target line (with margins) and keep daily points close to it.
  - Without this, the plant is balanced "on average" but out of balance on most days.
- **Making temperature follow light:**
  - Adjust the **ventilation set point** to current radiation or PAR.
  - After a **sunny day**, postpone the day-to-night drop and keep the night warmer, so the assimilates can be transported out of the leaves.
  - After a **dark day**, keep the night cooler; there are few sugars left to use.
  - Closing energy screens before sunset holds solar heat, so the warmer transition costs little extra heating.
  - If CO2 or RH are limiting (e.g. heavy ventilation), or whitewash or shade cuts light, the target temperature must come down.
  - At the start of a crop (low plant load), you can run warmer at the same light. Begin RTR control once fruit set and harvest are regular.
- **Plant load:**
  - Plan sink size (fruits/m², stems/m², buds) against a **10-year weekly average light curve**, including lamp light if used. Register fruit set, harvest and plant load weekly against the plan.
  - Sink strength = plant load × sink activity (temperature). A high load at low temperature equals a low load at high temperature.
  - With a **lower plant load**, raise the RTR line (more temperature per unit of light). Ventilate even less on sunny days, which gives more CO2 and humidity and more assimilates.
  - A typical failure is plant load above plan in late season, when light falls quickly but outdoor temperatures stay high.
- **Vertical temperature profile:** affects plant architecture and the relative sink strength of tip, fruits and roots. Monitor it with aspirator boxes at several heights. Lighting type matters: HPS heats the top, LED inter-lighting brings light and heat lower, and diffuse light penetrates deeper.
- **CO2-to-light rule of thumb:** keep CO2 in **ppm at least equal to outside radiation in W/m²** (e.g. 600 W/m² → at least 600 ppm). This gives the most economical dosing and best light use efficiency, with high RH to keep stomata open.
- **Photosynthesis management:**
  - It can't be measured directly at crop level in practice. A leaf photosynthesis meter is a research tool.
  - Monitor the combination of PAR, CO2, RH and temperature against your own target values, and keep a keen eye on the restricting factor.
  - Options: high-pressure misting to raise RH under high radiation; a retractable diffuse screen instead of whitewash.

## §4 Water, roots, architecture, health

- **Irrigation:**
  - Slab-weighing scales and drain measurement show supply, not the plant's water *status*. The plant can be stressed even when supply equals uptake: root capacity or stem resistance may be the limit.
  - Classic evaporation models assume leaf temperature equals air temperature. Energy-balance models that use **measured leaf temperature** need fewer parameters and work better.
  - Irrigate on **accumulated radiation energy**: a pyranometer or PAR sum, refined with leaf temperature, VPD and pipe temperature. The book's tool plots daily irrigation (L/m²) against radiation sum (J/cm²).
- **Root temperature:** slabs are coldest around sunrise, exactly when uptake must accelerate, and warmest around sunset, when guttation risk is highest. Cold roots in the morning cause stomatal closure and slow photosynthesis. Monitor root temperature with multiple sensors.
- **Avoid root overpressure:**
  - Regular root growth through a steady RTR and plant load.
  - An active climate with fans.
  - RH not too high.
  - A screen closed against heat emission.
  - No heating of the roots while evaporation is still low.
- **Plant architecture:** cell elongation is the sum of assimilate supply, evaporation, root pressure, aquaporins and hormones.
  - *Generative / compact:* low humidity under high radiation; less water (risky); a pre-night temperature drop for better transport to fruits; "reversed DIF" (warmer night than day) for short plants; red light for stocky plants (far-red gives long internodes).
  - *Vegetative:* high humidity with low radiation and regular watering.
  - Most standard "steering" acts on the water balance and is hard to predict. The GPE way steers mainly through **assimilate distribution**: the right combination of radiation, humidity and CO2 with higher temperature. That gives low sugar left in the leaves, better fruits or flowers (taste, vase life) and high light use efficiency.
- **Root management:** roots are the furthest sinks and feel assimilate shortage first. Keep production and consumption in balance (RTR), with regular harvesting and fruit set.
- **Plant health and resilience:** the classic "active climate" (open vents, open screens, high minimum pipe) works reasonably but costs energy and crop protection, and is no guarantee. GPE instead relies on:
  - Steady plant balances and a lower plant load in dark periods.
  - Double screens against heat emission.
  - Forced air movement.
- Biological control generally works well under GPE climates; avoid combinations like high temperature with low humidity where they hurt beneficials.
- **Post-harvest quality** (e.g. roses that wilt in the vase): grow healthy cells with an RTR matched to plant load, and **trigger normal stomatal action dynamically, about once a day**, so the stomata stay functional.

## §5 Challenging outdoor conditions

Frame every climate as an **RTR problem**: given the available light, can the greenhouse reach the target average temperature? It can be too high (hot climates) or too low (cold or dark climates).
- Raise the temperature-to-light ratio: more insulation (screens), higher plant temperature, lower plant load, or a suitable cultivar.
- Raise light: supplemental lighting.
- Matching cultivation to the climate makes temperature and humidity control easier and needs only limited extra technology.

- **High solar radiation:**
  - Beware the **negative spiral of shading**. Whitewash or shade reduces water stress but not greenhouse temperature, and it lowers photosynthesis and root development. The plant then becomes stressed at even lower light, which leads to more shading.
  - First reduce water stress by other means: humidity, water supply, root health, diffuse light.
- **Hot and dry:** misting or adiabatic cooling raises RH and enthalpy and cuts ventilation (and CO2 loss).
- **Hot and humid:** adiabatic cooling doesn't work. Keep the greenhouse slightly above outdoor temperature with high RH, so AH inside stays above outside for moisture exhaust. Use vertical fans to drive evaporation and push humid air up to the roof vents.
- **Hot, dry and dusty / high wind:**
  - Roof vents are impractical, so **pad & fan** is typical. Drawbacks: about 8 °C or more difference between pad and fan side (three climate zones in one house) and limited bay length (about 60 m).
  - The book suggests heavy misting with decentralized ventilation as a more uniform, lower-energy and lower-water alternative.
- **Lack of wind:** add fans (roof or sidewalls) for exhaust and inside fans for an active microclimate.
- **Very low outdoor temperature:**
  - Protect the cover from ice and snow (heat above the screens to melt it).
  - With two screens, make the **lower one airtight** to prevent condensation on the colder upper one. Gap the upper screen to release heat, not the single screen above the crop.
- **Low natural light:**
  - Supplemental lighting changes the temperature-to-light ratio.
  - Blackout screens (light-emission rules) trap humidity; use screens with adequate vapour permeability, or controlled ventilation.
- **Moisture at night by ventilation** works as long as inside AH is above outside AH. That holds in both a cool, humid climate (e.g. Netherlands) and a hot, dry one (e.g. Arizona).
- **Lower temperature is not automatically cheaper:** close to outdoor temperature, much more ventilation is needed to remove moisture, and the energy loss rises. Raising greenhouse temperature can *reduce* energy loss at a given moisture exhaust. A heat exchanger in forced ventilation cuts that loss by about 50% more.
- **Mechanical cooling or dehumidification** is expensive for small savings. Under GPE, high day temperatures are usually acceptable when RTR is balanced, and it's easier and cheaper to lower the night temperature.

## §6 Equipment

- **Cover:**
  - Glass vs PE; single roof plus retractable energy screens is the standard.
  - AR-coated low-iron glass raises PAR transmission; use the extra light with misting and CO2.
  - Diffuse cover or screen is good for most crops.
  - FIR transparency ("thermicity") matters for heat emission (see `physics.md` §6). On PE covers, watch condensation behaviour: droplets cut PAR, while a continuous film helps against heat emission.
- **Natural ventilation:**
  - Leeside and windside vents. Wind and the chimney effect drive exchange.
  - A wide-open single side gives poor control and cold air falling straight onto the crop.
  - **Open both sides at small angles** for gentler, local exchange. With very low outdoor temperature, combine with a fully closed screen.
  - Air above the screen should be close to outside AH; regulate vents on ΔAH or Δenthalpy.
  - Single-factor control (only temperature, only moisture or only CO2) never gives the best result. Combine all three.
- **GPE ventilation practice:** keep vents minimal by day so CO2 and AH stay high around the crop.
- **Mechanical ventilation:**
  - Used with airtight screens, in windless regions, and with lighting.
  - Regulate air volume on **ΔAH** when moisture must go (night) and on **Δenthalpy** when energy must go (day and evening). Control fan speed to hold a target evaporation at night, or the energy balance by day.
  - Avoid cold, dry jets onto the crop; put the biggest air volume around the top of the canopy.
  - *Sizing for moisture:* discharge = air volume × ΔAH. E.g. 5 m³/m²·h × 4 g/m³ = 20 g/m²·h. If ΔAH is too small, raise inside temperature or limit air exchange (close vents or screen) to raise inside AH.
  - *Sizing for heat* (lamps, blackout screens): air volume = heat ÷ Δenthalpy. Limit the heat at its source first.
- **Air tubes:**
  - Daytime cooling by tubes needs up to about 80 m³/m²·h and tubes up to about 1 m in diameter.
  - Dry air from tubes under the gutter boosts evaporation in the lower layers and starves the plant head under high light. At night it raises AH and condensation risk in the tops.
  - Tube air quickly adapts to surrounding temperature, so tubes are not a good means of heating or cooling.
- **Vertical injection fans:** an alternative to tubes under a fully closed screen. They mix cold, dry outside air horizontally just below the screen, so it blends before reaching the crop.
- **Air movement:**
  - **Minimum pipe temperature** creates air movement but causes extra evaporation and often needs screen gaps. Better: pipes only for temperature, screens closed, fans for movement.
  - **Horizontal fans** rarely fix temperature differences, which have many causes; they work only in airtight, well-insulated houses. They raise AH and RH along the airstream, can drop cold air, and move air mainly above the crop. Even 4800 m³/h works out to only about 8.3 mm/s of real air movement across the area.
  - **Vertical fans** (about 4000–6000 m³/h each; DC motors for easy speed control) push warm air and lamp heat down, cool overheated buds and tips (air speed above about 0.2 m/s), even out the vertical profile and CO2, and drive moisture up toward the roof.
- **Temperature differences:**
  - Wind creates under-pressure, so cold air drops through screens and gaps near the leeside or windside.
  - A **screen gap** sets up a circulation: cold air drops near the sidewall, warm air rises through the gap. Over a long bay this can mean up to about 8 °C difference, worse with heating or lamps. Gaps under about 10 cm still cause this; wider gaps no longer save energy.
  - **Vertical screens (apex seals)** above the screen split the space into sections of about 30–35 m.
  - Porous screens behave like gapped ones.
  - With two screens, keep both closed and ventilate above them rather than gapping.
- **Mechanical dehumidification:** condensing units and heat pumps (recovering latent heat) or liquid-desiccant (salt water) systems reduce the need for ventilation for humidity, but ventilation may still be needed for temperature.
- **Heating:**
  - Hot-water pipes, ideally with low pipes plus pipes just above the crop to offset heat emission.
  - Good screens allow smaller pipes and lower energy.
  - Heat by **daily average temperature according to light sum** (RTR) rather than fixed set points.
  - Avoid extra local heating at cold walls; fix the insulation or cold airflow instead. Otherwise control those pipes separately.
  - Air heaters are poor for uniformity.
- **Screens:** see `physics.md` §6 for heat emission. In practice:
  - **Night screens:** maximum insulation (still-air layers between screens), low emissivity (aluminized), low unwanted ventilation (seals at gutters and trusses), and controllable porosity for moisture.
  - **Morning:** opening a well-insulated screen drops cold air and shocks the crop (evaporation dips, pipes overheat later, condensation on heavy fruits). Raise greenhouse temperature gradually long before sunrise. Open only when the temperature above the screen has been raised by the sun; use a net-radiation sensor under the screen to time it.
  - **Transparent retractable day screens** (e.g. ETFE-type foils) cut PAR only about 11–15%. They can stay closed on cold days and cut ventilation by 30–50%.
  - **Blackout screens with lamps:** lamps add 50–250 W/m² and evaporation of 50–160 g/m²·h, needing large ventilation. Growers often gap the screen, causing cold spots. Better: a more airtight screen or a second screen, plus vertical fans. The book cites about 30% less energy input.
- **Misting:**
  - Use it to cover the gap between energy input and the root system's maximum uptake.
  - Control it on solar radiation (outside), PAR (inside), leaf temperature and air T/RH, not on RH alone. RH-only control causes fungal issues from over-misting at the wrong moments.
  - When misting and ventilation both follow radiation and enthalpy, temperature and humidity balance.
- **Roof sprinklers** cool the roof (lowering air temperature indirectly). Keep the roof continuously and evenly wet with multiple ridge pipes.
- **CO2 supply:** at least about 350 ppm around the stomata. Distribute both horizontally and vertically, dosing into the upper (light-intercepting) layers. Vertical fans plus some vent opening help distribution without enrichment.

## §7 Sensors

Simple control with only inside temperature and RH is not enough. **Outdoor sensors let the system anticipate.**

- **Weather station:**
  - Mast close to the greenhouse, about 2 m above the ridge.
  - Air temperature and RH in a radiation shield.
  - Pyranometer (total solar spectrum).
  - Wind speed and direction.
  - Rain detector (tilted, heated; intensity versions exist).
  - **Pyrgeometer** for sky heat emission. This is a crucial and often missing sensor.
- **Inside:**
  - **Aspirator box** (ventilated, shaded, protected from drips) with temperature and RH:
    - Low crops: just above the canopy. High crops: between the plant heads.
    - Ideally at two heights for the vertical profile, and several across large houses.
  - A **second box above the screen** is essential for screen and ventilation strategy. Keep it away from vents, lamps and gaps, and accessible for maintenance.
  - **CO2 sensor**, preferably inside the aspirator box.
  - **IR leaf temperature sensor:** called the most important practical sensor. Aim it at the crop at a fixed angle, avoiding soil, pipes and gables.
  - **PAR sensors:** several, in full light, or calculated from outdoor radiation and cover, whitewash and screen transmission.
  - Stomata sensor module (leaf temperature + PAR + climate, calculating conductance and evaporation).
  - Thermographic camera (relative differences matter more than absolute accuracy).
  - **Net radiation sensor** close to the canopy, level. Beware control oscillations if it directly operates screens.
  - Slab scale (2–3 m long) or wetness sensors.
  - Root-zone temperature (several probes, chosen depth).
  - **Wireless sensor networks** for heat maps of temperature, humidity, PAR and CO2 across the house.

## §8 The five roadmaps

Each roadmap has four parts: **basic principles → improved measurements → monitoring and interpreting → take small steps**. Every step affects other balances, so integrate changes into the overall strategy (see "Integrated adjustment" below). Small first steps pay off from day one.

1. **Improve climate uniformity:**
   - Find and fix causes first: screen gaps, cold airflows, cover leaks, heating layout, ventilation (use both leeside and windside).
   - Measure with multiple or wireless sensors and calculate AH differences across the house.
   - Horizontal fans without knowing the cause rarely help.
2. **Protect the crop against heat emission:**
   - Measure net radiation above the crop. Add an above-screen aspirator box. Use an outdoor pyrgeometer to estimate roof temperature.
   - Steps:
     - Close the night screen about **1 hour earlier** than the outdoor-temperature rule would, earlier still on a clear, sunny day.
     - Close it fully while the greenhouse is still about **1 °C above the night set point**, then go further step by step.
     - In the morning, keep it closed until the air above the screen has warmed; a transparent screen helps.
     - Two screens partly closed can cut heat emission without blocking heat and moisture exhaust.
     - A good time to start is at the end of a crop season, then extend year-round.
3. **Control the moisture balance:**
   - Monitor AH below the screen, above it and outdoors, plus roof temperature vs dew point.
   - Steps:
     - Cut unnecessary evaporation first: replace minimum pipe temperature with heating only on heat demand or when crop temperature nears dew point; don't let soil or crop be wet at day's end; adjust night irrigation.
     - Cool down less aggressively in the evening so inside AH stays a few g/m³ above outside; if RH gets too high, raise temperature slightly to increase exhaust capacity.
     - Keep cold spots above dew point.
     - Close the screen fully (no gap) to promote condensation on the roof; ventilate above it. With two or more screens, gap the lower one first if needed.
     - Keep air moving under closed screens.
4. **Support the assimilates balance:** three levels with different impact and reaction time.
   - **Cultivation plan:** plant load matched to the expected (10-year average) light curve; reaction time weeks; biggest impact.
   - **RTR management:** daily temperature matched to the light sum; reaction time days.
   - **Photosynthesis management:** PAR, CO2 and RH aligned; reaction time minutes.
   - Applying them in this order also helps solve quality and health issues: inner rot, Botrytis, glassiness, blossom-end rot.
5. **Support the water balance of the crop:**
   - Use leaf temperature and VPD (low VPD below about 1.5 kPa = open stomata; rising VPD = closing).
   - Steps:
     - Start controlling ventilation on **humidity instead of temperature in the late afternoon**, when overheating risk is lowest, then move the start earlier step by step.
     - Open **windside vents much earlier**, together with leeside vents (e.g. when leeside is 10% open, windside opens too), for smaller total openings and a more homogeneous climate. The old belief that windside ventilation harms the crop is mostly outdated.

**Integrated adjustment (book §10.6–10.7)**, in short:
- A higher temperature-to-light ratio (RTR) improves the assimilates, water and energy balances.
- Limited ventilation keeps moisture and CO2 in, raising enthalpy so temperature is easier to control and less ventilation is needed.
- Less heating means less excess evaporation. A higher RH under a closed screen means less ventilation demand. A bigger inside–outside difference improves exhaust.
- A homogeneous climate means less Botrytis. Warmer fruits and buds mean less condensation in the morning.
- Take the plant as the starting point. Apply insulation to the maximum and add solutions only where needed.
- Keep greenhouse temperature and AH sufficiently above outdoor levels. Ventilate for optimal photosynthesis (high CO2 and RH), not only for temperature. Interpret plant development and climate with data.

**Chapter 11 tools (LetsGrow.com, author-affiliated):** online psychrometric chart; greenhouse process simulation; heat-emission (radiation) simulator; weather-station module; data app; energy- and moisture-balance modules (enthalpy and calculated ventilation rate); heat maps; climate monitor; stomatal-conductivity module (VPD); root-zone module; plant-balance/RTR module (scatterplot, target band); crop registration; harvest prognosis. Recommend equivalent graphs in any climate computer if the user doesn't use LetsGrow.

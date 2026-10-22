# Plant Empowerment — Greenhouse Physics and Humid Air (Chapters 4–5, 8.12)

Paraphrased from the book. Formulas are given where they were legible in the source; the rest are described in words.

## Contents
- §1 The three-layer model and six balances
- §2 Energy transfer: short-wave, long-wave (heat emission), conduction, convection
- §3 The greenhouse energy balance
- §4 The greenhouse moisture balance: condensation and ventilation
- §5 The greenhouse CO2 balance
- §6 Screens and heat emission
- §7 Humid air and the psychrometric chart

---

## §1 Three layers, six balances

- **Three layers:**
  - The plant and its micro-atmosphere.
  - The greenhouse air.
  - The outdoor air.
  - They are separated by the cover (glass or plastic, with vents) and one or more movable screens (shading, blackout, thermal). Sometimes the space between the ridge and a closed screen counts as a fourth layer.
- For each layer, ask: **what comes in must go out** (energy: conservation of energy; water: every drop taken up leaves as vapour or harvest).
- **Six balances:**
  - Greenhouse: energy, moisture, CO2.
  - Plant: energy, water, assimilates.

## §2 Energy transfer

**Short-wave radiation (300–3000 nm; PAR 400–700 nm)**
- A pyranometer measures W/m² ("global radiation"). Daily sum in J/cm².
- PAR sensors count photons in µmol/m²·s, because lower-energy photons are as effective for photosynthesis.
  - Natural PAR: up to about 2000 µmol/m²·s.
  - Daily PAR sum (daily light integral): roughly 0–30 mol/m² depending on location and season.
  - Measure PAR at crop level so cover, whitewash and screens are included.
- A greenhouse reflects about 20–30% of solar radiation (angle, dust, cloud); roughly 70% enters.
- Cloudy weather has a higher PAR share of total energy (less UV/IR), so more assimilates per unit of water evaporated.
- **Diffuse vs direct:**
  - Diffuse light causes less water stress in plant heads and penetrates deeper.
  - The common Haze index is the % of light scattered more than 2.5° (ASTM D1003). It can't tell a narrow from a wide scatter; the newer **F-scatter** factor describes evenly-in-all-directions scattering better.
- **Lamps:**
  - HPS is mostly red; you need daylight for natural development.
  - LEDs have a narrow spectrum (e.g. 95% red + 5% blue mixes) and much less long-wave heat. Plant reactions under lamps can be unexpected.

**Long-wave radiation / heat emission (about 4500–100,000 nm)**
- Measured by a **pyrgeometer** or net radiation meter. Counted negative (outgoing).
- **On the roof:** about 0 W/m² under a cloudy sky to about −150 W/m² under a clear sky. A clear sky can be 30–40 °C colder than the air (high-altitude air is −50 to −60 °C). Rule of thumb for calculations: virtual clear-sky temperature ≈ outdoor air − 20 °C.
- **Above the canopy:** net radiation runs from about −50 W/m² at night to +700 W/m² on a very sunny day.
- **Rule of thumb:** crop ↔ environment exchange ≈ **5 W/m² per °C**. A crop 10 °C warmer than the cover loses ≈ 50 W/m², about what a heating pipe at 50 °C supplies. This loss comes at the expense of evaporation and calcium at the tip, and can drop leaves below dew point.
- Heat emission is often highest in **summer nights** (biggest crop-to-clear-sky difference).
- Plants have high emissivity. Glass largely absorbs long-wave radiation. Aluminium-strip screens protect better than plain PVC/PE screens at the same temperature.
- The impact of heat emission was long overlooked, causing many misunderstandings about plant health.

**Thermal conductance and the U-value**
- U-value = W per m² per °C across a material.
  - The book's glass-pane example: 10 W/m²·°C.
  - With air films on both sides, the effective U-value of a single-glass greenhouse under "normal" conditions is about 7; chapter 8 gives 6–8 W/m²·°C.
  - Wind and heat emission change it.
- **Stacked layers combine in series**, e.g. greenhouse 7 plus a screen of 6 gives a much lower total.
  - Screens are often sold by "% energy saving" instead of U-value. Those percentages can't simply be added.
  - The best screens reach about 0.5 W/m²·°C by using multiple layers with still air between.

**Convection (needs moving air)**
- Energy transfer depends on the air–surface temperature difference and air speed.
- It happens everywhere: roof ↔ outdoor and inside air, screens, pipes, lamps, leaves.
- Because leaf area is several times the floor area and both leaf sides exchange heat, air movement is a strong lever. It was long neglected.

**Heating pipe output** = convection + long-wave radiation. Both rise with pipe temperature relative to air and crop. The book's emissivity values: painted steel 0.8, crop 1.

## §3 The greenhouse energy balance

- Inputs: sun, heating, lamps. Outputs: conduction/convection through the cover (effective U-value), ventilation (sensible + latent heat), and heat emission to the sky. Crop evaporation and misting don't add energy; they convert sensible heat to latent heat.
- Any imbalance changes temperature until a new equilibrium is reached. In conventional greenhouses about 80% of the climate is set by the weather and only about 20% by equipment. A heating system gives about 150 W/m², while the sun can give far more.
- **Screens are the key** to good climate control under strongly varying outdoor conditions.
- **Effective ventilation rate** can't be estimated reliably from vent opening (wind, direction and temperature all interact; the upper greenhouse can be refreshed about 10× more than the lower part). Use the energy balance instead:
  - **Vr [m³/m²·h] = net energy input [kJ/m²·h] ÷ ΔEnthalpy inside–outside [kJ/m³]**
  - This is valid when solar radiation dominates and temperature is roughly constant.
  - The larger the enthalpy difference, the less ventilation is needed to remove the same energy. That is why keeping more moisture in (higher enthalpy) reduces the ventilation needed on sunny days.

## §4 The greenhouse moisture balance

- Input: crop evaporation, soil, misting. Output: **condensation** on the cold roof (or screen) and **ventilation** (vents or forced outside-air injection).
- **Use AH, not RH or HD, to read the trend.** Cooling air at constant AH raises RH and lowers HD even though no moisture was added.
  - The balance is in equilibrium when the AH trend is flat, at any humidity level.
  - AH rising: production > discharge. AH falling: discharge > production.
- **Avoiding high night RH starts with cooling down slowly in the evening.** Humidity control is tied to the temperature strategy.
- **Moisture production:** a full-grown tomato gives about 25 g/m²·h at night; far more under high sun.
- **Control from both sides:** first reduce unnecessary *input*:
  - Make air movement with fans rather than extra pipe heat, which adds evaporation.
  - Don't water late in the day.
  - Cover the soil.
  - Then manage the output.
- **Diffusion is negligible.** Even at 0.1 cm/s air speed, more than 99% of vapour transport is by air movement. Air movement transports moisture but doesn't remove it; removal needs condensation or ventilation.
- **Condensation:** depends on roof (or screen) temperature vs the dew point of the air touching it. Closing screens makes the roof colder, so condensation above the screen increases and AH above the screen drops, often to near outdoor AH. Moisture then moves through the screen, driven by ΔAH below vs above.
- **Ventilation:**
  - **Net moisture exhaust [g/m²·h] = ΔAH (inside − outside) [g/m³] × Vr [m³/m²·h]**
  - AH depends strongly on temperature, so keep the greenhouse **a few °C warmer than outside** at night. When ΔAH is small (the book's example: only 1.5 g/m³), the required air exchange becomes very large. In its hot sunny-day example, the whole greenhouse volume would have to be refreshed more than 20 times per hour, losing most of any dosed CO2.
  - Conversion: AH g/m³ ≈ 1.2 × AH g/kg.
  - The book's examples show moisture exhaust is easy at night in a cool, humid climate (Netherlands, even at 100% outside RH) and also in a hot, dry one (Arizona), as long as inside AH stays above outside AH.
- **Monitor AH at three points:** below the screen, above the screen and outdoors, to see where moisture can go.

**Energy and moisture interact.** Ventilating on temperature alone under high sun is a negative spiral:
- Stomata partly close and CO2 uptake falls.
- RH falls, which lowers enthalpy, which needs even more ventilation, which loses CO2.

The book's example: at 28 °C / 75% RH instead of 25 °C / 75% RH, the crop loses about 10% less water, the stomata stay more open, the leaves are warmer and photosynthesis is faster. **Less ventilation on sunny days for better photosynthesis** is one of GPE's most positive results.

## §5 The greenhouse CO2 balance

- Flows:
  - Crop dissimilation (output from the crop).
  - Crop uptake for photosynthesis by day.
  - CO2 enrichment.
  - Exchange by ventilation, in or out depending on inside vs outside concentration.
- **With enrichment:** less ventilation means higher CO2 at the same cost. Low ventilation boosts photosynthesis three ways at once: temperature, CO2 and humidity.
- **Without enrichment:** too little ventilation depletes CO2. Outside is about 400 ppm; inside can fall to about 200 ppm. Raising temperature or RH is pointless if CO2 is limiting, so trade off the three factors. Growth needs at least about 350 ppm around the stomata.
- **Distribution:** uptake follows local light, so dose into the **upper crop layers**. Air movement prevents local depletion inside the canopy. Thin dosing tubes low in the crop may not reach the top.
- A CO2 sensor is useful for ventilation control in both situations.

## §6 Screens and heat emission

- **Screen parameters:**
  - Light transmission (installing it parallel to the roof helps; water droplets cut transmission; wetting agents and surface structure help).
  - Insulation / energy saving.
  - Long-wave transmission and reflection.
  - Moisture permeability and air porosity.
  - Light scatter.
- **Heat-emission arithmetic (rule of thumb −5 W/m²·°C):**
  - With crop at 20 °C and cover at 17 °C, about −15 W/m². If a clear sky drops the cover to 14 °C, the loss doubles to −30 W/m².
  - A closed screen replaces the cold roof with something warmer. The book's example estimates screen temperature from inside air and air above the screen, and shows the loss falling from −15 to −10 W/m².
  - A closed screen covers on average about 85% of the crop's view.
- **Material matters:**
  - Glass is about 15–20% transparent to far-infrared (FIR), less with a continuous condensation film.
  - Polyethylene is about 60% FIR-transparent. Plants under a dry PE cover exchange much of their radiation directly with the cold sky. A continuous water film on PE makes it behave like single glass; droplets don't. Anti-condensation coatings actually promote that continuous film.
  - Without a wetting agent, or with a horizontally mounted plastic screen, use an **aluminized screen** to prevent heat-emission damage.
  - A transparent plastic foil closed alone under glass can even *increase* heat emission: the roof gets colder and the crop "sees" it through the foil. Put the foil *above* another screen instead.
- **Double screens:** two screens, each partly closed (e.g. 60–80% in opposite directions), can fully cover the crop against heat emission while still letting heat and moisture out. They reduce heat emission much better than one screen. Aluminized double layers with still air between them work best.
- **Gaps:** gaps cause energy loss and drop cold air onto the crop (see `practice.md` §6). If outside is only a few degrees colder, a screen closed with a gap is still better than open.
- The best screen combination depends on crop, climate, light, moisture and heat emission. The book points to an online simulation tool (LetsGrow heat-emission module).

## §7 Humid air and the psychrometric chart

- Water vapour has a maximum (saturation) partial pressure that rises steeply with temperature (Buck equations). The **psychrometric chart** (Mollier diagram in Europe) shows temperature vs **AH** (g/kg dry air).
- **RH** = actual vapour as % of saturation at that temperature. Example: at 20 °C saturation is 14.7 g/kg, so 10.0 g/kg means about 68% RH.
- **HD (humidity deficit)** = saturation AH − actual AH (g/kg or g/m³): the "evaporation space". Example: 14.7 − 10.0 = 4.7 g/kg.
- **Dew point** depends only on AH. Condensation appears on any surface below it, like a bathroom mirror.
- **Enthalpy** (kJ/kg) = sensible + latent heat.
- **Adiabatic cooling:** evaporating water at constant enthalpy until saturation; the end point is the **wet-bulb temperature**. Example: 25 °C with 6 g/kg can take about 4 g/kg more, giving a wet bulb of about 15 °C.
- Chart values depend on air pressure (printed charts are for sea level). Max vapour in g/m³ is nearly independent of pressure.
- **VPD terms:**
  - Vapour pressure *deficit* uses air temperature only.
  - Vapour pressure *difference* (VPD-plant) uses measured leaf temperature.
  - They're equal only when leaf temperature equals air temperature. **In this book VPD always means the leaf–air difference.**
- **Instruments:** hair hygrometer; dry/wet-bulb psychrometer (still common; wet-bulb depression gives RH, HD and AH via the chart); electronic RH meters; chilled-mirror dew point; acoustic AH sensors. Put sensors in a ventilated aspirator box.

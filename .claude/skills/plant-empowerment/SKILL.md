---
name: plant-empowerment
description: 'Apply "Plant Empowerment: The Basic Principles" (Geelen, Voogt & van Weel): Growing by Plant Empowerment (GPE, ex-Het Nieuwe Telen / Next Generation Growing): greenhouse cultivation by keeping six balances in equilibrium (plant energy, water and assimilates; greenhouse energy, moisture and CO2). Covers evaporation driven by energy rather than RH/VPD, stomata, VPD and leaf temperature, heat emission and screening, absolute humidity (AH) and the moisture balance, ventilation (leeside/windside, enthalpy), CO2 dosing and the CO2-to-light ratio, RTR (ratio temperature to radiation), plant load, root pressure/guttation, calcium shortage, crop condensation, air movement and vertical fans, psychrometrics, sensors, hot or cold climates and the five roadmaps. Use for greenhouse climate control, screen/ventilation/heating strategy, humidity or condensation problems, Botrytis or tip-burn tied to climate, RTR or plant-load planning, reading climate graphs, or GPE for tomato, cucumber, pepper, roses or vertical farms.'
---

# Plant Empowerment (Growing by Plant Empowerment, GPE)

A working guide distilled from *Plant Empowerment: The Basic Principles* by ir. P.A.M. Geelen, ir. J.O. Voogt and ing. P.A. van Weel. Its Latin motto is *Coniunctio physicae botanicaeque mirabile novos fructus producit* ("the union of physics and botany yields wonderful new fruits"). GPE grew out of Dutch research (the closed-greenhouse "Aircokas" project around 2004, then the *Het Nieuwe Telen* programme) and helped the winning team of the 2020 Autonomous Greenhouse Challenge (tomatoes). The book has 13 chapters:

1. Introduction
2. GPE in a nutshell
3. The plant
4. Physics
5. Humid air
6. Growing by Plant Empowerment
7. Challenging outdoor conditions
8. Greenhouse structures and equipment
9. Sensors
10. Roadmaps for implementation
11. LetsGrow online tools
12. References
13. Appendixes: glossary, Aircokas paper, heat emission basics, VPD

**Source coverage:** Built from the user's photographed copy (214 two-page spreads), which was OCR'd. The OCR is good for most text but partial on some pages: photos cropped at page edges, glare, and graphs. Formulas and numbers below were checked against legible passages. When a figure isn't given here, say so rather than inventing one.

## The core idea

Treat the plant as a **physical object subject to physical laws**, not only a physiological organism. Growth follows from keeping **six balances** in equilibrium:

| | Energy | Water / moisture | Carbon |
|---|---|---|---|
| **Plant** | Plant energy balance | Plant water balance | Plant assimilates balance |
| **Greenhouse** | Greenhouse energy balance | Greenhouse moisture balance | Greenhouse CO2 balance |

There are also three **secondary plant balances**: nutrients, microbiological (rootzone) and hormones. These stabilize themselves when the primary balances are steady.

**Guiding principles:**
1. **Support, don't steer.** The more you try to "correct" a plant, the more you disturb its balances. Support the plant so that all growth factors are optimal *at the same time*, like the barrel whose shortest stave limits the water level.
2. **Energy drives evaporation**, not RH, HD or VPD. A plant evaporates in proportion to the energy it receives: radiation, plus or minus convection. VPD is a *result* of stomatal behaviour, not its cause.
3. **Stomata are the valve** linking the energy, water and assimilate balances. They work only with air movement.
4. **Heat emission is the hidden enemy.** Longwave loss to a cold roof or clear sky cools the plant head. This cuts evaporation and calcium supply and raises the risk of condensation and root pressure. Screens are the key protection.
5. **Watch absolute humidity (AH)**, not just RH. Moisture leaves only by ventilation (ΔAH inside–outside) or condensation (roof below dew point).
6. **Keep a steady RTR:** a steady ratio of 24-hour average temperature to daily light sum, plus a **plant load** matched to the expected light. Together these give a balanced, resilient crop.
7. **Data-driven, not green fingers.** Use sensors and trend graphs to see *causes* (energy, moisture), not only symptoms (temperature, RH). Prevent problems rather than cure them.
8. **Energy saving is a bonus, not the goal.** The goal is optimal growth and plant health.

## How to use this skill

| User wants… | Go to |
|---|---|
| Why plants evaporate, stomata, leaf temp vs air temp, VPD ranges, root pressure, water buffer | `references/plant.md` §1–§3 |
| Assimilates balance: photosynthesis, temperature, CO2, LAI, light distribution, sinks, plant load, RTR | `references/plant.md` §4 |
| Secondary balances; calcium shortage, crop condensation, guttation, Botrytis, no air movement, heat emission damage | `references/plant.md` §5–§6 |
| Radiation (PAR, DLI, diffuse light), heat emission numbers, U-values, convection | `references/physics.md` §1–§2 |
| Greenhouse moisture balance, condensation, ventilation formulas, enthalpy, CO2 balance | `references/physics.md` §3–§5 |
| Screens and heat emission, multiple screens, gaps | `references/physics.md` §6 and `references/practice.md` §6 |
| Psychrometric chart: RH, HD, AH, dew point, enthalpy, wet bulb, VPD definitions | `references/physics.md` §7 |
| Climate strategy, monitoring each balance, reading graphs, irrigation, CO2/light ratio, RTR scatterplot | `references/practice.md` §1–§3 |
| Plant architecture, roots, plant health, post-harvest quality | `references/practice.md` §4 |
| Hot/dry, hot/humid, dusty, windless, cold, low-light or lit (vertical farm) conditions | `references/practice.md` §5 |
| Equipment: roof, ventilation, pad & fan, air tubes, fans, heating, screens, misting, CO2 supply | `references/practice.md` §6 |
| Which sensors and where | `references/practice.md` §7 |
| Step-by-step implementation: the five roadmaps and integrated adjustment | `references/practice.md` §8 |

**Workflow for a climate or crop problem:**
1. **Gather:** crop and stage, greenhouse type (glass/PE, screens, vents, heating, fans, lighting), climate zone and season, the symptom and when it occurs (night, sunrise, sunny midday, evening), and the sensor data available (inside T/RH, above-screen box, outdoor weather, PAR, leaf temperature, CO2, pyrgeometer).
2. **Find the balance at fault:** energy (heat emission, low net radiation), water (leaf T above air T, VPD above 1.5 kPa, root capacity), moisture (AH trend, ΔAH to outside), assimilates (RTR off target, plant load too high), or CO2.
3. **Look for the cause, not the symptom**, e.g. Botrytis → free water from heat emission or cold air drop, not "high RH".
4. **Recommend small, integrated steps** (roadmaps, `practice.md` §8). Each change touches other balances, so say what to watch next (AH trend, leaf temperature, net radiation).

## Output style and caveats

- Explain the physical *why* in plain language, then give concrete actions and what to measure. Use the book's numbers only where they're given here, and label them as rules of thumb.
- GPE sometimes contradicts common practice: keep vents more closed on sunny days, close screens fully, use windside vents, don't rely on minimum pipe temperature. Say when advice departs from convention, and why.
- Crops, cultivars, greenhouses and climates differ. Advise trying changes stepwise and checking against the user's own data. This is cultivation guidance, not a guarantee. For crop protection products, food safety and local regulations (e.g. light-emission screen rules), defer to local experts and rules.
- The book promotes LetsGrow.com tools (an author-affiliated platform). Mention them as options, not requirements.
- Don't reproduce long passages of the book. Paraphrase and apply.

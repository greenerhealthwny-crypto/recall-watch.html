# RTR for your tomatoes: what it is and how to set day and night temperatures with it

## 1. What RTR is

**RTR = Ratio of Temperature to Radiation.** It links the **24-hour average temperature** to the **daily light sum** that the crop received that day.

In the Plant Empowerment (GPE) approach, RTR is how you keep the **assimilates balance** steady:

- **Light makes sugars (production).** Photosynthesis depends mainly on light, with CO2 and humidity helping.
- **Temperature spends sugars (consumption).** Growth, respiration and transport to the fruits all speed up when it is warmer.

If the two stay in proportion every day, the plant uses what it makes and grows evenly. If they drift apart, you see it in the crop:

| Situation | What happens to the tomato |
|---|---|
| More light, same temperature | Sugars pile up. The plant gets too strong, thick and vegetative, and the extra sugar is wasted as starch or thick cell walls. |
| Higher temperature, no extra light | The plant burns more than it makes. It gets weak and too generative, short of assimilates, with poor fruit set and thin heads. |
| Both raised in the right ratio | Development speeds up and the plant keeps a balanced shape. |

A steady RTR also gives a steady rate of fruit set, flowering and ripening. That makes it a **plant-load tool** as well as a temperature tool. It also helps the secondary balances: regular root growth, less root pressure, and less glassiness and Botrytis risk.

The main point is that **a crop can be balanced "on average" over a week but out of balance on most individual days.** RTR control is about getting each day right.

## 2. Use your J/cm² data to find your RTR line

Your weather station's daily radiation sum in J/cm² is exactly what the book uses on the X-axis, so you can start now.

**Step 1: Make a scatterplot from your history.**
- X-axis: daily outside radiation sum (J/cm²).
- Y-axis: 24-hour average greenhouse temperature (°C), from your aspirator box between the plant heads.
- One dot per day. Use at least one full season if you have it.

**Step 2: Fit the trend line.** This line is the RTR you have *actually* been growing at.

**Step 3: Mark the periods when the crop looked best.** Look for regular fruit set, a good head thickness, a steady harvest and good quality. The days in those periods show you where your target line should be. Draw a **target line with a band around it**, for example ±0.5–1 °C. Choose the band width yourself; the book does not give one.

**Step 4: Keep each new day's dot inside the band.** Points far above the line mean the plant was burning more than it made. Points far below mean it was "overfed" with light.

**About the numbers:** the source I'm using does not give a fixed RTR value for tomato, so I won't invent one. Cultivar, plant load, CO2 level, glass transmission and your climate all shift the line. **Your own best weeks are the right reference.**

**A better X-axis later.** Outside J/cm² works, but the book prefers **PAR in mol/m² measured at crop level**, because that includes losses from the cover, whitewash and screens. If you want to estimate it from your current data, use this standard physics approximation (it is not from the book):

- 1 J/cm² = 0.01 MJ/m².
- About 45–50% of solar energy is PAR, at about 4.6 µmol per joule.
- The book's rule of thumb is that about 70% of outside radiation enters the greenhouse.
- So **inside PAR (mol/m²/day) ≈ outside J/cm² × 0.015.** For example, 1500 J/cm² outside ≈ 22 mol/m² outside ≈ 15 mol/m² at the crop.

Check this factor against a PAR sensor at crop level if you can. It changes with whitewash, screens and dirty glass. If you start whitewashing or shading, your outside-J/cm² line must come down, because the crop gets less light for the same outside reading.

## 3. Turn the 24-hour target into day and night setpoints

RTR sets the **24-hour average**. How you split that between day and night is your choice. The basic arithmetic is:

> **24-h average = (T_day × day hours + T_night × night hours) ÷ 24**

### Worked example (illustrative numbers only)

Suppose your best weeks put the target line at about **18.5 °C at 500 J/cm²** and **22 °C at 2500 J/cm²**. That is about +0.175 °C for every extra 100 J/cm².

- Forecast for tomorrow: **1500 J/cm²**, so the 24-hour target is about **20.3 °C**.
- Day period 14 h, night period 10 h. You want the night at 18 °C.
- Required day average = (20.3 × 24 − 18 × 10) ÷ 14 = **about 21.9 °C**.

If the day ends up sunnier than forecast and the greenhouse ran warmer, the higher light sum also raises the 24-hour target. Recalculate with the **actual** light sum late in the afternoon and adjust the night setpoint to land on the line.

### How to run it day to day

1. **Morning:** take the radiation forecast and calculate the 24-hour target from your line.
2. **Daytime:** let temperature follow light. Link the **ventilation setpoint to current radiation**: higher radiation means a higher vent setpoint. GPE prefers to keep vents more closed on sunny days. This keeps CO2 and humidity high, and you need that warmth anyway to use the extra sugars.
3. **Late afternoon:** compare the radiation sum and day temperature so far with the target, and set the night to close the gap.
4. **After a sunny day:** **postpone the day-to-night drop and keep the night warmer** so the extra sugars are transported out of the leaves to the fruits. Close the energy screen **before sunset** to hold solar heat. That makes the warmer evening cheap.
5. **After a dark day:** **keep the night cooler.** There are few sugars to spend, and a warm night would weaken the plant.
6. **Heat on the 24-hour average according to the light sum**, rather than to fixed day and night setpoints or a minimum pipe temperature.

## 4. Things that move your target line

- **CO2 or humidity limiting.** On days with heavy ventilation, the crop can't use all the light, so **lower the temperature target.** A related GPE rule of thumb: keep CO2 in ppm at least equal to outside radiation in W/m² (for example, 600 W/m² → at least 600 ppm).
- **Shading or whitewash:** less light reaches the crop, so the target comes down.
- **Plant load:**
  - Sink strength = plant load × temperature. A high load at low temperature acts like a low load at high temperature.
  - With a **lower plant load**, you can **raise the RTR line** (more degrees per unit of light). With a **higher load**, the line has to come down.
  - Plan fruits per m² against a **10-year weekly average light curve**, and record fruit set, harvest and load weekly against that plan.
  - **Watch late season.** Light falls quickly but outdoor temperatures stay high, and the load often ends up above plan. That is a classic way to slide into a weak, unbalanced crop.
- **Young crop:** before the plant carries fruit, it can run warmer at the same light. **Start strict RTR control once fruit set and harvest are regular.**

## 5. What to watch so you know it's working

- **The scatterplot itself.** Each day's dot should sit inside your band. Review it weekly.
- **Crop registration:** head thickness, truss development speed, fruit set and harvest rate. A steady RTR should make these steadier week to week.
- **Vertical temperature profile.** RTR uses the head-level aspirator box, but fruit temperature drives how strongly the fruits pull assimilates. Warm, well-lit fruits pull hard (more generative). Cold fruits in a closed crop push the plant vegetative. If you have a second box lower in the crop, use it.
- **Side effects of warmer nights after sunny days.** Keep the screen closed against heat emission and keep air moving with fans. This avoids cold plant heads and condensation, and keeps the absolute-humidity (AH) trend flat.

## 6. Where RTR fits in the bigger picture

GPE uses three levels to manage the assimilates balance. Each acts on a different time scale:

| Level | What you adjust | Reaction time | Impact |
|---|---|---|---|
| Cultivation plan | Plant load vs expected light | Weeks | Biggest |
| **RTR management** | **Daily temperature vs light sum** | **Days** | Large |
| Photosynthesis management | PAR, CO2 and RH aligned | Minutes | Fine-tuning |

Get the plant-load plan right first. Then use RTR to keep each day in line. Then fine-tune photosynthesis with CO2 and humidity.

## Practical advice

- Start by plotting what you already have: last season's daily J/cm² against 24-hour average temperature. That shows your current RTR and how scattered your days are. This step alone usually tells you a lot.
- Change one thing at a time, for example "warmer nights after sunny days", and check the effect against your own crop data for a couple of weeks before adding the next step.
- Many climate computers can plot this scatterplot. LetsGrow.com (affiliated with the book's authors) has an RTR module with a target band. A spreadsheet works just as well.
- These are rules of thumb from the Plant Empowerment approach, not guarantees. Cultivar, greenhouse and climate differ, so tune the line to your own results.

# RTR: Using Light to Set Day and Night Temperatures for Tomato

## What RTR is

**RTR (Ratio Temperature to Radiation)** sets how warm the crop should be over 24 hours based on how much light it received that day. The idea comes from Dutch "Next Generation Growing" / Plant Empowerment practice.

The reasoning:

- **Light drives assimilate production.** Photosynthesis makes sugars. More light means more sugars.
- **Temperature drives assimilate use.** It controls how fast the plant spends those sugars on respiration, growth, leaf and truss development, and fruit fill.
- **The two need to stay in balance.**
  - On a dark day with high temperature, the plant burns more sugar than it makes. The heads get thin, the plant turns weak and vegetative, flowers abort, and fruit gets small.
  - On a bright day with low temperature, sugars build up unused. The plant gets too generative or "stuck", development slows, and some potential production is lost.

RTR is the slope of a straight line linking the **24-hour average temperature** to the **daily light sum**:

```
T24 target = T_base + RTR × Light_sum
```

- **T_base**: the 24-hour temperature you would aim for at (nearly) zero light. This is about 16.5–18 °C for tomato.
- **RTR**: degrees of extra 24-hour temperature per unit of light.
- **Light_sum**: the day's radiation total. In your case this is outside global radiation in J/cm².

## Working with J/cm² from your weather station

Your station gives outside global radiation. Dutch growers commonly use exactly this unit, so you can work in it directly:

- Add up the day's radiation to get the daily total in J/cm². Typical totals:
  - Dark winter day: about 200–400 J/cm².
  - Spring day: about 1000–1500 J/cm².
  - Bright summer day: about 2500–3000 J/cm².
- When the data is in J/cm², RTR is usually written as **°C per 100 J/cm²**.

If you would rather work with light inside the greenhouse (mol PAR/m²/day), here is an approximate conversion:

```
1 J/cm² = 10,000 J/m² = 0.01 MJ/m²
Inside PAR (mol/m²) ≈ outside global (MJ/m²) × greenhouse transmission (~0.65–0.75) × 0.47 (PAR fraction) × 4.57 (mol per MJ PAR)
```

At 70% transmission, **100 J/cm² outside ≈ 1.5 mol PAR/m² inside**. A slope of 0.2 °C per 100 J/cm² is then about 0.13 °C per mol/m².

If you use supplemental lighting, add the lamp light to the sum. As a rough guide for typical LED or HPS, 1 hour at 200 µmol/m²/s is about 0.72 mol/m². Converting everything to inside PAR becomes the cleaner approach once lamps are involved.

## Starting values for tomato

| Parameter | Typical starting range | Notes |
|---|---|---|
| T_base (24 h temp at ~0 light) | 17–18 °C | Never let the 24 h average fall much below ~17 °C, or fruit set and development will suffer |
| RTR slope | 0.15–0.25 °C per 100 J/cm² outside | 0.2 is a common middle value |
| Upper cap on 24 h temp | ~22–23 °C | Above this, more heat no longer pays off. Fruit gets small and the plant weakens |
| Lower floor on 24 h temp | ~17 °C | Minimum needed for truss development and fruit set |

Using T_base = 17.5 °C and RTR = 0.2 °C per 100 J/cm²:

| Outside light sum (J/cm²/day) | Target 24 h temp |
|---|---|
| 300 (dark winter) | 17.5 + 0.2 × 3 = **18.1 °C** |
| 800 | 17.5 + 1.6 = **19.1 °C** |
| 1500 | 17.5 + 3.0 = **20.5 °C** |
| 2500 (bright summer) | 17.5 + 5.0 = **22.5 °C** |

Fine-tune the slope from how the crop responds (see the monitoring section below). Use a lower RTR for a more generative crop and a higher one when the crop can carry more temperature. Young crops, heavy fruit load and weak heads call for a lower slope. A strong, vegetative crop with thick heads can handle a higher one.

## Turning the 24-hour target into day and night setpoints

RTR gives you the **24-hour average**. You get there by splitting it into day and night temperatures. Use a time-weighted average:

```
T24 = (T_day × h_day + T_night × h_night) / 24
```

Solve for the day temperature:

```
T_day = (24 × T24 − T_night × h_night) / h_day
```

### Step by step

1. **Get the expected light sum for the day** from the forecast or a recent average. During the day, update it with the radiation measured so far.
2. **Calculate T24** from the RTR line, and clamp it between your floor and cap.
3. **Choose a night temperature.** For tomato this is usually 16–18 °C. A lower night temperature saves energy and steers the crop generatively, but stay at or above about 15–16 °C.
4. **Calculate the day temperature** needed to reach T24.
5. **Make sure the result is realistic.** On sunny days, solar gain will push actual day temperatures above the setpoint anyway. That is fine: RTR tells you whether to cool the night down to compensate.

### Example

On a spring day with a forecast of 1500 J/cm², there are 14 hours of light and 10 hours of dark.

- T24 = 17.5 + 0.2 × 15 = **20.5 °C**
- Night setpoint: 17 °C
- T_day = (24 × 20.5 − 17 × 10) / 14 = (492 − 170) / 14 = **23.0 °C**

On a dark winter day with 350 J/cm², there are 9 hours of light and 15 hours of dark.

- T24 = 17.5 + 0.2 × 3.5 = **18.2 °C**
- Night setpoint: 17 °C
- T_day = (24 × 18.2 − 17 × 15) / 9 = (436.8 − 255) / 9 = **20.2 °C**

On a dark day, keep the day temperature modest. Don't heat hard during the day when there is little light to fuel the extra growth.

## Practical tips

- **Integrate over several days.** Don't chase every single day. Most climate computers support temperature integration over a 3–6 day window. A day that ran too warm can be balanced by a cooler night or a cooler next day. This saves energy and smooths out forecast errors.
- **Adjust in real time.** If the morning turns out darker than forecast, lower that evening's and night's setpoints, or start the pre-night drop earlier. If it turns out brighter, you can allow a slightly warmer night.
- **Use the pre-night.** A temperature drop of 2–4 °C in the first 2–3 hours after sunset is an efficient way to pull down the 24-hour average. It also steers the crop generatively and helps move sugars to the fruit.
- **Morning ramp.** Raise the temperature gradually before and after sunrise, about 1 °C per hour. This avoids condensation on cold fruit and gives a smooth start to transpiration.
- **Don't break humidity and VPD limits for RTR.** If a cold night would give you too much humidity and disease pressure, accept a slightly higher 24-hour temperature or use a minimum pipe temperature or dehumidification.
- **CO₂ interacts with the slope.** With high CO₂ (800–1000 ppm), each unit of light produces more sugar, so the crop can often take a slightly higher RTR.

## Monitoring whether your RTR is right

Check the plant every week and adjust the slope in small steps of 0.02–0.05 °C per 100 J/cm²:

| Observation | Meaning | Action |
|---|---|---|
| Head thickness decreasing (e.g., < 9–10 mm, depending on cultivar), thin stems, pale heads | Too warm for the available light; sugar shortage | Lower RTR or T_base, or use a lower night/pre-night |
| Very thick heads, curled tops, slow growth, flowers set very close to the head | Too cool for the available light; sugar surplus | Raise RTR slightly |
| Flowering truss far from the head (> ~15–20 cm) | Vegetative | Lower 24 h temperature or increase DIF / pre-night drop |
| Flowering truss very close to the head | Generative | Raise 24 h temperature slightly |
| Truss development rate (trusses/week) | Should track the 24 h temperature | Compare with targets for your cultivar |

## Summary

1. Add up your outside radiation each day in J/cm².
2. Set the 24-hour temperature target with **T24 = 17.5 + 0.2 × (J/cm² ÷ 100)**, clamped between about 17 and 23 °C.
3. Choose a night temperature (16–18 °C) and work out the day temperature from the time-weighted average.
4. Use multi-day temperature integration and real-time light updates rather than fixed setpoints.
5. Check head thickness and flower position weekly, and adjust the RTR slope in small steps.

The numbers above are starting values. Cultivar, crop stage, greenhouse transmission and your CO₂ strategy all shift the ideal line. Treat the first few weeks as a calibration period, and record the light sums, realised 24-hour temperatures and crop measurements so you can fit the line to your own conditions.

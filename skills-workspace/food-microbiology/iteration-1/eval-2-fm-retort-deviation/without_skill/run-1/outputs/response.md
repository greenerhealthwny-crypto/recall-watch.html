# Retort Deviation: D Value, z Value, 12D, and What Your 240 °F Batch Received

**Short answer:** The batch got about **3 log reductions** of *C. botulinum* spores instead of the roughly **12** it needed. It is **not safe**. Put it on hold right away. Do not release it.

---

## 1. The D value (decimal reduction time)

The **D value** is how long it takes, at one constant temperature, to kill 90% of a microbial population. That is a 1-log (10-fold) reduction.

- It is written with the temperature as a subscript, for example **D₂₅₀ = 0.21 min**.
- Microbial death under heat is roughly logarithmic: N = N₀ × 10^(−t/D)
- The number of log reductions you get = **time held ÷ D value**.

For proteolytic *C. botulinum* spores, the standard reference value is **D₂₅₀°F ≈ 0.21 min** (often rounded to 0.2 min).

## 2. The z value (temperature sensitivity)

The **z value** is how many degrees the temperature must change to change the D value 10-fold.

- For *C. botulinum*, **z = 18 °F (10 °C)**.
- So each drop of 18 °F makes the spores 10 times harder to kill (D becomes 10 times longer).
- This gives the **lethal rate**: L = 10^((T − 250)/18). It tells you how much one minute at temperature T is worth compared with one minute at 250 °F.

## 3. F₀ and the 12D concept

- **F₀** is the total lethality of a process, expressed as equivalent minutes at 250 °F with z = 18 °F.
- **12D (the "botulinum cook")** is the minimum process for low-acid canned foods (pH > 4.6, a_w > 0.85). It must reduce *C. botulinum* spores by 12 logs.
  - 12 × 0.21 min ≈ **2.5 min F₀**. Your scheduled 2.4 min at 250 °F is this classic minimum botulinum cook.
  - In practical terms: if every can started with 1 spore, only 1 can in 10¹² would still contain a survivor. That is a vanishingly small risk.
- In practice, commercial processes usually deliver F₀ values of about 3 to 6+ min or more. This covers mesophilic spoilage spore-formers, which are more heat-resistant than *C. botulinum*.

## 4. Your batch: the calculation

**Lethal rate at 240 °F:**

L = 10^((240 − 250)/18) = 10^(−0.556) ≈ **0.278**

So 1 minute at 240 °F is worth only about 0.28 minutes at 250 °F.

**Delivered lethality:**

F = 2.4 min × 0.278 ≈ **0.67 min** (equivalent at 250 °F)

**Log reductions achieved:**

0.67 ÷ 0.21 ≈ **3.2 log reductions**

**Cross-check using D at 240 °F:**

D₂₄₀ = 0.21 × 10^(10/18) ≈ 0.21 × 3.59 ≈ 0.75 min
2.4 ÷ 0.75 ≈ **3.2 logs**, which matches.

| | Scheduled (250 °F) | Actual (240 °F) |
|---|---|---|
| Lethality (F₀) | 2.4 min | ~0.67 min |
| Log reductions of *C. botulinum* | ~11.4–12 | **~3.2** |
| Survivor probability (1 spore/can start) | ~1 in 10¹² | **~1 in 1,500 cans** |

A drop of only 10 °F cut the lethality by about **72%**. It removed roughly **8–9 logs** of safety margin. Under the 12D standard, the batch is short by a factor of about 10⁸–10⁹.

## 5. Is it safe?

**No.** Treat the batch as **under-processed and potentially hazardous**:

1. **Hold the batch.** Do not ship or release it. Label and segregate it.
2. **Document the deviation.** Record the retort charts, temperature and time records, and the batch and code identifiers. US regulations require this for low-acid canned foods (21 CFR 113.89, process deviations; also 21 CFR 108.35).
3. **Have a qualified process authority evaluate it.** Only a process authority can decide whether any lot can be salvaged. They may use actual heat-penetration data, the cold-spot history, and come-up time contributions.
4. **Choose a disposition.** The usual options are:
   - **Reprocess** the full scheduled process, if product quality allows and the process authority approves.
   - **Destroy** the batch.
   - Release only if a documented evaluation by a process authority proves the process gave adequate lethality. With about 3 logs delivered, this is very unlikely.
5. **Find and fix the root cause.** Check the steam supply, venting, controller and RTD/MIG calibration, and the recorder. Prevent a repeat.

Botulinum toxin can be present in cans that look, smell and taste normal. Do not use "no swelling" as evidence of safety. And do not taste-test the product.

---

**Teaching note:** The real scheduled process time is much longer than the F₀ value. Cans need come-up time, and the cold spot heats slowly. Treating "2.4 min at 250 °F" as a constant-temperature hold is a textbook simplification. The z-value math above is still exactly how deviations are judged. A small temperature shortfall produces a large exponential loss of lethality.

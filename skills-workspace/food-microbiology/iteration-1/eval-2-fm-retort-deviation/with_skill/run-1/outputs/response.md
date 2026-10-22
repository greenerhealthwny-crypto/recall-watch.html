# Retort Deviation: D, z, 12D and What Your 240 °F Batch Actually Got

**Short answer:** At 240 °F instead of 250 °F, the batch got about **3.3 log reductions** of *C. botulinum* spores, not 12. That is roughly **8.7 logs short**, and the process delivered only about **28% of the lethality** it was designed for. The batch is **not safe to release as is.** Under the low-acid canned food rules it has to be held and evaluated by a process authority. In practice that usually means reprocessing or destroying it.

The rest of this explains the concepts and works through the numbers step by step.

---

## 1. The concepts

### Thermal death is log-linear
When you hold spores at a constant lethal temperature, the same *fraction* dies in each equal time interval. If you plot log(survivors) against time, you get a straight line. Because of this, we describe heat kill in **log reductions** (powers of ten).

### D value (decimal reduction time)
**D is the time at a given temperature needed to kill 90% of the population, which is a 1-log reduction.**

- If D = 0.2 min, then every 0.2 min at that temperature cuts survivors 10-fold.
- 1,000,000 spores → 100,000 → 10,000 → … for each D interval.
- **Log reduction = time ÷ D.**
- D always refers to a specific temperature, written as D₂₅₀°F or D₁₂₁°C. For *C. botulinum* types A and B spores (the proteolytic, most heat-resistant group), **D₂₅₀°F ≈ 0.2 min**.

### z value
**z is the temperature change needed to change D 10-fold.**

- For *C. botulinum* spores, **z ≈ 18 °F (10 °C)**.
- Raising the temperature by 18 °F makes D ten times smaller, so killing is ten times faster. Dropping it by 18 °F makes D ten times larger.
- This gives the conversion formula:

  **D_T = D_ref × 10^((T_ref − T) / z)**

- A related idea is the **lethal rate**, L = 10^((T − T_ref)/z). It tells you how many "minutes at 250 °F" each minute at temperature T is worth. The **F value** (F₀ when the reference is 250 °F and z = 18 °F) adds up this lethality over the whole process.

### The 12D concept (the "botulinum cook")
Low-acid canned foods (pH > 4.6, a_w > 0.85) can support growth and toxin production by *C. botulinum* in the sealed, anaerobic can. They must be **commercially sterile**. The industry standard minimum is a **12-log reduction** of *C. botulinum* spores:

- 12 × D₂₅₀ = 12 × 0.2 min = **2.4 min at 250 °F** (F₀ ≈ 2.4, often rounded up to about 3 in practice).
- In practical terms, if every can started with one spore, only one can in 10¹² would be expected to contain a survivor. That is a huge safety margin. It is built that large because botulism is so severe and because spore loads vary.
- Any time and temperature combination that delivers the same lethality (the same F₀) is equivalent. A lower temperature is acceptable only if you hold it **much** longer.
- Real scheduled processes are much longer than 2.4 min of retort time. They are set by heat-penetration studies so that the **cold spot** of the container accumulates the required F₀. Spoilage control (for example thermophilic spores such as *Geobacillus stearothermophilus*, which are more heat resistant than botulinum spores) often pushes them higher still. For this problem, we treat it the textbook way: 2.4 min actually experienced at the stated temperature.

---

## 2. Worked calculation for your batch

**Given:** D₂₅₀ = 0.2 min, z = 18 °F, actual temperature = 240 °F, time = 2.4 min.

**Step 1. Find D at 240 °F.**
The temperature is 10 °F below the reference.

D₂₄₀ = 0.2 × 10^((250 − 240)/18) = 0.2 × 10^(0.556) = 0.2 × 3.59 ≈ **0.72 min**

At 240 °F, spores are about 3.6 times harder to kill than at 250 °F.

**Step 2. Log reductions delivered.**

Log reduction = 2.4 ÷ 0.72 ≈ **3.3 logs**

**Step 3. Check with F₀.**

Lethal rate at 240 °F = 10^((240 − 250)/18) = 10^(−0.556) ≈ 0.278
F₀ = 2.4 min × 0.278 ≈ **0.67 min equivalent at 250 °F**
0.67 ÷ 0.2 ≈ **3.3 logs**. The two methods agree.

| | Scheduled | Actual |
|---|---|---|
| Temperature | 250 °F | 240 °F |
| Time | 2.4 min | 2.4 min |
| D at that temperature | 0.20 min | 0.72 min |
| F₀ (min at 250 °F) | 2.4 | 0.67 |
| Log reduction | 12 | **≈ 3.3** |
| Shortfall | — | **≈ 8.7 logs** |

**Step 4. What it would have taken.**
To get 12D at 240 °F you would need 12 × 0.72 ≈ **8.6 min**, about 3.6 times the scheduled time.

### Why such a small temperature miss is such a big deal
A 10 °F drop is only 4% of the temperature, but it cost about 72% of the lethality. This is because of the logarithmic z relationship. **Temperature deviations matter far more than time deviations.**

- Compare: holding 250 °F for 10% less time (2.16 min) still delivers 10.8 logs.
- Missing the temperature by 10 °F for the full time delivers only 3.3 logs.

This is why retort temperature (via the reference mercury-in-glass or RTD thermometer) and its recorder chart are critical limits that operators watch most closely.

---

## 3. Is it safe?

**No. Treat it as under-processed and potentially hazardous.**

What 3.3 logs means in practice:
- With a load of 100 spores per can (10² spores), survivors per can ≈ 10^(2 − 3.3) ≈ 0.05. That is roughly **1 can in 20 with a surviving spore**.
- With 1 spore per can, about 1 can in 2,000 could still carry a survivor. Compare that with the design target of 1 in a trillion.
- Raw vegetables, especially soil-contact produce like potatoes, mushrooms and root crops, can carry high spore loads.

A surviving spore in a sealed, low-acid, anaerobic can held at room temperature can germinate, grow and produce **botulinum neurotoxin**. The can may not swell or smell off, especially with proteolytic strains in some foods. You cannot inspect or test your way to safety here: a few cans testing negative says almost nothing about one in 20 or one in 2,000.

### What has to happen (the regulatory and HACCP view)
In the US, low-acid canned foods fall under FDA 21 CFR Parts 108, 113 and 114 (or USDA-FSIS rules for meat and poultry products). A drop below the scheduled process temperature is a **process deviation**. In general terms:

1. **Hold the entire lot.** Identify every container from the affected retort load(s), and do not ship.
2. **Document it.** Keep the recorder chart, the thermometer readings, the time records and the cause, such as a steam supply, venting or controller problem.
3. **Have a recognized process authority evaluate it.** They may calculate the delivered F₀ at the cold spot using the actual temperature history, including come-up and cooling. If the deviation cannot be shown to have delivered a safe process, the options are:
   - **Reprocess** under a full scheduled process. This usually means a complete process, not just "the missing part", and it needs to be acceptable for the product and container.
   - **Destroy** the lot.
4. **Keep records** of the evaluation and disposition as required.
5. **Correct the root cause** and verify the retort before running again. This is HACCP principle 5 (corrective action) in action.

The textbook calculation here (3.3 logs) is a strong indication of an unsafe product. However, the real disposition decision belongs to the process authority, who works from the actual heat-penetration data and records. Check the current FDA/FSIS regulations for compliance details.

### Not for the home either
If this were a home canning situation, the same physics applies. Low-acid vegetables must be pressure-canned using a tested process (for example USDA or National Center for Home Food Preservation guidelines). An under-processed jar should not be eaten. Botulinum toxin itself is heat-labile, but "boil it before serving" is not a safe plan for a known under-processed low-acid product.

---

## 4. Key takeaways for your studies

- **D** = time for a 1-log (90%) kill at one temperature. **Log reduction = time ÷ D.**
- **z** = °F (or °C) to change D 10-fold. For *C. botulinum*, about 18 °F / 10 °C.
- **D_T = D_ref × 10^((T_ref − T)/z)**; **F₀** = time × 10^((T − 250)/18).
- **12D botulinum cook** = 12 × 0.2 = 2.4 min at 250 °F.
- **Your batch:** D₂₄₀ ≈ 0.72 min → 2.4/0.72 ≈ **3.3 logs** (F₀ ≈ 0.67). That is about 8.7 logs short. **Hold it, and have a process authority evaluate it; do not release it.**
- Lesson: a small temperature drop wipes out most of the lethality. Time shortfalls are much more forgiving.

*Educational content based on standard food microbiology principles (Matthews, Kniel & Montville, Food Microbiology: An Introduction, 4th ed.). This is not regulatory advice. Thermal process decisions must be made by a qualified process authority, following current FDA/USDA requirements.*

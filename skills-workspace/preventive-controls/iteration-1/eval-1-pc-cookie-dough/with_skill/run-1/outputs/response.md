# Hazard Analysis and Preventive Controls: Refrigerated Chocolate Chip Walnut Cookie Dough (Retail Tubs)

This is a working draft built on the FSPCA *Preventive Controls for Human Food* approach (21 CFR Part 117, Subpart C). Your PCQI needs to adapt it to your actual facility, suppliers, formula and data, then sign off on it. It is drafting help. It is not legal advice and does not replace a PCQI or FDA guidance.

---

## 0. Before you start: two threshold questions

1. **Are you a "qualified facility"?** A very small business is one with under about $1 million a year in human food sales plus the market value of food held without sale. That figure is inflation-adjusted and averaged over the prior 3 years. If you qualify, you file an attestation and follow **modified requirements** instead of a full Food Safety Plan. A full hazard analysis is still good practice, and your customers may require one. The rest of this draft assumes full Subpart C applies.
2. **Treat this dough as ready-to-eat for hazard analysis purposes.** The product is "ready to bake", but the hazard analysis must cover **intended and reasonably foreseeable use**. Consumers commonly eat cookie dough raw. Raw flour (*E. coli* O157:H7 and other STEC, *Salmonella*) and raw eggs (*Salmonella*) have caused outbreaks and recalls tied to exactly this habit. A "cook before eating" or "do not eat raw" label is good practice, but **it is not a preventive control**. Your facility has **no kill step**, so the safety of the dough depends on:
   - the controls your suppliers apply (heat-treated flour, pasteurized eggs, treated walnuts);
   - keeping the dough from being recontaminated in your plant;
   - allergen and label control.

---

## 1. Preliminary steps

### 1.1 Food safety team
- PCQI (owner or QA lead, FSPCA-trained)
- Production lead (mixing and depositing)
- Sanitation lead
- Maintenance (mixer, depositor, any metal detector)
- Receiving and purchasing (supplier approval)
- Optional outside help: process authority or lab for a_w and pH testing, and the FSPCA Technical Assistance Network

### 1.2 Product description

| Item | Description |
|---|---|
| Product name | Refrigerated ready-to-bake chocolate chip cookie dough with walnuts |
| Ingredients | Heat-treated wheat flour (supplier), liquid pasteurized whole egg, butter, sugar(s), chocolate chips, walnuts (plus any leavening, salt or vanilla; list every sub-ingredient) |
| Safety characteristics | **Measure them; don't assume.** Water activity is typically about 0.80–0.90 for cookie dough, depending on the sugar-to-water ratio. pH is near neutral (about 6–7), so it is not acid-controlled. No preservatives (confirm). |
| Packaging | Plastic retail tub with lid (state whether it is sealed or modified atmosphere; it is likely not reduced oxygen packaging) |
| Storage and distribution | Refrigerated, ≤ 41 °F (5 °C) |
| Shelf life | Set by your studies (state the days refrigerated, and frozen if allowed) |
| Labeling | Ingredient statement with allergen declaration; "Keep refrigerated"; baking instructions; "Do not eat raw dough" advisory (recommended, not a control); lot code and use-by date |
| Intended use | Baked by the consumer |
| **Foreseeable use** | **Eaten raw**, including by children |
| Intended consumers | General public, **including vulnerable groups** (children, elderly, pregnant, immunocompromised) |

### 1.3 Flow diagram (verify it by walking the line)

```
Receiving (refrigerated):         Receiving (dry/ambient):          Receiving: packaging
  liquid pasteurized egg            heat-treated flour                 tubs, lids, labels
  butter                            sugar, chocolate chips, walnuts
      |                                     |                              |
Refrigerated storage (≤41°F)       Dry storage (allergen-segregated)   Packaging storage
      |                                     |                              |
      +-------------> Weighing / scaling <--+                              |
                            |                                              |
                 Mixing (cream butter+sugar, add egg,                      |
                 add flour, fold in chips + walnuts)                       |
                            |                                              |
           [Rework? - define or prohibit]                                  |
                            |                                              |
                  Depositing into tubs  <----------------------------------+
                            |
                     Lidding / sealing
                            |
              Labeling + lot/date coding
                            |
             [Metal detection - if used]
                            |
          Refrigerated storage of finished goods (≤41°F)
                            |
               Refrigerated shipping / distribution
```

Show every ingredient's receiving step, any rework, and any water or compressed air that touches food or food-contact surfaces. Then confirm the diagram onsite.

---

## 2. Hazard analysis (FSPCA six-column format)

Key: **B** = biological, **C** = chemical (including allergens and radiological), **P** = physical. PC = preventive control.

### 2.1 Incoming ingredients and packaging

| (1) Ingredient / step | (2) Potential hazard | (3) Requires a PC? | (4) Justification | (5) Control measure | (6) Applied at this step? |
|---|---|---|---|---|---|
| **Heat-treated flour** (receiving) | **B:** STEC (*E. coli* O157:H7 and others), *Salmonella* | **Yes** | Raw flour is a recognized **sensitive ingredient**, with multiple outbreaks and recalls (including in raw cookie dough). Severity is high (HUS, death). There is no kill step in our process, and raw consumption is foreseeable. | **Supply-chain control**: the supplier's validated heat treatment, verified by us | No, controlled by the supplier; we verify at receiving |
| | **C:** allergen (**wheat**) | Yes | Major food allergen | **Allergen control** (labeling, cross-contact) | No, at labeling and storage/production |
| | C: pesticides, mycotoxins (DON) | No | Low likelihood at the levels in finished dough; handled by supplier specifications and GMPs | Supplier specs (prerequisite) | — |
| | P: foreign material | No | Flour is sifted by the supplier; specs and COA cover it | Supplier spec; optional in-house sifter | — |
| **Liquid pasteurized egg** | **B:** *Salmonella* | **Yes** | Eggs are a classic sensitive ingredient. The hazard is SAHCODHA, and no kill step follows. | **Supply-chain control**: the supplier's pasteurization. Liquid egg products are made under **USDA-FSIS** continuous inspection (Egg Products Inspection Act), which supports a lighter, justified verification. | No, supplier; we verify |
| | B: *L. monocytogenes*, spoilage, growth if temperature-abused | Yes (as part of storage control) | Refrigerated perishable | Receiving temperature check; refrigerated storage ≤ 40–41 °F; use within code (see the process control in 2.2) | Receiving and storage |
| | **C:** allergen (**egg**) | Yes | Major allergen | Allergen control | No |
| **Butter** | B: *L. monocytogenes* | No | Made from pasteurized cream; low historical association in butter. Controlled by supplier specs and refrigerated storage (GMP). | Approved supplier spec; refrigeration (prerequisite) | — |
| | **C:** allergen (**milk**) | Yes | Major allergen | Allergen control | No |
| **Sugar** | B, C, P | No | Low-moisture ingredient with no meaningful pathogen history; foreign material is managed by spec and GMPs | Supplier spec | — |
| **Chocolate chips** | B: *Salmonella* | No (document the reasoning) | There is a historical association with chocolate, but chips are made with roasting and conching steps and have a strong safety record. Use a supplier spec and COA. Change to **Yes / supply-chain control** if your supplier's process is unknown or unvalidated. | Approved supplier, spec, COA | — |
| | **C:** allergens (**milk**, **soy** lecithin, possible "may contain" tree nut, peanut or **sesame**) | Yes | Sub-ingredient allergens are a frequent cause of undeclared-allergen recalls | Allergen control: capture every sub-ingredient allergen on the label | No |
| **Walnuts** | **B:** *Salmonella*, STEC (*E. coli* O157:H7) | **Yes** | Tree nuts are a sensitive ingredient. Walnut recalls and outbreaks include *Salmonella*, and *E. coli* O157:H7 in 2024. Walnuts are folded in raw with no kill step. | **Supply-chain control**: buy walnuts that have had a **validated pathogen-reduction treatment** (e.g. pasteurization, steam or PPO treatment) and verify it. If you buy untreated walnuts you have no control, so don't. | No, supplier |
| | **C:** allergen (**tree nut: walnut**) | Yes | Major allergen with a high risk of severe reactions | Allergen control | No |
| | C: aflatoxin | No | Low likelihood in walnuts; supplier spec | Spec / COA | — |
| | **P:** shell fragments (hard, sharp) | Yes or No, **your call** | Shell fragments can be hazardous (hard or sharp objects about 7–25 mm). Probability depends on the supplier's sorting. | Most bakeries handle this with a supplier spec (shell-fragment limit, optical and X-ray sorting) plus a **supply-chain control** if rated Yes | No, supplier |
| **Tubs, lids** | C: migration | No | Food-grade packaging; letter of guarantee | Spec | — |
| **Labels** | **C:** wrong label, undeclared allergen | Yes | Labeling errors drive about a third or more of FDA food safety recalls | Allergen control (label review at receipt) | Partly, at receipt |

### 2.2 Processing steps

| (1) Step | (2) Potential hazard | (3) PC? | (4) Justification | (5) Control | (6) Here? |
|---|---|---|---|---|---|
| **Receiving: refrigerated ingredients** | B: growth of pathogens in egg and butter if abused | No (separately) | Covered by receiving temperature checks (GMP) and the storage control below | GMP / receiving procedure | — |
| **Receiving: flour, eggs, walnuts** | B: pathogens (supplier-controlled) | **Yes** | See 2.1 | **Supply-chain program**: approved supplier, COA or letter for each lot, records | **Yes** (verification activities) |
| **Ingredient storage** | C: allergen cross-contact (walnut dust or pieces, open egg containers) | Yes | Walnuts are a high-risk allergen. Other bakery products that lack walnuts could be contaminated. | **Allergen control**: designated, labeled storage below other ingredients; sealed containers; no open containers returned to the cooler | Yes |
| | B: growth in egg | Yes, as the refrigeration control | | Cooler ≤ 40–41 °F | Yes |
| **Weighing / mixing** | **B:** recontamination with environmental pathogens (*Salmonella*, *L. monocytogenes*) | **Yes** | The dough is RTE in practice, exposed to the environment, and **no lethal step follows**. *Salmonella* survives well in low-a_w doughs; *L. monocytogenes* persists in cool, wet areas. | **Sanitation control** (food-contact surfaces, cleaning and sanitizing; hygienic zoning), **verified by environmental monitoring** | Yes |
| | **B:** *S. aureus* growth or toxin; *B. cereus* growth if dough is held warm | Depends on a_w | If a_w is > ~0.86 and dough is held long at room temperature, *S. aureus* can grow. Mixing is usually short. | Time/temperature limit on dough before refrigeration (e.g. dough ≤ 50 °F, or a maximum time out of refrigeration, set from your data). The omelet batter model used ≤ 50 °F / ≤ 12 h. | Yes, if needed |
| | **C:** allergen cross-contact (shared mixer with non-walnut or non-egg products) | **Yes**, if you make any product on the same equipment without these allergens | Shared equipment is the main route | **Allergen control** (scheduling: walnut product last; validated changeover cleaning) **and/or sanitation control** | Yes |
| | **P:** metal (mixer paddle or bowl wear, depositor) | Yes or No, **your call** | It depends on equipment and the preventive maintenance record. The FSPCA notes two facilities can reasonably reach different conclusions. Dough is dense, and metal fragments are a real recall cause in doughs. | If Yes: **metal detection** as a process control after lidding; otherwise preventive maintenance and pre/post-shift equipment inspection (prerequisite) | Yes, at detection |
| **Rework** (if any) | B, C: pathogens, allergen carry-over | Yes, if rework is used | Rework from a walnut product into a non-walnut product is an allergen hazard | Allergen control: like-into-like only, labeled and dated; or no rework | Yes |
| **Depositing / lidding** | B: environmental pathogens | Yes | Exposed RTE dough | Sanitation control + EM (as above) | Yes |
| **Labeling and coding** | **C:** undeclared allergens (wheat, egg, milk, walnut, soy; sesame if present) | **Yes** | Highest-probability allergen failure mode | **Allergen control (labeling)** | **Yes** |
| **Metal detection** (if used) | P: metal | Yes, if chosen | — | **Process control** | Yes |
| **Finished goods cold storage and shipping** | **B:** *L. monocytogenes* growth (grows at refrigeration temperatures if a_w allows); *S. aureus* and others with temperature abuse | **Depends on a_w, confirmed by testing** | If dough a_w ≥ ~0.92, *L. monocytogenes* can grow, and refrigeration is essential to safety, so it is a **process control**. If a validated a_w is well below that (e.g. ≤ 0.85), refrigeration may be quality-driven and handled by GMPs. **Document whichever applies.** | **Process control: refrigeration ≤ 41 °F** (cooler temperature monitoring), or a documented justification that it is not needed | Yes |
| | C/B: transportation temperature abuse | As above | | Sanitary transportation rule; carrier temperature agreements and records | — |

---

## 3. Preventive controls you need (summary)

| # | Hazard requiring a preventive control | Control type | Where |
|---|---|---|---|
| 1 | STEC and *Salmonella* in flour | **Supply-chain control** | Receiving |
| 2 | *Salmonella* in liquid egg | **Supply-chain control** (FSIS-inspected supplier, so lighter verification with a written justification) | Receiving |
| 3 | *Salmonella* and STEC in walnuts | **Supply-chain control** | Receiving |
| 4 | Undeclared allergens: wheat, egg, milk, **tree nut (walnut)**, soy (check chips), sesame if present | **Food allergen control: labeling** | Labeling |
| 5 | Allergen cross-contact (walnut and egg into other bakery products, and the reverse) | **Food allergen control: cross-contact** (storage, scheduling, changeover cleaning, rework) | Storage, mixing, depositing |
| 6 | Environmental pathogens (*Salmonella*, *L. monocytogenes*) contaminating exposed RTE dough | **Sanitation control**, **verified by environmental monitoring** | Mixing, depositing, lidding |
| 7 | Pathogen growth in finished dough (*L. monocytogenes*, *S. aureus*) | **Process control: refrigeration ≤ 41 °F** (unless a_w data justify otherwise) | Cold storage |
| 8 | Metal (optional, based on your equipment and PM history) | **Process control: metal detection** | After lidding |
| 9 | Walnut shell (optional, based on supplier data) | Supply-chain control or supplier spec | Receiving |
| — | **Recall plan** | **Required**, because hazards requiring preventive controls were identified | — |

Validation is **required only for the process controls** (#7, #8). It is **not required** for the allergen, sanitation and supply-chain controls, though it is useful, e.g. allergen changeover cleaning.

---

## 4. Preventive control details

### 4.1 Supply-chain program (flour, liquid egg, walnuts)

| Element | Flour | Liquid pasteurized egg | Walnuts |
|---|---|---|---|
| Supplier-applied control | Validated heat treatment (log reduction for STEC/*Salmonella*, e.g. ≥ 5-log, per the supplier's validation) | Pasteurization under USDA-FSIS inspection | Validated pasteurization or pathogen-reduction treatment |
| Approval before first use | Review the supplier's food safety plan, **validation study for the heat treatment**, and audit report | Confirm FSIS establishment number; spec sheet | Review the validation study, food safety plan and audit |
| **Verification activity** | Hazard is SAHCODHA, so an **onsite audit before first use and at least annually** (a third-party audit by a qualified auditor is acceptable), **unless** a written justification supports another activity. Add a **COA for each lot** stating the treatment and pathogen test results. | Written justification that FSIS continuous inspection plus the spec and a letter of guarantee give adequate assurance; periodic review of supplier records | Annual onsite audit (third-party OK) plus a per-lot COA or certificate of treatment |
| Receiving procedure | Check that the lot is from an approved supplier, the COA is present and says "heat-treated", and packaging is intact | Approved supplier; product temperature ≤ 41 °F (or the spec); code date | Approved supplier; certificate of treatment; packaging intact |
| Corrective action | Lot without a COA or with an off-spec COA: **hold**; don't use until resolved; reject, or divert to a use with a kill step (e.g. baked products) | Temperature-abused: reject | Untreated or no certificate: reject or hold |
| Records | Approved supplier list; audit reports; COAs; receiving logs; corrective actions; reviewed by the PCQI | Same | Same |

Notes:
- A supplier's **own self-audit is not acceptable** verification.
- Watch for **temporary or unapproved suppliers**. Use them only with verification before use.
- If you ever buy flour that is *not* heat-treated, you lose this control entirely. Lock "heat-treated" into the purchase spec.

### 4.2 Food allergen preventive controls

**Allergens present:** wheat, egg, milk, tree nut (walnut), and likely **soy** (lecithin in chips). Check every sub-ingredient for **sesame**. Sesame became the 9th major food allergen in 2023, after the FSPCA manual was published.

**A. Labeling control**

| Component | Procedure |
|---|---|
| Parameter | Each tub carries the correct label, with an ingredient statement declaring all major food allergens, including "Contains: Wheat, Egg, Milk, Walnut, Soy" |
| Monitoring: what, how, when, who | The packing operator checks that the label matches the product and the label version **at start-up, at every label roll or changeover, and at the end of the run**, and initials the label-check log |
| Label receipt | A knowledgeable person checks each new label print against the current formula and sub-ingredient specs |
| Correction / corrective action | Wrong or missing label found: **hold** all product since the last good check, relabel, find the root cause (label storage, changeover), and record it |
| Verification | PCQI reviews records within **7 working days**; label audits when formula or supplier changes; destroy obsolete labels |

**B. Cross-contact control** (needed if the facility makes products without walnut, egg, etc.)
- Designated, labeled storage for walnuts in sealed containers. Store them low so dust and pieces cannot fall onto other ingredients.
- **Production scheduling:** run non-walnut and non-egg products first, then this product.
- Dedicated or color-coded scoops and utensils for walnuts.
- **Changeover cleaning** (wet clean the mixer, bowl, paddles and depositor) after this product. Do a visual inspection before the next product, and consider allergen-specific ELISA or lateral-flow swabs to verify.
- Rework: like-into-like only, labeled and dated, or not at all.
- "May contain" statements **do not replace** cross-contact controls.

### 4.3 Sanitation preventive control and environmental monitoring

**Why:** the dough is effectively RTE, exposed during mixing, depositing and lidding, and gets no lethal step afterwards. That makes **environmental pathogens** a hazard requiring a **sanitation control**, and **environmental monitoring (EM) is required** as verification.

| Component | Procedure |
|---|---|
| Scope | Food-contact surfaces (mixer bowl and paddle, scrapers, scoops, depositor hopper and nozzles, tub-filling surfaces); cross-contamination from personnel; hygienic zoning |
| Written cleaning procedure | Dry clean, pre-rinse, detergent wash, rinse, inspect, **sanitize at label concentration**, air dry. Dough is fatty and sugary, so specify detergent and water temperature. Minimize water in a dry bakery area, because wet areas favour *Listeria*. |
| Monitoring | **Pre-operational inspection** of food-contact surfaces each day before production; **sanitizer concentration check** each time sanitizer is mixed; recorded on the sanitation log |
| Correction | Surface found dirty before production: re-clean and re-inspect (a correction, with brief or no documentation) |
| Corrective action | Product was made on an unclean surface: evaluate and hold product, root cause, record |
| **Verification: EM** | Test for **Listeria spp.** (indicator) and consider ***Salmonella*** (relevant to dry and low-a_w dough). **Zones:** Zone 1 (food-contact surfaces) for Listeria spp. as verification of sanitation; Zones 2–3 (equipment frames, floors, drains, cooler) routinely. Set sites, number, frequency (e.g. weekly at first) and timing (several hours into production, not just after cleaning). **Corrective actions for positives:** intensified cleaning and vector swabbing; for a **Zone 1** positive, hold product, consider product testing, and do a root-cause investigation. |
| Other verification | PCQI reviews records within 7 working days; optional ATP checks |
| Prerequisites that support this | Hygienic zoning, traffic and personnel flow, hand washing, gowning, no raw (non-heat-treated) flour handled in the same area while this product is exposed |

**Important:** if the bakery uses **ordinary raw flour** for other products in the same room, flour dust is a real cross-contamination route into this dough. Separate in time or space, clean between products, and include this in your zoning and EM.

### 4.4 Process control: refrigeration (finished dough)

First, **measure a_w and pH** of the finished dough, with a lab on several batches. Then decide:
- **a_w high enough for pathogen growth** (e.g. *L. monocytogenes* above about 0.92, *S. aureus* above about 0.86): refrigeration is a **process control**.
- **a_w well below those levels**, confirmed by testing: you may justify refrigeration as quality only. Record the data and the reasoning in the hazard analysis.

If it is a process control:

| Component | Example (validate your own values) |
|---|---|
| Parameter / critical limit | Finished product cooler air temperature **≤ 41 °F (5 °C)**; dough out of refrigeration (mixing to cooler) **≤ X hours**, set from your data and kept short |
| Operating limit | Cooler set at ≤ 38 °F |
| Monitoring | Continuous temperature recorder with alarm, **or** a manual check at least twice per shift, by a trained employee on the cooler log |
| Corrective action | Above the limit: identify the cause, fix the cooler, **evaluate affected product** (time and temperature exposure against your validated growth data); hold, release or destroy; record |
| Validation | Scientific basis for the limit (literature, predictive models such as ComBase or the Pathogen Modeling Program used with caution, or a challenge study for shelf life) |
| Verification | Daily thermometer accuracy check; annual calibration; PCQI records review within 7 working days |
| Records | Temperature log, corrective actions, calibration, validation file |

Keep in mind that *L. monocytogenes* **grows at refrigeration temperatures**. Refrigeration slows it down; sanitation and EM keep it out. Shelf life should be backed by data.

### 4.5 Process control: metal detection (if your hazard analysis says Yes)

| Component | Example |
|---|---|
| Critical limit | A metal detector is present and working, and **rejects** test pieces (e.g. Fe 2.0 mm, non-Fe 2.5 mm, SS 3.0 mm; set for tub size and dough) |
| Monitoring | Pass the test pieces at **start, middle and end of each shift**, and at product changeover; check that the reject works; operator logs it |
| Corrective action | Detector fails: hold all product since the last good check, re-run it through a working detector, repair, root cause |
| Validation | Detector manufacturer or setup validation for the product's effect |
| Verification | Records review within 7 working days; periodic calibration and service |

If you decide **No**, document the justification: equipment design, preventive maintenance program, and a pre/post-shift inspection of mixer paddles and depositor parts for missing or damaged pieces.

---

## 5. Recall plan (required)

Because you have hazards requiring preventive controls, you need a written recall plan with assigned responsibilities for:
1. **Notifying direct consignees** (distributors, retailers): what is recalled, and how to return or destroy it.
2. **Notifying the public** when needed to protect health. Pathogen or undeclared-walnut recalls are typically **Class I**.
3. **Effectiveness checks.**
4. **Disposition** of recalled product (destroy, or divert where safe).

Supporting items:
- A recall team and contact list.
- FDA recall coordinator contacts.
- **Lot codes on every tub**.
- Distribution records.
- Trace capability one step back (flour, egg, walnut and chip lots by date) and one step forward.
- **Reportable Food Registry** reporting when required.
- At least an annual **mock recall**.

---

## 6. Verification, records and keeping the plan current

- **Records review** (monitoring, corrective action, verification) by or under a PCQI within **7 working days**.
- **Validate** the process controls before use, or within **90 days** of starting production.
- **Calibrate** thermometers and the metal detector.
- **Retain records** for at least **2 years**. Keep the Food Safety Plan **onsite**, and make offsite records retrievable within **24 hours**.
- **Training:** food hygiene and safety training for all staff, plus a PCQI.
- **Reanalyze** at least every **3 years**, or sooner if you:
  - change suppliers (especially of flour, egg or walnuts);
  - change the formula (which can affect a_w or allergens);
  - add equipment;
  - get EM positives or complaints.

---

## 7. Currency notes and things to confirm

- **Sesame** is a major food allergen as of 1 January 2023, after the 2016 FSPCA manual was published. Check every sub-ingredient for it.
- FDA's **hazard analysis draft guidance** (*Hazard Analysis and Risk-Based Preventive Controls for Human Food*), and its tables of ingredient- and process-related hazards, may have updated expectations. FDA has also issued consumer and industry messaging on raw flour and raw dough. Check the latest versions.
- **FSMA 204 traceability rule:** liquid egg products, walnuts and cookie dough do not appear to be on the Food Traceability List (shell eggs and nut butters are). **Confirm against the current list** and against any ingredients you add.
- **Liquid egg products** fall under **USDA-FSIS** for the supplier. Your dough falls under **FDA**. Your verification relies on the supplier's FSIS-inspected status.
- **Sanitary Transportation rule:** refrigerated shipping needs temperature specifications agreed with carriers.

**Next steps for your PCQI:**
1. Get a_w and pH data on the finished dough.
2. Walk the line to verify the flow diagram.
3. Collect supplier validation studies and COAs for flour, egg and walnuts.
4. Decide on metal detection and walnut shell control based on your own history.
5. Write the EM program (sites and frequency).
6. Sign and date the Food Safety Plan.

# Hazard Analysis and Preventive Controls: Refrigerated Ready-to-Bake Chocolate Chip Walnut Cookie Dough

**Rule:** FSMA Preventive Controls for Human Food (PCHF), 21 CFR Part 117, Subparts C (Hazard Analysis and Risk-Based Preventive Controls) and G (Supply-Chain Program)

> This is a starting framework. Your Food Safety Plan has to be prepared, or overseen, by a **Preventive Controls Qualified Individual (PCQI)** (117.126(a)(2)). It also has to reflect your actual facility, equipment, suppliers, and product data. Treat the conclusions below as a well-reasoned draft for your PCQI to confirm, not as a final plan.

---

## 0. First, check whether full Subpart C applies to you

- **Qualified facility (very small business):** If your business, including all subsidiaries and affiliates, averages less than about **$1 million per year** (inflation-adjusted; the current threshold is a little higher) in human food sales plus the market value of food held without sale, over the previous 3 years, you are a *qualified facility*. In that case you are **exempt from Subparts C and G**. You file the attestation on **Form FDA 3942a** (117.201) every 2 years. You then either attest that you identify and control hazards, or you comply with applicable state/local food safety law and put your name and address on the label or at the point of sale. CGMPs (Subpart B) still apply.
- Even if you qualify, the analysis below is the right way to make this product safe. A raw-dough product with a nut allergen is high-risk for recalls.
- The rest of this document assumes you are **not** a qualified facility and need a full Food Safety Plan.

---

## 1. Product Description (required context for hazard analysis)

| Item | Description |
|---|---|
| Product | Refrigerated ready-to-bake chocolate chip cookie dough with walnuts |
| Ingredients | Heat-treated wheat flour (supplier), liquid pasteurized whole egg (USDA-inspected egg product), butter, sugar(s), chocolate chips (likely contain milk and soy lecithin; confirm), walnuts |
| Process | Receive → refrigerated/dry storage → weigh → mix → deposit into tubs → lid/seal → label → refrigerated storage → refrigerated distribution |
| Packaging | Retail tubs, sealed lid |
| Storage/distribution | Refrigerated (target ≤41°F / 5°C) |
| Intended use | Labeled "bake before eating." **Reasonably foreseeable use:** consumers, including children, eat the dough raw. |
| Intended consumer | General public, including children, elderly, pregnant, and immunocompromised people |
| Allergens | **Wheat, egg, milk** (butter, and probably the chips), **tree nuts (walnut)**, **soy** (if the chips contain soy lecithin). Check every sub-ingredient, including for sesame. |

### The key judgment: treat this dough as ready-to-eat

FDA's hazard analysis has to consider hazards that are **known or reasonably foreseeable**. That includes reasonably foreseeable consumer behavior. Raw cookie dough is widely eaten unbaked. Flour-related STEC and Salmonella outbreaks (2016, 2019, 2023) and the large raw-dough recalls happened because of this behavior. A "do not eat raw" statement is good practice, but FDA does not consider it a control you can rely on for a product this commonly eaten raw.

Under the Part 117 definition, a ready-to-eat (RTE) food includes food for which it is reasonably foreseeable that it will be eaten without further processing that would significantly minimize biological hazards. So **treat this dough as an RTE food.** That drives two results:

1. Every ingredient that carries a pathogen hazard must arrive already treated (a supplier kill step), because **your facility has no kill step**.
2. The dough is exposed to the environment between mixing and sealing, so **environmental pathogens (Listeria monocytogenes)** must be considered.

---

## 2. Hazard Analysis Worksheet

Key: **HRPC** = hazard requiring a preventive control. "Supply-chain" = the hazard is controlled before you receive the ingredient, and you verify that through your supply-chain program (Subpart G).

### 2a. Ingredients / Receiving

| Ingredient | Potential hazard | Known or reasonably foreseeable? Justification | HRPC? | Control |
|---|---|---|---|---|
| **Heat-treated flour** | B: STEC (E. coli O157:H7, O121, O26), Salmonella | **Yes.** Raw flour is a recognized vehicle (multiple outbreaks and recalls). Illness is severe (HUS), so it is a SAHCODHA hazard. You have no kill step. | **Yes** | **Supply-chain-applied control:** supplier's validated heat treatment (typically ≥5-log reduction of Salmonella/STEC surrogates) |
| | B: post-treatment recontamination at supplier | Possible | (covered above) | Supplier's post-lethality sanitation and EMP. Verify by audit. |
| | C: mycotoxins (DON), pesticide residues | Low at levels that cause illness in US wheat. Controlled by the miller and FDA advisory levels. | No | Supplier specification (prerequisite program) |
| | C: allergen (wheat) | Inherent, so it must be labeled | Handled under allergen controls (labeling) | Allergen control |
| | P: foreign material | Low. Millers sift and use magnets. | No | Supplier specification |
| **Liquid pasteurized egg** | B: Salmonella Enteritidis | **Yes.** Eggs are a known source. Pasteurization is required by law under USDA FSIS (Egg Products Inspection Act). | **Yes** | **Supply-chain-applied control:** supplier pasteurization. Verify with documentation: USDA inspection legend, letter of guarantee, COA if available. |
| | B: growth after receipt (temperature abuse) | Yes, if not kept cold | Handled by receiving temperature check and storage ≤40°F (CGMP/prerequisite). Use within the supplier's open-container shelf life. | CGMP |
| | C: allergen (egg) | Inherent | Allergen control | Allergen control |
| **Butter** | B: Listeria, Salmonella | Low. Made from pasteurized cream under PMO/dairy oversight. Few outbreaks. | No (document justification) | Approved supplier, refrigerated receipt |
| | C: allergen (milk) | Inherent | Allergen control | |
| **Sugar** | B/C/P | Very low. Aw too low for pathogen growth. Refined. | No | Supplier specification |
| **Chocolate chips** | B: Salmonella | Historically linked to chocolate outbreaks, but cocoa roasting and the manufacturer's PCs control it. Low risk from a reputable supplier that is itself under PCHF. | **Judgment call.** Most plans conclude **No** (supplier is a PCHF facility controlling the hazard and the hazard is rare). A conservative plan adds it to the supply-chain program. Document your reasoning. | Approved supplier + spec, or supply-chain control |
| | C: allergens: milk, soy (lecithin), possibly tree nuts/peanuts from shared lines | **Yes.** Sub-ingredient allergens and "may contain" precautionary statements are a frequent cause of undeclared allergen recalls. | Yes, under allergen control (label review of incoming ingredient) | Allergen control (ingredient label/spec review at receiving) |
| **Walnuts** | B: Salmonella, E. coli O157:H7 | **Yes.** Tree nuts have had repeated Salmonella and STEC recalls and outbreaks, including a 2024 E. coli O157:H7 outbreak tied to raw organic walnuts. Walnuts go into the dough **with no kill step**. SAHCODHA. | **Yes** | **Supply-chain-applied control:** buy **pasteurized/treated walnuts** (validated process, such as steam, PPO, or dry heat, targeting ≥4-5 log Salmonella). Do **not** use raw walnuts. Alternatively, roast them in-house with a validated process; that would become a **process control** at your facility. |
| | C: aflatoxin | Low for walnuts compared with peanuts and pistachios | No (supplier specification) | Supplier spec |
| | C: allergen (tree nut, walnut) | Inherent. Also a cross-contact hazard for your other products. | Yes | Allergen control |
| | P: shell fragments, stones | **Yes.** Shell fragments are common in shelled nuts. Hard or sharp pieces 7-25 mm are a choking or injury hazard. | Generally **No** at your facility if the supplier sorts (optical/air) and gives a shell spec. Document why. Some plans make this a supply-chain control. | Supplier spec (e.g., max shell per lb) + visual inspection at weighing |
| **Packaging (tubs, lids)** | C: migration of non-food-grade material | Low with food-contact-compliant packaging | No | Letter of guarantee (21 CFR 174-178 compliance) |

### 2b. Processing steps

| Step | Potential hazard | Reasonably foreseeable? Justification | HRPC? | Control |
|---|---|---|---|---|
| **Receiving** | B: temperature abuse of refrigerated ingredients | Yes | No (CGMP) | Receiving temperature check |
| | C: receiving the wrong ingredient or one with an undeclared allergen (e.g., unpasteurized walnuts, chips with peanut) | Yes | Covered under the supply-chain program and allergen control | Check every lot against the approved spec/supplier list |
| **Storage** | B: pathogen growth in eggs and butter | Yes, if refrigeration fails | No (CGMP) | Cooler temperature monitoring |
| | C: allergen cross-contact (walnut dust or pieces getting into other ingredients) | Yes | Yes | Allergen control: segregated, sealed, labeled storage, with walnuts stored below or apart from other ingredients |
| **Weighing/scaling** | C: allergen cross-contact from shared scoops and scales | Yes | Yes | Allergen control: dedicated or cleaned utensils |
| | P: foreign material | Low | No | CGMP |
| **Mixing** | B: contamination from environment, equipment, or employees (Listeria, Salmonella) | **Yes.** RTE dough is exposed. Mixers, bowls, and depositors are wet-cleaned, and cooled areas support Listeria harborage. | **Yes** | **Sanitation control** + **environmental monitoring** |
| | C: allergen cross-contact with other bakery products (walnut into non-nut products, or other allergens such as peanut and sesame into this dough) | **Yes**, if equipment is shared | **Yes** | **Allergen control** (scheduling, validated cleaning between allergen changeovers) + **sanitation control** |
| | P: metal (mixer paddle or scraper wear, bowl contact, broken parts) | **Yes.** Mixers and depositors are known sources of metal fragments. | **Judgment call.** See Section 3.4. | Metal detection (process control) **or** equipment inspection program (CGMP) |
| **Depositing into tubs** | B: environmental pathogen contamination (Listeria) from depositor, hoppers, and food-contact surfaces | **Yes.** Last exposure before sealing. | **Yes** | Sanitation control + EMP |
| | P: metal from depositor (pistons, valves) | Yes | See Section 3.4 | |
| **Lidding/sealing** | B: post-packaging contamination | Low once sealed | No | Seal integrity check (CGMP/quality) |
| **Labeling** | C: **undeclared allergens** (wrong label, missing walnut/wheat/egg/milk/soy, label mix-up with a non-nut product) | **Yes.** This is the leading cause of FDA food recalls. | **Yes** | **Allergen control: label control** |
| | B: missing "keep refrigerated" or baking instructions | Supports safe handling | Covered in label check | |
| **Refrigerated storage and shipping** | B: growth of pathogens if temperature is abused (see Section 3.5) | Depends on the dough's water activity | **Depends on formulation.** See Section 3.5. | Refrigeration as a process control, or formulation (aw) as a process control, or no PC if validated to not support growth |
| | | | | Also follow the Sanitary Transportation rule (21 CFR Part 1, Subpart O) |

### 2c. Hazards considered and ruled out (document these too)

- **Radiological:** not reasonably foreseeable.
- **Economically motivated adulteration** (e.g., undeclared nut substitution): low for this supply chain. Note your reasoning.
- **Cleaning chemical residues:** controlled by CGMPs (labeled, stored separately, used per directions). Not an HRPC.
- **Staphylococcus aureus / B. cereus toxins:** low risk if formulation aw is low and the product is refrigerated. Employee hygiene (CGMP).
- **Clostridium botulinum:** not a concern. The product is aerobic, and its aw and refrigeration prevent it. Do not vacuum-pack or modified-atmosphere-pack without re-evaluating.

---

## 3. Preventive Controls You Need

### Summary

| # | Preventive control | Type (117.135(c)) | Hazard(s) controlled |
|---|---|---|---|
| 1 | **Supply-chain program**: heat-treated flour, pasteurized eggs, pasteurized/treated walnuts (chocolate chips optional) | Supply-chain control (Subpart G) | STEC and Salmonella in flour; Salmonella in eggs; Salmonella and STEC in walnuts |
| 2 | **Allergen controls**: label control + cross-contact control | Food allergen control | Undeclared wheat, egg, milk, soy, tree nut (walnut); cross-contact to and from other products |
| 3 | **Sanitation controls** for RTE dough food-contact surfaces, plus **environmental monitoring** | Sanitation control (+ EMP verification, 117.165(a)(3)) | Listeria monocytogenes (and Salmonella) from the environment; allergen cross-contact |
| 4 | **Metal detection** (recommended) or justified equipment controls | Process control (if adopted) | Metal fragments |
| 5 | **Refrigeration and/or formulation (aw)** | Process control, *only if* the dough supports pathogen growth | Pathogen growth during shelf life |
| 6 | **Recall plan** | Required, because you have HRPCs (117.139) | All |

---

### 3.1 Supply-Chain Program (21 CFR 117 Subpart G)

You are the **receiving facility**. Your **suppliers** control the pathogen hazards in flour, eggs, and walnuts. Under 117.410-117.475 you must:

1. **Use approved suppliers** (117.410(d), 117.420). Approve each supplier in writing, considering: their hazard analysis, the controls they apply, their compliance history (FDA warning letters, import alerts, recalls), and their food safety performance.
2. **Set appropriate verification activities** for each supplier (117.410(b), 117.430):
   - **Flour, walnuts, eggs: Salmonella/STEC are SAHCODHA hazards.** The default is an **annual onsite audit** by a qualified auditor (117.430(b)(1)), unless you document a determination that other verification activities and/or less frequent auditing give adequate assurance. In practice, accept the supplier's **third-party audit report** (e.g., a GFSI-benchmarked scheme such as SQF or BRCGS), which must cover FDA requirements. You do not have to do the audit yourself.
   - Add: **lot-specific Certificates of Analysis or Certificates of Treatment/Conformance** stating the heat treatment or pasteurization process was applied (e.g., "heat-treated to achieve ≥5-log reduction of Salmonella," with lot number).
   - Get the **supplier's process validation summary** (for example, the flour heat-treatment validation study or the walnut pasteurization validation) once at approval, then on change.
   - **Eggs:** the supplier is a USDA FSIS-inspected establishment, and pasteurization is mandatory. Verification is typically documentation-based: the USDA inspection legend on the package, a letter of guarantee/continuing guarantee, and spec sheets. Record your justification for the verification you choose.
   - **Optional periodic sampling and testing** (e.g., Salmonella on walnuts, or E. coli/Salmonella on flour) as a further check. Testing alone is not a kill step.
3. **Receiving procedures:** before use, check every lot against the approved-supplier list and the required documentation (COA/certificate). Reject and hold lots without documentation.
4. **Exceptions:** if a supplier is itself a **qualified facility**, or a small farm, the modified verification in 117.430(c)-(e) applies (written assurance plus attestation).
5. **Records** (117.475): written supply-chain program, supplier approval, audit reports, COAs, corrective actions, and review of records.
6. **Corrective actions:** if a supplier fails to control the hazard (failed audit, missing COA, a recall), stop using the supplier until it is resolved, and assess affected product.

> **Specification wording matters.** "Heat-treated flour" must be specified as **validated for pathogen reduction** (not just "heat-treated" for functional or baking properties). "Walnuts" must be specified as **pasteurized/treated** with a validated log reduction. If you cannot get treated walnuts, you need your own validated roasting step (see 3.6).

### 3.2 Food Allergen Controls (117.135(c)(2))

**a. Label control (most important)**
- **Monitoring:** at the start of each production run, at every label roll or lot change, and at the end of the run: confirm the label in use matches the product in the tubs. Confirm the ingredient statement and "**Contains: Wheat, Egg, Milk, Walnut, Soy**" (as applicable) match the current formula.
- **Label design review:** whenever the formula, supplier, or label changes. The PCQI or a designee checks every sub-ingredient specification, especially the chocolate chips and any precautionary "may contain" statements. Tree nuts must be declared by the specific nut ("walnuts").
- Keep labels for different products physically separated. Destroy obsolete labels.
- **Corrective action:** if the label is wrong, hold the product back to the last good check, relabel or destroy, find the root cause, and retrain.
- **Records:** label check log signed by the operator; review within 7 working days (117.165(a)(4)).

**b. Allergen cross-contact control**
- If you make other products **without walnuts** (or without any of these allergens) on the same mixer or depositor:
  - **Production scheduling:** run walnut dough **last** before a full clean, or on dedicated days.
  - **Validated allergen cleaning** between changeovers. Verify with visual inspection and allergen-specific test kits or protein swabs (ATP does **not** detect allergen protein).
  - Dedicated or color-coded scoops, bins, and utensils for walnuts.
  - Segregated storage of walnuts.
  - Control airborne nut fines and flour dust.
- Also consider allergens in **other** products (e.g., peanut, sesame) that could get into **this** dough.

### 3.3 Sanitation Controls + Environmental Monitoring (117.135(c)(3); 117.165(a)(3))

Because the dough is RTE (reasonably foreseeable raw consumption), is exposed to the environment before sealing, and gets no lethality treatment after packaging:

- **Sanitation PC:** written procedures for cleaning and sanitizing **food-contact surfaces** (mixer bowl, paddle, depositor hopper, pistons, nozzles, utensils, tub-filling area). Include frequency, method (disassembly, wash, rinse, sanitize, concentration), and who is responsible.
  - **Monitoring:** pre-operational inspection (visual + sanitizer concentration), documented each production day.
  - **Corrective action:** re-clean before starting. Evaluate any product made on inadequately cleaned equipment.
  - Include **allergen cleaning** in these sanitation procedures.
  - Dough equipment is often hard to clean (sugar and fat residue). **Minimize wet cleaning** where possible, and **dry the equipment** fully, because water is what lets Listeria establish.
- **Environmental monitoring program (EMP), required verification:**
  - Test for **Listeria spp.** (indicator organism) by zone:
    - Zone 1 (food-contact surfaces after sanitation, or during production): mixer bowl, paddle, depositor
    - Zone 2 (near food contact): equipment frames, control panels
    - Zone 3: floors, drains, carts
    - Zone 4: outside the processing area
  - Write down the **number and locations of sites, timing, frequency** (e.g., weekly to start), test method, and laboratory.
  - **Corrective actions for positives:** intensified cleaning, vector swabbing, and re-testing. For a **Zone 1 positive**, hold and test the product and do a root-cause investigation.
  - Add Salmonella testing at a lower frequency if your hazard analysis (e.g., dry-ingredient handling) supports it.

> Note: high sugar and low aw limit *growth* of Listeria in dough, but do not reliably *kill* it, and Listeria survives refrigeration. Contamination after mixing therefore stays a real risk.

### 3.4 Metal: Process Control or Justified CGMP

Mixers and depositors are known sources of metal fragments (worn paddles and scrapers, pistons, broken screws). You have two defensible options:

- **Option A (recommended): metal detector** on the filled tubs (most tubs are non-metallic, so in-line detection works well).
  - **Process control** with parameters such as sensitivity standards (e.g., ≥2.0 mm ferrous, 2.5 mm non-ferrous, 3.0 mm stainless; set for your product).
  - **Monitoring:** test with certified test pieces at start-up, at least every 2-4 hours, and at the end of the run.
  - **Corrective action:** if a check fails, re-inspect all product back to the last good check.
  - Reject mechanism or manual removal; investigate any rejects.
  - FDA guidance treats hard or sharp foreign objects of 7-25 mm as a health hazard. Metal detection catches much smaller pieces.
- **Option B:** conclude that metal is not an HRPC because of a **documented equipment inspection program** (pre-op and post-op inspection of paddles, scrapers, depositor parts, and screens, plus preventive maintenance). This is acceptable only if your hazard evaluation supports it: low-speed mixer, no metal-on-metal contact, and no history of incidents. **Write down the justification.**

### 3.5 Refrigeration and/or Formulation: Decide with Data

Whether temperature control is a **preventive control** or a CGMP depends on whether the dough supports pathogen growth:

- **Measure the finished dough's water activity (aw)** (and pH) on several batches.
  - Typical chocolate chip cookie dough has aw of about **0.80-0.90**, depending on the sugar-to-fat-to-egg ratio.
  - Listeria minimum aw for growth is about 0.92; Salmonella about 0.94; S. aureus can grow down to about 0.83-0.86 (toxin production at about 0.86+, aerobic).
- **If aw ≤ ~0.85 (validated):** pathogen growth is not reasonably foreseeable. Refrigeration is mainly a quality and spoilage control (CGMP), and **formulation** (sugar level, aw) may be your **process control**. Monitor it by batch formulation checks or periodic aw testing, and verify it.
- **If aw > ~0.86, or not validated:** make **refrigeration (≤41°F) a process control** for the finished product in storage. Monitor cooler temperature continuously or at set intervals. Correct deviations (evaluate time and temperature exposure, hold the product). Shipping temperature is also covered by the Sanitary Transportation rule.
- A **challenge study** by a process authority or university lab is the strongest support for your shelf-life claim and for the "no growth" conclusion.

### 3.6 If You Change the Process (Optional Alternatives)

- **In-house walnut roasting:** if you roast raw walnuts yourself to control Salmonella and STEC, that step becomes a **process control**. It needs a **validated** time and temperature (e.g., from a process authority or published data, with ≥4-5 log reduction of Salmonella), continuous monitoring, corrective actions, and validation records (117.160).
- **Untreated flour + reliance on consumer baking:** FDA does **not** accept this for a product that is foreseeably eaten raw. 117.136 (relying on a customer to control a hazard) applies to downstream *manufacturers* who get a written assurance, not to retail consumers.

---

## 4. Other Required Food Safety Plan Elements (117.126)

For each preventive control (except where the rule says otherwise), you need:

1. **Hazard analysis** (above), written. Include your justification for each "No" decision.
2. **Preventive controls** with parameters and critical limits where applicable.
3. **Monitoring procedures** and records (117.145).
4. **Corrective action procedures** (117.150). Include unanticipated problems: if a hazard shows up that the plan did not foresee, reanalyze.
5. **Verification** (117.155, 117.165):
   - **Validation** of process controls (e.g., metal detector sensitivity, refrigeration/aw decision, any in-house roasting) by a PCQI. Allergen, sanitation, and supply-chain controls do not require validation.
   - **Calibration** of thermometers, aw meter, metal detector.
   - **Records review** by the PCQI or under PCQI oversight within 7 working days of record creation, for monitoring and corrective action records.
   - **Environmental monitoring** (required here).
   - **Product testing** (optional but useful: periodic Salmonella/E. coli/Listeria testing of finished dough).
6. **Supply-chain program** (Section 3.1).
7. **Recall plan** (117.139): required because you have HRPCs. Cover notifying consignees, public notification, effectiveness checks, and disposition. Lot coding on every tub and distribution records are essential.
8. **Reanalysis:** at least every **3 years**, and whenever anything changes (new supplier, new product, new equipment, new hazard information, or a control failure).
9. **Records** (Subpart F): kept for 2 years, signed by the PCQI, and available to FDA.
10. **Training:** qualified individuals for each task (117.4), CGMP and food hygiene training, and PCQI training (e.g., FSPCA course or equivalent experience).

---

## 5. Practical Recommendations

- **Label "Bake before eating" / "Do not consume raw dough"**, include baking instructions, and "**Keep Refrigerated.**" Do this as good practice and consumer safety messaging, even though your controls (treated flour, pasteurized eggs, treated walnuts) are designed to make the dough safe if eaten raw.
- **Do not make a "safe to eat raw" claim** unless every ingredient is validated and verified for pathogen reduction, the EMP is mature, and you have finished-product testing data. If you plan to market it as edible raw, apply the same controls with more verification.
- **Start with a strong EMP** and finished-product testing for the first several months, then adjust frequency based on data.
- **Ask your flour supplier and walnut supplier for their validation reports now.** If they can't provide them, change suppliers.
- **Get an allergen cross-contact map** of your bakery. If walnuts are new to the facility, they add a tree nut allergen risk to all your existing products. Re-evaluate those products' hazard analyses and labels too.
- **Food Traceability Rule (FSMA 204):** walnuts, liquid egg products, flour, and finished cookie dough are not on the Food Traceability List. Lot coding and one-up/one-down records (Bioterrorism Act, 21 CFR 1 Subpart J) still apply.

---

## 6. Bottom Line

**Hazards requiring a preventive control:**
1. **Salmonella / STEC in flour**: supply-chain control (validated heat-treated flour).
2. **Salmonella in eggs**: supply-chain control (USDA-pasteurized liquid egg).
3. **Salmonella / E. coli O157:H7 in walnuts**: supply-chain control (pasteurized walnuts), or your own validated roast as a process control.
4. **Undeclared allergens and allergen cross-contact** (wheat, egg, milk, soy, walnut): allergen controls (label control + cross-contact control).
5. **Environmental pathogens (Listeria monocytogenes)** in RTE dough exposed before packaging: sanitation controls, verified by an environmental monitoring program.
6. **Metal fragments**: metal detection as a process control (recommended), or a documented equipment-inspection justification.
7. **Pathogen growth during refrigerated shelf life**: refrigeration or formulation (aw) as a process control, **if** aw testing shows the dough can support growth.

Plus a **recall plan**, verification (including records review and calibration), and **reanalysis**, all managed by a PCQI.

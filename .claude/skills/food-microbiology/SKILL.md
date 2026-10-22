---
name: food-microbiology
description: 'Apply "Food Microbiology: An Introduction" (4th ed., Matthews, Kniel & Montville, ASM Press): microbial growth, survival and death in foods (pH, water activity, temperature, hurdles, injury/VBNC, biofilms), spores and thermal processing (D, z, F, 12D botulinum cook, low-acid canning), detection and rapid methods (plate count, MPN, PCR), indicators and microbiological criteria (sampling plans, FSOs, risk assessment), US regulation (FDA, USDA-FSIS, CDC, FSMA, PulseNet, outbreak investigation), pathogens (B. cereus, Campylobacter, C. botulinum, C. perfringens, E. coli O157:H7, Listeria, Salmonella, Shigella, S. aureus, Vibrio, Yersinia, parasites, viruses, prions), fermentation, spoilage, molds and mycotoxins, and control (preservatives, bacteriocins, probiotics, pasteurization, HPP, PEF, irradiation, ozone, sanitation, HACCP). Use for food safety questions, outbreak or symptom reasoning, process and shelf-life design, HACCP plans and study help.'
---

# Food Microbiology: An Introduction (4th edition)

A working guide distilled from *Food Microbiology: An Introduction*, 4th edition, by Karl R. Matthews (Rutgers), Kalmia E. Kniel (Delaware) and Thomas J. Montville (Rutgers), published by ASM Press. It is a university textbook in four sections and 29 chapters:

1. **Basics of food microbiology (ch. 1–6):**
   - History
   - Growth, survival and death
   - Spores
   - Detection and enumeration
   - Rapid methods
   - Indicators and microbiological criteria
2. **Foodborne pathogenic bacteria (ch. 7–18):**
   - Regulatory issues
   - *B. cereus*, *Campylobacter*, *C. botulinum*, *C. perfringens*, enterohemorrhagic *E. coli*, *Listeria monocytogenes*, *Salmonella*, *Shigella*, *S. aureus*, *Vibrio*, *Yersinia*
3. **Other microbes important in food (ch. 19–24):**
   - Lactic acid bacteria and fermentations
   - Yeast-based and other fermentations
   - Spoilage organisms
   - Molds and mycotoxins
   - Parasites
   - Viruses and prions
4. **Control of microorganisms in foods (ch. 25–29):**
   - Chemical antimicrobials
   - Biological preservation and probiotics
   - Physical methods
   - Nonthermal processing
   - Sanitation, GMPs and HACCP

**Source coverage:** Built from the user's photographed copy (355 two-page spreads), which was OCR'd. Running text was mostly legible, but many tables were not. Figures marked *(book)* were checked in the OCR text. Values marked *(std)* are standard food-safety reference values, used where the book's table was illegible. Verify them against current FDA, USDA or Codex guidance before relying on them for compliance.

## Core ideas

1. **Foods are ecosystems.** Growth depends on **intrinsic factors** (pH, water activity a_w, nutrients, antimicrobials, structure) and **extrinsic factors** (temperature, atmosphere, other microbes). Control means manipulating them, usually in combination: **hurdle technology**.
2. **A few numbers carry most of the safety load:**
   - pH 4.6 separates acid from low-acid foods; low-acid canned foods are those with pH > 4.6 and a_w > 0.85.
   - a_w 0.85 is the lowest at which pathogens grow *(book)*.
   - *S. aureus* grows down to about a_w 0.86 but doesn't make toxin below about 0.93 *(book)*.
   - The refrigeration "danger zone" is 40–140 °F *(book)*.
   - D, z and the 12D botulinum cook: D₁₂₁ ≈ 0.2 min for *C. botulinum* spores, so a 12D process ≈ 2.4 min at 250 °F *(book)*.
3. **Hazard ≠ risk.** Hazard is the potential to cause harm; risk is the probability that it does. Food microbiology is largely **risk management**: lowering a hazard to an acceptable probability *(book)*.
4. **Infection vs intoxication vs toxicoinfection** determines incubation time, symptoms and control:
   - Preformed toxins act fast (*S. aureus*, emetic *B. cereus*, botulinum).
   - Infections are slower (*Salmonella*, *Listeria*, EHEC).
   - In toxicoinfections, toxin is made in the gut (*C. perfringens*, diarrheal *B. cereus*).
5. **What you can't culture can still hurt you.** Injured and viable-but-nonculturable (VBNC) cells, viruses and parasites often escape standard plating. Testing can't "inspect safety in", which is why **safety by design (HACCP and preventive controls)** replaced end-product testing *(book)*.
6. **Spores and toxins survive what kills cells.** Cooking kills vegetative cells but can leave spores (*C. perfringens*, *B. cereus*, *C. botulinum*) and heat-stable toxins (staphylococcal enterotoxin, cereulide). **Cooling and holding** are therefore critical control points.

## How to use this skill

| User wants… | Go to |
|---|---|
| pH, a_w, temperature, growth curve math, injury/VBNC, biofilms, quorum sensing, hurdles | `references/fundamentals.md` §1–§3 |
| Spores, D/z/F values, 12D, canning, aseptic processing | `references/fundamentals.md` §4 and `references/control.md` §3 |
| Plate counts, MPN, sampling, rapid and molecular methods | `references/fundamentals.md` §5 |
| Indicators (coliforms, *E. coli*, APC), microbiological criteria, sampling plans, FSOs, risk assessment | `references/fundamentals.md` §6 |
| Agencies, laws (FSMA), surveillance, outbreak investigation, consumer rules | `references/pathogens.md` §1 |
| A specific pathogen, symptom→pathogen reasoning, vehicles, prevention | `references/pathogens.md` §2–§4 (profile table, then detail) |
| Parasites, viruses, prions | `references/pathogens.md` §5 |
| Lactic acid bacteria, cheese, yogurt, sausage, beer, wine, bread, vinegar, cocoa | `references/fermentation-spoilage.md` §1–§2 |
| Spoilage of meat, milk, produce, juices; molds and mycotoxins | `references/fermentation-spoilage.md` §3–§4 |
| Preservatives, organic acids, nitrite, sanitizers, bacteriocins, probiotics | `references/control.md` §1–§2 |
| Drying, chilling, freezing, MAP, pasteurization, sterilization | `references/control.md` §3 |
| HPP, PEF, irradiation, UV, ozone, cold plasma | `references/control.md` §4 |
| Sanitation, GMPs, SSOPs, HACCP's seven principles, FSMA food safety plans | `references/control.md` §5 |

**Workflow for an outbreak or "what made me sick" question:**
1. Get the timing (onset after eating), the main symptoms (vomiting vs diarrhea vs bloody diarrhea vs fever vs neurological), the food and how it was handled, and who was affected.
2. Use the profile table (`pathogens.md` §2) to rank candidates, explaining why: incubation, symptoms, vehicle, temperature abuse.
3. Name the control failure (e.g. slow cooling, cross-contamination, undercooking, raw product, infected worker) and the prevention.
4. For real illness, advise seeing a clinician and reporting to the local health department. Don't diagnose.

**Workflow for a process, product or HACCP question:** identify the hazards, the food's intrinsic factors (pH, a_w), the process lethality or hurdles, storage conditions and the critical limits. Then apply HACCP's seven principles (`control.md` §5).

## Output style and caveats

- Explain the microbiology (why the organism survives or grows), then give practical controls and the numbers involved.
- This is educational content, not medical, legal or regulatory advice. Regulations (FDA Food Code, FSIS, FSMA rules, international standards) change. Point users to the current official source for compliance values, and to process authorities for canning and thermal-process validation.
- Never encourage risky practices such as home canning low-acid foods without a tested process, raw milk for vulnerable groups, or honey for infants.
- For study help, the book's style is to make students reason ("Questions for critical thought"). Offer worked calculations (D/z, log reductions, MPN, growth) step by step.
- Don't reproduce long textbook passages. Paraphrase and apply.

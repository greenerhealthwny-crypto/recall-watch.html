# Is a supplier self-audit plus a COA enough for pasteurized liquid egg in an RTE product?

**Short answer: No.** Under 21 CFR Part 117, Subpart G (the supply-chain program), a supplier's own audit does not count as supplier verification. Your situation is also the one where the rule asks the most: the hazard (*Salmonella*) can cause serious adverse health consequences or death (SAHCODHA), and **your facility has no kill step**. So the default requirement is an **onsite audit by a qualified auditor, before first use and at least once a year after that**. You can depart from that default only with a documented written justification. A COA can support your verification, but it cannot stand in for the audit.

---

## 1. Why you need a supply-chain-applied control at all

Work this through your hazard analysis:

| Ingredient | Hazard | Reasonably foreseeable? | Severity × probability (without controls) | Requires a preventive control? | Where is it controlled? |
|---|---|---|---|---|---|
| Pasteurized liquid egg | Biological: *Salmonella* (and other vegetative pathogens) from shell eggs | Yes. Eggs and *Salmonella* are a classic pairing. | High severity; probable without pasteurization | **Yes** | **At the supplier** (pasteurization). You have no later lethal step. |
| Pasteurized liquid egg | Chemical: egg allergen | Yes | High | Yes | **At your facility** (allergen control: labeling, cross-contact). This is not a supply-chain control. |

The rule calls a hazard controlled by your supplier a **"supply-chain-applied control."** When you are the **receiving facility**, your hazard analysis identifies a hazard requiring a preventive control in a raw material, and the supplier controls it, you need a **supply-chain program**. That is your situation.

For comparison, the FSPCA course example (E.G. Food Company, frozen omelets) buys the same ingredient. It *chose* to control *Salmonella* with its own validated cook step (omelet surface ≥ 158 °F), which made a supply-chain control unnecessary for that hazard. You don't have that option, because your product gets no further cook. Everything rests on the supplier's pasteurization and your verification of it.

## 2. Why the QA lead's plan falls short

| Proposed element | Status under Subpart G |
|---|---|
| Supplier's own annual self-audit | **Not acceptable.** The rule says a supplier may not audit itself or review its own records as your verification activity. The audit has to be done by a **qualified auditor** who is independent of the supplier. That can be a third-party auditor or someone from your company who is qualified. |
| COA with each lot | **Acceptable as a supporting activity**, but not on its own for a SAHCODHA hazard. A COA is a supplier record, so reviewing it counts as "review of the supplier's food safety records." It is not an onsite audit. |
| Approval, receiving procedures, corrective actions, records | **Missing from the proposal.** These are required program elements, covered below. |

**Some limits of COAs to keep in mind:**
- A COA only shows that the sampled units tested negative. Pathogens are spread unevenly in product, so a negative result does not prove the lot is free of *Salmonella*.
- It tells you nothing about how the pasteurization process was validated or monitored, or whether post-pasteurization sanitation and environmental monitoring were done.
- It must name the specific lot, the test method, the lab and the specification. A generic "meets spec" letter does not do the job.
- You should check it periodically yourself, for example by occasional confirmatory testing at your own lab and by tracing COA results during the audit.

## 3. What your supply-chain program has to include

Your **PCQI** should perform or oversee writing these into the Food Safety Plan:

1. **Approved supplier.** You must approve the egg supplier **before** you receive product from it, and document the approval. The basis can include its hazard analysis, pasteurization validation, regulatory standing and audit results. The supplier cannot approve itself. Only use an unapproved supplier temporarily, and only after verifying the product before use.
2. **Written receiving procedures.** Say what is checked at the dock, how, how often and by whom. For example:
   - Supplier is on the approved list.
   - Lot-specific COA is present, reviewed and within spec.
   - Product temperature is ≤ 40 °F (4.4 °C) or your spec.
   - Packaging is intact and the code date is acceptable.
   - Labeling says "pasteurized," and the establishment number is present.
   - Name what happens if any check fails: hold, reject, or contact the supplier.
3. **Decide on verification activities, and write the reasons down.** Base the choice on:
   - the hazard (*Salmonella*, SAHCODHA);
   - where it is controlled (pasteurization at the supplier, plus the supplier's post-pasteurization sanitation and environmental monitoring);
   - the supplier's performance: its procedures, processes and practices, its food safety history and test results, how it responds to problems, and its regulatory record (warning letters, recalls, import alerts).

   Only you, the receiving facility, can make this decision.
4. **Carry out and record the verification activities.** For this hazard:
   - **Onsite audit by a qualified auditor before first use, then at least annually.** The audit should cover the pasteurization process and its validation, monitoring records and deviations, post-pasteurization handling, sanitation, and environmental monitoring. Choose an auditor who knows egg products. A GFSI-scheme certification audit (SQF, BRCGS, FSSC 22000) may count if the auditor is qualified and the audit covers the hazard. Check that the audit's scope includes this product and line.
   - **Review of supplier records:** lot COAs, and periodically the pasteurization and environmental monitoring records.
   - **Sampling and testing** where it adds assurance, for example periodic *Salmonella* testing of incoming lots at an accredited lab. The supplier may do the sampling and testing, but you must review the results.
   - **Alternative to the annual audit:** you can do other activities, or audit less often, only if you **write a justification** showing they give adequate assurance that the hazard is controlled. The rule also lets you rely, under certain conditions, on a recent inspection of the supplier by a regulatory agency instead of an onsite audit *(standard regulatory knowledge, check 21 CFR 117.435 and current FDA guidance)*. A self-audit is never an alternative.
5. **Corrective action.** Act promptly if you find the supplier is not controlling the hazard. Examples: a positive test, a failed audit, a recall, or a pasteurization deviation. Responses can include holding or rejecting lots, evaluating product you have already used, suspending approval, and checking that the supplier has fixed the root cause before you use it again. Document all of it.
6. **Records.** Keep all of these for at least **2 years**:
   - the written supply-chain program
   - supplier approval documents
   - receiving procedures and receiving records
   - your documented determination of verification activities, including any written justification
   - audit reports, which show the auditor, date, scope, conclusions and the supplier's corrective actions
   - COA and test records, with your review of them
   - corrective action records

   Supplier records reviews should be reviewed by or under your PCQI's oversight as part of normal records verification.

**Special case:** if the supplier were a **qualified facility** (a very small business), modified requirements would apply. You would confirm its status before approval and annually by 31 December, and get written assurance of compliance at least every 2 years. A commercial pasteurized-egg plant is unlikely to qualify, but check.

## 4. Related things to check in your plan

- **Who regulates the supplier.** Liquid egg pasteurization plants are regulated by **USDA-FSIS** under the Egg Products Inspection Act. FDA's PCHF rule still applies to **your** facility, so your supply-chain program for the egg is still needed. Check that the egg carries the USDA inspection mark, and ask for the supplier's pasteurization validation. FSIS sets the pasteurization requirements.
- **Your own facility risks.** The supplier's pasteurization does nothing about *Salmonella* or *Listeria monocytogenes* that get into the egg or product **after** it arrives. These are environmental pathogens. Because your RTE product is exposed and gets no kill step, your hazard analysis probably needs:
  - **sanitation preventive controls**, with **environmental monitoring** (zoned sampling, *Listeria* spp. as an indicator, and corrective actions for positives); and
  - **process controls** for cold holding of the egg and finished product, if temperature abuse could allow growth.
- **Egg allergen.** You control this yourself through labeling and cross-contact controls, not through the supplier.
- **Recall plan.** Because you have hazards requiring preventive controls, you need a written recall plan. Make sure lot traceability for the egg works one step back and one step forward.
- **Reanalysis.** Reanalyze the plan if you change egg suppliers, the supplier changes its process, or you change the product. Reanalyze it at least every 3 years in any case.

## Bottom line for the QA lead

Keep the COA review as part of the program. Replace the self-audit with an **independent onsite audit by a qualified auditor before first use and at least annually**, or with a documented, PCQI-approved written justification for an equivalent alternative. Then put the rest of the program around it: approval, receiving procedures, a documented choice of verification activities, corrective actions and records.

---

*This guidance comes from the FSPCA Preventive Controls for Human Food curriculum (2016) and 21 CFR Part 117, Subpart G. It is training and drafting help, not legal advice. Your PCQI should finalize the program, and you should check the specific citations (e.g. 117.405–117.475) and current FDA supply-chain guidance before you rely on it for compliance.*

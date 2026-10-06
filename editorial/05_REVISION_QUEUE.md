# 05_REVISION_QUEUE.md

## Status

**ACTIVE REVISION QUEUE — ROPE TARGET**

This file controls execution order.

Implementation agents should work from the top of this queue downward.

No later phase should be started if an earlier gate fails.

---

# 0. Global rules

- No commit or push is implied by this queue.
- Do not perform global rewriting.
- Do not add new frameworks.
- Do not change the research question without reopening `03_ARGUMENT_ARCHITECTURE_LOCK.md`.
- Every edit must map to an item in `02_HOPE_TO_ROPE_REPAIR_LEDGER.md`.
- Every consequential claim must comply with `04_CLAIM_EVIDENCE_CONTRACT.md`.
- Preserve a clean compiled baseline in `outputs/` before substantive changes.

---

# Phase 0 — Baseline and repository audit

## Objective
Establish a reproducible current state.

## Tasks
- confirm manuscript source path;
- confirm bibliography path;
- confirm that the manuscript is flat `.tex`;
- identify any external file dependencies from `\input`, `\include`, `\includegraphics`, bibliography commands, or generated tables;
- compile current manuscript without editing;
- record current word count;
- record page count;
- record warnings/errors;
- save baseline PDF to `outputs/`.

## Deliverables
- `outputs/BASELINE_CURRENT.pdf`
- `outputs/BASELINE_AUDIT.md`

## Gate
PASS only if the baseline compiles or the exact blocking dependency is documented.

Status: **PENDING**

---

# Phase 1 — Gate A: argument diagnostic

## Objective
Resolve the five highest-level architecture risks before prose editing.

Ledger items:
- R02
- R03
- R04
- R05
- R23

## Tasks
Create:
`outputs/PHASE1_ARGUMENT_DIAGNOSTIC.md`

It must answer:

1. What exactly is being "recoded"?
2. What is the unit of institutional conversion?
3. Which actors can be shown to perform a reinterpretive/institutional action?
4. What direct evidence supports agency?
5. Which current labor-discipline claims have direct evidence?
6. Which must be downgraded?
7. What exactly is continuous from Samuelson/Hansen to Lucas/Sargent?
8. What exactly changes?
9. Does the present evidence support "same apparatus"?
10. Which claims cannot survive without new research?

No manuscript edits in this phase.

## Gate
PASS only if:
- recoding has one definition;
- institutional conversion has one unit;
- labor-discipline claims are classified;
- continuity/discontinuity is operationalized.

Status: **NEXT**

---

# Phase 2 — Reconstruct Section 4

## Objective
Turn Section 4 into the evidentiary center of the reinterpretation argument.

Ledger items:
- R06
- R07
- R14
- R15
- R17
- R21
- R22
- R23
- R30

## Required structure
1. brief crisis context;
2. measurement controversy;
3. Klein/Greenspan episode;
4. changing concept of macroeconomic constraint;
5. Lucas/Sargent relationship to the interpretive shift;
6. institutional/policy evidence;
7. bounded political-economy implication;
8. continuity/discontinuity synthesis.

## Presumptive cuts
- gold-price figure;
- long Bretton Woods excursion;
- broad civil-rights detour;
- independent de-democratization narrative;
- generic financialization exposition not tied to CU.

## Deliverables
- revised `.tex`;
- `outputs/PHASE2_SECTION4_CHANGELOG.md`;
- `outputs/PHASE2_CLAIM_AUDIT.md`;
- compiled PDF.

## Gate
PASS only if:
- ≥70% of Section 4 directly concerns CU/measurement/interpretation/policy use;
- Greenspan intent is not overstated;
- labor-discipline language complies with the evidence contract;
- continuity/discontinuity is explicit.

Status: **BLOCKED BY PHASE 1**

---

# Phase 3 — Introduction realignment

## Objective
Make the introduction advertise exactly the paper produced by the revised body.

Ledger items:
- R01
- R02
- R08
- R18
- R19
- R24

## Tasks
- define ideological embeddedness;
- state the research question;
- state primary claim;
- state secondary claim;
- introduce utilization-controversy payoff;
- provide one compact analytical bridge:
  theory → measurement → institutional stabilization → policy interpretation;
- provide one method/evidence paragraph;
- retain one roadmap only.

## Deliverables
- revised introduction;
- `outputs/PHASE3_INTRO_ALIGNMENT.md`

## Gate
PASS only if intro and Section 4 use the same definitions of:
- recoding;
- institutional conversion;
- policy use;
- political implication.

Status: **BLOCKED BY PHASE 2**

---

# Phase 4 — Conclusion reconstruction

## Objective
Stop contribution inflation.

Ledger items:
- R20
- R28

## Required conclusion hierarchy
1. answer research question;
2. primary historical contribution;
3. secondary continuity/reorientation finding;
4. ROPE utilization-controy payoff;
5. bounded normative implication.

## Remove as independent contribution claims unless newly demonstrated
- decolonizing economics;
- dependency theory;
- racialized political economy;
- global financial discipline.

## Deliverables
- revised conclusion;
- `outputs/PHASE4_CONCLUSION_ALIGNMENT.md`

## Gate
PASS only if:
- no new literature/framework appears;
- every conclusion claim is demonstrated in the body;
- intro and conclusion describe the same paper.

Status: **BLOCKED BY PHASE 3**

---

# Phase 5 — Upstream compression and balance

## Objective
Free word budget and rebalance evidence toward the measurement core.

Ledger items:
- R09
- R10
- R11
- R25
- R26
- R27

## Tasks
### Section 2
- retain Brookings measurement distinctions;
- add only bounded Brookings/Nourse context if needed;
- remove teleological phrasing.

### Section 3
- compress Hansen/Samuelson;
- eliminate duplicated feedback-loop prose;
- cut international textbook material unless it directly serves the mechanism;
- protect survey infrastructure section.

### Exhibits
- presumptively remove gold-price figure;
- assess McGraw–Hill acquisition table;
- preserve Brookings capacity figure if useful and legally usable.

## Deliverables
- revised full manuscript;
- `outputs/PHASE5_COMPRESSION_LEDGER.md`;
- word-count comparison before/after.

## Gate
PASS only if:
- manuscript is ≤9,500 words inclusive or has a documented route to that target;
- no evidentiary core was sacrificed to preserve contextual digressions.

Status: **BLOCKED BY PHASE 4**

---

# Phase 6 — Claim and source audit

## Objective
Close all factual, definitional, causal, and source-verification risks.

Ledger items:
- R16
- R22
- R29
- R30

## Tasks
- audit capacity terminology;
- complete continuity/discontinuity matrix;
- verify Klein & David;
- verify key quotations;
- audit agency verbs;
- search for unsupported:
  - "discipline";
  - "strategic";
  - "in order to";
  - "purpose";
  - "ruling class";
  - "financial capital";
  - "re-coded";
  - "same apparatus";
- log any remaining new-source needs.

## Deliverables
- `outputs/PHASE6_CLAIM_EVIDENCE_AUDIT.md`
- `outputs/PHASE6_SOURCE_VERIFICATION_LEDGER.md`

## Gate
PASS only if no `[VERIFY-*]` tags remain.

Status: **BLOCKED BY PHASE 5**

---

# Phase 7 — Writing and humanization pass

## Objective
Improve readability without changing substantive architecture.

Ledger item:
- R31

## Rules
- no new claims;
- no new citations except corrections already approved by Phase 6;
- no new framework language;
- remove repetitive rhetorical devices;
- shorten overloaded sentences;
- preserve technical distinctions;
- prefer direct verbs over inflated abstraction;
- reduce formulaic "not X but Y" structures where they add no analytical value.

## Deliverables
- clean prose version;
- `outputs/PHASE7_STYLE_AUDIT.md`

## Gate
PASS only if substantive diff is minimal and all claim strengths remain unchanged.

Status: **BLOCKED BY PHASE 6**

---

# Phase 8 — ROPE compliance pass

## Objective
Prepare the actual submission package.

Ledger item:
- R32

## Tasks
- confirm word count;
- abstract ≈200 words;
- 3–5 keywords;
- ≤5 JEL codes;
- reference-style conversion;
- funding statement;
- competing-interest statement;
- generative-AI declaration;
- acknowledgements;
- quotation style;
- table/figure submission handling;
- permissions checks;
- title reassessment.

## Deliverables
- submission `.tex`;
- compiled submission PDF;
- `outputs/PHASE8_ROPE_COMPLIANCE.md`.

## Gate
PASS only if all formal requirements are satisfied.

Status: **BLOCKED BY PHASE 7**

---

# Phase 9 — Cold-reader simulation

## Objective
Evaluate the revised manuscript as if the revision history were unknown.

## Inputs
- final compiled PDF;
- `00_ROPE_TARGET.md`;
- ROPE submission requirements.

Do **not** provide the HOPE reports to the first cold reader.

Then run a second adversarial review with:
- HOPE reports;
- repair ledger;
- architecture lock.

## Deliverables
- `outputs/PHASE9_COLD_ROPE_REVIEW.md`
- `outputs/PHASE9_ADVERSARIAL_REVIEW.md`
- `outputs/PHASE9_FINAL_DECISION.md`

## Final release gate
Submission is authorized only if:
- no P0 issue remains;
- no more than bounded P1 issues remain;
- cold reader identifies the same primary contribution as the architecture lock;
- no reviewer finds the labor-discipline claim unsupported because it has either been demonstrated or removed;
- the utilization-controv​ersy payoff is visible and persuasive.

Status: **BLOCKED BY PHASE 8**

---

# Current next action

**Run Phase 0, then Phase 1.**

Do not begin manuscript rewriting before `PHASE1_ARGUMENT_DIAGNOSTIC.md` passes Gate A.

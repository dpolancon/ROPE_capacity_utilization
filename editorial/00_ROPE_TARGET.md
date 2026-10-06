# 00_ROPE_TARGET.md

## Status

**ACTIVE JOURNAL TARGET — Review of Political Economy (ROPE)**  
Date locked: **2026-10-06**

This file defines the publication target and submission constraints for the manuscript.

It is not a general style guide. It exists to prevent revision drift.

---

# 1. Target journal

**Review of Political Economy (ROPE)**

Target article type: **Research Article**

The paper is being repositioned after a prior rejection from *History of Political Economy* (HOPE). The ROPE revision should not attempt to reproduce HOPE's preferred genre. It should preserve the strongest history-of-measurement material while sharpening the paper's contemporary political-economy payoff.

---

# 2. Intellectual fit

The paper fits ROPE through the intersection of:

- heterodox macroeconomics;
- history of economic thought;
- historical political economy;
- political economy of macroeconomic measurement;
- institutional analysis of statistical practices;
- the capacity-utilization controversy.

The manuscript should foreground its relevance to current heterodox debates over the measurement and interpretation of capacity utilization.

The paper should **not** depend on the reader accepting a full regulation-theory, dependency-theory, STS, or decolonial framework.

---

# 3. Locked editorial objective

The revision should produce a paper that can be summarized as follows:

> Capacity utilization became an authoritative macroeconomic indicator through historically specific institutional and measurement choices. Competing operationalizations of productive capacity were not interchangeable, and the eventual authority of survey-based measures reflected their embedding in administrative routines as much as technical considerations. During the crisis of postwar demand management, the policy meaning of high utilization shifted toward inflationary constraint. This history matters for contemporary heterodox debates because the statistical object used to adjudicate theories of normal utilization is itself institutionally constructed.

This is the target article.

---

# 4. Submission requirements

For a standard ROPE Research Article:

- maximum manuscript length: **10,000 words inclusive**;
- internal working target: **≤9,500 words inclusive**;
- abstract: approximately **200 words**, unstructured;
- keywords: **3–5**;
- JEL codes: **maximum 5**;
- tables and figures count toward effective journal space;
- tables and figures should ultimately be supplied separately at submission;
- section headings should be concise;
- spelling convention may vary but must be internally consistent;
- single quotation marks should be used except for quotations within quotations;
- long quotations (more than ~40 words) should be set as block quotations;
- author-date reference style must be converted to ROPE house style before submission;
- funding statement required;
- competing-interest/disclosure statement required;
- generative-AI declaration required;
- third-party material and reproduction permissions must be checked where applicable.

Formatting is a final-stage task. Substantive architecture should not be distorted merely to satisfy house style early.

---

# 5. Current repository assumptions

Current repository state:

```text
ROPE_capacity_utilization/
├── manuscript/
│   ├── AK_workingpaper.tex
│   ├── references.bib
│   └── [no external figure assets currently used]
├── editorial/
├── outputs/
└── README.md
```

Important:

- the manuscript is treated as a **flat `.tex` source**;
- do not assume a `figures/` dependency unless the source itself proves otherwise;
- do not create a `sources/` tree merely for organizational symmetry;
- create evidence/source folders only when concrete documentary material is actually added;
- `outputs/` is reserved for compiled PDFs, audits, ledgers, diffs, and review artifacts generated during revision.

---

# 6. Journal-facing contribution hierarchy

## Primary contribution
Institutional history of competing capacity-utilization measurements and the consolidation of survey-based authority.

## Secondary contribution
Historical reinterpretation of utilization from a slack-oriented indicator toward an inflation-constraint indicator during the crisis of postwar demand management.

## Contemporary ROPE payoff
Official utilization series cannot be treated as theoretically neutral objects in current debates about normal utilization.

## Bounded implication
The reinterpretation of utilization participated in a broader reorientation of macroeconomic governance away from discretionary full-employment demand management.

Do not advertise more than this unless the architecture lock is explicitly reopened.

---

# 7. Submission-risk priorities

The paper is most vulnerable if it:

1. claims more political causality than the documentary evidence supports;
2. uses "institutional conversion," "recoding," or "same apparatus" inconsistently;
3. lets general histories of neoliberalism, Bretton Woods, racial politics, or de-democratization displace the history of measurement;
4. fails to show actor-specific evidence for the 1970s reinterpretation;
5. hides the utilization-controversy payoff until the conclusion;
6. exceeds the word limit because contextual material is preserved at the expense of the empirical core.

---

# 8. Final target condition

The paper is ready for submission only when:

- the argument architecture passes all gates in `03_ARGUMENT_ARCHITECTURE_LOCK.md`;
- all P0 and P1 items in `02_HOPE_TO_ROPE_REPAIR_LEDGER.md` are closed or explicitly waived;
- the claims satisfy `04_CLAIM_EVIDENCE_CONTRACT.md`;
- the queue in `05_REVISION_QUEUE.md` reaches the cold-review stage;
- a fresh reader can understand the contribution without knowing the manuscript's HOPE history.

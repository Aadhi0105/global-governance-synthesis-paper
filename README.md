# Informalization in International Banking Regulation: Empirical Data Repository

**Course:** Current Trends in Global Governance | University of St. Gallen  
**Instructor:** Professor Klaus Dingwerth  
**Assignment:** Synthesis Paper (Individual, 60% of grade)  
**Deadline:** 19 May 2026  
**Author:** Aadhitya Srinivasan  

---

## Overview

This repository contains all empirical data, coding sheets, and analysis files supporting the synthesis paper:

> **"Hard Rules, Soft Handshakes: The Structural Entrenchment of Informalization in International Banking Regulation, 1988–2017"**

The paper maps a specific trend — formalization versus informalization — in a specific issue area — international banking regulation — using a multi-indicator empirical framework. This repository serves as the complete audit trail for the data collection, coding, and analysis process.

---

## Research Question

**Primary question:**  
Has the governance of international banking regulation become more informal since the 1988 Basel Accord, and if so, through what institutional mechanisms and with what consequences for compliance?

**Three operationalizable sub-questions:**

- **Q1:** How have the obligation, precision, and delegation scores of key financial governance instruments changed from Basel I (1988) to Basel III (2017)?
- **Q2:** Where compliance has been incomplete — Basel II in the United States, Basel III in the European Union — which causal mechanisms (uploading-stage exclusions or downloading-stage political mobilization) produced the gap?
- **Q3:** Have the four Brummer compliance mechanisms (reputation, market access, institutional synchronization, network pressure) strengthened or weakened across the three Basel Accords?

---

## Core Argument

International banking regulation has undergone systematic informalization since the 1988 Basel Accord — not as a transitional arrangement pending formalization, but as a structurally entrenched architecture. This informalization is characterized by **rising precision alongside stable low legal obligation** (codification without legalization), producing systematic compliance gaps explained by the uploading-downloading disjuncture between international standard-setting and domestic implementation.

---

## Theoretical Framework

### Type (a) — Methodological Papers

| Paper | Role in Analysis |
|---|---|
| Abbott, K.W. et al. (2000). The Concept of Legalization. *International Organization*, 54(3), 401–419. | Framework for Indicator 2 (obligation, precision, delegation scoring) |
| Roger, C.B. (2020). The Move to Informality. In *The Origins of Informality* (pp. 1–20). Oxford University Press. | Framework for Indicator 1 (formal vs. informal binary classification) |
| Dingwerth, K. & Pattberg, P. (2006). Global Governance as a Perspective on World Politics. *Global Governance*, 12(2), 185–203. | Conceptual framing of the governance perspective (Section 1) |
| Hale, T., Held, D. & Young, K. (2013). Gridlock. *Global Policy*, 4(3), 223–235. | Structural explanation for why formalization is politically impossible |
| Faude, B. & Karlsrud, J. (2025). The Institutional Dynamics of Global Governance in Hard Times. *Ethics & International Affairs*, 39(2), 114–129. | Innovation vs. decline evaluative lens (Section 4) |

### Type (b) — Empirical Studies on Financial Governance

| Paper | Role in Analysis |
|---|---|
| Brummer, C. (2012). *Soft Law and the Global Financial System*. Cambridge University Press. | Compliance mechanism framework (Indicator 5; Focal Point C) |
| Verdier, P.-H. (2013). The Political Economy of International Financial Regulation. *Indiana Law Journal*, 88(4), 1405–1474. | Five-objective framework; overall explanatory architecture (Focal Point C; Section 4) |
| Newman, A. & Posner, E. (2016). Structuring Transnational Interests. *Review of International Political Economy*, 23(5), 768–798. | Second-order political effects; contextual framing (Section 1; Indicator 4 logic) |
| Quaglia, L. (2019). The Politics of State Compliance with International 'Soft Law' in Finance. *Governance*, 32(1), 45–62. | Uploading-downloading disjuncture framework (Indicators 3 and 4; Focal Point B) |

---

## Five Indicators

### Indicator 1 — Legal Basis of Governance Institutions
**Framework:** Roger (2020) binary classification  
**Method:** Binary coding (Formal / Informal) based on whether the institution is constituted by a legally binding international agreement  
**Institutions coded:** Basel Committee on Banking Supervision (BCBS), Financial Stability Board (FSB), G20 finance track, International Organization of Securities Commissions (IOSCO), International Monetary Fund (IMF)  
**Time range:** 1974 (BCBS founding) to present  
**Data file:** `outputs/indicator1_roger_binary.csv`

### Indicator 2 — Obligation, Precision, and Delegation Scores
**Framework:** Abbott et al. (2000) three-dimensional legalization framework  
**Method:** Qualitative scoring (High / Medium / Low) on three dimensions applied to Basel I (1988), Basel II (2004), Basel III (2010/2017)  
**Scoring dimensions:**
- *Obligation:* Is the instrument legally binding / subject to ratification?
- *Precision:* How specifically does it define required conduct?
- *Delegation:* What third-party monitoring/enforcement authority exists?  
**Data file:** `outputs/indicator2_abbott_scoring.csv`

### Indicator 3 — Compliance Timing and Content Deviation
**Framework:** Quaglia (2019) operationalization, using BCBS RCAP assessments as primary data  
**Method:** Three-value coding (Compliant / Largely Compliant / Materially Non-Compliant) on two dimensions:
- *Timing:* Did the jurisdiction meet the Basel implementation deadline?
- *Content:* Does the domestic rule deviate from the international standard?  
**Jurisdictions:** United States, European Union, Japan, Canada, Switzerland  
**Standards covered:** Basel III risk-based capital, Liquidity Coverage Ratio (LCR), Net Stable Funding Ratio (NSFR)  
**Primary source:** BCBS RCAP Database (bis.org/bcbs/implementation.htm)  
**Data file:** `outputs/indicator3_rcap_compliance.csv`

### Indicator 4 — Uploading-Stage Participation Structure
**Framework:** Quaglia (2019) disjuncture framework; Young (2012)  
**Method:** Categorization of BCBS consultation participants by institution type and jurisdiction  
**Categories:** Internationally active banks vs. domestically oriented banks; G10 vs. non-G10 jurisdictions  
**Standards covered:** Basel II and Basel III consultation processes  
**Primary sources:** BCBS consultation documents (bis.org); Young (2012) for Basel II record  
**Data file:** `outputs/indicator4_uploading_participation.csv`

### Indicator 5 — Compliance Mechanism Strength
**Framework:** Brummer (2012) four-mechanism compliance theory, assessed against Verdier (2013) five-objective framework  
**Method:** Qualitative assessment of four mechanisms across key standards:
- *Reputation mechanism:* Pointed naming of non-compliance in FSB peer review reports?
- *Market access mechanism:* EU equivalence / US substituted compliance conditioning market access on Basel compliance?
- *Institutional synchronization:* Degree to which domestic regulatory texts mirror international standards?
- *Network pressure:* Frequency of BCBS plenary meetings as proxy for peer-to-peer regulatory interaction  
**Data file:** `outputs/indicator4_uploading_participation.csv`

---

## Five Data Sources

| # | Source | URL | Role |
|---|---|---|---|
| 1 | **BCBS Regulatory Consistency Assessment Programme (RCAP) Database** | bis.org/bcbs/implementation.htm | Primary compliance data (Indicator 3) |
| 2 | **FSB Implementation Monitoring Reports** | fsb.org/publications | Broader reform tracking; cross-validation of Indicator 3; Indicator 5 reputation mechanism |
| 3 | **IMF Financial Sector Assessment Program (FSAP) Reports** | imf.org/publications | Independent cross-check on domestic regulatory quality (Indicator 5) |
| 4 | **BCBS Consultation Documents and Comment Letter Summaries** | bis.org | Uploading-stage participation data (Indicator 4) |
| 5 | **Institutional Charter Documents** | FSB Charter (fsb.org); IMF Articles of Agreement; IOSCO bylaws; G20 Declarations; BCBS mandate letter | Legal basis classification (Indicator 1); obligation scoring (Indicator 2) |

---

## Repository Structure
'''
/
├── README.md
├── .gitignore
├── Data Sources/          # Raw PDFs and downloaded source documents
│   ├── rcap/              # BCBS RCAP assessment reports
│   ├── fsb/               # FSB peer review and monitoring reports
│   ├── imf_fsap/          # IMF FSAP country reports
│   ├── consultation/      # BCBS consultation documents
│   └── charters/          # Institutional charter documents
├── notebooks/             # All Jupyter notebooks (.ipynb)
├── outputs/               # All notebook outputs (CSVs, figures)
│   └── figures/           # Visualizations generated by notebooks
├── codebook/              # Coding rules and decision criteria
├── analysis/              # Focal point write-ups
└── paper/                 # Working paper draft
'''
'''
---

## Section 3 Structure (Empirical Section)

The empirical findings are organized around three focal points, corresponding to the three sub-questions:

### Focal Point A — Legal Form Over Time (~600 words)
Maps Indicators 1 and 2 combined. Tracks the Basel I → II → III sequence across obligation, precision, and delegation dimensions. Establishes the codification-without-legalization pattern empirically.

### Focal Point B — The Compliance Gap (~900 words)
Maps Indicator 3 (RCAP compliance data) and deploys Indicator 4 as the explanatory mechanism. Central empirical cases: US non-implementation of Basel II (pre-2008, documented through secondary sources) and EU's material non-compliance with Basel III (BCBS RCAP, December 2014). Explained through Quaglia's (2019) uploading-downloading disjuncture.

### Focal Point C — Why Compliance Fails Structurally (~700 words)
Maps Indicator 5 selectively. Demonstrates that compliance mechanisms are weak specifically for prudential standards across Verdier's (2013) five-objective framework. Uses this to argue that the compliance gap is structurally produced, not incidental.

---

## Key Empirical Findings (Summary)

### From Indicator 1 (Roger binary):
- IMF: **FORMAL** (Articles of Agreement, 190 signatories)
- BCBS (est. 1974): **INFORMAL** (G10 central bank communiqué)
- IOSCO (est. 1983): **INFORMAL** (organizational bylaws, no treaty)
- FSF (est. 1999): **INFORMAL** (G7 mandate)
- G20 finance track (est. 1999): **INFORMAL** (no charter, no legal personality)
- FSB (est. 2009): **INFORMAL** (G20 mandate + FSB Charter; Charter ≠ treaty)
- **Finding:** Every institution that writes international banking standards is informal. Post-2008 response created zero new formal institutions.

### From Indicator 2 (Abbott et al. scoring):

| Dimension | Basel I (1988) | Basel II (2004) | Basel III (2010/2017) |
|---|---|---|---|
| Obligation | LOW | LOW | LOW |
| Precision | LOW–MEDIUM | HIGH | VERY HIGH |
| Delegation | LOW | LOW–MEDIUM | MEDIUM |

- **Finding:** Codification without legalization — precision rises steeply, obligation stays flat.

### From Indicator 3 (RCAP compliance):

| Jurisdiction | Basel III Overall Rating | Date |
|---|---|---|
| Japan | **Compliant** | October 2012 |
| Switzerland | **Compliant** | June 2013 |
| Canada | **Compliant** | June 2014 |
| United States | **Largely Compliant** | December 2014 |
| European Union | **Materially Non-Compliant** | December 2014 |

- **Finding:** The compliance gradient runs inversely to power — the jurisdictions that dominated standard-setting showed the worst compliance records.

---

## Coding Protocol Summary

Full coding rules are in `codebook/coding_protocol.md`. Key principles:

- **Indicator 1:** An institution is FORMAL if and only if it is constituted by a legally binding international agreement (treaty, convention, or equivalent). A Charter that is not a treaty = INFORMAL.
- **Indicator 2:** Obligation is LOW if the instrument uses non-binding language and was not subject to legislative ratification. Precision is scored on the specificity of operative provisions. Delegation is scored on whether an independent third party holds interpretive or enforcement authority.
- **Indicator 3:** BCBS RCAP ratings are used directly without re-coding. For Basel II (US, pre-2008): documented through Quaglia (2019) and Young (2012) as secondary sources, since RCAP was only established in 2012.
- **Indicator 4:** Consultation participants are categorized as internationally active bank, domestically oriented bank, banking association, public authority, or other.
- **Indicator 5:** Each mechanism is coded as Strong / Moderate / Weak based on documentary evidence. Comparative assessment across Verdier's five objective categories.

---

## Citation Format

APA 7th edition throughout. References excluded from the 4,500-word count per assignment instructions.

---

## Contact

For questions about data sources or coding decisions, refer to the `codebook/coding_protocol.md` file.

*Last updated: May 2026*
# The Informal Architecture of International Banking Regulation: Codification, Compliance Gaps, and Structural Entrenchment, 1988–2017

**Author:** Aadhitya Tejaswin Prakash Sridevi  
**University of St. Gallen (HSG)** · Current Trends in Global Governance  
**Instructor:** Prof. Klaus Dingwerth · **Submitted:** 18 May 2026

## Read the research

**[Read the synthesis paper (PDF, 17 pages)](paper/The_Informal_Architecture_of_International_Banking_Regulation.pdf)**

Selected short writing samples:

- **[Hard Rules, Soft Handshakes](writing_samples/Hard_Rules_Soft_Handshakes.pdf)** — How Global Financial Governance Went Informal (2 pages).
- **[Who Owns the World’s Money?](writing_samples/Who_Owns_the_Worlds_Money.pdf)** — Global Governance and the Making of Cross-Border Payment Policies (3 pages).

This academic research portfolio examines international banking regulation, financial standard-setting, and domestic implementation. It brings together the synthesis paper, two shorter analytical essays, and the supporting notebooks, coded data, figures, and source documents. The public paper copy retains the submitted analysis and academic attribution, with the student number removed.

## Research question and argument

How has informality become entrenched in international banking regulation since the 1988 Basel Accord, and what does it mean for compliance?

The paper argues that the Basel sequence combines increasing technical precision with persistently low international legal obligation: **codification without legalization**. It examines the gap between international standard-setting and domestic implementation, and assesses how reputation, market access, institutional synchronization, and regulatory networks support or constrain compliance.

The research combines institutional classification, qualitative coding, descriptive comparisons of historical RCAP assessments, and synthesis of the financial-governance literature. These are historical, interpretive findings rather than causal estimates or a current assessment of jurisdictions’ compliance.

## Empirical framework and materials

| Indicator | Focus and framework | Notebook | Coded output |
|---|---|---|---|
| 1 | Institutional legal basis: formal/informal classification following Roger (2020) | [Legal basis](Notebooks/indicator1_roger_binary.ipynb) | [Institutional inventory](outputs/indicator1_roger_binary.csv) |
| 2 | Obligation, precision, and delegation across Basel I–III, following Abbott et al. (2000) | [Legalization](Notebooks/indicator2_abbott_scoring.ipynb) | [Accord scoring](outputs/indicator2_abbott_scoring.csv) |
| 3 | Historical Basel III risk-based capital compliance in Japan, Switzerland, Canada, the United States, and the European Union | [RCAP compliance](Notebooks/indicator3_rcap_compliance.ipynb) | [Jurisdiction ratings](outputs/indicator3_rcap_compliance.csv) · [Component ratings](outputs/indicator3_rcap_components.csv) |
| 4 | Basel II and III consultation participation by respondent type, interpreted through the standard-setting/implementation gap | [Consultation participation](Notebooks/indicator4_uploading_participation.ipynb) | [Participation data](outputs/indicator4_uploading_participation.csv) |
| 5 | Brummer’s (2012) four compliance mechanisms for Basel III prudential standards, compared across Verdier’s (2013) governance objectives | [Compliance mechanisms](Notebooks/indicator5_brummer_mechanisms.ipynb) | [Mechanism assessments](outputs/indicator5_brummer_mechanisms.csv) · [Comparison matrix](outputs/indicator5_mechanism_matrix.csv) |

The paper develops three connected themes: legal form across the Basel sequence; the gap between standard-setting and domestic compliance; and variation in compliance mechanisms across financial-governance objectives. Full references are included in the paper.

## Repository structure

```text
.
├── README.md
├── .gitignore
├── paper/
│   └── The_Informal_Architecture_of_International_Banking_Regulation.pdf
├── writing_samples/
│   ├── Hard_Rules_Soft_Handshakes.pdf
│   └── Who_Owns_the_Worlds_Money.pdf
├── Data Sources/
│   ├── Charters/
│   ├── consultation/
│   ├── fsb/
│   └── rcap/
├── Notebooks/
│   ├── indicator1_roger_binary.ipynb
│   ├── indicator2_abbott_scoring.ipynb
│   ├── indicator3_rcap_compliance.ipynb
│   ├── indicator4_uploading_participation.ipynb
│   └── indicator5_brummer_mechanisms.ipynb
└── outputs/
    ├── figures/
    ├── indicator1_roger_binary.csv
    ├── indicator2_abbott_scoring.csv
    ├── indicator3_rcap_compliance.csv
    ├── indicator3_rcap_components.csv
    ├── indicator4_uploading_participation.csv
    ├── indicator5_brummer_mechanisms.csv
    └── indicator5_mechanism_matrix.csv
```

## Reading and reproducing the analysis

Start with the paper for the argument and interpretation. Use the indicator table above to trace each part of the analysis to its notebook and CSV outputs; [figures](outputs/figures/) are also available separately.

The repository includes institutional charters, a BCBS consultation document, FSB peer reviews, and five RCAP assessment reports under [Data Sources](Data%20Sources/). Other literature and sources discussed in the paper are identified in its references; they are not all archived here.

To inspect or rerun the analysis, download or clone the repository and open the notebooks in Jupyter with a Python environment containing their imported libraries. Preserve the existing directory names and run with `Notebooks/` as the working directory where relative paths are used. Review cells before running: execution can regenerate files in `outputs/`. The notebooks retain their saved outputs; this presentation update does not constitute an independent replication or source-data audit.

## Suggested citation

Aadhitya Tejaswin Prakash Sridevi. (2026). *The Informal Architecture of International Banking Regulation: Codification, Compliance Gaps, and Structural Entrenchment, 1988–2017*. Synthesis paper, University of St. Gallen, Current Trends in Global Governance.

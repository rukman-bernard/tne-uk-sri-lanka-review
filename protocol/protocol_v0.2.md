# Review Protocol v0.2 — Transnational Education & Framework Mapping

**Lead Author:** R. B. Fernando Pulle  
**Institutional Context:** Independent researcher, Negombo, Sri Lanka  
**Date:** 02 Nov 2025  
**Version:** 0.2 (Stable)

---

## 1. Background & Rationale
This review investigates how UK higher-education regulatory frameworks (OfS, QAA, DfE, etc.) interface with Sri Lanka’s national frameworks (SLQF, TVEC, MOHE). It aims to produce a transparent evidence base to inform cross-border programme design and recognition.

---

## 2. Objectives & Research Questions
- How are qualification levels and credit frameworks defined across UK and Sri Lankan systems?
- What oversight mechanisms exist for TNE, validation, and franchising?
- How do exit awards and recognition pathways align between jurisdictions?

---

## 3. Eligibility Criteria

### Inclusion
- Official or statutory publications from listed UK and Sri Lankan authorities.
- Documents that define or regulate qualifications, credit, or quality assurance.
- English-language full texts (PDF/HTML).
- Current versions in force as of 2025.

### Exclusion
- Opinion articles, press releases, and news posts.
- Non-HE or non-UK/Sri Lankan materials.
- Superseded versions unless directly referenced.
- Sources lacking identifiable publication year or authority.

---

## 4. Information Sources
- **Fixed (UK):** OfS, QAA, DfE, UK ENIC/ECCTIS, UUK, SCQF Partnership, SFC, Welsh Government, NI Department for the Economy, Ofqual.  
- **Context (Sri Lanka):** SLQF/UGC, MOHE, TVEC, British Council Sri Lanka.

---

## 5. Search Strategy
Search conducted using Google advanced operators.  
Exact queries archived in `queries_used.txt` (G1–G8).  
Example:  
> site:qaa.ac.uk ("FHEQ" OR "qualification descriptors" OR "levels")

No date limit; relevance judged by in-force status as of 2025.

---

## 6. Screening & Selection
- Each item logged in `screening_log.csv` with DocID, Source, Title, Year, Status, ReasonCode.
- PDFs stored under `evidence/<SRC>/` with naming convention `<DocID>__<slug>__<Year>.pdf`.
- Borderline and Excluded items retained for audit.
- Second-reader random check ≈15% + all borderline/excluded items.
- Disagreements resolved and summarised in `agreement_summary.csv`.

---

## 7. Data Extraction
- Fields defined in `evidence_table.csv`:  
  `DocID, Title, Year, Jurisdiction, DocType, PrimaryFocus, KeyProvisions, Levels/Credits, ExitAwards, TNE/PartnerRules, Recognition/Entry(ENIC), Citations, UseInReview.`

---

## 8. Quality Assurance & Risk
- Random sampling and dual verification.  
- Risks: document updates, broken links, missing metadata, inconsistent pagination.

---

## 9. Limitations
The review includes only documents publicly available as of 2025 and may not capture confidential or internal guidance.

---

## 10. Version History
| Version | Date | Description |
|----------|------|-------------|
| v0.2 | 2025-11-02 | First full protocol aligned with Methods v0.1 — includes UK & SL context, formal inclusion/exclusion, and QA sampling plan. |

---

*End of Protocol v0.2*

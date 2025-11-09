# Human Clarity Institute – Digital Life Survey 2025
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17393881.svg)](https://doi.org/10.5281/zenodo.17393881)

## Source and Citation

**Official site:** [https://humanclarityinstitute.com](https://humanclarityinstitute.com)  
**Dataset page:** [https://humanclarityinstitute.com/datasets/digital-life-2025/](https://humanclarityinstitute.com/datasets/digital-life-2025/) 

**Full reports using this dataset:**  
- [Digital Fatigue & Energy – Full Report](https://humanclarityinstitute.com/reports/digital-fatigue-and-energy-full-report/)  
- [Digital Trust – Full Report](https://humanclarityinstitute.com/reports/digital-trust-full-report/)  
- [Coping & Wellbeing – Full Report](https://humanclarityinstitute.com/reports/coping-and-wellbeing-full-report/)  
- [Values Discovery – Full Report](https://humanclarityinstitute.com/reports/values-discovery-full-report/)  

**License:** Creative Commons Attribution 4.0 (CC BY 4.0)  
Please cite as: *Human Clarity Institute (2025). Digital Life 2025 Dataset.*


**Dataset ID:** HCI_2025_DigitalLifeSurvey  
**Version:** 1.0  
**Date Published:** 2025-10-21  
**Data Collected:** September 2025   
**Sample Size:** N = 1,003  
**Geographies:** United Kingdom, United States, Canada, Australia, Ireland, New Zealand
**Survey Platform:** Google Forms + Prolific  
## Description and Purpose  

The Digital Life Survey 2025 explores how people experience attention, energy, trust, and focus in an always-connected world.  
It includes 1,003 anonymised responses from participants in the United Kingdom, United States, Canada, Australia, Ireland, and New Zealand.  
Respondents answered questions on screen-time habits, digital fatigue, values alignment, and levels of trust across online environments such as social media, news sites, and search platforms.  
Findings from this dataset underpin several Human Clarity Institute reports — *Values vs Noise*, *Why Can’t I Focus*, *Digital Fatigue & Energy*, *Digital Trust*, and *Coping & Wellbeing* — providing the quantitative foundation for each report’s hero statistics.

## Structure of the Dataset  

Each row represents one participant’s complete response.  
Each column corresponds to a single survey variable.  

**Variable groups include:**  
- **Demographics** – country, age group, gender identity, employment status.  
- **Digital Behaviour** – average hours online, devices used, purpose of use, multitasking frequency.  
- **Fatigue & Energy** – post-session energy levels, signs of digital tiredness, recovery activities.  
- **Trust & Information** – perceived reliability of different online environments, self-reported confidence in identifying misinformation.  
- **Values Alignment** – extent to which online actions reflect personal values, perceived conflict between values and digital habits.  
- **Wellbeing Indicators** – focus quality, motivation, satisfaction after digital sessions.  
- **Open-Ended Questions** – short free-text reflections about digital balance and clarity.

All direct identifiers present in the raw exports (e.g., PROLIFIC_PID, SESSION_ID, timestamps, IP addresses) have been removed from this public dataset.  
Columns that could enable re-identification (such as country of birth when highly specific, or detailed language variants) were generalised or deleted.  
The released CSV is fully de-identified and compliant with open-data ethical standards.  
Missing data are encoded as blank cells; explicit responses such as “Prefer not to say” are retained as text.


---

## Data Integrity Note

This dataset has undergone a full internal audit by the Human Clarity Institute (HCI) to confirm the accuracy, completeness, and consistency of all source data and metadata.  
All validation steps were completed as part of HCI’s 2025 data audit initiative to ensure long-term integrity across the Institute’s open datasets.

No alterations were made to survey responses or core data values during the audit.  
Minor adjustments (e.g., metadata formatting, schema alignment, DOI cross-referencing) were applied only where required for cross-platform consistency between GitHub, Zenodo, and the HCI website.

This dataset is therefore considered **final and integrity-verified** as of the 2025 audit completion date.

---

## Data Verification Method (Legacy Audit Process)

This dataset was part of HCI’s first internal verification cycle, conducted before the rollout of the Institute’s standardised 2026 data-validation framework.  
The verification process for this dataset was therefore **manual and analytical**, focusing on internal accuracy and thematic integrity rather than automated schema testing.

### Process Summary
- All survey responses were **cross-checked against original collection files** for duplication or structural errors.  
- **Pivot-table analysis** in Excel was used to identify response clustering patterns and confirm consistency across categorical data.  
- Thematic clusters (e.g., “focus erosion”, “digital fatigue”, “trust degradation”) were **derived manually** through qualitative review and cross-tabulation rather than algorithmic grouping.  
- Final data tables were reconciled with metadata to ensure correct alignment of variable names, labels, and count totals.

This legacy verification process differs from HCI’s current workflow, which now employs:
1. Automated schema validation scripts,  
2. Version-locked dataset manifests, and  
3. A reproducible integrity-reporting pipeline used across all new datasets.

While the current dataset remains accurate and stable, it is retained here as a **reference example of HCI’s early verification methodology**.








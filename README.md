# Digital Life 2025 (Dataset, n = 1,003)

A cross-national behavioural dataset measuring attention, trust, values alignment, fatigue, and wellbeing in digitally saturated environments across six English-speaking countries.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17393880.svg)](https://doi.org/10.5281/zenodo.17393880)

**Latest version:** v2.0 — 2025-12-15  
**License:** CC-BY-4.0

**Dataset page:**  
https://humanclarityinstitute.com/datasets/digital-life-2025/

**Data summary pages:**  
https://humanclarityinstitute.com/data/digital-trust-data-2025/  
https://humanclarityinstitute.com/data/purpose-meaning-data-2025/

**Dashboard:**  
https://humanclarityinstitute.com/data-dashboard/

---

## Key Features

- 1,003 anonymised responses collected across six English-speaking countries  
- Measures attention, trust, digital fatigue, values alignment, and wellbeing  
- Canonical machine-readable tokens and standardised multi-select formatting  
- Fully de-identified and aligned with open behavioural data standards  
- Part of the **Human–AI Experience 2025** longitudinal data series

---

## Files Included

| Filename | Description |
|---------|-------------|
| **Digital_Life_raw20251215.csv** | Raw dataset (PII removed). Original column order; no transformations applied. |
| **Digital_Life_clean20251215.csv** | Clean, machine-readable dataset. Canonical tokens, standardised multi-selects, minimal text cleaning. |
| **Digital_Life_dictionary20251215.csv** | Full variable dictionary with definitions, types, and allowed values. |
| **sha256.txt** | SHA-256 checksums for all files in this release (raw, clean, dictionary, README). |
| **README.md** | Documentation describing dataset purpose, provenance, file structure, and citation. |

---

## Provenance & Data Collection

Data collected in **10 September 2025** via **Prolific** as part of HCI’s Human–AI Experience research programme.  
Participants provided **explicit consent** for anonymised open publication.

### Sampling & Quality Controls

- **Final n:** 1,003  
- **Countries:** United Kingdom, United States, Canada, Australia, Ireland, New Zealand  
- **Eligibility:** Fluent English speaking  
- **Compensation:** £7.38/hr GBP (average)  
- **Approval-rate filter:** None applied  
- **Attention checks:** None  
- **AI-deception traps:** None  
- **Anonymisation:** Prolific IDs and timestamps removed before publication  

---

## Data Structure (Summary)

| Variable | Type | Description |
|----------|------|-------------|
| country | categorical | Country of residence (ISO-style codes) |
| age_group | categorical | Participant age bracket |
| average_daily_screen_time | categorical | Self-reported average daily time spent online |
| digital_fatigue_level | ordinal | Reported level of tiredness after extended online use |
| values_alignment_online | ordinal | Perceived alignment between online behaviour and personal values |
| trust_in_online_information | ordinal | Trust in information encountered online |
| ... | ... | ... |

Multi-select formatting:
Stored as semicolon-delimited canonical tokens, e.g.:
value_one;value_two;value_three

Open-text fields:
Minimal cleaning applied (trim + newline removal).
Raw participant meaning preserved exactly.

---

## Related Datasets (Human–AI Experience 2025 Series)

| Dataset | DOI |
|--------|------|
| **Focus and Distraction 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17394086.svg)](https://doi.org/10.5281/zenodo.17394086) |
| **Human Values, Purpose & Meaning 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17705733.svg)](https://doi.org/10.5281/zenodo.17705733) |
| **Digital Trust 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17717450.svg)](https://doi.org/10.5281/zenodo.17717450) |
| **Emotion, Identity & Creativity in the Age of AI 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17653906.svg)](https://doi.org/10.5281/zenodo.17653906) |
| **AI Safety, Risk Perception & Boundary Behaviour 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17782046.svg)](https://doi.org/10.5281/zenodo.17782046) |

---

## Related Reports

- **Why Can’t I Focus?**  
  https://humanclarityinstitute.com/reports/why-cant-i-focus-full-report/

- **Values vs Noise**  
  https://humanclarityinstitute.com/reports/values-vs-noise-full-report/

---

## License

This dataset is released under the **Creative Commons CC-BY-4.0 License**.  
You may copy, modify, distribute, or build upon the material for any purpose, including commercial use, provided appropriate credit is given.

---

## Recommended Citation

### APA
Human Clarity Institute. (2025). *Digital Life Survey 2025 (Dataset).* https://doi.org/10.5281/zenodo.17393880

### BibTeX
@dataset{HCI_DigitalLife_2025,
  author    = {Human Clarity Institute},
  title     = {Digital Life Survey 2025},
  year      = {2025},
  publisher = {Zenodo},
  version   = {v2.0},
  doi       = {10.5281/zenodo.17393880},
  url       = {https://doi.org/10.5281/zenodo.17393880}
}

---

## Version History

| Version | Date | Change |
|---------|------------|---------|
| v2.0 | 2025-12-15 | Upgraded to machine-readable standard; added canonical tokens; added dictionary; updated README. |
| v1.0 | 2025-10-20 | Initial release |

---

## Contact

For questions, collaboration opportunities, or media enquiries:

- **Website:** https://humanclarityinstitute.com  
- **Email:** info@humanclarityinstitute.com  

HCI is an independent research institute documenting the human experience of the AI era.


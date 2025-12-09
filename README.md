# Emotion, Identity & Creativity in the Age of AI (Dataset, n = 507)

A cross-sectional dataset (n = 507) capturing how AI use influences emotional states, personal identity, authenticity, creative originality, cognitive depth, and overall meaning-making in everyday life.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17653906.svg)](https://doi.org/10.5281/zenodo.17653906)

**Latest version:** v3.0 — 2025-12-09  
**License:** CC-BY-4.0

**Dataset page:**  
https://humanclarityinstitute.com/datasets/emotion-identity-creativity-in-the-age-of-ai-dataset/

**Data summary page:**  
https://humanclarityinstitute.com/data/emotion-identity-creativity-in-the-age-of-ai-data-summary-2025/

**Dashboard:**  
https://humanclarityinstitute.com/data-dashboard/

---

## Key Features

- Measures emotional impact, identity alignment, authenticity, and creativity shifts linked to AI use  
- Includes cognitive meaning-making indicators and perceived influence on thinking and values  
- Clean, machine-readable variables with canonical snake_case names  
- Two open-text fields capturing lived experience in participants' own words  
- Part of the **Human–AI Experience 2025** longitudinal data series

---

## Files Included

| Filename | Description |
|---------|-------------|
| **Emotion_Identity_Creativity_2025_raw20251119.csv** | Raw dataset (PII removed). Original column order; no transformations applied. |
| **Emotion_Identity_Creativity_2025_clean20251119.csv** | Clean, machine-readable dataset. Canonical tokens, validated scales, and minimal text cleaning. |
| **Emotion_Identity_Creativity_2025_data_dictionary.csv** | Full variable dictionary with definitions, types, and allowed values. |
| **sha256.txt** | SHA-256 checksum references for all files in the release. |
| **README.md** | Full documentation and citation guidance. |

---

## Provenance & Data Collection

Data were collected on **19 November 2025** via **Prolific** as part of the Human Clarity Institute’s Human–AI Experience research programme.  
Participants provided **explicit informed consent** for anonymised open publication.

### Sampling & Quality Controls

- **Final n:** 507  
- **Countries:** UK, US, Canada, Australia, New Zealand, Ireland  
- **Eligibility:** Fluent English  
- **Compensation:** £10.11/hour average reward (GBP)  
- **Approval-rate filter:** None  
- **Attention checks:** None  
- **AI deception traps:** None  
- **Anonymisation:** Prolific IDs and all timestamps removed prior to release  

---

## Data Structure (Summary)

| Variable | Type | Description |
|----------|------|-------------|
| consent | categorical | Explicit participant consent (yes). |
| work_status | categorical | Employment status. |
| ai_tool_use | categorical | Whether participant uses AI tools. |
| ai_tool_use_frequency | categorical | Frequency of AI tool use. |
| ai_emotion_influence | numeric | Extent AI affects emotional state. |
| ai_identity_mine_vs_ai | numeric | AI influence on sense of self. |
| ai_creativity_spark_ideas | numeric | AI effects on creative originality. |
| ai_thinking_focus_attention | numeric | AI impact on thinking and attention. |
| ai_validation_check_thoughts | numeric | Reliance on AI for thought validation. |
| ai_meaning_tasks_feel | numeric | AI’s influence on personal meaning-making. |
| ai_effects_on_emotions | text | Open-text description of emotional effects. |
| ai_effects_on_creativity | text | Open-text description of creative effects. |
| age_group | categorical | Age categories (18_24–over_65). |
| country | categorical | Participant country (au, ca, ie, nz, uk, us). |
| gender | categorical | Gender identity. |

**Multi-select formatting:**  
*(No multi-select variables in this dataset.)*

**Open-text fields:**  
Minimal cleaning (trim + newline removal).  
Raw participant wording preserved.

---

## Related Datasets (Human–AI Experience 2025 Series)

| Dataset | DOI Badge |
|--------|-----------|
| **Digital Life 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17393880.svg)](https://doi.org/10.5281/zenodo.17393880) |
| **Focus & Distraction 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17394087.svg)](https://doi.org/10.5281/zenodo.17394087) |
| **Human Values, Purpose & Meaning 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17705733.svg)](https://doi.org/10.5281/zenodo.17705733) |
| **Digital Trust 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17717450.svg)](https://doi.org/10.5281/zenodo.17717450) |
| **AI, Work & Human Identity 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17604671.svg)](https://doi.org/10.5281/zenodo.17604671) |
| **AI Safety, Risk Perception & Boundary Behaviour 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17782046.svg)](https://doi.org/10.5281/zenodo.17782046) |

---

## Related Reports

- **Values vs Noise**  
  https://humanclarityinstitute.com/reports/values-vs-noise-full-report/

- **Digital Fatigue & Energy**  
  https://humanclarityinstitute.com/reports/digital-fatigue-and-energy-full-report/

---

## License

This dataset is released under the **Creative Commons CC-BY-4.0 License**.  
You may copy, modify, distribute, or build upon the material for any purpose, including commercial use, provided appropriate credit is given.

---

## Recommended Citation

### **APA**  
Human Clarity Institute. (2025). *Emotion, Identity & Creativity in the Age of AI (Dataset).* https://doi.org/10.5281/zenodo.17653906

### **BibTeX**
    
    @dataset{hci_emotion_identity_creativity_2025,
      author       = {Human Clarity Institute},
      title        = {Emotion, Identity \& Creativity in the Age of AI},
      year         = {2025},
      publisher    = {Zenodo},
      version      = {v3.0},
      doi          = {10.5281/zenodo.17653906},
      url          = {https://doi.org/10.5281/zenodo.17653906}
    }

---

## Version History

| Version | Date | Change |
|---------|------------|---------|
| v3.0 | 2025-12-09 | Cleaned dataset; corrected variable names; updated README; added machine-readable structure |
| v2.0 | 2025-11-19 | Internal updates (not publicly released) |
| v1.0 | 2025-11-19 | Initial release |

---

## Contact

For questions, collaboration opportunities, or media enquiries:

- **Website:** https://humanclarityinstitute.com  
- **Email:** info@humanclarityinstitute.com  

HCI is an independent research institute documenting the human experience of the AI era.

# ARISE

**Awakening & Respiratory Integration for Safe Extubation**

[![Version](https://img.shields.io/badge/version-3.7.2-teal.svg)](https://github.com/shoyu21/ARISE)
[![License](https://img.shields.io/badge/license-Proprietary-red.svg)](LICENSE)
[![Clinical Tool](https://img.shields.io/badge/type-Clinical%20Decision%20Support-blue.svg)]()

---

## Overview

ARISE is an evidence-synthesized clinical decision support tool designed to assist ICU healthcare professionals in making informed decisions about ventilator weaning and extubation readiness.

### Key Features

- **Three Assessment Modes**
  - **Quick SAT** - Spontaneous Awakening Trial screening 
  - **Quick SBT** - Spontaneous Breathing Trial assessment
  - **Full Assessment** - Comprehensive pre-extubation evaluation 

- **Evidence-Based Decision Support**
  - Integrated evidence tooltips with citations
  - Risk stratification with validated thresholds
  - Special population considerations (COPD, Heart Failure, Obesity, Elderly)

- **Auto-Calculated Parameters**
  - BMI calculation
  - P/F ratio
  - RSBI (Rapid Shallow Breathing Index)
  - GCS total score
  - APACHE II score integration

- **Live-Updating Interface**
  - Real-time conclusion bars that update as criteria are checked
  - Immediate visual feedback without requiring button clicks
  - Color-coded status indicators

- **Mobile-Friendly Design**
  - Responsive interface for bedside use
  - Works on smartphones and tablets
  - No installation required

---

## Access

**Live Tool:** [https://shoyu21.github.io/ARISE](https://shoyu21.github.io/ARISE)

### Mobile Access
1. Open the link above on your mobile device
2. Add to Home Screen for app-like experience:
   - **iOS:** Share → Add to Home Screen
   - **Android:** Menu → Add to Home Screen

---

## Clinical Use

### Important Notice

⚠️ **ARISE is a clinical decision support tool only and does not replace clinical judgment.**

This tool is designed to:
- Assist in systematic assessment for ventilator liberation
- Provide evidence-based guidance for clinical decisions
- Support ICU liberation protocols (SAT/SBT coordination)

This tool does NOT:
- Provide medical diagnoses
- Prescribe treatments
- Replace the expertise of qualified healthcare professionals

All clinical decisions remain the responsibility of the treating healthcare team.

### Intended Users
- ICU Nurses
- Respiratory Therapists
- Intensivists and ICU Physicians
- Advanced Practice Nurses (APNs)

---

## Data Privacy

**ARISE does NOT collect, store, or transmit patient data.**

- All calculations are performed locally in your browser
- No data is sent to external servers
- No user accounts or login required
- No cookies or tracking

For detailed privacy information, see [PRIVACY.md](PRIVACY.md).

---

## Evidence Base & Resources

ARISE synthesizes evidence from multiple authoritative sources to provide validated clinical thresholds and recommendations.

### Institutional Protocol
- **MICU NUH Awake & Breathe Protocol** (June 2025) — Foundational framework for SAT/SBT criteria and workflow integration

### Evidence Synthesis
- **[Consensus](https://consensus.app)** — AI-powered academic search engine used for systematic evidence retrieval and validation of clinical parameters

### Key Literature Sources
Evidence integrated into ARISE includes findings from:

| Topic | Key References |
|-------|----------------|
| Weaning Guidelines | Boles 2007 (ERS/ATS); MacIntyre 2001; AARC 2024 |
| RSBI Validation | Yang & Tobin 1991; Meta-analyses 2023 |
| Extubation Failure Predictors | Thille 2013; Taran 2022; Li 2022 |
| Pain Assessment (CPOT) | Gélinas 2006; Zhai 2020 |
| Sedation (RASS/PADIS) | Sessler 2002; PADIS Guidelines 2018 |
| Post-Extubation Support | Hernández 2016, 2022; Boscolo 2023 |
| Special Populations | Goharani 2019 (COPD); De Jong 2024 (Obesity); Thille 2016 (Heart Failure) |
| Risk Scoring | APACHE II; ExPreS Score; RISC Score |

All evidence citations are provided within the tool's tooltips for point-of-care reference.

---

## Acknowledgments

We gratefully acknowledge the following resources and contributions:

- **Medical Intensive Care Unit, National University Hospital** — For the Awake & Breathe Protocol that forms the clinical foundation of this tool
- **Consensus** — For enabling efficient evidence synthesis through AI-powered academic search
- **The broader critical care research community** — Whose published work makes evidence-based tools like ARISE possible

---

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 3.7.2 | Jan 2025 | GCS and CPOT converted to dropdown selects with clinical descriptors; Oxygenation section renamed to Ventilator Settings; PaO2 moved to Post-SBT ABG as optional field; Header updated to acknowledge MICU Awake & Breathe Protocol 2025 and Consensus |
| 3.7.1 | Dec 2024 | All input fields blanked with placeholders; calculated displays show "—" until values entered; dropdown defaults to "Select..."; prevents user confusion from preset values |
| 3.7.0 | Dec 2024 | Live-updating conclusion bars, APACHE II streamlining, UTF-8 encoding fixes |
| 3.6.0 | Dec 2024 | Clinical feedback integration, enhanced evidence tooltips |
| 3.5.x | Nov 2024 | Three-mode system, evidence synthesis |
| 3.0.x | Oct 2024 | Complete redesign with tab-based results |

---

## License

**ARISE is proprietary software. All rights reserved.**

- ✅ Clinical use is permitted
- ✅ Academic citation is permitted (see [CITATION.cff](CITATION.cff))
- ❌ Redistribution is not permitted
- ❌ Modification is not permitted
- ❌ Commercial use requires licensing

See [LICENSE](LICENSE) for full terms.

---

## Citation

If you reference ARISE in academic work, please cite:

```
ARISE: Awakening & Respiratory Integration for Safe Extubation
Clinical Decision Support Tool, Version 3.7.2
https://github.com/shoyu21/ARISE
```

---

## Disclaimer

See [DISCLAIMER.md](DISCLAIMER.md) for full clinical and legal disclaimers.

---

## Contact

For inquiries regarding:
- Commercial licensing
- Institutional deployment
- Research collaboration
- Bug reports and feedback

Please open an issue in this repository or contact [ccx2211@gmail.com].

---

*ARISE — Evidence-Synthesized ICU Liberation Decision Support*

Copyright © 2024-2025. All Rights Reserved.

# Privacy and Access Control (PAC): Systems Security & Privacy Preference Modeling

Author: Rishindra Mateti  
Department of Computer Science, Wright State University  
Email: mateti.7@wright.edu | research@rishindramateti.com  

---

## Overview

This repository contains academic research manuscripts, seminar presentations, and critical literature reviews conducted as part of advanced graduate studies in Privacy and Access Control (PAC) at Wright State University.

The collection investigates systems-level security vulnerabilities within mobile operating system task schedulers alongside empirical human-centric privacy preference elicitation and spatial location disclosure policies.

---

## Repository Structure

```text
Privacy-and-Access-Control-Analysis/
|
|-- PAC PPT.pdf                                     # Seminar presentation: Android task mechanism vulnerabilities
|-- PAC_PR1_Personality_Privacy_Preferences.pdf     # Literature review: personality-based privacy elicitation
|-- PAC_PR2_Location_Sharing_Privacy.pdf            # Literature review: context factors in location disclosure
|-- README.md                                       # Repository documentation and analysis
`-- .gitignore                                      # Build artifact exclusions
```

---

## Document Overviews & Technical Scope

### 1. Privilege Leakage and Information Stealing through the Android Task Mechanism
- **File:** `PAC PPT.pdf`
- **Authors:** Megha Mathew, Rishindra Mateti
- **Focus Areas:**
  - Operating system task scheduling and Activity stack lifecycle in Android.
  - Analysis of attack surfaces utilizing task affinities (`taskAffinity`), launch modes (`singleTask`, `singleInstance`), and back-stack hijacking.
  - Information stealing techniques without requiring elevated system permissions.
  - Structural mitigations, manifest configuration audits, and OS runtime boundary enforcements.

### 2. Measuring Personality for Automatic Elicitation of Privacy Preferences
- **File:** `PAC_PR1_Personality_Privacy_Preferences.pdf`
- **Author:** Rishindra Mateti
- **Focus Areas:**
  - Automated prediction and elicitation of user privacy profiles to alleviate configuration fatigue.
  - Evaluation of the Five-Factor Model (FFM / Big Five: Openness, Conscientiousness, Extraversion, Agreeableness, Neuroticism) as predictive features.
  - Critical analysis of machine learning clustering techniques applied to survey data, identification of class imbalance pitfalls, and generalizability limitations.

### 3. Deriving Privacy Settings for Location Sharing
- **File:** `PAC_PR2_Location_Sharing_Privacy.pdf`
- **Author:** Rishindra Mateti
- **Focus Areas:**
  - Empirical study on continuous and fine-grained GPS location disclosure in mobile environments.
  - Comparative impact of contextual factors (recipient category, physical location type, temporal interval) versus static user personality profiles.
  - Design recommendations for adaptive, context-aware privacy architectures that dynamically calibrate location precision.

---

## Citation

```bibtex
@misc{mateti2025pacstudies,
  author = {Mateti, Rishindra},
  title = {Privacy and Access Control: Systems Security and Privacy Preference Modeling},
  year = {2025},
  institution = {Wright State University},
  url = {https://github.com/rishindra-mateti-tech/PAC-Security-and-Privacy-Analysis}
}
```

---

## License

This project is licensed under the MIT License.

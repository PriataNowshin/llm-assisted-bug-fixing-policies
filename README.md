# LLM-Assisted Bug Fixing Policies: A Multi-Phase Study

## Overview
This repository contains survey instruments and analysis for a multi-phase study examining organizational policies around LLM-assisted bug fixing, focusing on practitioner concerns, disclosure requirements, oversight mechanisms, and organizational equilibria.

## Repository Structure

```
.
├── Survey Design/
│   ├── Phase 1/
│   │   └── Phase 1.pdf
│   └── Phase 2/
│       ├── managerial.pdf
│       └── non-managerial.pdf
└── Survey Findings/
    ├── Phase 1/
    │   ├── Consent and Demographics(in).csv
    │   └── RQ1/
    │       ├── Governance Preferences and Policy Mechanisms(in).csv
    │       ├── LLM Usage Concerns(in).csv
    │       ├── Preferences and Attribution of Assistance Types(in).csv
    │       └── rq1_thematic_analysis_disclosure_oversight.xlsx
    └── Phase 2/
        ├── MAN Consent and Demographics(in).csv
        ├── NON-MAN Consent and Demographics(in).csv
        ├── RQ2/
        │   ├── MAN Policy benefits-challenges-motivators(in).csv
        │   ├── NON-MAN Policy benefits-challenges(in).csv
        │   ├── thematic_analysis_disclosure_oversight_tradeoff_managerial(in).csv
        │   ├── thematic_analysis_motivators_nonmanagerial(in).csv
        │   └── thematic_analysis_tradeoffs_nonmanagerial(in).csv
        └── RQ3/
            ├── MAN policy choice for GTDM(in).csv
            ├── NashEquilibriaScripts.ipynb
            └── NON-MAN policy choice for GTDM(in).csv
```

## Implementation Details

### Nash Equilibria Analysis
The Nash equilibria analysis is implemented using Python with the following dependencies:

```python
import numpy as np
import matplotlib.pyplot as plt
import math
```

Key components:
- Expected utility computation
- Joint probability matrices
- Mixed strategy best responses
- Visualization of equilibrium outcomes

### Policy Components Analyzed

#### Disclosure Components
- Usage Pattern
- Usage Restriction 
- Channel
- Access Level
- Purpose & Scope
- Code Contribution

#### Oversight Components
- Code Verification
- Sensitive Data Protection
- Security and Automated Testing
- Review Responsibility
- Credit and Liability Evaluation
- Final Decision Ownership

## Survey Instruments
The survey instruments for both phases are available in the `Survey Design` directory:
- Phase 1: Initial investigation of policy preferences
- Phase 2: Detailed examination of managerial and non-managerial perspectives

## Analysis Results
Results are organized by research questions (RQ1-RQ3) in the `Survey Findings` directory:
- RQ1: Practitioners' Concerns and Preferences in Oversight & Disclosure, and Their Translation into Policy
- RQ2: Adoption of Disclosure & Oversight Policies--Benefits, Challenges, and Trade-offs
- RQ3: Game-Theoretic Results--Nash-Equilibrium Policy–Behavior Alignments

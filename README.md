# Artificial Intelligence: The Gap Between Expectations and Real-World Performance

> COOP2 Project Report — Chitkara University Institute of Engineering and Technology

---

## Research Paper

**Title:** AI — The Gap Between Expectations and Real-World Performance

| Author | Roll Number |
|---|---|
| Ritvik Sachdeva | 2210990733 |
| Riya Kundra | 2210990735 |
| Gurseerat Singh Sidhu | 2210991599 |

**Current Status:** The paper has been communicated to **SN Computer Science** journal and is on the waitlist for approval.

---

## Overview

This repository contains the research paper and COOP2 project report investigating the **AI Reality Gap** — the measurable difference between the performance AI systems demonstrate in controlled benchmarks and the outcomes they deliver in real-world organisational deployments.

Despite over **$180 billion in global private AI investment** between 2024 and 2025, and frontier models achieving record scores across reasoning, coding, and multimodal benchmarks, large-scale productivity gains remained elusive by 2026. This work quantifies why.

---

## Key Findings

- A **Random Forest classifier** trained on clean clinical data (UCI Heart Disease Dataset) achieved **85.25% accuracy**, which fell to **59.02%** under full mixed-noise corruption — a drop of over 26 percentage points under data conditions plausible in real enterprise deployments.
- A **Productivity J-Curve model** anchored to Stanford AI Index 2025 and McKinsey survey data produced a **28.1-point productivity gap** at month 36 between ideal and failed AI adoption scenarios — using identical underlying technology.
- A **Cross-Model Hallucination experiment** documented a verified instance of AI hallucination occurring not from data noise, but from indirect, chained reasoning — a failure mode that data governance alone cannot prevent.

---

## The Three Research Factors

| Factor | Description |
|---|---|
| **Human Verification Tax** | Time and cost humans spend verifying AI outputs, which scales with data quality degradation |
| **Enterprise Data Readiness** | Limitations of unclean and unorganised legacy data infrastructure in supporting AI models |
| **Organisational Resistance** | Challenges organisations face in redesigning workflows and retraining staff for AI integration |

---

## Repository Contents

```
├── AI-The_Gap_Between_Reality_and_Expectations_Final.docx   # Research paper
├── COOP2_Project_Report.docx                                # COOP2 project report
└── README.md
```

---

## Methodology

**Case Study 1 — Mayo Clinic Augmented Intelligence**
A reference case study of AI-assisted ECG analysis achieving **93% diagnostic accuracy** through structured data, incremental workflow integration, and mandatory human oversight at every stage.

**Case Study 2 — Cross-Model Hallucination Experiment**
An original experiment by Ritvik Sachdeva in which progressively complex Python reasoning tasks were used to probe ChatGPT and Google AI, ultimately producing a documented and verified hallucination under indirect reasoning conditions.

**Experiment 1 — Data Quality Degradation**
A Random Forest classifier was evaluated on the UCI Heart Disease dataset under three noise types (missing value, corruption, and mixed noise) at intensities from 0% to 100%, implemented in Python on Google Colab.

**Experiment 2 — Productivity J-Curve Modelling**
The Productivity J-Curve was formalised as a continuous-time differential equation with parameters anchored to real survey data, modelled across three organisational adoption scenarios: ideal, typical, and proof-of-concept trap.

---

## Tools and Technologies

- **Language:** Python 3
- **Environment:** Google Colab
- **Libraries:** scikit-learn, NumPy, Pandas, Matplotlib
- **Dataset:** UCI Heart Disease Dataset (Cleveland Clinic Foundation)
- **Data Sources:** Stanford AI Index 2025, McKinsey & Company AI Survey 2024

---

## Central Conclusion

> The AI Reality Gap is not a model problem — it is a systems problem. The same technology produced a 132.0 productivity score under ideal conditions and 103.9 under failed adoption after 36 months. The gap exists entirely because of the conditions surrounding the AI system, not the model itself.

---

## Department

**Computer Science and Engineering**
Chitkara University Institute of Engineering and Technology
Chitkara University, Punjab, India

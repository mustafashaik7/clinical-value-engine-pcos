# Transforming PCOS Care with an AI-Enhanced EHR Workstream

> Accelerating PCOS diagnosis and optimizing guideline-driven care through a clinically governed, explainable AI workstream.


## Occasion and purpose

This poster was submitted to and selected for the **2025 Mayo Clinic Quality Academy Research Poster** program. It was created to communicate a quality-improvement research concept focused on reducing diagnostic delay in PCOS care through an AI-enhanced EHR workstream.

The purpose of the poster was to present the problem, baseline quality gap, proposed intervention, measurement strategy, balancing measures, implementation plan, monitoring approach, and hand-off model in a format suitable for clinical quality, informatics, IT, and operational stakeholders.

For this repository, the poster is reframed as a Flow Research Fellowship case study: a concrete example of how clinician judgment and AI persistence can form a new unit of work where contribution to a clinical intent is recognized, measured, governed, and returned as operational value.

## Why this project matters

Polycystic Ovary Syndrome (PCOS) is common, heterogeneous, and frequently under-recognized. The problem is not simply lack of clinical knowledge; it is that the signals needed for timely diagnosis are often scattered across labs, clinical notes, patient history, encounter narratives, and care-team handoffs.

This project explores how an AI-enhanced EHR layer can turn fragmented clinical context into a safer, faster, more explainable diagnostic workstream.

The core research question:

**Can an AI-enabled clinical intelligence layer reduce time-to-PCOS diagnosis while improving guideline adherence and minimizing overdiagnosis risk?**

## Flow Research framing

Flow Research describes a new paradigm where the user brings judgment, taste, and intent, while the agent brings speed, memory, persistence, and execution. This project is a healthcare example of that idea.

In PCOS care, the clinician remains the source of judgment: assessing patient context, interpreting risk, deciding when to escalate, and determining what recommendation is clinically appropriate. The AI layer acts as a persistent operator: synthesizing longitudinal data, surfacing missing diagnostic signals, tracking pathway adherence, and presenting explainable recommendations at the right point in the workflow.

The value is not that AI replaces diagnosis. The value is that contribution to a clinical intent becomes more visible:

- Earlier recognition of risk signals
- Better synthesis of fragmented context
- More consistent use of diagnostic criteria
- Reduced cognitive burden during encounters
- Safer escalation through explainable recommendations
- Continuous feedback through monitoring and governance

## Problem statement

Current EHR workflows are not designed to synthesize longitudinal, multimodal patient data into a real-time diagnostic pathway. For PCOS, relevant indicators such as menstrual irregularity, biochemical markers, hirsutism, BMI, metabolic risk, and patient-reported symptoms may be distributed across structured fields, unstructured notes, labs, and portal messages.

As a result, patients may experience diagnostic delays, inconsistent application of Rotterdam criteria, and variable adherence to guideline-driven care.

## Proposed intervention

The proposed intervention is an AI-driven clinical intelligence layer integrated into the EHR workflow with three core capabilities:

### 1. Predictive Identification

Uses longitudinal patient data to estimate potential PCOS risk and surface patients who may need further review.

### 2. Contextual Synthesis

Summarizes key diagnostic evidence during relevant clinical encounters, including structured data and note-derived signals.

### 3. Explainable Recommendations

Provides guideline-aligned next steps with transparent reasoning, supporting clinician review rather than autonomous diagnosis.

## Workstream model

```text
Patient history + labs + notes + encounters
                |
                v
       AI clinical intelligence layer
                |
    ---------------------------------
    |               |               |
Risk detection  Context synthesis  Explainable recommendation
    |               |               |
    ---------------------------------
                |
                v
       Clinician judgment and action
                |
                v
 Outcome tracking + feedback + governance
```

## Measurement strategy

### Improvement measure

**AI-Assisted Time-to-PCOS Diagnosis**

Operational definition: Months from first documented symptom or signal to PCOS diagnosis flagged for clinician review.

Planned sample: approximately 1,200 patients, age and BMI stratified.

### Balancing measure

**Accuracy of AI-Flagged PCOS Diagnoses**

Operational definition: Percentage of AI-flagged PCOS cases reversed or rejected after expert review within 12 months.

Planned sample: approximately 300 AI-flagged cases.

### Additional signals

- Diagnostic guideline adherence
- Management guideline adherence
- Clinician cognitive load
- Recommendation acceptance rate
- Provider interaction with AI outputs
- Model drift and retraining triggers

## Governance and safety considerations

This project treats AI as a governed clinical workflow component, not as a black-box automation layer.

Key controls include:

- Explainability requirements for clinician trust
- Human-in-the-loop review for diagnostic decisions
- Monitoring for overdiagnosis and false positives
- Feedback loops from clinician interaction data
- Model retraining protocols
- Audit trails through REDCap and EHR-linked entries
- Governance checkpoints before scale-up
- Clear hand-off to clinical informatics and IT operations

## Why this is relevant to Flow Research

This project sits at the intersection of AI agents, reputation, and fair value exchange.

A clinical workstream has many contributors: clinicians, patients, informaticists, data engineers, AI systems, quality teams, and operational leaders. Much of the value they create is invisible: catching a missing signal, reducing diagnostic delay, avoiding overdiagnosis, improving adherence, or making a handoff safer.

A Flow-style value engine would ask:

**How do we recognize, exchange, and return value when human judgment and AI execution jointly improve an outcome?**

This PCOS use case provides a concrete healthcare setting to study that question. It is not only about building an AI tool. It is about designing a trusted workstream where contribution can be observed, evaluated, governed, and improved over time.

## Repository contents

```text
.
├── README.md
├── poster/
│   └── PCOS-2025-v1.1.pptx
├── excerpts/
│   ├── problem-statement.md
│   ├── intervention-summary.md
│   ├── measurement-plan.md
│   └── governance-notes.md
└── docs/
    └── flow-research-application-notes.md
```

## Suggested public excerpts

When publishing this repository, include only non-confidential, de-identified, and approved excerpts. Avoid internal system details, patient data, proprietary implementation specifics, or unpublished operational metrics.

Recommended excerpts:

1. Problem statement and quality gap
2. High-level intervention design
3. Workstream diagram
4. Measurement and balancing strategy
5. Governance and safety principles
6. Reflection on Flow Research alignment

## Status

Selected quality-improvement research poster for the **2025 Mayo Clinic Quality Academy Research Poster** program.

The poster presents a proposed AI-enhanced EHR intervention and includes hypothetical and illustrative values for improvement and balancing measures. Any public version of this repository should clearly label planned, simulated, or illustrative metrics and distinguish them from validated production outcomes.

## Author

Mustafa Shaik  
Technology Leader | Forward-Deployed AI, Security & Platform Engineering | Enterprise Solutions

## Disclaimer

This repository is intended for research, fellowship application, and portfolio discussion purposes. It should not include protected health information, proprietary implementation details, or operational data that has not been approved for public release.

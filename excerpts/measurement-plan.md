# Measurement Plan

## Measurement philosophy

The project uses both improvement and balancing measures. The goal is not only to determine whether the AI-enhanced EHR layer accelerates PCOS diagnosis, but also whether it does so safely, accurately, and without creating harmful workflow burden.

All public metrics should be clearly labeled as planned, baseline, hypothetical, illustrative, or validated depending on their source and maturity.

## Primary improvement measure

### AI-assisted time-to-PCOS diagnosis

**Operational definition:** Number of months from first documented symptom, signal, or clinically relevant indicator to PCOS diagnosis flagged for clinician review.

**Purpose:** Evaluate whether the AI-enhanced workstream reduces diagnostic delay.

**Planned sample:** Approximately 1,200 patients, age and BMI stratified.

**Data sources may include:**

- Structured EHR data
- ICD codes
- Laboratory results
- Clinical notes
- Patient history
- Manual chart review
- REDCap entries with audit trails

## Balancing measure

### Accuracy of AI-flagged PCOS diagnoses

**Operational definition:** Percentage of AI-flagged PCOS cases reversed, rejected, or deemed unsupported after expert review within a defined follow-up period.

**Purpose:** Monitor overdiagnosis risk and ensure faster identification does not come at the cost of diagnostic quality.

**Planned sample:** Approximately 300 AI-flagged cases.

## Secondary measures

Potential secondary measures include:

- Diagnostic guideline adherence
- Management guideline adherence
- Clinician cognitive load
- Recommendation acceptance rate
- Provider interaction with AI-generated outputs
- Frequency of missing-data prompts
- Time spent reviewing synthesized evidence
- False-positive and false-negative patterns
- Model drift indicators

## Comparative design

A pragmatic comparative effectiveness approach can be used to evaluate the intervention in real-world clinical settings. A cluster-randomized design across primary care and OB/GYN clinics may help compare usual EHR workflow against AI-enhanced workflow while accounting for clinical setting variation.

## Monitoring cadence

Post-implementation monitoring should include:

- Real-time dashboard review for diagnostic intervals and adherence patterns
- Quarterly performance reviews
- Expert review of flagged cases
- Workflow feedback from clinicians and clinical informatics teams
- Governance review before broader scale-up

## Flow Research connection

Measurement is where value becomes visible. In a Flow-style value engine, contribution to an intent must be recognized, exchanged, and returned. For this project, the intent is timely, accurate, guideline-driven PCOS care.

The measurement plan helps determine whether the human-agent workstream is actually producing useful work: reducing delay, improving adherence, preserving safety, and earning clinician trust.

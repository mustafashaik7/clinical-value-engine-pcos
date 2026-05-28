# Intervention Summary

## Proposed intervention

The proposed intervention is an AI-enhanced clinical intelligence layer integrated into the EHR workstream to support earlier recognition of PCOS risk and more consistent guideline-driven care.

The intervention has three primary components.

## 1. Predictive identification

The system uses longitudinal patient data to identify patients who may warrant further review for possible PCOS. Signals may include structured EHR data, diagnosis history, labs, BMI/metabolic indicators, menstrual irregularity, symptom documentation, and other clinically relevant markers.

The purpose of this component is to surface risk for clinician review, not to make an autonomous diagnosis.

## 2. Contextual synthesis

The system summarizes relevant diagnostic evidence during the clinical workflow. Instead of requiring a clinician to manually search across prior notes, labs, encounters, and portal messages, the AI layer presents a concise synthesis of the information most relevant to PCOS evaluation.

This synthesis should be transparent, traceable, and reviewable.

## 3. Explainable recommendations

The system provides guideline-aligned recommendations with clear reasoning. Recommendations should reference the clinical rationale behind the suggestion and support clinician decision-making rather than replace it.

Examples of recommendation categories may include:

- Additional evaluation to confirm or rule out PCOS
- Review of Rotterdam criteria elements
- Follow-up care pathway suggestions
- Escalation when uncertainty or risk is present
- Documentation prompts for missing clinical context

## Workstream design principle

The intervention is designed around a human-agent workflow:

```text
Clinician intent + patient context
            |
            v
AI persistence across longitudinal EHR data
            |
            v
Risk detection + context synthesis + explainable recommendation
            |
            v
Clinician review, judgment, and action
            |
            v
Outcome tracking + feedback + governance
```

## What makes this more than automation

The intervention is not simply a notification, alert, or chatbot. It is a workstream intelligence layer that helps convert fragmented clinical data into actionable, explainable, and measurable support.

Its value depends on whether it improves diagnostic timeliness, supports guideline adherence, reduces cognitive burden, and maintains trust through transparency and governance.

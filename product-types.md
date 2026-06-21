# Product Types

Version: `v0.1`

This page is a starting map for common health AI product types.

It helps answer a simple question:

Where should I begin if I am trying to understand the regulatory and safety shape of this product?

## Quick map

| Product type | Primary user | Start here | Main risk lens |
| --- | --- | --- | --- |
| Patient-facing symptom checker | patient or consumer | medical advice boundary, FDA | individualized guidance, false reassurance, escalation failure |
| Clinician-facing workflow copilot | clinician | clinical decision support, FDA, EU MDR / SaMD | support drifting into influence |
| Ambient scribe | clinician | clinical decision support, review questions | documentation becoming action-shaping workflow infrastructure |
| AI imaging or screening tool | clinician or operator | FDA, EU MDR / SaMD, ISO 14971, evidence signals | false positives, false negatives, validation gap |
| Triage or escalation system | patient, operator, or clinician | clinical decision support, FDA, ISO 14971 | timing, routing, and delayed care |
| AI-enabled wellness or prevention tool | consumer | medical advice boundary, review questions | wellness language masking medical consequence |
| UK innovation sandbox announcement | policy or company audience | MHRA, comparison page, evidence signals | innovation language outrunning evidence maturity |

## Product-type cues

### Patient-facing symptom checker

Public cues that should raise attention:

- symptom interpretation
- triage suggestions
- care-seeking advice
- drug or dosage adjacent language

### Clinician-facing workflow copilot

Public cues that should raise attention:

- ranking options
- recommending next steps
- surfacing likely diagnoses
- summarizing evidence in high-speed settings

### Ambient scribe

Public cues that should raise attention:

- action items auto-generated from conversations
- note structures that shape downstream decisions
- billing, coding, or referral suggestions

### AI imaging or screening tool

Public cues that should raise attention:

- sensitivity and specificity headlines
- replacement framing
- whole-body or broad-coverage claims
- comparisons against MRI, CT, or radiologist performance

### Triage or escalation system

Public cues that should raise attention:

- urgency classification
- escalation recommendations
- routing between human teams
- waitlist or prioritization logic

## Why product type matters

Health AI is too broad to analyze well with one generic checklist.

The questions that matter most depend on:

- who the user is
- what claim is being made
- whether the system is shaping care, workflow, or patient action
- how much downstream consequence is attached to the output

## Use with

- [frameworks/comparison.md](./frameworks/comparison.md)
- [review-questions.md](./review-questions.md)
- [evidence-signals.md](./evidence-signals.md)
